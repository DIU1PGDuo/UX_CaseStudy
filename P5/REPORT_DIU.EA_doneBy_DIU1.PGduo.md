# Usability Report: Evaluación del Diseño B (DIU.EA / Rakuin Ramen)

## 1. Resumen Ejecutivo (Executive Summary)

Este informe documenta la evaluación de usabilidad del prototipo "Rakuin Ramen" (Caso B), un concepto de restaurante japonés basado en la estética de anime Seinen y centrado en la accesibilidad de la interfaz. El objetivo principal de la investigación fue validar su hipótesis de diseño: comprobar si un sistema con filtros de alérgenos claros y una estructura inclusiva mejora la experiencia del usuario general, incluyendo a aquellos con necesidades específicas. A pesar de lograr una puntuación perfecta en accesibilidad técnica automatizada, los resultados empíricos de usabilidad revelan que los flujos de interacción (como la localización de filtros y el procesamiento de la reserva) generan confusión cognitiva, dejando un amplio margen de mejora funcional en la jerarquía visual.


## 2. Metodología y Reclutamiento

El estudio se llevó a cabo mediante un diseño A/B testing inter-sujetos con una muestra total de 10 participantes, de los cuales 5 evaluaron exclusivamente el prototipo interactivo de DIU.EA / Rakuin Ramen (Caso B)

* **Muestra Caso B:** 5 usuarios (60% femenino, 40% masculino).
* **Perfil Demográfico:** Media de edad de 31.2 años, abarcando desde perfiles jóvenes con alta soltura tecnológica hasta adultos de más de 50 años con conocimientos digitales nulos o básicos, coincidiendo con el espectro de usuarios potenciales del restaurante.
* **Entorno de prueba:** Pruebas de navegación moderadas utilizando ordenadores portátiles y dispositivos móviles. Se solicitó a los usuarios interactuar con la interfaz para buscar opciones aptas para alérgenos y formalizar una reserva online.


## 3. Resultados del Cuestionario SUS (Datos Cuantitativos)

Tras procesar las respuestas de la Escala Likert de los 5 participantes del Caso B mediante el algoritmo estándar SUS, los resultados son los siguientes:

* **Puntuación media SUS (Caso B):** **58.5 / 100**
* **Análisis:** En la escala lingüística de usabilidad, un 58.5 se categoriza como **"Marginal" a "Pobre"** (por debajo del promedio aceptable global de 68). Esto indica que, aunque el sistema es estructuralmente correcto y accesible, la experiencia de uso real presenta fricciones considerables. El sistema requiere optimización y simplificación en sus flujos de conversión antes de considerarse verdaderamente intuitivo para el público general.


## 4. Análisis de Eye Tracking (Datos Biométricos)

Para la prueba de seguimiento ocular se empleó la herramienta Gaze Recorder sobre las pantallas estáticas de Inicio, Carta y Reserva, analizando la fijación visual de los usuarios en intervalos de 15 segundos.

* **Zonas de Interés (POI) definidas:** Botón de llamada a la acción ("Contempla Nuestro Menú") en la Hero Section, imágenes destacadas de platos y el panel lateral de filtros de la carta.
  
* **Hallazgos de VisionCalorInicio.png:** El mapa de calor muestra una intensa concentración de fijaciones (puntos rojos y cálidos) en el carrusel de imágenes de platos de ramen situados a la derecha. Por el contrario, el bloque de texto izquierdo y el botón crítico de conversión ("Contempla Nuestro Menú") muestran fijaciones dispersas y tardías. Existe un claro efecto de distracción visual provocado por las fotografías, lo que debilita la eficacia del CTA principal.
  
* **Hallazgos de VisionCalorCarta.png:** En la interfaz del menú, la atención se focaliza casi exclusivamente en las cuadrículas de los platos individuales (imágenes de la comida). El panel lateral izquierdo que contiene los filtros de categorías y atributos dietéticos (Picante, Sin gluten, Vegano) sufre de "tunnel vision"; los usuarios apenas fijan la mirada en él de manera espontánea, lo que explica la dificultad observada para segmentar los platos por alérgenos durante las tareas.
  
* **Hallazgos de VisionCalorReserva.png:** En el proceso de reserva, la atención visual se reparte entre los campos del formulario y los elementos decorativos, sin una concentración clara en el botón de confirmación. Esto refuerza la idea de que el flujo de conversión necesita una jerarquía visual más directa y una llamada a la acción más destacada.

## 5. Auditoría de Accesibilidad (WCAG 2.1/2.2)

Herramientas utilizadas: Lighthouse (Google Chrome DevTools) evaluando el prototipo web desplegado.

* **Valoración general:** Sobresaliente en accesibilidad (Puntuación Lighthouse: 100/100), cumpliendo con creces el objetivo planteado en su hipótesis de diseño. Sin embargo, el rendimiento técnico (74/100) y el SEO (63/100) presentan un margen de mejora considerable.
* **Perceptible:** Excelente. A pesar de utilizar una paleta de colores oscuros adaptada a su temática *Seinen*, los ratios de contraste entre las fuentes tipográficas claras y los fondos son óptimos para la lectura.
* **Operable:** La arquitectura de la información y el despliegue de componentes no interfiere con la usabilidad básica. Navegación predecible a través del teclado.
* **Comprensible:** El uso de etiquetas y la navegación principal (Inicio, Quiénes somos, Carta, Reserva) es clara y estandarizada.
* **Robusto:** El código base generado superó los estándares de lectores de pantalla automatizados sin reportar errores críticos de marcado HTML.


## 6. Conclusiones y Recomendaciones (Actionable Insights)

Tras el análisis cuantitativo, cualitativo y biométrico de Rakuin Ramen, se proponen las siguientes mejoras estratégicas:

1. **Rediseño de la Jerarquía Visual en la Home:** Reubicar o aumentar el contraste y tamaño del botón "Contempla Nuestro Menú". Se recomienda aplicar técnicas de aislamiento visual para que las imágenes de los platos no monopolicen el 100% de la atención inicial del usuario.
2. **Optimización del Panel de Filtros (Carta):** El mapa de calor demuestra que el panel de alérgenos actual es ignorado visualmente. Se sugiere transformar los filtros de texto en botones iconográficos flotantes o integrarlos directamente en la parte superior de la cuadrícula de platos para forzar la fijación visual del usuario.
3. **Optimización de Rendimiento (Performance):** El escáner Lighthouse revela un First Contentful Paint de 3.2 s. Se debe comprimir obligatoriamente el peso de las imágenes de alta resolución empleadas en el carrusel y en la carta para reducir los tiempos de carga web y evitar el abandono prematuro.
4. **Mejora del SEO:** Con una puntuación de 63/100, el sitio requiere una revisión de las metaetiquetas descriptivas y la indexación general del documento HTML para mejorar su posicionamiento frente a la competencia local.
