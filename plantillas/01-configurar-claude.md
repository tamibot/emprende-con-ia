# 1 · Configura tu Claude

Se hace una sola vez. Con esto Claude puede leer tu información, trabajar en tus archivos y conectarse a tus
herramientas.

## 1.1 · Lo que necesitas

| # | Qué | Costo aproximado |
|---|---|---|
| 1 | **Cuenta de Claude** (plan Pro o superior) e instalar **Claude Code** desde la app de escritorio | Desde US$ 20 al mes |
| 2 | **Cuenta de GitHub**: ahí se guardan tus proyectos y se instalan skills y repositorios | Gratis |
| 3 | **Un VPS** (servidor propio) con **WAHA** para WhatsApp, **n8n** para automatizaciones y tu **base de datos** | ≈ US$ 20 al mes |
| 4 | **Google Chrome** con la misma sesión de correo que usa tu Claude | Gratis |

Repositorios: WAHA en github.com/devlikeapro/waha · n8n en github.com/n8n-io/n8n.

## 1.2 · Primero, que entre toda la información

Antes de armar agentes, conecta tus fuentes para que la IA trabaje con datos y no adivine:

- **Correo** (Gmail): lo que te piden, lo que prometiste, lo que falta.
- **WhatsApp con WAHA**: chats y también **grupos**; la IA los lee y los analiza.
- **Calendario y archivos**: reuniones, propuestas y documentos.
- **Una base de datos** en tu VPS donde todo queda ordenado por cliente.

## 1.3 · Activa esto en Claude Code

| Opción | Para qué |
|---|---|
| **Omitir permisos** | Trabaja de corrido sin pedirte permiso a cada paso. Úsalo en tus proyectos, nunca con datos ajenos. |
| **GitHub conectado** | Guarda tu trabajo e instala skills y repositorios. |
| **Navegador** | Mejor Google Chrome, con la misma sesión de correo que usa tu Claude. |
| **Artefactos** | Presentaciones, landings y paneles que compartes con un link. |
| **Instalar skills y plugins** | Que pueda agregar herramientas nuevas cuando hagan falta. |

## 1.4 · Un proyecto por emprendimiento

```
mi-emprendimiento/
├── CLAUDE.md          el negocio en una página: qué vendes, a quién, precios, tono, reglas
├── estrategico/       idea, mercado, cliente ideal
├── marketing/         landing, anuncios, contenido
├── comercial/         CRM, atención, seguimiento
├── administrativo/    SUNAT, caja
├── operativo/         agenda, tareas
└── legal/             contratos, datos personales
```

Una carpeta por emprendimiento o cliente. Dentro, un especialista por área, cada uno con su sesión o rama.
Antes de pedir, ten claro qué quieres armar: la IA ejecuta mejor un pedido concreto.

## 1.5 · Skills para instalar primero

Se instalan con `npx skills add <repositorio>`. La primera te ayuda a encontrar las demás («busca una skill
para…»).

| Skill | Para qué | Repositorio |
|---|---|---|
| find-skills | Buscar e instalar skills nuevas | github.com/vercel-labs/skills |
| caveman | Respuestas cortas: gasta menos y va más rápido | github.com/JuliusBrussee/caveman |
| ponytail | Hacer lo mínimo que funciona, sin complicar | github.com/DietrichGebert/ponytail |
| copywriting | Textos, CRO, SEO y marketing | github.com/coreyhaines31/marketingskills |
| UI/UX | Diseño de páginas y apps profesionales | github.com/nextlevelbuilder/ui-ux-pro-max-skill |
| remotion | Videos con código: edición, subtítulos, gráficos | github.com/remotion-dev/skills |
| hyperframes | Videos desde HTML hechos por el agente | github.com/heygen-com/hyperframes |
| skills de Anthropic | Documentos, PDF, Excel y presentaciones | github.com/anthropics/skills |

Repositorios verificados el 1 de noviembre de 2026.
