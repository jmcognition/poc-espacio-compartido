# ⚖️ Comparativa de plataformas

> [← Volver al inicio](../README.md)

Cuatro candidatas para alojar el espacio de conocimiento. La pregunta no es cuál es mejor en general, sino **cuál le sirve a un equipo de tres con cuentas Claude Max**.

## Vista rápida

| Criterio | <img src="https://cdn.simpleicons.org/googledrive" width="16"> Google Drive | <img src="https://cdn.simpleicons.org/microsoftonedrive/0078D4" width="16"> OneDrive | <img src="https://cdn.simpleicons.org/github" width="16"> GitHub | <img src="https://cdn.simpleicons.org/confluence" width="16"> Confluence |
|----------|:---:|:---:|:---:|:---:|
| Conector nativo en Claude | ✅ | ⚠️ | ✅ | ✅ |
| Edición fácil para no técnicos | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐ | ⭐⭐⭐⭐ |
| Historial de versiones | ⭐⭐⭐ | ⭐⭐⭐ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐ |
| Estructura y navegación | ⭐⭐ | ⭐⭐ | ⭐⭐⭐ | ⭐⭐⭐⭐⭐ |
| Plan gratuito suficiente | ✅ | ✅ | ✅ | ✅ *(hasta 10 usuarios)* |
| Curva de aprendizaje | Baja | Baja | Media | Media |

<sub>✅ sí · ⚠️ parcial · ❌ no — valoraciones del equipo, no mediciones.</sub>

## Puntaje ponderado

```mermaid
%%{init: {"theme": "base", "themeVariables": {"xyChart": {"plotColorPalette": "#4338ca"}}}}%%
xychart-beta
    title "Puntaje ponderado (sobre 100)"
    x-axis ["Google Drive", "OneDrive", "GitHub", "Confluence"]
    y-axis "Puntos" 0 --> 100
    bar [74, 61, 70, 86]
```

## Detalle por opción

<details>
<summary><b>📁 Google Drive</b>: lo que todos ya conocen</summary>

<br>

**A favor**
- Cero curva de aprendizaje.
- Conector oficial en Claude.
- Comentarios y sugerencias excelentes.

**En contra**
- Los documentos se pierden en carpetas; no hay navegación de "wiki".
- Fácil terminar con `Copia de Copia de Contexto (final) v2`.

</details>

<details>
<summary><b>☁️ OneDrive</b>: si el equipo vive en Microsoft 365</summary>

<br>

**A favor**
- Integrado con Word, Teams y Outlook.

**En contra**
- Nadie del equipo lo usa a diario.
- Soporte en Claude menos directo.

</details>

<details>
<summary><b>🐙 GitHub</b>: Markdown puro y versionado perfecto</summary>

<br>

**A favor**
- Historial completo, *diffs* y revisiones.
- Markdown es el formato nativo de Claude.
- Claude Code trabaja directamente sobre el repo.

**En contra**
- Intimidante para quien no programa.
- Editar desde el navegador funciona, pero no se siente como un documento.

</details>

<details>
<summary><b>📘 Confluence</b>: una wiki de verdad</summary>

<br>

**A favor**
- Árbol de páginas, plantillas, menciones, tareas.
- Macros visuales: paneles, estados, índices.
- Juan ya lo usa a diario.
- Conector oficial de Atlassian para Claude.

**En contra**
- Atlassian insiste con correos para pasar a pago.
- El plan gratuito tiene límites de almacenamiento y de permisos finos.

</details>

## Recomendación

> [!TIP]
> **Confluence como espacio principal**, con la opción de exportar a Markdown si algún día migramos. Para tres personas el plan gratuito alcanza con holgura.

> [!WARNING]
> Los correos de Atlassian pidiendo datos de pago son **comerciales**: el plan Free no vence. Conviene revisar los límites vigentes antes de decidir.

## Matriz esfuerzo / valor

```mermaid
quadrantChart
    title Esfuerzo de adopción vs. valor para el equipo
    x-axis Bajo esfuerzo --> Alto esfuerzo
    y-axis Bajo valor --> Alto valor
    quadrant-1 Vale la pena
    quadrant-2 Ganancia rápida
    quadrant-3 Evitar
    quadrant-4 Solo si sobra tiempo
    Google Drive: [0.2, 0.62]
    OneDrive: [0.35, 0.4]
    GitHub: [0.7, 0.68]
    Confluence: [0.55, 0.85]
```
