# 📝 Registro de decisiones

> [← Volver al inicio](../README.md)

Cada decisión que afecta al equipo queda aquí, **la más reciente arriba**. Formato inspirado en los *Architecture Decision Records* (ADR).

| ID | Fecha | Decisión | Estado | Quién |
|:--:|:-----:|----------|:------:|:-----:|
| D-003 | 2026-11-19 | Plataforma del espacio de conocimiento | 🟡 Propuesta | Julián |
| D-002 | 2026-11-17 | Markdown como formato base del contenido | 🟢 Aceptada | Juan |
| D-001 | 2026-11-12 | No pagar Teams mientras validamos la idea | 🟢 Aceptada | Julián |

---

## D-003 · Plataforma del espacio de conocimiento

| | |
|---|---|
| **Estado** | 🟡 Propuesta, se decide en la reunión |
| **Propone** | Juan |
| **Decide** | Julián |

**Contexto.** Tres personas con cuentas Claude Max necesitan compartir conocimiento como lo haría un Project de Teams.

**Opciones.** Google Drive, OneDrive, GitHub, Confluence. Ver la [comparativa](02-comparativa-plataformas.md).

**Propuesta.** Confluence (plan Free).

**Consecuencias**
- ➕ Navegación tipo wiki, plantillas y macros.
- ➕ Conector oficial para Claude.
- ➖ Una herramienta más para la nueva persona.

---

## D-002 · Markdown como formato base

**Contexto.** No queremos quedar atados a una plataforma.

**Decisión.** El contenido se escribe pensando en Markdown: títulos, tablas, listas y bloques de código. Nada que dependa de una función exclusiva de una herramienta.

**Consecuencias.** Cualquier documento se puede mover entre GitHub, Google Docs y Confluence con una conversión automática.

---

## D-001 · Sin plan Teams por ahora

**Contexto.** Teams cobra por puesto y aún no sabemos si el proyecto despega.

**Decisión.** Cada uno mantiene su cuenta Max y compartimos el conocimiento por fuera de Claude.

**Revisión.** Volver a evaluarlo en **marzo de 2027** o si el equipo pasa de cinco personas.

---

<details>
<summary>📋 Plantilla para una decisión nueva</summary>

```markdown
## D-00X · Título corto

| | |
|---|---|
| **Estado** | 🟡 Propuesta / 🟢 Aceptada / 🔴 Rechazada |
| **Propone** | Nombre |
| **Decide** | Nombre |

**Contexto.** Qué problema hay.

**Opciones.** Qué se consideró.

**Decisión.** Qué se eligió.

**Consecuencias.** Qué gana y qué pierde el equipo.
```

</details>
