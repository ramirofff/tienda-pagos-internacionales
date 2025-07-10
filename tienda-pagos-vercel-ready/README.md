# Tienda Pagos Internacionales

Este repositorio contiene la aplicación Next.js configurada para despliegue en Vercel.

## Estructura

- `app/` – Contiene la carpeta App Router de Next.js, con un único `layout.jsx` en la raíz.
- `package.json` – Dependencias y scripts.
- `.gitignore` – Archivos ignorados para Git.

## Despliegue en Vercel

1. Crea un nuevo repositorio en GitHub (o GitLab).
2. Clona localmente o sube directamente este proyecto.
3. Inicializa Git y sube a tu remoto:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin <URL de tu repo>
   git push -u origin main
   ```
4. Ve a [Vercel](https://vercel.com/) y conecta tu repositorio.
5. Vercel detectará Next.js automáticamente y desplegará sin errores de layout.

¡Listo! Tu aplicación estará online inmediatamente.