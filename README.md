# UX

Agentes personalizados de Claude Code para diseño de producto y UX.

## Qué es esto

Una colección de subagentes de Claude Code para trabajo de Product Design / UX. Cada agente es un archivo `.md` con sus instrucciones, listo para copiar a la carpeta `.claude/agents/` de cualquier proyecto.

## Agentes

Por ahora hay un agente, pero muy pronto habrá más.

| Agente | Qué hace |
|---|---|
| [`desi.md`](./desi.md) | Experta en Design Systems en Figma: audita librerías (variables, estilos, componentes, naming), diseña arquitectura de tokens y temas, y detecta deuda de sistema. |

## Cómo usarlos

1. Copia el `.md` del agente que te interese a `.claude/agents/` dentro de tu proyecto.
2. Ábrelo con Claude Code. Se invoca por su nombre en el chat (por ejemplo, "Desi, audita esta librería") o Claude lo detecta solo cuando la petición encaja con su descripción.

