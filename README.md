# Mi Sitio Web E-commerce

## Descripción del proyecto

Este proyecto consiste en una página web de comercio electrónico desarrollada con **HTML5 y CSS3**. Presenta un catálogo de mates personalizados, reseñas de clientes y un formulario de contacto.

El objetivo es practicar la estructura semántica de HTML y la aplicación de estilos con CSS para organizar y presentar el contenido de una tienda online.

## Características

- **Encabezado y navegación:** enlaces para acceder a Inicio, Productos, Reseñas y Contacto.
- **Catálogo de productos:** tarjetas con imágenes, categoría, nombre, descripción, precio y botón para agregar al carrito.
- **Reseñas de clientes:** sección con opiniones de compradores.
- **Formulario de contacto:** campos para nombre, correo electrónico y mensaje.
- **Diseño con recursos externos:** uso de fuentes de Google Fonts, Material Symbols y Font Awesome.

## Tecnologías utilizadas

- HTML5
- CSS3
- Google Fonts
- Material Symbols
- Font Awesome
- Formspree para el envío del formulario de contacto

## Estructura del proyecto

```text
proyecto/
├── index.html
├── css/
│   └── style.css
└── asset/
    └── img/
        ├── FAVICOM.png
        ├── mate duki2.jpg
        ├── mate airbag.jpg
        └── mate tini2.jpg
```

> La estructura anterior refleja las rutas de recursos referenciadas en `index.html`. Si tu proyecto contiene más archivos o carpetas, agregalos a este esquema.

## Cómo ejecutar el proyecto

1. Descargá o cloná el repositorio.
2. Verificá que `index.html`, la carpeta `css` y la carpeta `asset/img` mantengan las rutas indicadas.
3. Abrí `index.html` en un navegador web.
4. Para modificar los estilos, editá `css/style.css`.

## Observaciones

- Los botones **“Agregar al Carrito”** están presentes en la interfaz, pero el archivo HTML por sí solo no implementa la lógica de un carrito funcional.
- El formulario está configurado para enviar los datos a través de Formspree. Para que funcione correctamente, el servicio debe estar configurado y activo.
- Los precios y los textos de los productos pueden editarse directamente en `index.html`.

## Autor

Proyecto realizado como entrega práctica de HTML y CSS.
