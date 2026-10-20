# Introducción a la Inteligencia Artificial con Python

Materiales y ejercicios prácticos del curso **Introducción a la Inteligencia Artificial con Python** de FLACSO Ecuador, desarrollado por [Diversa](https://diversa.studio/).

El curso está pensado para personas de **ciencias sociales** con poca o ninguna experiencia en programación.

## Objetivos de aprendizaje

Al finalizar el curso, las y los participantes podrán:

- Explicar qué es la inteligencia artificial y distinguir entre IA, machine learning, deep learning e IA generativa.
- Usar Google Colab y los elementos básicos de Python para leer y adaptar código.
- Trabajar con tablas en pandas y procesar carpetas completas de archivos.
- Aplicar modelos preentrenados para analizar **imágenes**, **documentos escaneados** y **grabaciones de audio**.
- Leer e interpretar las salidas de un modelo de IA.
- Reflexionar sobre los límites, sesgos e implicaciones éticas de usar IA en investigación social.

---

## Estructura del curso

**12 clases · 20 horas · 4 semanas · Google Colab**
Horario: lunes 2 h, martes 2 h, jueves 1 h.

| Semana | Tema | Clases |
|---|---|---|
| 1 | **Fundamentos** | ¿Qué es la IA? · Python y Colab · Estructura de Python y pandas |
| 2 | **Imágenes** | Imágenes como datos · Clasificar y detectar · Segmentar |
| 3 | **Documentos** | Documentos escaneados (OCR) · Analizar el texto · Del archivo al hallazgo |
| 4 | **Audio** | Transcribir entrevistas · Quién habla y qué dice · Proyecto final |

Las tres modalidades son complementarias: documentos y audio terminan convertidos en texto, por lo que las herramientas de análisis de texto de la semana 3 se reutilizan en la semana 4.

---


*Este repositorio se actualiza a medida que avanza el curso.*

---

## Herramientas que usaremos

| Tarea | Librerías |
|---|---|
| Datos y tablas | `pandas`, `numpy`, `matplotlib` |
| Imágenes | `CLIP`, `YOLO` (Ultralytics), `SAM` (Segment Anything) |
| Documentos (OCR) | `Tesseract`, `EasyOCR` |
| Análisis de texto | `spaCy`, `BERTopic` |
| Audio | `Whisper`, `pyannote` |
| Modelos preentrenados | [Hugging Face](https://huggingface.co/) |

---

## Cómo usar este repositorio

1. Haz clic en el botón **Abrir en Colab** de la clase.
2. Guarda tu propia copia: **Archivo → Guardar una copia en Drive**.
3. Ejecuta las celdas **en orden** con `Shift + Enter`.
4. Resuelve los ejercicios en tu copia. Cada notebook tiene ejercicios en tres niveles:  básico,  intermedio y avanzado, con soluciones al final.
5. Para las semanas 2 a 4, activa la GPU: **Entorno de ejecución → Cambiar tipo de entorno de ejecución → GPU**.

No es necesario instalar nada en tu computadora. Solo necesitas una cuenta de Google y un navegador.

---

## Recomendaciones

- Escribe y modifica el código tú mismx, aunque esté resuelto.
- Lee los mensajes de error: la última línea dice qué pasó.
- Usa Gemini en Colab como copiloto: pídele que te **explique** antes de pedirle que resuelva, y lee el código antes de ejecutarlo.
- Comenta tu código con `#` con notas de ayuda.
- Recuerda que al reiniciar Colab hay que volver a ejecutar las celdas y reinstalar las librerías.

---

## Uso responsable de datos

Trabajaremos con datos que pueden ser sensibles: entrevistas, fotografías y documentos personales. Antes de procesarlos con IA, pregúntate:

- ¿Las personas dieron su **consentimiento informado** para este uso?
- ¿**Anonimicé** nombres, lugares y otros datos que puedan identificarlas?
- ¿**Dónde se procesan** los datos? Todo lo que se sube a Colab o a un chatbot se procesa en servidores externos.
- ¿Quién produjo los datos, quién está representado y quién queda fuera?
- ¿Qué categorías impone el modelo y qué no puede "ver" o "escuchar"?
- ¿Qué conclusiones puedo sacar y cuáles no? El modelo produce etiquetas y transcripciones; **la interpretación sigue siendo humana**.

---

## Lecturas y recursos

- [Elements of AI](https://www.elementsofai.com/es/) – curso introductorio gratuito, en español.
- Russell, S. y Norvig, P. *Inteligencia Artificial: un enfoque moderno*. Pearson.
- Géron, A. *Aprende Machine Learning con Scikit-Learn, Keras y TensorFlow*. Anaya.
- Prince, S. [*Understanding Deep Learning*](https://udlbook.github.io/udlbook/). MIT Press (acceso abierto).
- Crawford, K. *Atlas de IA*. NED Ediciones.
- [Documentación de Python](https://docs.python.org/es/3/) · [Google Colab](https://colab.research.google.com/notebooks/intro.ipynb) · [pandas](https://pandas.pydata.org/docs/)

Cursos que inspiraron este diseño: [CS50 AI (Harvard)](https://cs50.harvard.edu/ai/), [AI for Beginners (Microsoft)](https://github.com/microsoft/AI-For-Beginners), [Building AI (Elements of AI)](https://buildingai.elementsofai.com/) y [AI Python for Beginners (DeepLearning.AI)](https://www.deeplearning.ai/courses/ai-python-for-beginners).

---

## Curso relacionado

[Introducción al análisis de datos con Python](https://github.com/DiversaStudio/Analisis_de_datos_FLACSO) – FLACSO Ecuador · Diversa.

---

## Licencia

Materiales bajo licencia [MIT](LICENSE). Puedes reutilizarlos y adaptarlos citando la autoría: **Diversa · FLACSO Ecuador**.
