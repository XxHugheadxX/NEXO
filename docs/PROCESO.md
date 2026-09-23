# Cómo se hizo esta página (guion para escenario)

Documento para que William lea o paraphrase en la charla. Narrativa real del making-of con Grok Bot.

---

## El pitch en una frase

Esta landing es la demo: un brief en chat → scaffold HTML/CSS → copy en español → pulido visual y docs de escenario. Sin npm, sin frameworks. Solo Grok Bot + archivos estáticos.

## Acto 1 — El brief (19 sep 2026)

- Evento: SpaceX Santa Cruz, talk sobre Grok Bot.
- Objetivo: presentarme + mostrar qué se puede hacer; la demo vivo = esta página.
- Fuera de scope: productos y campañas que no pertenecen a esta charla.
- Idioma: español (es-BO), tono “tú”.
- Secciones fijadas: Quién soy · Qué es Grok Bot · Cómo gestiona el trabajo · Demo timeline · Proceso y viabilidad.

Grok Bot dejó `index.html` con placeholders, `styles.css` dark base y `docs/BRIEF.md`.

## Acto 2 — El equipo de bots (modelo mental)

No es un solo bot mágico. Es un equipo:

| Rol | Qué hace |
|-----|----------|
| Orquestador (“Jefe”) | Interpreta el brief, integra HTML, cuida el scope |
| Research | Clarifica audiencia y límites de mensaje |
| Marketing / copy | Textos listos para hablar, sin anglicismos sueltos |
| Landing / UI | Estructura, cards, timeline, mobile |

Tú decides prioridades; ellos ejecutan en paralelo cuando conviene.

## Acto 3 — Sprint de cierre (23 sep 2026)

Cuatro días después del scaffold:

1. Placeholders `[Copy X Marketing]` → copy real en español.
2. CSS: nav sticky, cards, timeline visual, contraste, mobile.
3. Docs de escenario: este PROCESO, TIMELOG, checklist pre-charla, README.
4. ZIP listo para subir a GitHub Pages / Netlify / cualquier hosting estático.

## Acto 4 — Qué decir sobre viabilidad

- **Simple:** brief claro + HTML estático + un idioma.
- **Cuidado:** no inventar fechas/fotos; respetar scope; legibilidad en proyector.
- **Replicable:** con brief + 1–2 horas enfocadas, cualquiera en la audiencia puede sacar una landing así.

## Cierre sugerido

> “No les estoy vendiendo una idea abstracta. Les estoy mostrando el archivo. Abrí `index.html` y esto es lo que salió del chat con Grok Bot.”

