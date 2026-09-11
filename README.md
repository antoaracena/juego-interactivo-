# 🎧 Escucha & Relaciona

## Entrega N°2 — Edición de Sonido y Experiencia Educativa Interactiva

**Taller de Interfaces — Universidad Adolfo Ibáñez**

---

## Descripción del proyecto

**Escucha & Relaciona** es una experiencia educativa interactiva desarrollada para la web que utiliza el sonido como elemento principal de la interacción.

El proyecto consiste en un juego de reconocimiento auditivo en el que el usuario debe escuchar diferentes sonidos cotidianos y relacionarlos con la imagen del objeto o elemento que considera correcto.

La experiencia contiene sonidos de:

- Agua
- Llaves
- Papel
- Puerta
- Taza
- Teclado
- Tetera
- Tijeras

En cada ronda se reproduce uno de estos sonidos y se presentan cuatro imágenes como alternativas. El usuario debe utilizar únicamente la información auditiva para identificar cuál de las imágenes corresponde al sonido escuchado.

---

## 🧠 Concepto pedagógico

El objetivo pedagógico de **Escucha & Relaciona** es desarrollar y ejercitar la **percepción auditiva, la atención y la asociación entre estímulos sonoros y visuales**.

La actividad obliga al usuario a escuchar atentamente un estímulo antes de tomar una decisión. En lugar de entregar directamente el nombre del objeto, el juego presenta únicamente imágenes, evitando pistas escritas durante la selección.

De esta manera, el usuario realiza un proceso de:

**Escuchar → Reconocer → Asociar → Decidir → Recibir retroalimentación**

La experiencia busca demostrar que el sonido puede funcionar como una interfaz activa y como una fuente de información necesaria para interactuar con una aplicación web.

---

## 🎯 Objetivos de aprendizaje

A través del juego se busca que el usuario pueda:

- Reconocer sonidos presentes en situaciones cotidianas.
- Asociar estímulos auditivos con representaciones visuales.
- Ejercitar la atención y memoria auditiva.
- Diferenciar sonidos con características similares.
- Aprender mediante ensayo, error y retroalimentación inmediata.

---

## 🎮 Funcionamiento del juego

Al comenzar el juego, el usuario debe presionar el botón **“Escuchar sonido”**.

Después de escuchar el audio se presentan cuatro fotografías sin nombres ni pistas escritas.

El usuario debe seleccionar la fotografía que considera correspondiente al sonido.

### Si la respuesta es correcta:

La imagen seleccionada se destaca visualmente en verde, se reproduce un feedback sonoro positivo y se suma un punto al puntaje.

### Si la respuesta es incorrecta:

La alternativa seleccionada se destaca en rojo, mientras que la imagen correcta se muestra en verde. Además, se reproduce un feedback sonoro de error.

Después de responder, se revela el nombre del elemento que produjo el sonido y el usuario puede avanzar a la siguiente ronda.

Al terminar las ocho preguntas, la aplicación muestra el puntaje final obtenido.

---

## 🔊 El sonido como interfaz

En este proyecto el audio no funciona como música de fondo ni como un elemento decorativo.

El sonido constituye la información principal necesaria para resolver cada pregunta.

Sin escuchar el archivo de audio, el usuario no puede determinar de manera correcta qué imagen debe seleccionar.

Por esta razón, la interacción principal del proyecto se estructura como:

**Audio → Interpretación → Imagen → Respuesta**

Además, se utilizan señales sonoras diferentes para comunicar respuestas correctas e incorrectas, complementando el feedback visual de la interfaz.

---

## 🎚️ Edición de audio — Audacity

Los archivos de sonido utilizados en la experiencia fueron preparados y procesados utilizando **Audacity**.

El proceso de edición considera:

1. Importación o grabación del sonido original.
2. Selección del fragmento relevante.
3. Recorte de silencios y partes innecesarias.
4. Limpieza o reducción de ruido cuando es necesario.
5. Normalización del nivel de audio.
6. Nivelación para mantener una intensidad consistente entre los diferentes sonidos.
7. Aplicación de Fade In y Fade Out para evitar entradas o cortes bruscos.
8. Exportación en formato MP3 para su utilización en la aplicación web.

Este proceso permite obtener archivos más limpios, consistentes y optimizados para su reproducción desde el navegador.

---

## 💻 Desarrollo web

La experiencia fue desarrollada utilizando:

- HTML
- CSS
- JavaScript
- Web Audio API

HTML estructura el contenido de la aplicación.

CSS controla el diseño visual, las tarjetas de imágenes, animaciones, colores y feedback.

JavaScript controla la lógica del juego, incluyendo:

- Reproducción de los audios.
- Cambio de preguntas.
- Comparación de respuestas.
- Sistema de puntaje.
- Feedback visual.
- Feedback sonoro.
- Pantalla de resultados.

---

## 📁 Organización del proyecto

La estructura de archivos utilizada es:

juego/

├── index.html

├── README.md

├── audio/

│   ├── agua.mp3

│   ├── llaves.mp3

│   ├── papel.mp3

│   ├── puerta.mp3

│   ├── taza.mp3

│   ├── teclado.mp3

│   ├── tetera.mp3

│   └── tijeras.mp3

└── imagenes/

    ├── agua.jpg

    ├── llaves.jpg

    ├── papel.jpg

    ├── puerta.jpg

    ├── taza.jpg

    ├── teclado.jpg

    ├── tetera.jpg

    └── tijeras.jpg

---

## 🔄 Flujo de interacción

INICIO

↓

Presionar “Comenzar”

↓

Escuchar sonido

↓

Observar las cuatro imágenes

↓

Seleccionar una imagen

↓

Comprobar respuesta

↓

Feedback visual + sonoro

↓

Actualizar puntaje

↓

Siguiente sonido

↓

Resultado final

---

## 💡 Decisiones de diseño

Una decisión importante fue eliminar los nombres de los objetos debajo de las imágenes.

Esto evita entregar pistas textuales y hace que la asociación entre sonido e imagen sea el centro de la experiencia.

Las imágenes funcionan como alternativas visuales y el sonido funciona como el estímulo que contiene la información necesaria para resolver cada desafío.

También se incorporaron colores y señales sonoras para entregar retroalimentación inmediata:

- Verde = respuesta correcta.
- Rojo = respuesta incorrecta.
- Sonido ascendente = acierto.
- Sonido descendente = error.

---

## Conclusión

**Escucha & Relaciona** explora el sonido como una forma de interacción dentro de una interfaz web.

A través de una dinámica sencilla de reconocimiento y asociación, la experiencia transforma sonidos cotidianos en una actividad educativa interactiva.

El proyecto combina edición de audio, diseño de interfaz y programación web para generar una experiencia en la que escuchar es una acción fundamental para poder interactuar y avanzar.
