# Cómo se hizo esta página (guion para escenario)

Documento para que William lea o paraphrase en la charla. Narrativa real del making-of con Grok Bot.

---

## El pitch en una frase

Esta landing es la demo: un brief en chat → gabinete de bots → scaffold HTML/CSS → copy en español → mapa de orquestación + potencial → pulido visual y docs. Sin npm, sin frameworks. Solo Grok Bot + archivos estáticos.

## Acto 1 — El brief (19 sep 2026)

- Evento: SpaceX Santa Cruz, talk sobre Grok Bot.
- Objetivo: presentarme + mostrar qué se puede hacer; la demo vivo = esta página.
- Fuera de scope: productos y campañas que no pertenecen a esta charla.
- Idioma: español (es-BO), tono “tú”.
- Secciones fijadas: Quién soy · Qué es Grok Bot · Mapa de orquestación · Potencial · Demo timeline · Proceso y viabilidad.

Grok Bot dejó `index.html` con placeholders, `styles.css` dark base y `docs/BRIEF.md`.

## Acto 2 — El gabinete (modelo mental)

No es un solo bot mágico. Es un equipo con RACI práctico. Ver **`docs/ORQUESTACION.md`** para el mapa completo.

| Rol | Qué hace |
|-----|----------|
| Orquestador (“Jefe”) | Interpreta el brief, integra HTML, cuida el scope y los repos |
| Research | Clarifica audiencia y límites de mensaje |
| Marketing / copy | Textos listos para hablar, sin anglicismos sueltos |
| Landing / UI | Estructura, cards, timeline, mobile |
| Auditor | Scope, contraste, idioma |
| Scout / validator | Valida ideas; no construye producto |

Tú decides prioridades y repos; ellos ejecutan en paralelo cuando conviene. Cada sprint deja TIMELOG.

## Acto 3 — Sprint de cierre (23 sep 2026)

Cuatro días después del scaffold:

1. Placeholders `[Copy X Marketing]` → copy real en español.
2. CSS: nav sticky, cards, mapa de orquestación, timeline, contraste, mobile.
3. Docs: este PROCESO, TIMELOG, checklist, **ORQUESTACION.md**, **POTENCIAL.md**, README.
4. Push solo al repo autorizado por el humano.

## Acto 4 — Potencial demostrado

Mismo sistema, otros frentes (sep 14–23): ops de marketing multi-bot, research de Hackathon Web3 CRM, Auto Research Pipeline (solo validación de ideas), y esta landing. Detalle en **`docs/POTENCIAL.md`**.

## Acto 5 — Qué decir sobre viabilidad

- **Simple:** brief claro + HTML estático + un idioma + roles.
- **Cuidado:** no inventar fechas/fotos; respetar scope y repos; legibilidad en proyector.
- **Replicable:** con brief + 1–2 horas enfocadas, cualquiera en la audiencia puede sacar una landing así.

## Cierre sugerido

> “No les estoy vendiendo una idea abstracta. Les estoy mostrando el archivo y el mapa del gabinete. Abrí `index.html` — y en `docs/` está cómo orquesta el Jefe y cuánto potencial ya demostramos.”
