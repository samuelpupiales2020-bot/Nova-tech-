# Informe técnico — NovaTech

**Estudiante:** Christian Samuel Pupiales Martínez  
**Programa:** Ingeniería de Software  
**Semestre:** Primero (1.er semestre)  
**Proyecto:** Tienda demostrativa de accesorios tecnológicos  
**Contacto suministrado:** `3135'87237` (confirmar formato antes de publicar)

## Descripción
NovaTech es un prototipo de comercio electrónico en español para mostrar audífonos, smartwatch, baterías portátiles, parlantes, celular y accesorios de gaming. Su diseño responsive incluye búsqueda, filtros por categoría, carrito de demostración, favoritos simulados, notificaciones y formulario de novedades.

## Herramientas
- **IA generativa utilizada como apoyo:** ChatGPT (LLM) para diseño de estructura, código, depuración y redacción de la documentación.
- **Tecnologías:** HTML5, CSS3 y JavaScript sin frameworks.
- **Control de versiones y publicación:** Git/GitHub y Netlify.
- **Editor recomendado:** VS Code o Cursor.
- **Imágenes:** conjunto visual generado para la maqueta y guardado localmente en `assets/`.

## Prompt base
> Actúa como desarrollador frontend y diseñador UX/UI con principios de ingeniería de software. Construye una tienda responsive en español llamada NovaTech para accesorios tecnológicos con HTML semántico, CSS moderno y JavaScript sin frameworks. Usa una identidad oscura con acento verde lima, catálogo con fotografías locales relacionadas con cada producto, precios claros en COP, categorías, búsqueda, carrito de demostración, favoritos simulados, notificaciones accesibles y formulario con validación básica. Mantén una estructura mantenible, funciones descriptivas, diseño mobile-first, animaciones sutiles, instrucciones de GitHub y Netlify, y deja explícito que pagos y pedidos no son reales.

## Parámetros generales
- Idioma: español; referencias de precio en COP.
- Diseño: mobile-first, responsive, contraste legible y animaciones moderadas.
- Frontend: HTML5, CSS3 y JavaScript vanilla.
- Catálogo: 8 productos de demostración; imágenes incluidas como archivos locales.
- Interacciones: búsqueda, filtros, agregar al carrito, contador, favoritos simulados y mensaje del formulario.
- PWA: manifest y service worker básico; instalación/cache disponibles en contexto compatible con HTTPS o localhost.
- Despliegue estático: comando de build vacío; directorio de publicación `.`.

## Principios de ingeniería de software
- Separación de estructura, presentación y lógica por secciones HTML, CSS y JavaScript.
- Modularidad a través de funciones de renderizado, filtrado, notificación y carrito.
- Accesibilidad base: etiquetas, textos alternativos y región `aria-live`.
- Mantenibilidad: nombres descriptivos, README e instrucciones de despliegue.
- Transparencia sobre datos ficticios y límites de las funciones simuladas.

## Despliegue
1. Abrir la carpeta y probar con `python -m http.server 8000`; visitar `http://localhost:8000`.
2. Crear un repositorio GitHub vacío y subir el contenido.
3. En Netlify importar el proyecto desde GitHub.
4. Dejar **Build command** vacío y usar `.` como **Publish directory**.
5. Desplegar y comprobar imágenes, responsive, filtros, carrito y consola del navegador.

## Pruebas recomendadas
- Verificar anchos de 360 px, tablet y escritorio.
- Probar búsqueda y filtros en todas las categorías.
- Añadir uno o varios productos y comprobar contador y total de demostración.
- Verificar que las fotografías locales carguen, así como teclado y foco accesible.
- Confirmar que no se procesan pagos ni se almacenan correos.

## Límites y siguientes pasos
No incluye autenticación, backend, base de datos, inventario, pagos ni pedidos reales. Las puntuaciones, precios y descuentos son datos de muestra. La PWA es una base instalable; no es una app nativa ni incluye APK. Antes de un uso comercial, validar precios, condiciones, políticas, derechos de imágenes y el formato del teléfono de contacto.
