---
status: framed
segment: Team Leads y mandos medios que convocan y conducen reuniones recurrentes de seguimiento de más de 5 personas en Teams
personas: marcela-fuentes, diego-herrera, patricia-soto
---

# Oportunidad: Reuniones de seguimiento que no cierran

Quienes conducen reuniones recurrentes en Teams las ven alargarse más allá de lo agendado y terminar sin acuerdos con responsable y fecha, y por eso repiten temas o convocan reuniones extra. Importa ahora porque "pagamos por funciones que no usamos" es la primera razón de las cuentas que bajan de plan o no renuevan.

## Segmento y personas

- Marcela Fuentes (primary) — lo sufre: su reunión de los lunes dura casi 2 horas y casi nunca termina a tiempo; los acuerdos quedan en su cuaderno o en el chat y repite tareas
- Diego Herrera (primary) — lo sufre: planning y retro de más de una hora; rehízo trabajo por una decisión que nadie vio
- Patricia Soto (tertiary) — no lo sufre; decide si la cuenta renueva o baja de plan, así que responde la creencia de viabilidad
- Javier Molina (negative) — no lo sufre como problema propio: sufre las reuniones largas como asistente, pero no las conduce; queda fuera como límite de alcance
- Falta: alguien que conduzca reuniones en una cuenta de más de 1.000 licencias (esas cuentas concentran el 58% de las licencias; Marcela ~400 y Diego ~80 no las representan)

## Señales

| Señal | Origen | Fuente |
|---|---|---|
| El 26% de los comentarios negativos post-reunión son "demasiadas reuniones" o reuniones demasiado largas | unverified | `product/overview.md` (cifra del brief, sin fuente) |
| El 23% de las reuniones supera la hora; el 41% tiene más de 8 participantes | unverified | `product/overview.md` |
| El usuario promedio del segmento corporativo pasa 11,4 h a la semana en reuniones | unverified | `product/overview.md` |
| Las notas de reunión se usan en el 8% de las reuniones | unverified | `product/overview.md` |
| Reunión semanal de casi 2 h que nunca termina a tiempo; acuerdos que nadie encuentra a la semana | synthetic | persona marcela-fuentes |
| Planning y retro de más de 1 h; decisiones que nadie vio y trabajo rehecho | synthetic | persona diego-herrera |
| "Pagamos por funciones que no usamos" es la primera razón de las bajas de plan y no renovaciones | unverified | `product/overview.md` |
| "No compro funciones, compro que la gente las use" | synthetic | persona patricia-soto |

## Resultado de negocio

Comercial — retención: bajar el 3,6% de cuentas que bajan de plan o no renuevan.

## Restricciones

- Teams lo contrata y despliega el área de IT de cada organización; los empleados no eligen sus herramientas.
- La gerencia de TI bloquea lo que sume tickets de soporte o herramientas paralelas (persona patricia-soto).
- La etapa del curso cierra el 25-11-2026.

## Creencias

Referencias a `product/overview.md` (registro único de creencias):

- [opportunity: reuniones-sin-cierre] [value] Quienes conducen reuniones recurrentes de seguimiento terminan la mayoría pasadas de hora o sin acuerdos con responsable y fecha, y por eso repiten temas en la reunión siguiente o convocan reuniones extra cada semana. (#1)
- [opportunity: reuniones-sin-cierre] [viability] Las cuentas donde quienes conducen dejan acuerdos registrados en Teams bajan de plan o dejan de renovar menos que las que no, porque IT ve uso real de lo que paga. (#2)

## Agenda de investigación

| Creencia | Instrumento | Decisión que destraba | Para cuándo |
|---|---|---|---|
| #1 | Datos del producto: duración real vs. agendada en reuniones recurrentes · Encuesta (`/design-survey`) a quienes conducen: cuántas de sus reuniones terminan tarde o sin acuerdos, cuántas reuniones extra convocan · Entrevistas (`/design-interview`, reclutadas entre quienes acepten en la encuesta): por qué no cierran | Seguir con esta oportunidad o cambiar de problema | Primera quincena de noviembre 2026 |
| #2 | Datos del producto: renovación de cuentas que usan notas o tareas de reunión vs. las que no · `/research-market` sobre retención y herramientas de reuniones · Entrevistas a administradores de TI | Si justifica invertir frente a otras prioridades de Meetings | Antes del 25-11-2026 |

## Ideas candidatas (no evaluadas)

- Registro de acuerdos con responsable y fecha dentro de la reunión
- Agenda en vivo con tiempo por tema
- Resumen de acuerdos enviado al terminar la reunión
