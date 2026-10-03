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

Antes de redactar, el motor clasifica cada hecho del día en **HISTORIA** o
**RESULTADO**.

### Es HISTORIA (y lleva post propio) si cumple al menos uno de estos criterios

1. Cae una pareja cabeza de serie 1 o 2, masculina o femenina.
2. Cae una cabeza de serie contra una pareja no cabeza de serie o de la previa.
3. Hay una retirada o lesión de un jugador o jugadora top 10.
4. Hay un título, una racha o un récord: primera final, X semanas seguidas
   ganando o un debut.
5. Hay un partido con dato excepcional: remontada desde 0-5, un tie-break
   larguísimo o más de 3 horas de juego.

Todo lo que no cumpla ninguno de esos criterios es RESULTADO.

### Cómo se monta cada tipo

**Post de HISTORIA**
- Trata un solo tema. El gancho va en la primera línea y no puede ser el
  nombre del torneo.
- Lleva como máximo 900 caracteres de copy.
- Se publica en cuanto el dato está contrastado, sin esperar a que acabe la
  jornada.
- Si el motor solo tiene una fuente (por ejemplo, el marcador en vivo), lo
  indica en el resumen para Marta.

**Post de RESULTADOS**
- Recoge el resto de la jornada y se publica cuando termina.
- Las historias que ya tienen post propio se reducen a una línea neutra con el
  marcador, sin repetir el relato. Por ejemplo: `🎾 (2) Galán y Chingotto caen
  ante X: 6-4, 6-3`.
- Lleva como máximo 1.500 caracteres. Si no cabe, el contenido va en
  carrusel (una lámina por cuadro) y el copy se queda corto.

### Límites para no saturar

- Se publican como máximo **3 posts al día**: 2 de historia y 1 de resultados.
- Si hay más de 2 historias, se eligen por orden de criterio (el 1 pesa más
  que el 5) y el resto baja al post de resultados.
- Dos posts de historia del mismo día deben separarse al menos 2 horas.

### Masculino y femenino

> PENDIENTE DE DECIDIR (ver la pregunta a Marta). Hasta entonces se aplica:
> las historias del cuadro femenino siguen los mismos criterios que las del
> masculino y llevan post propio. Los resultados de los dos cuadros van en el
> mismo post.

## Comprobación antes de dejar el borrador en Postiz

- [ ] ¿Se puede resumir el post en una frase sin usar "y"? Si no, hay que
      partirlo.
- [ ] ¿La primera línea funcionaría sola como titular?
- [ ] ¿El copy cabe holgadamente por debajo del límite (≤ 900 o ≤ 1.500)?
- [ ] En el resumen para Marta, ¿se indica qué post sustituye a cuál y qué
      datos tienen una sola fuente?
