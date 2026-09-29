# Checklist

Un check más, un problema menos.

Web app de una sola página (HTML, CSS y JavaScript, sin dependencias ni build) para organizar tus tareas del día.

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo `checklist`).
2. Sube los archivos de esta carpeta a la raíz del repositorio: `index.html`, `.nojekyll` y `README.md`.
3. Ve a **Settings → Pages**.
4. En **Build and deployment**, elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`. Pulsa **Save**.
5. Espera un minuto. Tu app estará en `https://TU-USUARIO.github.io/checklist/`.

## Desde la terminal

```bash
git init
git add .
git commit -m "Checklist"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/checklist.git
git push -u origin main
```

Después activa Pages como en los pasos 3 y 4.
