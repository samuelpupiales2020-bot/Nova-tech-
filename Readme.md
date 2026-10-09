# NovaTech — Tienda de accesorios tecnológicos

**Proyecto académico de Ingeniería de Software**

## Información del estudiante

- **Nombre completo:** Cristian Samuel Pupiales Martínez
- **Programa:** Ingeniería de Software
- **Semestre:** Primero (1.er semestre)
- **Proyecto:** Desarrollo de una página web y una experiencia móvil para una tienda de productos tecnológicos.

## Descripción

NovaTech es un prototipo de comercio electrónico para mostrar accesorios tecnológicos mediante una interfaz moderna, responsive e interactiva. Su diseño utiliza una paleta oscura con detalles en verde lima, tarjetas de productos, fotografías y animaciones sutiles.

## Tecnologías utilizadas

- **HTML5:** estructura de la página.
- **CSS3:** diseño visual, animaciones y adaptación a dispositivos.
- **JavaScript:** búsqueda, filtros por categoría, favoritos de demostración y carrito de compras.
- **ChatGPT:** asistencia con la planificación, generación y revisión del código.
- **Git y GitHub:** control de versiones y almacenamiento del proyecto.
- **Netlify:** alojamiento y despliegue de la página web.
- **Progressive Web App (PWA):** configuración inicial mediante `manifest.json` y `sw.js`.

## Funcionalidades

- Catálogo de productos tecnológicos.
- Búsqueda de productos.
- Filtros por categorías.
- Carrito de compras demostrativo.
- Botones de favoritos.
- Diseño adaptable a celulares, tabletas y computadores.
- Formulario demostrativo de novedades.
- Efectos visuales y animaciones.
- Configuración inicial para instalación como PWA.

## Estructura del proyecto

```text
NovaTech/
├── index.html
├── manifest.json
├── sw.js
├── README.md
├── INFORME.md
└── assets/
    └── workspace.jpg
```

**Nota:** conserva los archivos y carpetas que realmente existan en tu versión del proyecto. El archivo `index.html` debe estar en la raíz para el despliegue indicado.

## Cómo ejecutar el proyecto localmente

1. Descarga y descomprime el archivo ZIP.
2. Abre la carpeta del proyecto en Visual Studio Code.
3. Abre `index.html` en el navegador o utiliza la extensión Live Server.
4. Prueba la búsqueda, los filtros, el carrito y la adaptación móvil.

Para probar las funciones de PWA y el service worker, utiliza un servidor local o HTTPS.

## Cómo subir el proyecto a GitHub

Crea un repositorio vacío en GitHub. Después, abre una terminal en la carpeta del proyecto y ejecuta:

```bash
git init
git add .
git commit -m "feat: crear tienda web NovaTech"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/novatech-store.git
git push -u origin main
```

Reemplaza `TU-USUARIO` con tu usuario real de GitHub.

Si el repositorio ya tiene configurado un remoto, comprueba su configuración antes de ejecutar `git remote add origin`.

## Cómo desplegar en Netlify

1. Accede a Netlify.
2. Selecciona **Add new site** o **Import an existing project**.
3. Conecta tu cuenta de GitHub.
4. Selecciona el repositorio `novatech-store`.
5. Configura el comando de compilación dejándolo vacío.
6. Establece el directorio de publicación como `.`.
7. Selecciona **Deploy site**.
8. Abre la URL generada y prueba la página en computador y celular.

Cuando hagas cambios en GitHub y los envíes a la rama configurada, Netlify podrá desplegar la nueva versión automáticamente.

## Parámetros generales

- Idioma: español.
- Moneda de presentación: pesos colombianos (COP).
- Diseño: responsive y mobile-first.
- Tecnologías frontend: HTML, CSS y JavaScript.
- Estilo: tecnológico, minimalista y moderno.
- Imágenes: recursos fotográficos externos; se requiere conexión a Internet para cargarlos.
- Datos: productos y precios de demostración.

## Prompt principal utilizado

> Actúa como desarrollador frontend y especialista en UX/UI. Desarrolla una tienda web responsive llamada NovaTech para mostrar accesorios tecnológicos. Utiliza HTML5, CSS3 y JavaScript, una identidad visual moderna con fondo oscuro y detalles en verde lima, fotografías de productos, tarjetas organizadas, búsqueda, filtros, carrito de demostración, favoritos y animaciones sutiles. Aplica principios de ingeniería de software, accesibilidad básica, diseño adaptable y código mantenible. Incluye instrucciones para ejecutar y desplegar el proyecto en GitHub y Netlify. No simules pagos ni almacenamiento de datos reales.

## Principios de ingeniería de software

- **Modularidad:** separar estructura, estilos y comportamiento cuando la organización del proyecto lo permita.
- **Mantenibilidad:** utilizar nombres descriptivos y documentación.
- **Usabilidad:** facilitar la navegación y la búsqueda.
- **Accesibilidad:** incorporar etiquetas accesibles y textos alternativos.
- **Diseño adaptable:** facilitar el uso desde diferentes tamaños de pantalla.
- **Pruebas:** comprobar interacciones y funcionamiento antes del despliegue.
- **Control de versiones:** conservar los cambios del proyecto mediante Git.

## Limitaciones actuales

Este proyecto es un prototipo académico. El catálogo, los precios y el carrito son demostrativos. No incluye pasarela de pago, procesamiento de pedidos, autenticación, base de datos ni backend. El formulario no almacena ni envía correos electrónicos.

Las fotografías remotas dependen de la disponibilidad de sus servidores y de la conexión a Internet.

## Conclusión

NovaTech demuestra la aplicación de tecnologías frontend y herramientas de inteligencia artificial en el desarrollo de una solución web. El proyecto permite explorar el diseño responsive, las interacciones con JavaScript, los principios básicos de ingeniería de software y el proceso de publicación mediante GitHub y Netlify.

**Autor:** Christian Samuel Pupiales Martínez  
**Programa:** Ingeniería de Software  
**Semestre:** Primero
