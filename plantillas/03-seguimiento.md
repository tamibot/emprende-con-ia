# 3 · Seguimiento automático

La mayoría de las ventas no se pierden por precio: se pierden porque nadie volvió a escribir.
El seguimiento necesita una regla, una lista y unos mensajes. Los tres están aquí.

## 3.1 · La regla de toques

Un «toque» es un mensaje que no recibió respuesta. Usamos esta regla en Creators Latam:

| Tipo de cliente | Toques | Cuándo |
|---|---|---|
| **Con interés claro** (pidió precio, tiene fecha o presupuesto) | Hasta 5 | Día 0 · mismo día (+3 h) · día 1 · día 3 · día 7 → después, **llamar** |
| **Resto** | Hasta 2 | Primer mensaje + un recordatorio → después, se archiva |

Si el cliente responde, se acaba lo automático: le contestas tú, leyendo la conversación.

## 3.2 · Mensajes por toque

Cortos, sin presión y sin pegar los datos que el cliente llenó en un formulario.

| Toque | Mensaje |
|---|---|
| 1 | Hola [nombre], soy [tu nombre] de [negocio]. Te escribo por [lo que consultó]. ¿Lo sigues buscando? |
| 2 | Te dejo [el precio / el catálogo / la propuesta] por aquí, para que lo revises con calma. |
| 3 | Hola [nombre], ¿pudiste revisarlo? Si te sirve, lo vemos en una llamada de 10 minutos. |
| 4 | Esta semana tengo espacio para [entregar / atender] el [día]. ¿Te lo separo? |
| 5 | Te escribo por última vez para no llenarte de mensajes. Si más adelante lo necesitas, aquí estoy. |

## 3.3 · La lista (Google Sheets o Excel)

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

## 3.4 · «¿A quién le escribo hoy?»

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

## 3.5 · Cuando quieras que corra solo

El paso siguiente es que la lista se actualice sola y los mensajes salgan a su hora: un CRM con WhatsApp
(por ejemplo Kommo) o una automatización con n8n. Primero haz que la regla funcione a mano durante dos
semanas; después automatiza lo que ya funciona.

> Regla: no automatices el desorden. Si a mano no sabes a quién escribirle, una herramienta tampoco lo
> sabrá.
