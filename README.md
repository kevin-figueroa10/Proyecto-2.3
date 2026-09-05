# DevTrack Pro — GitHub Pages

Proyecto de portafolio de mesa de ayuda / gestión de incidencias.

## Tecnologías
- HTML5
- CSS3
- JavaScript
- LocalStorage

## Funciones
- Inicio de sesión demo con roles Administrador, Técnico y Usuario
- Dashboard de métricas
- Crear y editar tickets
- Estados, prioridades y categorías
- Asignación de tickets a técnicos
- Comentarios e historial
- Gestión de usuarios
- Búsqueda y filtros
- Exportación CSV
- Respaldo JSON
- Diseño responsive

## Usuarios demo
- Administrador: `admin@devtrack.local` / `admin123`
- Técnico: `tecnico@devtrack.local` / `tecnico123`
- Usuario: `usuario@devtrack.local` / `usuario123`

## Publicar en GitHub Pages
1. Crea un repositorio en GitHub.
2. Sube `index.html`, `styles.css`, `app.js` y `README.md` a la raíz.
3. Ve a **Settings > Pages**.
4. En **Build and deployment**, elige **Deploy from a branch**.
5. Selecciona la rama **main** y la carpeta **/(root)**.
6. Guarda y espera a que GitHub muestre la URL pública.

## Nota
Es una demo de portafolio sin backend ni base de datos. La autenticación y los datos se guardan en el navegador mediante LocalStorage, por lo que no es adecuada para datos sensibles ni para uso empresarial real.
