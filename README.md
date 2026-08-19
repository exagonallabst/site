# Regalo sorpresa 💌

Página interactiva de regalo sorpresa (bienvenida → menú → fotos, canción, carta y razones).

## Personalizar
Abre `index.html` y busca los comentarios `<!-- EDITA: ... -->` para:
- Cambiar el nombre
- Escribir tu propia carta
- Poner tu canción de YouTube (reemplaza VIDEO_ID)
- Agregar tus fotos (reemplaza los recuadros punteados)
- Editar la lista de razones

## Desplegar en Railway
1. Sube esta carpeta a un repo de GitHub
2. En railway.app → New Project → Deploy from GitHub repo
3. Elige el repo (Railway detecta Node con package.json y ejecuta `npm start`)
4. En Settings → Networking → Generate Domain para obtener tu link público

## Desplegar en GitHub Pages (alternativa)
1. Sube el repo a GitHub
2. Settings → Pages → Branch: main, carpeta /root → Save
3. Tu link: https://tu-usuario.github.io/nombre-repo/
