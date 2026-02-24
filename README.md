# SATURN3D

Proyecto final de Lenguajes de Marca. Web desarrolada para una empresa real de modelado 3D. 

## Tecnologías Utilizadas
* **HTML5:** Estructura semántica de las diferentes secciones de la web.
* **CSS3:** Diseño visual, maquetación (Layout) y efectos de profundidad para la temática 3D.
* **Git/GitHub:** Control de versiones y despliegue continuo.

**HTML5:**
El proyecto se ha desarrollado siguiendo una estructura semántica y organizada, cumpliendo con los siguientes hitos técnicos:

Estructura Multidocumento: Se han creado 11 documentos HTML independientes y vinculados (index, servicios, diseno, materiales, presupuesto, equipo, galeria, contacto, faq, aviso-legal y el archivo sitemap.xml).

Arquitectura Coherente: Todos los documentos comparten una estructura de maquetación idéntica basada en las etiquetas semánticas de HTML5: <header>, <nav>, <main> y <footer>.

Navegación Avanzada: Implementación de un menú desplegable multinivel presente en todas las páginas. Utiliza una estructura de listas anidadas (<ul>, <li>) controlada mediante CSS y pseudoclases para una experiencia de usuario fluida.

Formularios Completos: En la página de presupuesto.html se ha integrado un formulario de contacto profesional que incluye:

Entradas de texto y email.
Listas de selección desplegables (<select>).
Áreas de texto extensas (<textarea>).
Controles de opción múltiple (checkbox y radiobuttons).
Botones de acción (submit y reset).

Contenidos Especializados: Uso de tablas de datos (<table>) en la sección de materiales para mostrar especificaciones técnicas.

Integración de elementos interactivos nativos como <details> y <summary> en la sección de preguntas frecuentes (FAQ).

Galería de imágenes optimizada con clases descriptivas para el diseño responsivo.

SEO y Accesibilidad: Inclusión de etiquetas <meta> para el control de la escala en dispositivos móviles y un archivo sitemap.xml correctamente estructurado para la indexación.

**CSS3:** 
El apartado visual y de experiencia de usuario se ha implementado utilizando CSS3 puro, siguiendo principios de diseño moderno y organización modular:

Maquetación y Layout:
Uso avanzado de CSS Grid para las cuadrículas de servicios, equipo y galería, permitiendo una disposición flexible de los elementos.

Implementación de Flexbox en el sistema de navegación y en los contenedores de redes sociales para un alineamiento preciso.

Diseño Responsivo (Adaptabilidad):
Configuración de Media Queries específicas para cumplir con los estándares de la tarea: disposición para PC (máximo 1300px) y disposición para móvil (máximo 600px).

Sistema de menú adaptable que se transforma en un menú de hamburguesa funcional en dispositivos móviles mediante el "checkbox trick".

Animaciones Dinámicas (Requisito Principal):
Slider/Carrusel: Desarrollo de una animación compleja de 25 segundos en la página principal que gestiona la transición de 5 imágenes mediante el desplazamiento del eje X.
Keyframes Personalizados: Implementación de animaciones adicionales como el efecto de "latido" (latidoProyecto) en la galería y efectos de entrada suave (fadeInUp) en la sección de servicios.

Interactividad con Pseudoclases:
Uso extensivo de :hover para efectos de elevación en tarjetas, cambios de color en el menú y filtros de escala en la galería.
Gestión de menús desplegables multinivel basados puramente en CSS mediante la selección de descendientes.

Estilización de Formularios:
Diseño personalizado de todos los elementos de entrada (input, select, textarea), incluyendo estados de :focus con transiciones suaves para mejorar la accesibilidad y el feedback visual.
