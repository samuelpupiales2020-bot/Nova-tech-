# NovaTech — tienda tecnológica

Prototipo académico responsive de una tienda de accesorios tecnológicos. HTML5, CSS3 y JavaScript, con imágenes locales incluidas en `assets/` para que el catálogo no dependa de servicios de fotografías externos.

## Contenido
- `index.html` / `NovaTech.html`: web principal.
- `assets/`: fotografías recortadas de la maqueta visual generada para este concepto.
- `manifest.json` y `sw.js`: base de Progressive Web App (PWA).
- `Informe_NovaTech.docx`: informe académico.
- `INFORME.md`: resumen de la memoria técnica.

## Probar en local
La página puede abrirse con `index.html`, pero para probar el service worker/PWA se recomienda un servidor local:

```bash
python -m http.server 8000
```

Después abre `http://localhost:8000` en el navegador.

## Publicar en GitHub + Netlify
1. Crea un repositorio vacío en GitHub.
2. Copia el contenido de esta carpeta a la raíz del repositorio.
3. En la terminal dentro de la carpeta ejecuta:

```bash
git init
git add .
git commit -m "feat: publicar prototipo NovaTech"
git branch -M main
git remote add origin https://github.com/USUARIO/novatech-store.git
git push -u origin main
```

Sustituye `USUARIO` por tu nombre de usuario real. Si el repositorio ya tiene remoto, verifica su dirección antes de agregar otro.
4. En Netlify selecciona **Add new site → Import an existing project**, conecta GitHub y elige el repositorio.
5. Deja **Build command** vacío y establece **Publish directory** como `.`.
6. Pulsa **Deploy site** y verifica la URL pública. Los siguientes `git push` vuelven a desplegar el sitio.

## Límites de la demo
Los productos, precios y puntuaciones son demostrativos. El carrito calcula un total de muestra, pero no crea pedidos ni procesa pagos. El formulario no guarda correos. La entrega es una web responsive con base PWA, no un APK nativo de Android/iOS.
