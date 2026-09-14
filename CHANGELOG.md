# Changelog

Registro de cambios semana a semana. Cada clase mantiene su propio número de versión (`vX.Y`) independiente del historial de Git.

## Semana 4 — Estructuras de datos fundamentales: listas, diccionarios, tuplas, conjuntos

### v1.0 — 2026-09-14
- Primera publicación: listas (indexación positiva/negativa, *slicing*, métodos `.append()`, `.insert()`, `.remove()`, `.pop()`, `.sort()` vs. `sorted()`), *list comprehensions*, diccionarios (pares clave-valor, `.get()` para evitar `KeyError`, `.keys()`/`.values()`/`.items()`), tuplas (inmutabilidad y por qué importa) y su conexión directa con el `return` de múltiples valores de la Semana 3, *tuple unpacking* (incluyendo el intercambio de variables sin auxiliar), conjuntos (eliminación automática de duplicados, operaciones de unión/intersección/diferencia), tabla comparativa para elegir la estructura correcta, sección "Por qué esto importa para IA/ML" (DataFrames de pandas como diccionarios de listas, *batches* como listas de tuplas, vocabularios como sets), ejemplo práctico de un analizador de carrito de compras (pseudocódigo + Python con *tuple unpacking*, `max()` con `key`, *set comprehension*), segundo ejemplo (agenda de contactos con diccionario de diccionarios), notas de vigencia técnica (orden garantizado de diccionarios desde Python 3.7, `list[int]` desde Python 3.9), errores comunes de principiante, ejercicio propuesto (resumen de inventario, sin resolver), autoevaluación de 9 preguntas, verificación de dependencias.
- Diapositivas: 21, mismo diseño y guía de marca fijada en la Semana 1.
- PDF generado a partir de un documento HTML con la misma guía de marca, vía Python + weasyprint.

## Semana 3 — Estructuras de control y funciones

### v1.0 — 2026-09-07
- Primera publicación: operadores lógicos (`and`, `or`, `not`) y decisiones compuestas, precedencia y condicionales anidados, `range()`, control fino de bucles con `break`/`continue`, funciones (`def`, parámetros, valores por defecto, `return`), alcance (*scope*) local vs. global, sección "Por qué esto importa para IA/ML", ejemplo práctico de un validador de contraseñas (pseudocódigo + Python con `break`), segundo ejemplo (refactor del promedio de notas de la Semana 2 en una función reutilizable), notas de vigencia técnica, errores comunes de principiante, ejercicio propuesto (clasificador de triángulos, sin resolver), autoevaluación de 9 preguntas, verificación de dependencias.
- Diapositivas: 19, mismo diseño y guía de marca fijada en la Semana 1.
- PDF generado a partir de un documento HTML con la misma guía de marca, vía Python + weasyprint.

## Semana 2 — Sintaxis de Python básica: variables, tipos de datos, entrada/salida

### v1.0 — 2026-08-31
- Primera publicación: variables en Python (sintaxis y reglas de nombrado), los cuatro tipos de datos primitivos (`int`, `float`, `str`, `bool`), `type()`, operadores aritméticos y de comparación, `input()`/`print()` y por qué `input()` siempre devuelve texto, conversión explícita de tipos (`int()`, `float()`, `str()`), f-strings, sección "Por qué esto importa para IA/ML", ejemplo práctico de una calculadora de IMC (pseudocódigo + Python), segundo ejemplo (promedio de calificaciones), notas de vigencia técnica, errores comunes de principiante, ejercicio propuesto (caja registradora, sin resolver), autoevaluación de 9 preguntas, verificación de dependencias.
- Diapositivas: 19, mismo diseño y guía de marca fijada en la Semana 1.

## Semana 1 — ¿Qué es programar? Pensamiento computacional

### v1.1 — 2026-08-28
- Se agregó el Ejemplo 4 (el explorador del laberinto) a la sección de los tres bloques universales.
- Se agregó el ejemplo "el guardián y la fila VIP" (pseudocódigo + traducción a Python), para contrastar `while` vs. `for`.
- Se agregó la sección "Por qué esto importa para IA/ML".
- Se agregó la sección "Errores comunes de principiante".
- Se agregó un ejercicio propuesto (sin resolver) para práctica del alumno.
- La autoevaluación pasó de 7 a 9 preguntas.
- Diapositivas: de 11 a 18, mismo diseño y guía de marca.

### v1.0 — 2026-08-28
- Primera publicación: objetivos, los tres bloques universales (secuencia/decisión/repetición), datos y variables, pseudocódigo, ejemplo del paraguas (pseudocódigo + Python), segundo ejemplo (números pares), notas de vigencia técnica, autoevaluación de 7 preguntas, verificación de dependencias.
