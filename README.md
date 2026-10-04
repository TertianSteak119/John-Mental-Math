# John Mental Math

Prototipo funcional del desafío matemático del torneo.

## Uso
Abre `index.html` en un navegador moderno.

## Reglas implementadas
- Usuario individual y récord persistente en `localStorage`.
- Cuenta regresiva 5-4-3-2-1 con opción de cancelar.
- Ronda de 60 segundos.
- Sumas: 3 cifras + 2 cifras.
- Restas: 2 cifras - 1 cifra, sin resultados negativos.
- Multiplicaciones: 2 cifras × 2 cifras.
- Operaciones aleatorias dentro de esos rangos.
- Respuesta correcta: +1 punto y nueva operación.
- Respuesta incorrecta: -1 punto, permanece la misma operación hasta resolverla.
- El puntaje puede ser negativo sin límite.
- Indicador gráfico correctas/intentos.
- Temporizador con transición gradual de color.
- Al llegar a 0, la operación en curso no se contabiliza si no fue comprobada.
- Estadísticas finales: correctas/intentos, puntaje neto, errores, precisión, ejercicios resueltos y tiempo promedio de respuesta.
- Intentos ilimitados.
- Mejor intento por usuario: mayor puntaje neto; en empate, más respuestas correctas.
