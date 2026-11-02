# 4 · Comercial: atención por WhatsApp y seguimiento hasta el cierre

Tres niveles. Empieza por el primero: es gratis y se arma en una tarde.

| Nivel | Qué es | Costo |
|---|---|---|
| 1 | **WhatsApp Business**: mensaje de bienvenida, mensaje de ausencia, respuestas rápidas, catálogo y etiquetas | Gratis |
| 2 | **Asistente con IA** que responde con la información de tu negocio y te pasa lo importante | Bajo costo |
| 3 | **Todo en un solo lugar**: un CRM como Kommo con WhatsApp conectado (WAHA o la API oficial); la IA atiende o supervisa a tus asesores | De pago |

## 4.1 · La ficha de tu negocio (llénala una sola vez)

Todo lo que responde la IA sale de aquí. Si no está en la ficha, la IA no debe inventarlo.

```
NEGOCIO: [nombre] · [qué vendes, en una línea]
ZONA Y HORARIO: [distritos que atiendes] · [días y horas]
PRODUCTOS Y PRECIOS:
- [producto 1]: S/ [precio] · [qué incluye]
- [producto 2]: S/ [precio] · [qué incluye]
CÓMO SE COMPRA: [anticipación, adelanto, medios de pago]
DELIVERY: [zonas y costo]
PREGUNTAS FRECUENTES:
- [pregunta] → [respuesta]
- [pregunta] → [respuesta]
LO QUE NO HACEMOS: [por ejemplo: no hacemos envíos a provincia]
TONO: [cercano / formal] · trato de «tú» · sin exagerar
```

## 4.2 · Instrucciones del asistente

Pégalas en un chat nuevo junto con la ficha, o guárdalas en un proyecto (Claude), un GPT (ChatGPT) o un
Gem (Gemini) para no repetirlas.

```
Eres el asistente de WhatsApp de [negocio]. Respondes a clientes con la información de la FICHA
y nada más.

Reglas:
1. Responde en 2 o 3 líneas, en el tono de la ficha, tratando de «tú».
2. Si el dato no está en la FICHA, no lo inventes: di que lo confirmas con el equipo.
3. Termina cada respuesta con una pregunta que acerque la venta
   (fecha, cantidad, distrito, forma de pago).
4. Pasa la conversación a una persona y escribe «PASAR A PERSONA: [motivo]» cuando:
   - el cliente quiere confirmar un pedido o pagar,
   - hay una queja o un problema con un pedido,
   - pide un precio especial o algo fuera de la ficha,
   - no estás seguro de la respuesta.
5. Nunca prometas fechas, descuentos ni resultados que no estén en la FICHA.

FICHA:
[pega aquí la ficha 4.1]
```

Para probarlo, escribe tú como si fueras un cliente: una pregunta de precio, una de delivery, un pedido
y una queja. Corrige la ficha cada vez que el asistente dude.

## 4.3 · Diez respuestas rápidas para WhatsApp Business (nivel 1, gratis)

En WhatsApp Business: **Herramientas para la empresa → Respuestas rápidas**. Se usan escribiendo «/» y el
atajo.

| Atajo | Mensaje |
|---|---|
| /hola | Hola, gracias por escribirnos. Soy [nombre] de [negocio]. ¿En qué te ayudo? |
| /precios | Te comparto nuestros precios: [lista corta]. ¿Cuál te interesa? |
| /catalogo | Aquí tienes nuestro catálogo: [link]. Si algo te gusta, dime cuál y te paso los detalles. |
| /delivery | Hacemos delivery a [zonas] por S/ [costo]. ¿A qué distrito sería? |
| /horario | Atendemos de [días] de [hora] a [hora]. |
| /pago | Puedes pagar con [Yape / Plin / transferencia]. Te paso los datos cuando confirmes tu pedido. |
| /pedido | Para separar tu pedido necesito: fecha, cantidad y distrito. |
| /gracias | Gracias por tu compra. Cualquier cosa, aquí estamos. |
| /seguimiento | Hola, ¿pudiste revisar lo que te envié? Si tienes alguna duda, te ayudo. |
| /fuera | Ahora estamos fuera de horario. Te respondemos [mañana] desde las [hora]. |

Los mensajes de bienvenida y de ausencia se activan en el mismo menú. Usa las **etiquetas** para ordenar:
«Nuevo», «Cotizado», «Pagado», «Seguimiento».

> Regla: la IA atiende y ordena; tú cierras. Todo lo que tenga plata o una queja de por medio lo ve una
> persona.

## Seguimiento hasta el cierre

La mayoría de las ventas no se pierden por precio: se pierden porque nadie volvió a escribir.
El seguimiento necesita una regla, una lista y unos mensajes. Los tres están aquí.

## 4.4 · La regla de toques

Un «toque» es un mensaje que no recibió respuesta. Usamos esta regla en Creators Latam:

| Tipo de cliente | Toques | Cuándo |
|---|---|---|
| **Con interés claro** (pidió precio, tiene fecha o presupuesto) | Hasta 5 | Día 0 · mismo día (+3 h) · día 1 · día 3 · día 7 → después, **llamar** |
| **Resto** | Hasta 2 | Primer mensaje + un recordatorio → después, se archiva |

Si el cliente responde, se acaba lo automático: le contestas tú, leyendo la conversación.

## 4.5 · Mensajes por toque

Cortos, sin presión y sin pegar los datos que el cliente llenó en un formulario.

| Toque | Mensaje |
|---|---|
| 1 | Hola [nombre], soy [tu nombre] de [negocio]. Te escribo por [lo que consultó]. ¿Lo sigues buscando? |
| 2 | Te dejo [el precio / el catálogo / la propuesta] por aquí, para que lo revises con calma. |
| 3 | Hola [nombre], ¿pudiste revisarlo? Si te sirve, lo vemos en una llamada de 10 minutos. |
| 4 | Esta semana tengo espacio para [entregar / atender] el [día]. ¿Te lo separo? |
| 5 | Te escribo por última vez para no llenarte de mensajes. Si más adelante lo necesitas, aquí estoy. |

## 4.6 · La lista (Google Sheets o Excel)

Usa el archivo **seguimiento-clientes.xlsx** (se abre en Google Sheets: Archivo → Importar). Una fila por
cliente:

| Columna | Qué va |
|---|---|
| Cliente | Nombre |
| Qué pidió | En pocas palabras |
| Interés | Claro / Resto |
| Último mensaje | Fecha en que le escribiste |
| Toque | 1 a 5 |
| ¿Respondió? | Sí / No |
| Próximo paso | Lo calcula la hoja según la regla |

## 4.7 · «¿A quién le escribo hoy?»

Copia tu lista (o descárgala como CSV) y pégala con este texto:

```
Esta es mi lista de clientes en seguimiento. Hoy es [fecha].
Regla: los de interés «Claro» reciben hasta 5 toques (día 0, +3 horas, día 1, día 3, día 7)
y después se llaman; el «Resto», hasta 2 toques y se archivan.
Si un cliente respondió, no le toca mensaje automático: márcalo para responder a mano.

1. Dime a quién le toca escribir hoy, ordenado por prioridad.
2. Redacta cada mensaje: máximo 2 líneas, trato de «tú», sin presión,
   mencionando solo lo que pidió.
3. Lista aparte a quién hay que llamar y a quién archivar.

LISTA:
[pega aquí tu lista]
```

Revisa los mensajes antes de enviarlos: la IA redacta, tú envías.

## 4.8 · Cuando quieras que corra solo

El paso siguiente es que la lista se actualice sola y los mensajes salgan a su hora: un CRM con WhatsApp
(por ejemplo Kommo) o una automatización con n8n. Primero haz que la regla funcione a mano durante dos
semanas; después automatiza lo que ya funciona.

> Regla: no automatices el desorden. Si a mano no sabes a quién escribirle, una herramienta tampoco lo
> sabrá.

## 4.9 · Remarketing

```
Estos son los clientes que preguntaron y no compraron en los últimos 30 días: [lista con qué pidieron].
Agrúpalos por motivo probable (precio, tiempo, dudas, no respondieron) y propón para cada grupo
un mensaje de WhatsApp y un anuncio de remarketing. Nada de presión: una razón nueva para volver.
```
