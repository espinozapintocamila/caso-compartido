---
source: secondary
method: web
date: 2026-10-28
question: ¿Quién ya ataca las reuniones que no cierran (agenda, acuerdos, tareas) y cómo lo cobra? ¿Qué dicen los estudios públicos sobre reuniones sin acuerdos? ¿Hay evidencia de que la adopción real de funciones reduce las bajas de plan en software para empresas?
opportunity: reuniones-sin-cierre
---

# Research: reuniones que no cierran — mercado, estudios y adopción

> El caso es didáctico y sus cifras son ficticias; lo que sigue describe el mercado real. Sirve para contrastar el caso, no para confirmarlo.

Tres hallazgos cambian decisiones. **(1) El problema existe a escala:** en el estudio más grande encontrado (31.000 personas, 31 mercados), el 55% dice que al terminar una reunión los próximos pasos no quedan claros, y "reuniones ineficientes" es el obstáculo de productividad número uno. **(2) El espacio de soluciones ya está ocupado, y casi siempre como un pago extra:** Microsoft cobra el resumen inteligente con tareas en Teams Premium (USD 10 por usuario al mes), Zoom lo incluye en sus planes pagados y Google lo ofrece en Workspace con Gemini; Fellow cobra desde USD 7. En el caso, entonces, la pregunta no es "¿falta esta función?", sino "¿por qué quienes conducen no la usan?" (las notas de reunión aparecen solo en el 8% de las reuniones del caso). **(3) La evidencia de que más adopción da menos bajas es débil:** viene de proveedores de software de customer success, es correlacional y las cifras más citadas no tienen la fuente original a la vista.

## Competidores directos

| Producto | Qué hace contra "reuniones que no cierran" | Precio | Fuente |
|---|---|---|---|
| Microsoft Teams Premium | Resumen inteligente: notas generadas, tareas recomendadas, capítulos y momentos destacados | USD 10 por usuario al mes, pago anual; prueba de 30 días | [verificado: microsoft.com/en-us/microsoft-teams/premium — 2026-10-28]; [verificado: microsoft.com, blog 2023-02-01 — 2026-10-28] |
| Microsoft 365 Copilot (en Teams) | Resumen y tareas, además de conversar con Copilot sobre la transcripción; recordatorios de tareas | ~USD 30 por usuario al mes sobre Microsoft 365 (cifra de blogs, no de Microsoft) | [verificado: copilot-experts.com, notes-so.pages.dev — 2026-10-28; precio sin confirmar en microsoft.com] |
| Zoom AI Companion | Resumen y tareas extraídas al terminar; invita a compartir los próximos pasos en el chat | Sin costo extra en las cuentas pagadas; Pro desde ~USD 13,33 por usuario al mes (cifra de terceros) | [verificado: blog de Zoom en careers.zoom.us; nota de prensa en nasdaq.com — 2026-10-28] |
| Google Meet + Gemini ("Take notes for me") | Notas en tiempo real, decisiones y "próximos pasos sugeridos", que requieren revisión manual | Incluido en algunos planes de Workspace (Business Standard en adelante, según terceros) | [verificado: blog.google; workspace.google.com — 2026-10-28; lista de planes sin confirmar] |
| Fellow | Agenda compartida antes de la reunión; tareas con responsable y fecha, con seguimiento; se integra con Teams | Gratis (limitado); Team USD 7, Business USD 15 por usuario al mes, pago anual (hay listados con otras cifras) | [verificado: spendflo.com, getapp.com — 2026-10-28; sin confirmar en fellow.app] |
| Otter, Fireflies, Read.ai y otros asistentes de notas | Transcripción, resumen y tareas en Teams, Zoom y Meet | desconocido (no revisado) | [conocimiento del modelo — verificar] |

**Lo que prueba su existencia:** hay demanda pagada por "salir de la reunión con acuerdos y tareas"; los tres grandes de videollamadas lo convirtieron en parte de su oferta pagada. **Lo que no prueba:** que quienes conducen lo usen ni que esto cambie la renovación. Que exista una función no significa que se adopte, y ese es justamente el hueco que muestra el caso.

## Alternativas y no consumo

- Cuaderno personal, chat de la reunión, un Excel o un correo de seguimiento tras la reunión [conocimiento del modelo — verificar]. Coincide con lo que hace la persona sintética Marcela (cuaderno y chat).
- Planner o To Do alimentados a mano o con Power Automate desde el resumen [verificado: notes-so.pages.dev — 2026-10-28].
- "Nada": nadie registra y el líder vuelve a preguntar en la reunión siguiente [conocimiento del modelo — verificar].

## Precios y modelos de negocio

- **Modelo dominante: complemento pagado por usuario** (Teams Premium a USD 10, Copilot a ~USD 30) o **incluido en el plan pagado** (Zoom, Google). Las herramientas independientes (Fellow) cobran entre USD 7 y 25 por usuario al mes.
- Microsoft movió algunas funciones de Teams Premium a Teams Enterprise desde el 1 de abril de 2026; no está claro cuáles [verificado: microsoft.com/en-us/licensing/news/microsoft365-teams-2025 — 2026-10-28, detalle sin confirmar].
- En el caso, el salto Premium → Max cuesta USD 8. Esa cifra queda dentro del rango del mercado real (USD 7–10) para este tipo de capacidades.

## Posicionamiento

- **Espacio lleno:** "la IA toma notas y tareas por ti". Todos los grandes lo dicen casi con las mismas palabras.
- **Menos lleno:** lo que pasa **durante** la reunión para que cierre a tiempo (agenda con tiempo por tema, decidir antes de terminar) y **el seguimiento la semana siguiente** (¿se cumplió lo acordado?). Fellow es el único revisado que pone la agenda en el centro. Hay quejas de que las tareas sugeridas requieren revisión y distribución manual [verificado: guía de terceros sobre Gemini — 2026-10-28].

## Tendencias y estudios sobre reuniones

- **Microsoft Work Trend Index 2023** (31.000 personas, 31 mercados, del 1 de febrero al 14 de marzo de 2023): las reuniones ineficientes son el obstáculo de productividad número uno; el **55%** dice que los próximos pasos no quedan claros al final de la reunión y el **56%** que cuesta resumir lo que pasó [verificado: microsoft.com/en-us/worklab/work-trend-index/will-ai-fix-work — 2026-10-28].
- **Bain & Company:** "dos tercios de las reuniones terminan antes de que los participantes puedan tomar decisiones importantes" (artículo de 2010, sin metodología publicada en la página) [verificado: bain.com/insights/most-meetings-end-before-decisions-are-made — 2026-10-28]. Es antiguo y no tiene método visible: sirve como señal, no como dato.
- **Atlassian 2024** (5.000 trabajadores): el 54% sale de las reuniones sin claridad sobre los próximos pasos o sobre quién es responsable [verificado: citado por un blog de terceros — 2026-10-28; informe original no revisado].
- **Cronofy 2026:** el 52% señala la falta de acciones claras de seguimiento como la razón principal de que las reuniones no sirvan [verificado: cronofy.com/meeting-efficiency-report-2026 — 2026-10-28; solo el resumen].
- Las definiciones cambian de un estudio a otro ("próximos pasos poco claros", "decisiones importantes", "seguimiento"): no se pueden sumar ni promediar.

## Adopción y bajas de plan (viabilidad)

- Gainsight presenta la tasa de adopción de funciones como la señal más importante de si un cliente renueva, amplía o se va [verificado: gainsight.com/blog/product-adoption — 2026-10-28]. Es la opinión de un proveedor de software de retención.
- "El 67% de las bajas en SaaS se explica por baja adopción" (atribuido a Gainsight) y "quien deja de usar funciones avanzadas tiene 3,8 veces más riesgo de irse" (atribuido a Bridge Group): **citas de segunda mano sin la fuente original** [verificado como cita: gigacatalyst-lp.pages.dev, pulserevops.com — 2026-10-28; datos de origen no verificados].
- No se encontró ningún estudio controlado que muestre que subir la adopción *causa* menos bajas: la evidencia es correlacional.

## Impacto en creencias

| Creencia (de overview.md) | Veredicto | Evidencia |
|---|---|---|
| #1 [opportunity: reuniones-sin-cierre] [value] Quienes conducen terminan la mayoría de sus reuniones pasadas de hora o sin acuerdos, y por eso repiten temas o convocan reuniones extra | apoya (en el mercado, no en el caso) | El 55% dice que los próximos pasos no quedan claros [verificado: Work Trend Index 2023]; el 54% en Atlassian 2024 [cita de terceros]. Pero son personas que *asisten*, no solo quienes *conducen*, y nadie mide "repiten temas" ni "reuniones extra". |
| #2 [opportunity: reuniones-sin-cierre] [viability] Las cuentas donde se registran acuerdos en Teams bajan de plan o dejan de renovar menos | apoya débil | La adopción se usa como señal de renovación en la industria [verificado: gainsight.com], pero los números más citados no tienen fuente a la vista y la relación es correlacional. Además, las funciones ya existen y se cobran aparte (Teams Premium, Copilot): el riesgo es pagarlas y no usarlas, que es justo la queja del caso. |

## Qué sigue necesitando research primario

- **Datos del producto (en el caso):** duración real frente a la agendada en reuniones recurrentes (#1); renovación de las cuentas que usan notas o tareas de reunión frente a las que no (#2). Es lo más barato y lo que más podría desmentir.
- **Encuesta** (`/design-survey`) a quienes conducen: cuántas de sus reuniones recurrentes terminan tarde o sin acuerdos con responsable y fecha, cuántas veces repiten un tema o convocan otra reunión, y si usan hoy alguna función de notas, resumen o tareas (#1).
- **Entrevistas** (`/design-interview`): por qué no cierran; qué hacen hoy con los acuerdos; por qué no usan las notas o el resumen que ya existen (#1). A administradores de TI: qué miran en los reportes de uso al decidir la renovación (#2).
- Desconocido: si las funciones que se movieron a Teams Enterprise en abril de 2026 incluyen el resumen con tareas, y los precios actuales de Copilot y Fellow en sus páginas oficiales.
