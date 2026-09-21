# YAYA — Desiertos de cuidados y plan de guarderías, CDMX

App interactiva del Datatón ITAM 2026. Es un solo archivo estático (`index.html`)
con los datos incrustados; no necesita servidor, base de datos ni claves.
La única dependencia externa es la librería D3 (se carga desde cdnjs).

## Cómo publicarla con "yaya" en la dirección

**Opción 1 — GitHub Pages (recomendada, dirección `TU-USUARIO.github.io/yaya`)**
1. Crea un repositorio público llamado exactamente `yaya`.
2. Sube estos tres archivos a la raíz: `index.html`, `.nojekyll`, `README.md`.
3. En el repo: Settings → Pages → Source: "Deploy from a branch" → Branch: `main` / `(root)` → Save.
4. En 1-2 minutos queda en `https://TU-USUARIO.github.io/yaya/`.

**Opción 2 — Netlify Drop (dirección `yaya-cdmx.netlify.app`, 2 minutos)**
1. Entra a app.netlify.com/drop y arrastra la carpeta `yaya-web` completa.
2. Site settings → Change site name → escribe `yaya-cdmx` (o el que esté libre).

**Opción 3 — Vercel (`yaya-cdmx.vercel.app`)**
1. vercel.com/new → importa la carpeta o el repo → Project name: `yaya-cdmx` → Deploy.

Todas son gratuitas y públicas: cualquiera con la liga puede usar la app sin cuenta.
Para actualizarla, sustituye `index.html` y vuelve a subir.
