# DIU - Práctica 5, entregables

## Evaluación de usabilidad y accesibilidad

### 5.a Reclutamiento de usuarios
El proceso de evaluación se ha basado en un estudio entre-sujetos (*Between-Subjects Study*) con una muestra total de 10 participantes independientes, distribuidos de manera equitativa: 5 usuarios asignados para evaluar nuestra propuesta (Caso A) y 5 usuarios para evaluar la propuesta de los compañeros (Caso B - Rakuin Ramen).

A continuación, se detalla la tabla anonimizada con los perfiles reales que evaluaron el **Caso B**:

| ID | Sexo / Edad | Ocupación | Nivel Competencia Digital | Experiencia Previa | Plataforma |
| :---: | :---: | :---: | :---: | :---: | :---: |
| P06 | F / 24 | Estudiante | Básico | Ninguna | Web / Móvil |
| P07 | F / 26 | Empleada | Normal | Mínima | Web / Móvil |
| P08 | M / 24 | Estudiante | Fuerte | Básica | Web |
| P09 | M / 51 | Empleado | Ninguno | Básico | Web |
| P10 | F / 31 | Desempleada | Básico | Ninguna | Web |

---

### 5.b Diseño de las pruebas
Las pruebas de usabilidad se planificaron mediante sesiones moderadas (con una duración aproximada de 5 a 10 minutos por participante). Se definieron dos tareas o misiones críticas equivalentes para ambos prototipos con el fin de evaluar los flujos de interacción clave y comprobar la efectividad del diseño:
* **Tarea 1 (Navegación e Inclusión):** "Accede a la sección de la carta y localiza de forma rápida un plato principal que sea apto para personas veganas o celíacas utilizando el sistema de filtrado disponible".
* **Tarea 2 (Conversión final):** "Inicia el flujo de reserva online y formaliza una mesa para dos personas en el establecimiento para este próximo sábado a las 21:00h".

Tras completar las tareas guiadas, se permitió también un breve periodo de navegación libre para observar recorridos espontáneos, dudas y elementos que llamaran la atención de los usuarios sin instrucciones directas.

---

### 5.c Cuestionario SUS
Inmediatamente después de completar las tareas de interacción, cada participante rellenó de forma individual el cuestionario estandarizado de la Escala de Usabilidad del Sistema (SUS) integrado en la herramienta Tally.so. Los datos brutos se procesaron a través de herramientas de análisis multivariable para obtener la puntuación final sobre 100.

* **Valoración e interpretación de resultados:** El **Caso B - DIU.EA / Rakuin Ramen** obtuvo una puntuación media SUS de **58.5 / 100**. De acuerdo con la escala lingüística convencional, este resultado se sitúa en la categoría de usabilidad **"Marginal-Baja" / "Pobre"** (por debajo del estándar de aceptación óptimo fijado en 68). Las respuestas reflejan que, aunque el sistema es funcional, los formularios de entrada de datos y la navegación de reservas presentan barreras cognitivas que confunden o ralentizan al usuario.

---

### 5.d A/B Testing
Tras recopilar y contrastar las métricas de percepción subjetiva obtenidas en el experimento de testeo A/B, se presenta la siguiente comparativa directa:
* **Diseño A (AnimeRamen):** Obtuvo una puntuación media SUS de **47.5 / 100** (Usabilidad deficiente / Inaceptable).
* **Diseño B (Rakuin Ramen):** Obtuvo una puntuación media SUS de **58.5 / 100** (Usabilidad marginal-baja).

**Conclusión del análisis comparativo:** El **Caso B** demuestra ser cuantitativamente más usable que el Caso A, superándolo por un margen de 11 puntos. No obstante, ambas soluciones se sitúan por debajo del umbral de aceptación recomendado de 68, lo que evidencia una necesidad crítica de rediseñar y simplificar los flujos de interacción de reserva y potenciar las llamadas a la acción (CTA) en ambos proyectos.

---

### 5.e Aplicación del método Eye Tracking

Se aplicó la metodología biométrica de seguimiento ocular (*Eye Tracking*) mediante la herramienta *Gaze Recorder* para analizar el recorrido visual y la jerarquía de contenidos exclusivamente en el **Caso B**.

* **Análisis de la página de Inicio:** El mapa de calor muestra una intensa fijación visual concentrada casi en su totalidad en el carrusel de fotografías de platos de ramen situado en el lateral derecho de la pantalla. En contraste, el bloque de texto descriptivo de la izquierda y el botón de llamada a la acción principal (*CTA*) "Contempla Nuestro Menú" sufren del fenómeno de "ceguera visual", recibiendo un impacto atencional bajo debido al peso de las imágenes decorativas.

![Mapa de calor - Inicio](../img/VisionCalor.png)

* **Análisis de la Carta:** En la pantalla del menú, la atención se monopoliza por completo en la cuadrícula central con las imágenes de la comida. El panel lateral izquierdo destinado a los filtros por categorías y atributos dietéticos es ignorado visualmente por los usuarios (*tunnel vision*), lo que justifica las fricciones para completar con éxito la Tarea 1.

![Mapa de calor - Carta](../img/VisionCalorCarta.png)

* **Análisis del proceso de Reserva:** Durante el flujo de conversión final, la atención visual se dispersa entre los elementos decorativos y los diferentes campos del formulario. Esta falta de foco visual claro en el botón de confirmación explica la frustración de los usuarios y la baja puntuación obtenida en el cuestionario SUS.

![Mapa de calor - Reserva](../img/VisionCalorReserva.png)

---

### 5.f Usability Report de B
Se ha elaborado un informe de usabilidad completo y detallado para el Caso B, el cual consolida los hallazgos de la auditoría técnica automatizada de rendimiento y accesibilidad con Lighthouse (donde obtuvieron una puntuación de 100/100), el análisis biométrico de los mapas de calor y las conclusiones cuantitativas de la escala SUS.

* El documento de la auditoría se encuentra publicado en el repositorio de forma pública bajo la nomenclatura oficial:[Usability Report del Caso B - DIU.EA / Rakuin Ramen](REPORT_DIU.EA_doneBy_DIU1.PGduo.md)
