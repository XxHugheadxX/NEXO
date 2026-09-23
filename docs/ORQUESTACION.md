# Orquestación — Jefe de gabinete y bots especialistas

Cómo Grok Bot trabaja como **bróker / Jefe de gabinete**: reparte trabajo, integra resultados y deja rastro. Basado en el uso real de William Yucra (sep 14–23 2026).

---

## Idea central

No es un solo bot que lo hace todo. Es un **gabinete**: el humano define objetivo y límites; el Jefe interpreta, asigna a especialistas, abre bucles de revisión y entrega artefactos listos (landing, docs, research packs). El humano siempre decide **scope** y **a qué repos se toca**.

## Mapa de roles (RACI simplificado)

| Rol | R (Responsible) | A (Accountable) | C (Consulted) | I (Informed) |
|-----|-----------------|-----------------|---------------|--------------|
| **Humano (William)** | Decide scope, repos, go/no-go | Dueño del resultado final | — | Recibe TIMELOG y entregables |
| **Jefe / orquestador** | Brief → plan → integración | Cumplir el brief sin salirse | Humano en dudas de scope | Especialistas al cerrar sprint |
| **Research** | Hechos, audiencia, límites de mensaje | Exactitud del research | Jefe | Marketing / copy |
| **Marketing / copy** | Textos en es-BO, tono “tú” | Copy listo para escenario | Research, Jefe | UI |
| **UI / landing** | HTML/CSS, estructura, mobile | Página presentable | Copy, Jefe | Auditor |
| **Auditor** | Checklist de scope, contraste, idioma | Nada fuera de brief | Jefe | Humano |
| **Scout / validator** | Validar ideas (sí/no + por qué), no construir producto | Criterio de viabilidad | Research | Jefe / humano |

RACI aquí es práctico: **quién escribe**, **quién responde si falla**, **quién se consulta**, **quién solo se entera**.

## Flujo típico (loop)

```
1. Humano → brief (objetivo, fuera de scope, idioma, repos permitidos)
2. Jefe → descompone en tickets por especialista
3. Especialistas → ejecutan (en paralelo si no hay dependencia)
4. Jefe → integra + pide Auditor / Scout cuando hace falta
5. TIMELOG → sesión, qué se hizo, artefactos
6. Humano → aprueba, ajusta scope, o abre otro loop
```

Bucles cortos > planes eternos. Si el scope cambia, el Jefe **no inventa repos**: pregunta o se queda en lo permitido.

## Especialistas en la práctica (sep 2026)

- **Research:** brief de audiencia, mensajes clave, qué no decir en público.
- **Marketing / copy:** landings, posts, guiones de charla en español claro.
- **UI / landing:** HTML/CSS estático, dark premium, sin npm.
- **Auditor:** scope (p. ej. sin pitch de producto ajeno a la charla), contraste, enlaces a docs.
- **Scout / validator:** pipelines de validación de ideas (investigación y criterio), **sin** construir el producto.

## TIMELOG y docs

Cada sprint relevante deja:

- `docs/TIMELOG.md` — fecha, sesión, qué, artefactos
- `docs/BRIEF.md` — acuerdo de kickoff
- Docs de proceso / orquestación / potencial — para narrar en escenario

Así el making-of se puede contar en vivo sin “confianza, créeme”.

## Reglas de oro del Jefe

1. **El humano manda el scope** (y los repos).
2. **Un especialista, un entregable** cuando se pueda medir.
3. **Integrar en el artefacto final** (HTML, MD), no dejar chat suelto.
4. **Auditar antes de “listo”** (idioma, fuera de scope, mobile).
5. **Registrar TIMELOG** para que el trabajo sea demostrable.

## Relación con esta landing

Esta página es un loop completo: brief → orquestación → copy + UI → docs → (push a un solo repo permitido). El mismo modelo escala a campañas de marca, research de hackathons y pipelines de validación de ideas.
