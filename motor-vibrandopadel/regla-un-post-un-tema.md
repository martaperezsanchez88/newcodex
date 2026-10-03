# Regla para el motor de VibrandoPádel: un post, una historia

> Este bloque va en las instrucciones del motor
> (`00. CLAUDE\sistema\motor-contenido`). Este repo no lo ejecuta: es la
> versión de referencia para copiar allí.

## Por qué existe

El motor estaba metiendo varias historias en un solo copy. Por ejemplo, el post
del 01-10-2026 (octavos del Rotterdam P2) juntaba en 2.160 de los 2.200
caracteres permitidos: dos sorpresas, una lesión, 16 resultados y los cruces de
cuartos. La noticia fuerte quedaba enterrada en una lista y además no salía
hasta las 23:13, cuando terminaba el último partido.

## La regla

Antes de redactar, el motor clasifica cada hecho del día en **NOTICIA** o
**RESULTADO**. Solo es noticia lo importante; todo lo demás es resultado.

### Es NOTICIA (y lleva post propio) si cumple al menos uno de estos criterios

Los criterios valen igual para el cuadro masculino y para el femenino.

1. **Eliminación de una de las 4 primeras parejas**: cae una cabeza de serie
   1, 2, 3 o 4.
2. **Resultado ajustado**: el partido se decide en el tercer set por 7-5
   o 7-6.
3. **Lesión**: hay una retirada, un walkover por lesión o un jugador o una
   jugadora que se lesiona durante el partido, en cualquier ronda del cuadro
   final.

Todo lo que no cumpla ninguno de estos criterios es RESULTADO, aunque sea una
sorpresa (por ejemplo, que caiga la cabeza de serie 7).

**No hay tope de posts.** Si en una jornada hay 5 noticias, se hacen 5 posts
de noticia más el de resultados.

### Cómo se monta cada tipo

**Post de NOTICIA**
- Trata un solo tema. El gancho va en la primera línea y no puede ser el
  nombre del torneo.
- Lleva como máximo 900 caracteres de copy.
- Se publica en cuanto el dato está contrastado, sin esperar a que acabe la
  jornada.
- Si el motor solo tiene una fuente (por ejemplo, el marcador en vivo), lo
  indica en el resumen para Marta.
- Si un mismo partido cumple varios criterios (por ejemplo, la cabeza de serie
  2 cae 7-6 en el tercero), se hace un solo post de noticia, no uno por
  criterio.

**Post de RESULTADOS**
- Recoge el resto de la jornada de los dos cuadros y se publica cuando
  termina.
- Las noticias que ya tienen post propio se reducen a una línea neutra con el
  marcador, sin repetir el relato. Por ejemplo: `🎾 (2) Galán y Chingotto caen
  ante X: 6-4, 6-3`.
- Lleva como máximo 1.500 caracteres. Si no cabe, el contenido va en
  carrusel (una lámina por cuadro) y el copy se queda corto.

## Comprobación antes de dejar el borrador en Postiz

- [ ] ¿El post de noticia cumple alguno de los 3 criterios? Si no, va en
      resultados.
- [ ] ¿Se puede resumir el post en una frase sin usar "y"? Si no, hay que
      partirlo.
- [ ] ¿La primera línea funcionaría sola como titular?
- [ ] ¿El copy cabe holgadamente por debajo del límite (≤ 900 o ≤ 1.500)?
- [ ] En el resumen para Marta, ¿se indica qué post sustituye a cuál y qué
      datos tienen una sola fuente?
