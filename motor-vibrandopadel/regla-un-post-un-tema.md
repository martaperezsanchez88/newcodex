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

Antes de redactar, el motor clasifica cada hecho del día en **NOTICIA**,
**PARTIDOS IGUALADOS** o **RESULTADO**. Lo que más pesa es quién juega: que
haya una cabeza de serie de por medio es más noticia que un marcador apretado.

Los criterios valen igual para el cuadro masculino y para el femenino.

### Es NOTICIA (y lleva post propio) si cumple al menos uno de estos criterios

Por orden de importancia:

1. **Cae una de las 4 primeras cabezas de serie.** Es el notición del día:
   sale la primera y con el gancho más fuerte.
2. **Cae cualquier otra cabeza de serie** (de la 5 a la 8).
3. **Lesión**: hay una retirada, un walkover por lesión o un jugador o una
   jugadora que se lesiona durante el partido, en cualquier ronda del cuadro
   final.
4. **Una cabeza de serie gana sufriendo**: el partido va a tres sets y el
   tercero termina 6-4, 7-5 o 7-6. Cuanto más alta la cabeza de serie, más
   fuerte el gancho ("Coello y Tapia sufren para pasar: 6-4 en el tercero").
   No se inventan bolas de partido ni remontadas si el marcador no las da.

Si un mismo partido cumple varios criterios, se hace un solo post y manda el
de número más bajo.

### PARTIDOS IGUALADOS (un post al día, para los jugadores menos conocidos)

Los partidos sin ninguna cabeza de serie que van a tres sets con el tercero en
6-4, 7-5 o 7-6 se juntan en **un solo post al día**: "Los partidos más
igualados de la jornada". El objetivo es etiquetar a esos jugadores y
jugadoras para que lo compartan. No compiten con las noticias por el gancho,
pero tampoco se pierden en la lista de resultados.

### RESULTADO

Todo lo demás va al post de resultados al cerrar la jornada.

**No hay tope de posts.** Si en una jornada hay 5 noticias, se hacen 5 posts
de noticia, el de partidos igualados (si hay alguno) y el de resultados.

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

**Post de PARTIDOS IGUALADOS**
- Una línea por partido con el marcador completo y los 4 jugadores
  etiquetados.
- Se publica al cerrar la jornada, antes que el de resultados.
- Si hay más de 5 partidos, se reparte en dos posts (ver el límite de
  etiquetas abajo).

**Post de RESULTADOS**
- Recoge el resto de la jornada de los dos cuadros y se publica cuando
  termina.
- Las noticias que ya tienen post propio se reducen a una línea neutra con el
  marcador, sin repetir el relato. Por ejemplo: `🎾 (2) Galán y Chingotto caen
  ante X: 6-4, 6-3`.
- Lleva como máximo 1.500 caracteres. Si no cabe, el contenido va en
  carrusel (una lámina por cuadro) y el copy se queda corto.

### Etiquetas

- Instagram admite como máximo **20 menciones (@) por post**; si se pasa, el
  post puede fallar. El motor cuenta las menciones antes de crear el borrador.
- Cuando no caben todas, la prioridad es: 1) protagonistas de la noticia,
  2) ganadores que **no** son cabeza de serie, 3) ganadores cabeza de serie,
  4) perdedores. Los jugadores menos conocidos son los que más suelen
  compartir; las estrellas casi nunca lo hacen con cuentas pequeñas.
- Solo se etiqueta un handle verificado. Si el motor no está seguro del
  handle, pone el nombre en texto plano y lo dice en el resumen para Marta:
  etiquetar a la persona equivocada es peor que no etiquetar.

## Comprobación antes de dejar el borrador en Postiz

- [ ] ¿El post de noticia cumple alguno de los 4 criterios? Si no, va en
      resultados.
- [ ] ¿Se puede resumir el post en una frase sin usar "y"? Si no, hay que
      partirlo.
- [ ] ¿La primera línea funcionaría sola como titular?
- [ ] ¿Hay 20 menciones o menos?
- [ ] ¿El copy cabe holgadamente por debajo del límite (≤ 900 o ≤ 1.500)?
- [ ] En el resumen para Marta, ¿se indica qué post sustituye a cuál y qué
      datos tienen una sola fuente?
