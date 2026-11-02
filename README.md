# Emprende con IA

Guía práctica para usar **Claude** en cada área de tu emprendimiento, del **CODE Talk «Emprende con IA»**
(sábado 14 de noviembre de 2026), por **Martín Velasco**, fundador de Creators Latam y Partner de Kommo.

*Emprende con Inteligencia: menos operatividad, más escalabilidad.*

- **La presentación completa:** [`deck/emprende-con-ia.pdf`](deck/emprende-con-ia.pdf)
- **El kit con todos los prompts:** [`plantillas/kit-emprende-con-ia.pdf`](plantillas/kit-emprende-con-ia.pdf)

---

## La idea en tres frases

1. **Primero, que toda tu información entre a un solo lugar:** correo, WhatsApp (con WAHA, incluidos los grupos),
   calendario y archivos. Sin información, la IA adivina.
2. **Un proyecto por emprendimiento y un agente por área:** estratégico, marketing, comercial, administrativo,
   operativo y legal.
3. **Lo que funciona, a una skill:** cuando un pedido queda bien, dile a Claude *«guarda esto como skill»* y todo tu
   equipo lo reutiliza. La IA hace el borrador; tú apruebas.

## Empieza en 4 pasos

| # | Qué | Costo |
|---|---|---|
| 1 | Cuenta de Claude (plan Pro o superior) y **Claude Code** desde la app de escritorio | Desde US$ 20 al mes |
| 2 | Cuenta de **GitHub** | Gratis |
| 3 | Un **VPS** con [WAHA](https://github.com/devlikeapro/waha), [n8n](https://github.com/n8n-io/n8n) y una base de datos (pídeselo a Claude) | ≈ US$ 20 al mes |
| 4 | En Claude Code: omitir permisos (solo en tus proyectos), GitHub, navegador (**Google Chrome con la misma sesión de correo**), artefactos y permiso para instalar skills | — |

Detalle paso a paso: [`plantillas/01-configurar-claude.md`](plantillas/01-configurar-claude.md).

## Estructura recomendada

```
mi-emprendimiento/
├── CLAUDE.md          el negocio en una página: qué vendes, a quién, precios, tono y reglas
├── estrategico/       idea, mercado, cliente ideal
├── marketing/         landing, anuncios, contenido
├── comercial/         CRM, atención, seguimiento
├── administrativo/    SUNAT, caja
├── operativo/         agenda, tareas
└── legal/             contratos, datos personales
```

Cada agente tiene cuatro piezas: **una instrucción** (qué hace y qué no), **un disparador** (cuándo corre),
**permisos** (qué puede leer y tocar) y **dónde entrega** (un borrador, una tarea o un reporte; nunca envía solo).

## Plantillas por área

| Archivo | Qué trae |
|---|---|
| [`01-configurar-claude.md`](plantillas/01-configurar-claude.md) | Instalación, centralizar la información, ajustes, estructura y skills |
| [`02-estrategico.md`](plantillas/02-estrategico.md) | Agente autocrítico que te entrevista, panel simulado, Biblioteca de anuncios de Meta y validación en 7 días |
| [`03-marketing.md`](plantillas/03-marketing.md) | Landing y presentación, checklist de lanzamiento, anuncios con IA, pauta conectada y contenido |
| [`04-comercial.md`](plantillas/04-comercial.md) | Ficha del negocio, asistente de WhatsApp, respuestas rápidas, regla de seguimiento y remarketing |
| [`seguimiento-clientes.xlsx`](plantillas/seguimiento-clientes.xlsx) | Hoja que calcula a quién escribir hoy (se abre en Google Sheets) |
| [`05-administrativo-y-legal.md`](plantillas/05-administrativo-y-legal.md) | Borrador de la declaración ante SUNAT, flujo de caja en tres escenarios, agenda y contratos |
| [`06-hoja-de-ruta.md`](plantillas/06-hoja-de-ruta.md) | Un área por semana durante un mes y qué medir |
| [`demos/`](demos/) | Los textos exactos de las tres demos en vivo y cómo salen normalmente |

## El prompt que más usamos

```
Actúa como un analista de mercado escéptico, justo y neutral. Sé muy autocrítico con mi idea:
sin favoritismo, sin halagos y sin suavizar. Si es débil, dímelo y explícame por qué.
Antes de opinar, entrevístame: una pregunta a la vez.
Al final dame la probabilidad realista de éxito, los tres riesgos principales, el cliente ideal,
cómo le hablaría y qué probar primero con poca plata.
Mi idea: [tu idea]
```

Cuando quede bien: *«Guarda este proceso como una skill llamada validar-idea»*.

## Skills para instalar primero

Se instalan con `npx skills add <repositorio>`.

| Skill | Para qué | Repositorio |
|---|---|---|
| find-skills | Buscar e instalar skills nuevas | [vercel-labs/skills](https://github.com/vercel-labs/skills) |
| caveman | Respuestas cortas: gasta menos y va más rápido | [JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman) |
| ponytail | Hacer lo mínimo que funciona | [DietrichGebert/ponytail](https://github.com/DietrichGebert/ponytail) |
| copywriting | Textos, CRO, SEO y marketing | [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills) |
| UI/UX | Páginas y apps profesionales | [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) |
| remotion | Videos con código | [remotion-dev/skills](https://github.com/remotion-dev/skills) |
| hyperframes | Videos desde HTML | [heygen-com/hyperframes](https://github.com/heygen-com/hyperframes) |
| skills de Anthropic | Documentos, PDF, Excel y presentaciones | [anthropics/skills](https://github.com/anthropics/skills) |

## Reglas para no equivocarte

- La IA hace el borrador; **una persona revisa antes de enviar o publicar**.
- Si un dato no está en tu información, la IA **no debe inventarlo**.
- **No automatices el desorden:** primero que funcione a mano, después que corra solo.
- Meta Ads, el CRM y tus cuentas se conectan por **conector (MCP) o app propia**, no por el navegador.
- SUNAT y contratos: Claude prepara el borrador; **lo revisa tu contador o tu abogado**.

## Sígueme

Martín Velasco · Fundador de Creators Latam · Partner de Kommo · Cofundador de TamiBot y DOXS.AI

- WhatsApp: +51 995 547 575
- Correo: mvelascoo@tamibot.com
- LinkedIn: [linkedin.com/in/mvelasco97](https://linkedin.com/in/mvelasco97)
- Web: [creatorslatam.com](https://creatorslatam.com)
- TikTok: [@__conceptstudio](https://www.tiktok.com/@__conceptstudio)
- YouTube: [@_creatorslatam](https://www.youtube.com/@_creatorslatam)
- Instagram: [@_creatorslatam](https://www.instagram.com/_creatorslatam)

Si te sirvió, dale una estrella al repositorio y compártelo con otro emprendedor.
