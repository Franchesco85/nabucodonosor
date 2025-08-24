# Casa de Comidas Nabuconodosor

¡Bienvenido al repositorio de la Casa de Comidas Nabuconodosor! Este proyecto es una página web diseñada para una casa de comidas familiar que busca combinar tradición y sabor en cada plato. La página permite a los usuarios explorar el menú, obtener información sobre la empresa y contactarse, además de ofrecer una experiencia de compra interactiva a través de un carrito de compras.

---

## 🍽️ Descripción del Proyecto

"Nabuconodosor" es más que una simple casa de comidas; es una empresa familiar dedicada a ofrecer recetas caseras elaboradas con **ingredientes frescos y de calidad superior**. La página web está diseñada para ser intuitiva y atractiva, brindando a los clientes una forma sencilla de descubrir nuestra variedad de pizzas, pastas, hamburguesas, empanadas, carnes y mucho más.

---

## ✨ Características Principales

* **Menú Interactivo**: Explora una amplia selección de platos, divididos en categorías como "Variedad de Pizzas" y "Variedad de Comidas".
* **Carrito de Compras Flotante**: Añade productos al carrito y gestiona tu pedido de manera dinámica, con un contador de ítems y un resumen del total.
* **Información Detallada**: Conoce la historia de "Nabuconodosor" en la sección "Sobre Nosotros" y descubre las reseñas de otros clientes satisfechos.
* **Servicios Ofrecidos**: Descubre nuestros servicios, incluyendo **Delivery**, **Elaboración Propia** de todos nuestros platos y **Menú Mediodía** con promociones especiales.
* **Contacto y Ubicación**: Encuentra nuestra dirección, correo electrónico y horarios de atención, además de un práctico enlace a WhatsApp para consultas rápidas.
* **Diseño Adaptativo**: Experiencia de usuario optimizada para cualquier dispositivo, desde computadoras de escritorio hasta teléfonos móviles.
* **Integración con Redes Sociales**: Accede fácilmente a nuestras redes sociales como Facebook, Instagram, YouTube, Twitter y TikTok.

---

## 🚀 Tecnologías Utilizadas

* **HTML5**: Estructura semántica del contenido de la página.
* **CSS3**: Estilos visuales y diseño responsivo para una experiencia atractiva en cualquier dispositivo.
* **JavaScript**: Funcionalidades interactivas, como el manejo del carrito de compras.
* **Font Awesome**: Iconos vectoriales utilizados para la navegación y elementos visuales.

---

## 🛠️ Instalación y Uso

Para ejecutar este proyecto localmente, sigue estos pasos:

1.  **Clona el repositorio**:
    ```bash
    git clone <URL_DEL_REPOSITORIO>
    ```
2.  **Navega al directorio del proyecto**:
    ```bash
    cd CasaDeComidasNabuconodosor
    ```
3.  **Abre el archivo `index.html`**:
    Simplemente abre el archivo `index.html` en tu navegador web preferido. No se necesita un servidor web para ver la página, ya que es un proyecto estático.

---

## 📂 Estructura del Proyecto

El proyecto está organizado de la siguiente manera:

.
├── index.html          # Página "Acerca de Nosotros"
├── menu.html           # Página del menú de comidas
├── contacto.html       # Página de contacto con formulario
├── reviews.html        # Página de reseñas de clientes
├── css/
│   └── style.css       # Estilos CSS personalizados para la navegación y elementos compartidos
└── images/             # Directorio para todas las imágenes del sitio
    ├── bg.jpg
    ├── Delivery.jpeg
    ├── Hamburguesas.jpg
    ├── Empanadas.jpg
    ├── Asado.jpeg
    ├── Pastas.jpg
    ├── Picadas.jpeg
    ├── Pizza.jpg
    ├── Pollo a la Brasa.jpeg
    ├── PolloLoco.jpg
    ├── Tartas.jpeg
    └── MenudeComidas.jpg
🚀 Páginas del Sitio Web
A continuación, se detalla cada archivo HTML:

1. index.html - Página de Inicio ("Acerca de Nosotros")
Esta es la página principal que presenta la casa de comidas "Nabucodonosor".

Propósito: Ofrecer una introducción atractiva sobre el negocio, su filosofía y sus fundadores.

Contenido:

Un contenedor principal (.contenedor-principal) que organiza el contenido en un diseño flexible.

Dos imágenes de comida (.imagen-comida) que flanquean el texto descriptivo, mejorando la estética visual.

Un párrafo descriptivo (.texto-nabucodonosor) que narra la historia y el propósito de la empresa.

Estilos: Utiliza CSS personalizado para fuentes (Georgia, Playfair Display), colores (#333a42 para el fondo, #b87333 y #8b4513 para el texto y títulos), sombras y bordes redondeados. Los estilos son responsivos gracias a media queries, ajustando el diseño y el tamaño de la tipografía e imágenes para diferentes tamaños de pantalla (apilando elementos en pantallas más pequeñas).

2. menu.html - Página del Menú
Muestra las diferentes categorías de comidas que ofrece el negocio, utilizando un diseño de galería de tarjetas.

Propósito: Presentar el menú de manera visual y organizada, permitiendo a los clientes explorar las opciones.

Contenido:

Un encabezado (<header>) con el título "Menú de Comidas".

Una sección de galería (.gallery) que utiliza el sistema de Grid de Bootstrap (.row, .col) para mostrar las comidas en un diseño de columnas (row-cols-1 row-cols-md-2 row-cols-lg-4). Esto permite que se muestre 1 columna en móviles, 2 en tablets y 4 en escritorios.

Cada elemento del menú es una tarjeta (.card) de Bootstrap, que incluye:

Una imagen (<img> con card-img-top).

Un cuerpo de tarjeta (.card-body) con un título (<h3> con card-title) y una descripción (<p> con card-text).

Una sección de servicios (.services) que destaca el servicio de Delivery, incluyendo una imagen (.delivery-img), un botón directo a WhatsApp (.whatsapp-button) y descripciones adicionales sobre la elaboración propia y el menú de mediodía.

Estilos: Combina estilos personalizados (como colores de fondo #F8F4EA, colores de texto #333, y colores específicos para el header y títulos de tarjetas en #e63946) con las clases de Bootstrap para la estructura del grid, las tarjetas y los botones, asegurando un diseño moderno y responsivo.

3. contacto.html - Página de Contacto
Proporciona un formulario para que los clientes puedan enviar mensajes y enlaces a redes sociales.

Propósito: Facilitar la comunicación directa con el negocio.

Contenido:

Un contenedor principal (.custom-container) centrado en la página. Se renombra a custom-container para evitar conflictos con la clase container de Bootstrap.

Un título (<h1>) "Contacto".

Un formulario (<form>) para nombre, email y mensaje, que usa la plataforma Formspree para el envío de correos.

Una sección de iconos sociales (.social-icons) con enlaces a Facebook, Instagram, YouTube, Twitter y TikTok. Utiliza clases de flexbox de Bootstrap para su alineación.

Un botón flotante de WhatsApp (.whatsapp-float) fijo en la esquina inferior derecha para un acceso rápido al chat.

Estilos: Integra Bootstrap 5 para los elementos del formulario (form-label, form-control, btn btn-primary) y utilidades de espaciado y alineación (mb-3, mt-4, d-flex, justify-content-center). Mantiene colores primarios (--primary-color: #007BFF;) y fondos oscuros (--background: #2c2c2c;) definidos en variables CSS. El botón flotante de WhatsApp tiene un estilo personalizado para su posición y diseño.

4. reviews.html - Página de Reseñas de Clientes
Permite a los usuarios ver y añadir reseñas sobre el servicio.

Propósito: Mostrar la satisfacción del cliente y permitir nuevas contribuciones.

Contenido:

Un contenedor principal (.container) centrado para las reseñas.

Un título (<h2>) "Reseñas de nuestros clientes" con una animación de aparición.

Una rejilla de reseñas (.review-grid) donde se muestran las opiniones existentes. Cada reseña es un div con un párrafo y un nombre.

Un formulario para agregar reseñas (.reseña-form) con campos para nombre y comentario.

Estilos: Presenta un fondo suave (#F8F4EA) y un contraste con el blanco de las reseñas y el formulario. El título tiene un color distintivo (#ff5733) y una animación CSS. El formulario tiene un gradiente de fondo sutil y una sombra interactiva al pasar el ratón.

Funcionalidad JavaScript:

Carga de Reseñas: Al cargar la página, recupera las reseñas guardadas en el localStorage del navegador.

Envío de Reseñas: Cuando se envía el formulario, el JavaScript captura el nombre y el comentario, los añade dinámicamente a la lista de reseñas en la página y los guarda en el localStorage para persistencia.

💅 Estilos Globales y Compartidos (css/style.css)
Este archivo CSS contiene estilos que se aplican globalmente o a la navegación principal, complementando o extendiendo las funcionalidades de Bootstrap.

Reset y Base:

Reinicia márgenes y paddings (margin: 0; padding: 0;).

Establece box-sizing: border-box; para un control más intuitivo del tamaño de los elementos.

Define la fuente principal ('Poppins', sans-serif) y colores base para el body (#2d343c para el fondo, #FFFFFF para el texto).

Asegura que las imágenes sean responsivas (max-width: 100%; height: auto;).

Define un contenedor genérico (.container) con un ancho máximo y padding horizontal.

Header y Menú Principal:

Define un header con una imagen de fondo (images/bg.jpg) y un gradiente, ocupando min-height: 70vh.

Estilos para el menu (navegación), con display: flex para alinear elementos (logo, navbar, iconos).

Logo: Estilos para la imagen del logo (.logo-img).

Menú Hamburguesa (Mobile): Define el comportamiento del checkbox (.menu-toggle) y el label (.menu-label) para el ícono de hamburguesa, que se muestra solo en dispositivos móviles.

Barra de Navegación (.navbar):

Estilos para la lista de enlaces (<ul>) y los elementos de la lista (<li>).

Define el tamaño de la fuente, el color (#FFFFFF) y el efecto hover (color: #f35200;) para los enlaces.

Ícono de Carrito y Menú de Carrito:

cart-icon: Un ícono de carrito fijo en la parte superior derecha de la pantalla, con un contador de elementos (#cartCount).

cart-menu: Un menú desplegable para el carrito, inicialmente oculto y con una transición suave. Se activa con la clase .activo.

Botones del Carrito: Estilos para los botones "Vaciar Carrito" y "Finalizar Compra".

Media Queries: Incluye reglas @media para ajustar la disposición de elementos en pantallas pequeñas (por ejemplo, la posición del ícono del carrito en móvil, y el comportamiento del menú hamburguesa).

🛠️ Tecnologías Utilizadas
HTML5: Estructura del contenido.

CSS3: Estilos personalizados y diseño.

Bootstrap 5.3.3: Framework CSS para diseño responsivo y componentes UI.

Font Awesome 6.4.0 (o 6.5.0): Librería de íconos.

JavaScript: Para la funcionalidad de las reseñas (guardar y mostrar).

Formspree: Servicio para manejar envíos de formularios sin necesidad de backend propio.

💡 Cómo Usar
Clona o descarga este repositorio.

Abre los archivos index.html, menu.html, contacto.html o reviews.html en tu navegador web.

Asegúrate de que la carpeta images/ contenga las imágenes referenciadas en el código para que el diseño se visualice correctamente.

¿Necesitas ayuda para personalizar alguno de estos archivos o tienes alguna pregunta sobre el código?







Ahora creame el archivo readme.md para ponerlo en el VSC


Documentación del Proyecto "Comidas Caseras"
Este README.md describe la estructura y funcionalidad de un sitio web para un negocio de comidas caseras, diseñado para ser desplegado fácilmente. El proyecto utiliza Bootstrap 5 para el diseño responsivo y Font Awesome para los íconos, complementado con CSS personalizado para una estética única y el manejo de reseñas con JavaScript.

📁 Estructura del Proyecto
El proyecto está organizado de la siguiente manera:

.
├── index.html          # Página "Acerca de Nosotros"
├── menu.html           # Página del menú de comidas
├── contacto.html       # Página de contacto con formulario
├── reviews.html        # Página de reseñas de clientes
├── css/
│   └── style.css       # Estilos CSS personalizados para la navegación y elementos compartidos
└── images/             # Directorio para todas las imágenes del sitio
    ├── bg.jpg
    ├── Delivery.jpeg
    ├── Hamburguesas.jpg
    ├── Empanadas.jpg
    ├── Asado.jpeg
    ├── Pastas.jpg
    ├── Picadas.jpeg
    ├── Pizza.jpg
    ├── Pollo a la Brasa.jpeg
    ├── PolloLoco.jpg
    ├── Tartas.jpeg
    └── MenudeComidas.jpg
🚀 Páginas del Sitio Web
A continuación, se detalla cada archivo HTML con sus características principales:

1. index.html - Página de Inicio ("Acerca de Nosotros")
Esta es la página principal que introduce la casa de comidas "Nabucodonosor". Presenta la historia del negocio y su filosofía.

Propósito: Ofrecer una bienvenida atractiva y contar la narrativa de la marca.

Contenido clave:

Un diseño flexible que muestra dos imágenes de comida flanqueando un texto descriptivo central.

Un texto detallado que narra la fundación y el compromiso familiar de "Nabucodonosor".

Estilos: Utiliza fuentes serif (Georgia, Playfair Display) y una paleta de colores cálidos y terrosos para un ambiente acogedor. El diseño es completamente responsivo, ajustando la disposición y el tamaño de los elementos en diferentes dispositivos.

2. menu.html - Página del Menú
Muestra un catálogo visual de las comidas ofrecidas, permitiendo una fácil exploración de las opciones.

Propósito: Presentar el menú de manera organizada y visualmente atractiva.

Contenido clave:

Un encabezado que destaca el título "Menú de Comidas".

Una galería de productos implementada con el sistema de Grid de Bootstrap, que muestra cada comida en una tarjeta (.card) con imagen, título y descripción. El diseño de la cuadrícula se adapta responsivamente para mostrar 1, 2 o 4 columnas según el tamaño de la pantalla.

Una sección dedicada a los servicios, que resalta el Delivery e incluye un botón directo a WhatsApp para pedidos, junto con detalles sobre la elaboración propia y el menú del mediodía.

Estilos: Combina estilos personalizados para colores (#F8F4EA, #e63946) y efectos de hover con las utilidades de Bootstrap para el diseño de tarjetas y la estructura de la cuadrícula, ofreciendo una experiencia de usuario moderna y adaptable.

3. contacto.html - Página de Contacto
Proporciona un formulario sencillo y enlaces a redes sociales para que los clientes puedan comunicarse con el negocio.

Propósito: Facilitar la comunicación directa y la conexión en redes sociales.

Contenido clave:

Un formulario de contacto con campos para nombre, correo electrónico y mensaje, que utiliza Formspree para el envío.

Iconos de redes sociales (Facebook, Instagram, YouTube, Twitter, TikTok) organizados con flexbox de Bootstrap.

Un botón flotante de WhatsApp en la esquina inferior derecha para un acceso rápido y visible.

Estilos: Implementa Bootstrap 5 para el diseño de formularios, botones y utilidades de espaciado. Los colores principales (--primary-color: #007BFF;) y el fondo oscuro (--background: #2c2c2c;) mantienen una estética consistente con la marca.

4. reviews.html - Página de Reseñas de Clientes
Permite a los usuarios ver las opiniones de otros clientes y añadir sus propias reseñas.

Propósito: Construir confianza mostrando testimonios de clientes y fomentar la interacción.

Contenido clave:

Un listado de reseñas existentes, presentado en una cuadrícula adaptable.

Un formulario interactivo para que los usuarios puedan dejar sus propias reseñas.

Estilos: Presenta un fondo claro y el contraste con los elementos del formulario. El título de la sección de reseñas incluye una animación de aparición para un efecto visual dinámico.

Funcionalidad JavaScript:

Persistencia: Utiliza localStorage para guardar y cargar las reseñas, permitiendo que persistan incluso si el usuario cierra y vuelve a abrir la página.

Interacción: Las reseñas enviadas a través del formulario se añaden dinámicamente a la página sin necesidad de recargarla.

💅 Estilos Globales y Compartidos (css/style.css)
Este archivo contiene los estilos base y la configuración de la navegación principal.

Reset Básico: Elimina márgenes y paddings por defecto del navegador y establece box-sizing: border-box; para un control predecible del diseño.

Tipografía y Colores Base: Define la fuente 'Poppins', sans-serif y colores de fondo y texto generales para el body.

Imágenes Responsivas: Asegura que todas las imágenes se ajusten a su contenedor sin desbordarse.

Contenedor Global: Establece un ancho máximo y padding para el contenido principal del sitio.

Header y Navegación:

Define un header con una imagen de fondo y un gradiente superpuesto, dándole una altura mínima para una presencia visual impactante.

Estilos para el logo y la barra de navegación (.navbar), que incluye enlaces con efectos de hover.

Menú Hamburguesa (Mobile): Implementa un menú hamburguesa con un icono (.menu-icon) que aparece en dispositivos móviles para una navegación compacta.

Carrito de Compras (futura implementación): Incluye estilos para un ícono de carrito fijo con un contador de elementos, y un menú desplegable para el carrito (.cart-menu), que se activa con JavaScript. Aunque la lógica del carrito no está completamente implementada en los HTML proporcionados, los estilos base están listos.

Media Queries: Contiene reglas CSS para adaptar el diseño del header, la navegación y otros elementos específicos en diferentes tamaños de pantalla.

🛠️ Tecnologías Utilizadas
HTML5: Estructura semántica del contenido.

CSS3: Estilos personalizados y diseño.

Bootstrap 5.3.3: Framework CSS para componentes UI y diseño responsivo.

Font Awesome 6.x: Librería de íconos para elementos visuales.

JavaScript: Para la funcionalidad de las reseñas y la futura lógica del carrito.

Formspree: Servicio para el manejo de envíos de formularios sin backend.

🚀 Cómo Usar / Desplegar
Clona o descarga este repositorio en tu máquina local.

Abre el proyecto en tu editor de código (como Visual Studio Code).

Puedes abrir cualquiera de los archivos .html directamente en tu navegador para ver la página, o usar una extensión de servidor local (como "Live Server" en VS Code) para un desarrollo más cómodo.

Asegúrate de que la carpeta images/ contenga todas las imágenes referenciadas en el código para que el diseño se visualice correctamente.

Para el formulario de contacto, configura tu cuenta en Formspree y actualiza la URL en el atributo action del formulario en contacto.html.
