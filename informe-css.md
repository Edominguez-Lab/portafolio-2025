# Informe – Portafolio con CSS

## ¿Qué estilos aplicaste?
Aplique estilos visuales a diversas secciones de mi portafolio web para mejorar su apariencia y legibilidad. Específicamente, realicé los siguientes cambios:
-   **Estilos generales del cuerpo (`body`):** Definí la fuente principal, el interlineado y colores de fondo/texto base para toda la página.
-   **Encabezado (`header`):** Le di un fondo verde, texto blanco, centré el contenido y estilice el título principal y el eslogan. También hice la imagen de perfil circular con un borde.
-   **Secciones de Contenido (`.contenido-seccion`):** Les apliqué un fondo blanco, márgenes automáticos para centrarlas, relleno interno, bordes redondeados y una sombra sutil para darles profundidad.
-   **Títulos (`h1`, `h2`):** Ajusté tamaños y colores, centrándolos en sus respectivas secciones.
-   **Párrafos (`p`):** Aseguré un buen espaciado y justifiqué el texto.
-   **Listas de Habilidades y Contacto (`ul`, `li`):** Eliminé viñetas predeterminadas, centré los elementos, les di fondos suaves con bordes redondeados y agregué un efecto de cambio de color al pasar el mouse (hover).
-   **Enlaces de Contacto (`a` dentro de `#lista-contacto`):** Les di un color específico, eliminé el subrayado y añadí un efecto de subrayado y cambio de color al pasar el mouse.
-   **Separadores (`hr`):** Les di un estilo más discreto y consistente.

## ¿Qué selectores usaste (clases, ID, etiquetas) y por qué?
Utilicé los siguientes tipos de selectores para aplicar mis estilos:

-   **Selectores de etiqueta (globales):** Como `body`, `p`, `h1`, `h2`, `header`, `footer`, `ul`, `li`, `a`, `hr`. Los usé para aplicar estilos base a todos los elementos de un tipo específico en la página, estableciendo una consistencia general sin necesidad de añadir atributos extra en el HTML.
-   **Selectores de clase (`.mi-clase`):** Usé la clase `.contenido-seccion` para estilizar las secciones "Sobre Mí", "Habilidades" y "Contacto". Esto me permitió aplicar un conjunto de estilos (fondo, margen, padding, sombra) a múltiples secciones que comparten una apariencia similar, promoviendo la reutilización de código CSS.
-   **Selectores por ID (`#mi-id`):** Usé el ID `#lista-contacto` específicamente para estilizar los enlaces dentro de la sección de contacto. Los IDs son ideales cuando necesitas aplicar estilos muy específicos a un elemento único en la página.

## ¿Qué parte del diseño fue más fácil o más difícil?

La parte más fácil fue aplicar estilos básicos a elementos como `p` o `h1`, o usar los nombres de color.

La parte que me costó más lograr una buena organización del CSS, el uso de `margin` y `padding` para el espaciado exacto, entender la herencia de estilos, el efecto `hover` o la elección de la paleta de colores coherente (debo practicar mas)

## ¿Qué aprendí aplicando CSS?
Aprendí la importancia de la separación de la estructura HTML del diseño CSS para un código más limpio y fácil de mantener, la especificidad de los selectores (etiquetas, clases, ID), cómo las propiedades como `margin` y `padding` controlan el espaciado, la utilidad de los efectos `hover` para la interactividad, o cómo lograr una coherencia visual con una paleta de colores limitada]. También comprendí la ventaja de usar CSS externo para una mejor organización del proyecto. Debo practicar mas para dar un estilo profesional 