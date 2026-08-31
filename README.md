# Aprende con Gutyy IA

Curso semanal de programación, inteligencia artificial y Machine Learning, publicado en Google Classroom y pensado a la vez como pieza de portafolio público. Progresión: **básico → intermedio → avanzado → profesional**.

Cada semana se produce con un flujo de tres roles que se validan entre sí antes de publicarse:

1. **INSTRUCTOR_IA_ML** — define el tema de la semana y redacta la clase (objetivos, contenido con analogías, ejemplo práctico, autoevaluación).
2. **INGENIERO_SOFTWARE_SENIOR** — añade código real y actualizado, detecta obsolescencia, traduce jerga técnica.
3. **DISENADOR_GRAFICO** — convierte el contenido validado en material visual (diapositivas), aplicando la guía de marca.

Cada clase queda versionada (`vX.Y`) con fecha, y el [CHANGELOG.md](CHANGELOG.md) registra qué cambió semana a semana.

## Roadmap general

| # | Módulo |
|---|---|
| 1 | Fundamentos de programación y pensamiento computacional *(Semana 1)* |
| 2 | Sintaxis de Python básica: variables, tipos de datos, entrada/salida |
| 3 | Estructuras de control y funciones |
| 4 | Estructuras de datos fundamentales: listas, diccionarios, tuplas, conjuntos |
| 5 | Algoritmos y complejidad básica (búsqueda, ordenamiento, Big O) |
| 6 | Buenas prácticas de ingeniería: POO introductoria, Git, testing básico |
| 7 | Matemáticas para ML I: álgebra lineal y cálculo esencial |
| 8 | Matemáticas para ML II: probabilidad y estadística aplicada |
| 9 | Python científico: NumPy, Pandas, Matplotlib |
| 10 | Machine Learning clásico: regresión, clasificación, scikit-learn |
| 11 | Deep Learning: redes neuronales, PyTorch/TensorFlow |
| 12 | IA generativa y agentes: LLMs, prompting, RAG, frameworks de agentes |

## Semanas publicadas

| Semana | Tema | Versión | Material |
|---|---|---|---|
| 1 | ¿Qué es programar? Pensamiento computacional | v1.1 | [clase.md](semanas/semana-01-pensamiento-computacional/clase.md) · [diapositivas.html](semanas/semana-01-pensamiento-computacional/diapositivas.html) · [clase.pdf](semanas/semana-01-pensamiento-computacional/clase.pdf) |
| 2 | Sintaxis de Python básica: variables, tipos de datos, entrada/salida | v1.0 | [clase.md](semanas/semana-02-sintaxis-python-basica/clase.md) · [diapositivas.html](semanas/semana-02-sintaxis-python-basica/diapositivas.html) · [clase.pdf](semanas/semana-02-sintaxis-python-basica/clase.pdf) |

## Guía de marca

Identidad visual fijada en la Semana 1 y reutilizada en todas las semanas siguientes.

- **Estilo:** claro-minimalista, académico-editorial, un solo acento, tema único (no cambia con dark mode del sistema — la identidad del curso debe verse igual siempre, como un PDF impreso).
- **Paleta:**
  - `--bg: #FFFFFF` · `--bg-alt: #F5F6FA`
  - `--ink: #171A24` · `--ink-secondary: #4B4F5E` · `--ink-tertiary: #8A8FA3`
  - `--accent: #3548C4` · `--accent-dark: #24308C` · `--accent-tint: #EAEDFB`
  - `--border: #E2E4EC`
  - Código: fondo `#F3F4F8`, borde `#E3E5EE`, texto `#23262F`, comentarios `#9297A8`
- **Tipografías:** IBM Plex Sans (texto/títulos) + IBM Plex Mono (código, metadatos, kickers), vía Google Fonts.
- **Patrón de diapositivas:** pantalla completa con scroll-snap vertical, rail de puntos de navegación, contador `NN/total` y marca fijos arriba, portada con eyebrow + título con palabra clave en acento + metadatos (Nivel/Prerrequisitos/Versión/Fecha) en mono. Callouts con borde izquierdo de acento, tarjetas de código tipo editor.

## Formato de cada clase

Cada clase (`clase.md`) sigue esta estructura obligatoria:

- Nivel, prerrequisitos, versión y fecha
- Objetivos de aprendizaje (verificables)
- Contenido con analogías y progresión de ejemplos
- Ejemplo práctico (pseudocódigo → código real)
- Notas de vigencia técnica
- Autoevaluación corta
- Verificación de dependencias (por qué el tema no depende de nada no visto)
