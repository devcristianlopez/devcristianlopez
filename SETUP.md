# 🚀 Guía de instalación — Perfil GitHub de `devcristianlopez`

Este repo contiene el README de perfil (repositorio especial `devcristianlopez/devcristianlopez`),
el header animado y el workflow que genera la serpiente de contribuciones.

## 1. Publicar el perfil

GitHub solo muestra el README del perfil si el repositorio se llama **igual que tu usuario** y es **público**.

### Opción A — con GitHub CLI (recomendado)

Desde esta carpeta:

```bash
git init -b main
git add .
git commit -m "feat: cyberpunk profile README"
gh repo create devcristianlopez/devcristianlopez --public --source=. --remote=origin --push
```

> La cuenta autenticada en `gh` es `devcristianlopez`, así que el repo quedará en tu cuenta.

### Opción B — desde la web

1. Crea un repo público llamado exactamente `devcristianlopez`.
2. Sube `README.md`, la carpeta `assets/` y `.github/workflows/snake.yml`.

## 2. Personalizar los `TODO`

Busca y reemplaza en `README.md`:

| Placeholder | Dónde | Qué poner |
| :--- | :--- | :--- |
| `TODO: Tu Nombre` | clase Python | tu nombre real o alias |
| `TODO: Ciudad, País` | clase + badge `LOCATION` | ej. `Santiago, Chile` |
| `TODO: tu@email.com` | clase Python | tu correo de contacto |
| `TODO: https://tu-web.dev` | clase Python | portafolio o blog |
| `TODO: https://linkedin.com/in/tu-usuario` | clase Python | tu LinkedIn |
| `TODO: https://x.com/tu-usuario` | clase Python | tu X / Twitter |
| `TODO: https://youtube.com/@tu-canal` | clase Python | tu canal (si tienes) |
| `href="TODO"` | sección `CONNECT` | reemplaza por tus URLs reales |
| `TODO` del badge `LOCATION` | badges superiores | ej. `Santiago-FF2A6D` (usa guiones, no espacios) |
| `coffee_level` | clase Python | tu nivel real de café ☕ |

Ejemplo rápido:

```bash
# nombre
sed -i 's/TODO: Tu Nombre/Tu Nombre/g' README.md
# ubicación en el badge
sed -i 's/LOCATION-TODO/LOCATION-Santiago/g' README.md
```

## 3. Activar la serpiente de contribuciones

La imagen `output/github-contribution-grid-snake-dark.svg` no existe hasta que corre el workflow.

1. Ve a **Settings → Actions → General**.
2. En *Workflow permissions* elige **Read and write permissions** → guarda.
3. Ve a **Actions → Generate Snake → Run workflow**.
4. Espera ~1 minuto: se crea la rama `output` con los SVG.
5. Recarga tu perfil.

El workflow corre solo cada 12 horas y en cada push a `main`.

## 4. Probar en local (opcional)

```bash
# validar SVG
rsvg-convert -w 1200 assets/header.svg -o /tmp/header.png

# previsualizar markdown
npx --yes markdown-preview-cli README.md   # o abre el repo en GitHub
```

## 5. Extras que puedes añadir después

- **Spotify Now Playing:** [spotify-github-profile](https://github.com/kittinan/spotify-github-profile) o `novatorem`.
- **Blog posts automáticos:** [blog-post-workflow](https://github.com/gautamkrishnar/blog-post-workflow).
- **Métricas avanzadas (auto-hospedadas):** [lowlighter/metrics](https://github.com/lowlighter/metrics) si quieres un panel 100% propio.
- **WakaTime:** `github-readme-stats/api/wakatime` (requiere cuenta y setup).
- **Record personal:** cambia el `<img src="./assets/header.svg">` por un GIF si prefieres aún más movimiento.

## 6. Problemas frecuentes

| Síntoma | Causa | Solución |
| :--- | :--- | :--- |
| El README no aparece en el perfil | Repo con otro nombre o privado | Debe ser público y llamarse `devcristianlopez` |
| El header no se ve | GitHub cacheó la imagen | Espera unos minutos o fuerza recarga (`Ctrl+Shift+R`) |
| La serpiente sale rota | El workflow aún no corrió | Ejecuta el workflow y verifica la rama `output` |
| Una tarjeta de stats no carga | Rate limit de la instancia pública | Recarga más tarde o auto-hospeda el servicio |
| Los badges muestran texto raro | Espacios en el valor | Usa `_` o `-` en lugar de espacios |

---

Hecho con demasiado café y un poco de código. ☕
