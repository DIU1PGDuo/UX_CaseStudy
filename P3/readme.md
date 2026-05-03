# DIU - Practica 3, entregables

Proyecto: **RamenFlow - Anime Ramen Redesign**  
Grupo: **DIU1.PGduo**  
Curso: **2025/26**

---

## Objetivo de la práctica

En esta práctica se desarrollan los prototipos Hi Fi del rediseño de **Anime Ramen**. A partir de los bocetos low-fi definidos en la Práctica 2, se construye una propuesta Hi Fi más cercana a la versión final, apoyada en una guía visual, un sistema de diseño ligero y una organización de componentes en Figma.

El objetivo principal ha sido mantener la personalidad  del restaurante, relacionada con el ramen y la estética anime/japonesa, pero resolviendo mejor los problemas detectados en las prácticas anteriores, carga visual, falta de claridad en la carta, dificultad para localizar información útil y necesidad de una reserva más directa.

Para ello, se ha trabajado con una metodología basada en **Atomic Design**, estructurando el diseño en foundations, átomos, moléculas y organismos. Esta organización permite construir pantallas de forma más coherente y reutilizable, tanto en móvil como en escritorio.

---

## Diseño visual

* [Moodboard + logotipo](Moodboard_AnimeRamen.pdf)

El moodboard define la dirección del rediseño, y en él se explican las principales decisiones de estilo que posteriormente hemos aplicado en el sistema de diseño y en los mockups Hi Fi.

La propuesta utiliza una estética cálida, temática y gastronómica, manteniendo la relación con Anime Ramen. El rojo se utiliza como color principal de acción, el negro como color de contraste e identidad, y los tonos crema, marrón y gris cálido ayudan a suavizar la interfaz y mejorar la legibilidad.

En tipografía se trabaja con **Space Grotesk** para títulos y elementos destacados, y **Inter** para textos funcionales, botones, filtros y contenido de lectura. La combinación busca mantener personalidad visual sin perjudicar la claridad de uso.

Además, se han definido tres versiones de logotipo:

- Logotipo principal para uso web.
- Imagotipo reducido en rojo.
- Imagotipo reducido en negro.

Estos recursos permiten adaptar la identidad visual a distintos espacios de la interfaz, como cabeceras, iconos, pantallas iniciales o elementos de marca dentro del sistema.

---

## Design System / Atomic Design

Para construir el prototipo Hi-Fi se ha desarrollado un sistema de diseño en Figma basado en **Atomic Design**. La idea principal ha sido organizar los elementos visuales y funcionales en distintos niveles de complejidad, de forma que el diseño sea más coherente, mantenible y reutilizable.

La estructura del sistema se divide en:

* [Foundations](Foundations_AnimeRamen.pdf)
* [Átomos](Atomos_AnimeRamen.pdf)
* [Moléculas](Moleculas_AnimeRamen.pdf)
* [Organismos](Organismos_AnimeRamen.pdf)

---

### Foundations

* [Foundations](Foundations_AnimeRamen.pdf)

Las foundations recogen las bases visuales del sistema. No son componentes funcionales como tal, sino las reglas y recursos que definen el aspecto general.

En este proyecto, las foundations sirven para asegurar que el rediseño mantiene la identidad de Anime Ramen, pero con una estructura más ordenada. La paleta de colores se apoya en colores cálidos y contrastados, mientras que la jerarquía tipográfica permite separar mejor títulos, textos descriptivos, botones, precios y etiquetas.

Estas decisiones son importantes porque uno de los problemas detectados en la web original era la dificultad para escanear información rápidamente. Por eso, las foundations no solo tienen una función estética, sino también funcional.

---

### Átomos

* [Átomos](Atomos_AnimeRamen.pdf)

Los átomos son los elementos mínimos reutilizables de la interfaz. Son piezas que sirven como base para construir componentes más complejos.

En el proyecto se han creado átomos como:

- Botones principales y secundarios.
- Botón de añadir producto.
- Botón de pago.
- Input de búsqueda.
- Chips informativos.
- Iconos de navegación y acción.
- Textos base.
- Precios.
- Imágenes de producto.
- Versiones del logotipo.

La creación de estos átomos nos ha permitido que elementos como botones, iconos o etiquetas mantengan el mismo estilo en todas las pantallas. Además, al estar creados como componentes en Figma, se pueden reutilizar y modificar de forma más controlada.

---

### Moléculas

* [Moléculas](Moleculas_AnimeRamen.pdf)

Las moléculas combinan varios átomos para formar unidades funcionales más completas. No son elementos aislados, sino pequeños bloques de interfaz con una finalidad concreta.

En este proyecto se han desarrollado moléculas relacionadas con la carta, la navegación, la búsqueda, los filtros, el contacto, las redes sociales y las acciones de confirmación o cancelación.

Ejemplos de moléculas:

- Tarjeta de ramen.
- Barra de búsqueda.
- Elemento de navegación.
- Filtro.
- Dropdown de opciones.
- Elemento de contacto.
- Elemento de redes sociales.
- Botón de aceptar.
- Botón de cancelar.
- Alerta de eliminación de producto.
- Bloque descriptivo de ramen.

La molécula principal del proyecto es la **tarjeta de ramen**, ya que agrupa varios elementos fundamentales de la carta, imagen del plato, nombre, información de ingredientes/precio y botón de acción. Esta tarjeta responde directamente a uno de los objetivos del rediseño, que era hacer que la carta sea más clara, visual, fácil de consultar e integrada en la página principal.

El uso de moléculas ayuda a evitar diseños repetidos manualmente y permite construir pantallas más consistentes.

---

### Organismos

* [Organismos](Organismos_AnimeRamen.pdf)

Los organismos son secciones completas de interfaz formadas a partir de moléculas y átomos. En esta fase, los componentes ya tienen suficiente complejidad como para formar bloques reconocibles dentro de una pantalla.

En el proyecto se han creado organismos como:

- Header principal.
- Hero banner.
- Grid de productos.
- Bloques de menú.
- Footer.
- Footer alternativo.
- Bloque de filtros y navegación.
- Pop-up de alerta.
- Bloques informativos de producto.

Estos organismos se utilizan como base para montar los bocetos Hi Fi. Por ejemplo, la pantalla de carta se construye a partir de organismos como el header, el grid de productos y los filtros. La home combina hero, productos destacados y footer. La reserva aprovecha componentes de formulario, navegación y confirmación.

El uso de organismos permite pasar del sistema de componentes al diseño de pantallas completas de forma más ordenada.

---

## Layout Hi-Fi

Los mockups Hi-Fi son la evolución visual de los wireframes low-fi definidos en la Práctica 2. No se han añadido nuevos flujos, sino que se han desarrollado las mismas pantallas con mayor nivel de detalle visual, aplicando el moodboard y el sistema de componentes.

El objetivo ha sido convertir los bocetos iniciales en interfaces más cercanas al producto final, incorporando:

- Colores definitivos.
- Tipografías.
- Imágenes.
- Logotipos.
- Iconografía.
- Componentes reutilizables.
- Jerarquía visual.
- Distribución responsive.
- Coherencia entre móvil y desktop.

---

### Hi-Fi móvil

En móvil se han desarrollado las cuatro pantallas principales que ya estaban definidas en los low-fi:

* [Home móvil](HiFi_Home_Movil.pdf)
* [Carta móvil](HiFi_Carta_Movil.pdf)
* [Reserva móvil](HiFi_Reserva_Movil.pdf)
* [Confirmación de reserva móvil](HiFi_Confirm_Reserva_Movil.pdf)


#### Home móvil

La Home móvil funciona como pantalla inicial del rediseño. Presenta la identidad visual de Anime Ramen y prioriza los accesos principales a la carta y a la reserva.

Esta pantalla busca que el usuario entienda rápidamente dónde está, qué ofrece el restaurante y qué acciones puede realizar. Por eso se da importancia a los CTA principales y a la presentación visual de la marca.


#### Carta móvil

La Carta móvil está pensada para resolver uno de los problemas principales detectados en la investigación: la dificultad para consultar platos, precios e información útil de forma rápida.

El diseño utiliza tarjetas de producto, filtros y elementos visuales más ordenados para facilitar la exploración de la carta desde el móvil.


#### Reserva móvil

La pantalla de Reserva móvil organiza el proceso en pasos claros. El objetivo es reducir la incertidumbre del usuario y facilitar que pueda seleccionar local, fecha, hora, número de personas y datos de contacto sin perderse.


#### Confirmación de reserva móvil

La Confirmación de reserva proporciona feedback inmediato al usuario. Esta pantalla cierra el flujo y confirma que la acción se ha realizado correctamente, reforzando la sensación de control y confianza.

---

### Hi-Fi desktop

En desktop se han desarrollado las tres adaptaciones responsive definidas en los low-fi:

* [Home desktop](HiFi_Home_PC.pdf)
* [Carta desktop](HiFi_Carta_PC.pdf)
* [Reserva desktop](HiFi_Reserva_PC.pdf)


#### Home desktop

La Home desktop adapta la pantalla inicial a un formato más amplio. Aprovecha el espacio horizontal para distribuir mejor el hero, la imagen principal, los productos destacados y la información útil del restaurante.


#### Carta desktop

La Carta desktop utiliza una estructura más amplia que la versión móvil. Incorpora navegación superior, filtros laterales y grid de productos, lo que permite comparar platos con mayor facilidad y mejora la exploración de la carta.


#### Reserva desktop

La Reserva desktop organiza el proceso en dos zonas principales: formulario y resumen lateral. Esta solución permite que el usuario complete los datos y revise la información antes de confirmar, aprovechando mejor el espacio disponible en escritorio.


---

## Publicación del Case Study

* [README principal del Case Study](../README.md)

El case study completo se encuentra documentado en el README principal del repositorio. En él se integra esta práctica dentro del proceso completo de diseño.

Este README específico de la Práctica 3 funciona como índice técnico de evidencias y como explicación del trabajo visual realizado.

---


## Conclusiones

La Práctica 3 permite cerrar la evolución visual del proyecto, pasando de los bocetos low fi a una propuesta Hi Fi más coherente y cercana al producto final.

El moodboard ayudó a definir una dirección clara para el rediseño, manteniendo la personalidad temática de Anime Ramen sin repetir la carga visual excesiva detectada en la web original. La elección de colores, tipografías, iconos y logotipo permitió construir una identidad más consistente.

El uso de **Atomic Design** ha sido especialmente útil para ordenar el trabajo en Figma. Separar el sistema en foundations, átomos, moléculas y organismos nos ha permitido construir las pantallas finales de forma más modular y reutilizable. Además, trabajar con componentes e instancias facilitó mantener coherencia entre pantallas.

La realización de mockups Hi Fi tanto en móvil como en desktop permitió comprobar la adaptación responsive de la propuesta. En móvil se prioriza la claridad y la navegación directa, mientras que en desktop se aprovecha el espacio horizontal para mejorar la distribución de la carta, la home y el proceso de reserva.

Como valoración final, consideramos que **RamenFlow** conserva el atractivo visual y temático de Anime Ramen, pero plantea una experiencia más clara, funcional y orientada a las tareas principales.
