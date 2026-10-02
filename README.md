# MentorIA

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23099577.svg)](https://doi.org/10.5281/zenodo.23099577)

Tutor virtual para el **TFG, el TFM o cualquier trabajo académico** de cualquier grado o máster. Aplicación web de un solo fichero que acompaña al estudiante desde su primer interés hasta la defensa, sin escribir el trabajo por él.

**Usar la app:** https://fborrasumh.github.io/mentoria/

*English summary: a virtual tutor for bachelor's, master's and other academic projects. It asks questions, suggests options and points out gaps, but never writes the work for the student. The interface is available in Spanish and English; the tutor answers in the language the student chooses.*

## Origen de la idea

MentorIA parte del cuaderno **«Tutor virtual para el TFG de Derecho Tributario del Grado en DADE»**, de **Irene Martínez Quiles** (Universidad Miguel Hernández de Elche): un tutor de IA que acompaña, que nunca sustituye la labor intelectual del estudiante ni la supervisión del tutor, y que permite al estudiante visualizar sus progresos. Esta app generaliza esa idea a cualquier titulación.

## Qué hace

- **Siete fases:** punto de partida, tema, pregunta y objetivos, diseño (metodología, fuentes e índice), revisión de borradores, preparación de la defensa e informe.
- **Ocho ámbitos** que adaptan vocabulario, fuentes, metodología y estructura: Derecho; Economía, empresa y ciencias sociales; Educación y psicología; Ciencias experimentales y de la vida; Salud y deporte; Ingeniería y tecnología; Arquitectura, diseño, comunicación y humanidades; y «Otro».
- **El estudiante decide y escribe.** El tutor propone alternativas, hace preguntas y señala carencias. Si se le pide que redacte el trabajo, se niega y orienta.
- **Procedencia de cada decisión:** al confirmarla, se anota si es del estudiante, una propuesta de la IA elegida o una propuesta editada.
- **Referencias señaladas:** se detectan leyes, sentencias, citas de autor y DOI que mencione la IA; los DOI se comprueban en Crossref. Todo debe verificarse en la fuente original.
- **Informe para el tutor (Word)** con las decisiones, su procedencia, el uso de IA y la declaración del estudiante, y **proyecto en JSON** con un registro encadenado con huellas.
- **Chat libre** con el tutor, con el contexto de lo ya decidido.

## Cómo se usa la IA

Cada estudiante usa **su propia clave** de OpenAI, Google Gemini o Anthropic Claude. La clave se guarda solo en su navegador y se envía únicamente a su proveedor. No hace falta ningún servidor.

## Privacidad

El proyecto se guarda en el navegador. Lo que el estudiante escribe al tutor y sus decisiones confirmadas viajan a su proveedor de IA. No debe pegarse información personal de terceros ni datos clínicos identificables. Los DOI se consultan en Crossref.

## Límites

- La IA puede equivocarse y la supervisión académica corresponde al tutor o tutora del trabajo.
- La procedencia se estima comparando textos; el registro con huellas es una señal de transparencia, no una prueba.
- No hay vista específica para el tutor: se le entrega el informe.

## Autoría

Fernando Borrás Rocher e Irene Martínez Quiles · Universidad Miguel Hernández de Elche.

## Cómo citar

Borrás Rocher, F. y Martínez Quiles, I. (2026). *MentorIA* (v1.0.0) [Software]. Universidad Miguel Hernández de Elche. DOI: [10.5281/zenodo.23099577](https://doi.org/10.5281/zenodo.23099577)

## Licencia

MIT. Véase [LICENSE](LICENSE).
