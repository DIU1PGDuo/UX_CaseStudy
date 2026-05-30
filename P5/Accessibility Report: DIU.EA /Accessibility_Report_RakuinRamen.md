# Accessibility Report: DIU.EA / Rakuin Ramen

## 1. Ficha técnica del informe

- **Proyecto evaluado:** DIU.EA / Rakuin Ramen.
- **Equipo evaluador:** DIU1.PGduo.
- **Normativa de referencia:** WCAG 2.1 / 2.2, nivel AA.
- **Herramienta utilizada:** Lighthouse en Google Chrome DevTools.
- **Ámbito de evaluación:** prototipo web del Caso B utilizado durante la práctica de evaluación de usabilidad.

## 2. Puntuaciones globales

La evaluación automática realizada con Lighthouse obtuvo una puntuación de **100/100 en accesibilidad**, lo que indica que el prototipo no presenta errores críticos detectados automáticamente en aspectos como contraste, estructura semántica básica, navegación y compatibilidad con tecnologías de asistencia.

Además de la accesibilidad, se observaron métricas complementarias con margen de mejora: **rendimiento 74/100** y **SEO 63/100**. Aunque estas puntuaciones no invalidan la accesibilidad del prototipo, sí muestran oportunidades de optimización técnica.

## 3. Análisis por principios POUR

### Perceptible

La interfaz utiliza una estética oscura con textos claros, manteniendo ratios de contraste adecuados en los principales bloques de contenido. Esto favorece la lectura y permite que los elementos principales sean distinguibles.

**Resultado:** correcto.  
**Mejora recomendada:** revisar que todos los textos secundarios y etiquetas pequeñas mantengan contraste suficiente en pantallas de menor calidad o con brillo reducido.

### Operable

La navegación principal es sencilla y predecible. Los apartados principales permiten avanzar por el prototipo sin una estructura excesivamente compleja.

**Resultado:** correcto con margen de mejora.  
**Mejora recomendada:** reforzar visualmente los estados de foco y selección, especialmente en filtros, botones de reserva y controles de formulario.

### Comprensible

Las etiquetas principales de navegación, como Inicio, Carta y Reserva, son claras. No obstante, los resultados de usabilidad muestran que algunos usuarios no localizaron con facilidad ciertos filtros o acciones principales.

**Resultado:** parcialmente mejorable.  
**Mejora recomendada:** simplificar el flujo de reserva y hacer más visibles las llamadas a la acción principales.

### Robusto

El prototipo supera la auditoría automática sin errores críticos de marcado detectados por Lighthouse. Esto indica una base técnica aceptable para lectores de pantalla y validaciones automáticas.

**Resultado:** correcto.  
**Mejora recomendada:** realizar una validación manual adicional si el prototipo evolucionara hacia una implementación final.

## 4. Tabla de hallazgos y prioridades

| ID | Prioridad | Principio | Hallazgo | Recomendación |
| :--- | :--- | :--- | :--- | :--- |
| ACC-01 | Media | Operable | Algunos estados interactivos no destacan lo suficiente. | Reforzar foco, hover y selección en botones y filtros. |
| ACC-02 | Media | Comprensible | Los filtros de la carta no son detectados visualmente por varios usuarios. | Reubicar filtros en una zona superior o convertirlos en chips más visibles. |
| ACC-03 | Baja | Perceptible | Algunos textos secundarios podrían perder legibilidad en pantallas con bajo brillo. | Aumentar tamaño o contraste de etiquetas y textos auxiliares. |

## 5. Conclusiones

El prototipo evaluado presenta una buena base de accesibilidad técnica, con una puntuación Lighthouse de 100/100. Sin embargo, la accesibilidad automática no garantiza por sí sola una experiencia completamente usable. Los resultados de SUS y Eye Tracking muestran que algunos elementos, especialmente filtros y llamadas a la acción, necesitan una jerarquía visual más clara.

Como próximos pasos, se recomienda reforzar estados interactivos, mejorar la visibilidad de filtros y optimizar la claridad del flujo de reserva. Estas mejoras ayudarían a que el prototipo no solo sea técnicamente accesible, sino también más comprensible y eficaz para usuarios reales.
