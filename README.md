# Landing Speaker — Grok Bot @ SpaceX Santa Cruz

Landing estática en español para la charla de **William Yucra** sobre Grok Bot.
Demo en vivo: esta misma página, construida con Grok Bot.

## Abrir en local

No hay build ni npm.

1. Entra a la carpeta del proyecto.
2. Abre `index.html` en el navegador (doble clic, o arrastra el archivo a Chrome/Firefox/Safari).

Listo. Todo el CSS está en `styles.css` (fuentes del sistema, sin CDN).

## Qué incluye

| Ruta | Rol |
|------|-----|
| `index.html` | Página completa (hero + secciones) |
| `styles.css` | Tema oscuro, responsive |
| `docs/BRIEF.md` | Brief original del kickoff |
| `docs/PROCESO.md` | Guion del making-of para escenario |
| `docs/TIMELOG.md` | Log de sesiones (19 y 23 sep 2026) |
| `docs/CHECKLIST-EVENTO.md` | Checklist pre-charla |

## Subir a tu GitHub (cuando tengas el repo)

Desde tu máquina, con Git instalado:

```bash
cd grokbot-speaker-landing
git init
git add .
git commit -m "Landing speaker Grok Bot — SpaceX Santa Cruz"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/TU_REPO.git
git push -u origin main
```

O sube el ZIP desde la UI de GitHub: **Add file → Upload files**.

### Hosting estático rápido

- **GitHub Pages:** Settings → Pages → branch `main` / root.
- **Netlify / Cloudflare Pages:** arrastra la carpeta o conecta el repo.
- La home debe apuntar a `index.html`.

## Scope

- Idioma: español (es-BO), tono “tú”.
- Fuera de scope: Tangem, campañas crypto, npm.
- Solo HTML/CSS estático.

## Licencia / uso

Uso personal de William Yucra para la charla en SpaceX Santa Cruz.
