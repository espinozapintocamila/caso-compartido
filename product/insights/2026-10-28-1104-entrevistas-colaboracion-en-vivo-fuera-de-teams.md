---
source: real
opportunity: colaboracion-en-vivo-fuera-de-teams
guide: product/interview-guides/2026-10-21-2030-colaboracion-en-vivo-fuera-de-teams.md
transcripts:
  - product/interviews/2026-10-26-0900-javier-molina.md
  - product/interviews/2026-10-26-0930-martina-rojas.md
  - product/interviews/2026-10-26-1000-diego-paredes.md
  - product/interviews/2026-10-26-1000-tomas-aguirre.md
  - product/interviews/2026-10-26-1100-andres-quintero.md
  - product/interviews/2026-10-26-1200-sofia-martinez.md
  - product/interviews/2026-10-26-1400-paula-benitez.md
  - product/interviews/2026-10-26-1500-valeria-castro.md
  - product/interviews/2026-10-26-1600-lucia-fernandez.md
  - product/interviews/2026-10-26-1700-ricardo-salinas.md
survey_analysis: product/insights/2026-10-28-1059-encuesta-colaboracion-en-vivo-fuera-de-teams.md
n: 10
date: 2026-10-28
---

# Insights: entrevistas sobre trabajo colaborativo en reuniones grandes

> Caso didáctico: las entrevistas son ficticias. Se tratan como `source: real` porque así las entrega el curso.

**Quiénes:** 10 líderes de empresas SaaS de 650 a 2.000 empleados, con equipos en 3 o 4 países (México, Colombia, Argentina, Chile, Perú y España). Siete del panel y tres del email. La selección incluyó a quienes contradicen las creencias: cuatro casi no salen de Teams (Andrés, Lucía, Paula, Ricardo) y cuatro trabajan sobre un artefacto que ya existía (Martina, Diego, Sofía, Javier).

**Lo que más se repite:** en las 10 entrevistas aparece una decisión que se perdió o se entendió distinto entre la reunión y la ejecución, con un costo concreto. Ninguna otra cosa aparece tanto.

## 1. La decisión se pierde entre la reunión y la ejecución, y el registro lo hace a mano el líder (10 de 10)

Los 10 relatan un caso reciente en que lo decidido se perdió o se entendió distinto: una release movida, dos semanas de desarrollo rehechas, una semana de un diseñador en algo descartado, un cliente esperando cuatro días, una migración rota con un fin de semana de guardia. En 8 de 10, el registro lo hace el propio líder después de la reunión, sin que nadie lo vea, y le toma entre 10 minutos y una hora por reunión: reescribe el recap, manda un correo, pasa los acuerdos a Jira. Cualquier solución debe cerrar la reunión con **decisión, responsable y fecha confirmados en el momento** y llevarlos a donde trabaja el equipo (Jira, Confluence, el correo que revisa auditoría). Esa es la palanca, más que la pizarra.

> Evidencia: "Desde entonces, después de cada planning, reescribo el recap. Media hora, más o menos. Una lista: decisión, responsable, fecha… Es trabajo mío, nadie más lo hace. Y si no lo hago, vuelve a pasar" — Javier Molina · "Saqué capturas del tablero y después me pasé casi una hora pasando todo a Jira… Y un diseñador trabajó una semana entera en algo que habíamos sacado" — Valeria Castro · "Se habló en la sync, cada uno se fue con su versión y nadie lo escribió" — Ricardo Salinas

## 2. El resumen de IA resume la conversación, no las decisiones, y cuando se confía en él provoca errores (6 de 10)

Seis lo usan o lo probaron, y todos describen la misma falla. Pone todo al mismo nivel, convierte ideas en decisiones, no dice quién se comprometió a qué y no ve lo que pasó en la herramienta externa (la votación en FigJam) ni qué datos se miraban (el filtro del dashboard). En dos casos el error del recap llegó a la ejecución: México entendió que la API no era prioridad y Porto Alegre empezó una integración que no estaba aprobada. Martina lo abandonó; Paula y Javier lo corrigen siempre. Mejorar el recap para que **separe decisiones, responsables y fechas, lo deje confirmar al líder e incorpore lo que pasó en lo compartido** es mejorar algo que ya se adopta.

> Evidencia: "El recap resume todo al mismo nivel. Dos páginas. No distingues qué se decidió de qué se comentó" — Javier Molina · "Marca como decisión cosas que eran solo ideas… Perdimos más o menos una semana de dos desarrolladores" — Paula Benítez · "No ve lo que pasó en el FigJam, solo lo que se habló… el resumen decía 'se discutieron prioridades'. Pues sí, gracias" — Valeria Castro

## 3. Lo que se trabaja dentro de Teams se pierde de una reunión a la siguiente; la continuidad es la razón para quedarse en Miro (6 de 10)

Cuatro perdieron una pizarra o unas notas de Teams porque quedaron atadas al chat de una reunión que después se reprogramó o se convocó de nuevo (Tomás, Sofía, Lucía, Paula). Dos explican que usan Miro justamente porque un tablero por trimestre les permite retomar los acuerdos anteriores (Tomás, Javier). Además, Whiteboard se abandona por lo que le falta: no tiene votación ni plantillas, agrupar es lento y se traba con 9 a 14 personas (Javier, Tomás, Sofía, Lucía, Ricardo). Lo que se cree dentro de una reunión tiene que vivir en la **serie o el proyecto**, no en la instancia del chat, y poder retomarse al empezar la siguiente.

> Evidencia: "A las dos semanas, para la retro siguiente, fui a buscarla y no estaba… se había recreado la serie de la reunión… Perdí los acuerdos, así de simple. Ahí dije: listo, volvemos a Miro" — Tomás Aguirre · "Desde entonces hago captura de pantalla al terminar y la pego en Confluence… Es cutre, pero es lo único que sé que voy a encontrar" — Lucía Fernández

## 4. Sobre la pantalla compartida solo opera quien comparte: el resto dicta y quien no puede entrar no objeta (7 de 10)

Cuando el trabajo vive en Jira, Excel, Power BI o Figma, la pantalla se comparte y el grupo no puede señalar ni tocar: "la de abajo, no, la otra". Andrés cerró el ticket equivocado y al cliente le llegó la notificación de cierre. Cuando el tablero es externo, quien no tiene licencia o cuenta dicta por el chat (Nico, Marta) o se queda mirando, y sus objeciones llegan tarde: Gloria contó en un café, una semana después, que no estaba de acuerdo con la prioridad. Valeria y Javier lo ponen por encima de los minutos de acceso. Hace falta **interactuar sobre lo que se comparte (señalar, marcar, comentar) sin salir de la reunión ni necesitar licencias**, para que participen también quienes no tienen acceso.

> Evidencia: "Ellos ven mi pantalla. No pueden marcar nada, no pueden señalar. Si pudieran apuntar con algo, me dirían 'esta' y listo" — Andrés Quintero · "La gente que no entra al tablero no es poca. En casi todas hay alguien mirando desde afuera, y esa gente no opina. Eso me preocupa más que los minutos" — Valeria Castro

## 5. Sin una forma confiable de converger, el líder termina decidiendo solo (6 de 10)

Priorizar se traba de 10 a 20 minutos y lo cierra el líder, a veces con desacuerdos que se notan en la cámara o que llegan después por privado (Javier, Martina, Tomás, Andrés, Sofía, Lucía). Votar con manos o reacciones no es confiable ("se me pasa uno porque la mano baja rápido") y en FigJam alguien votó dos veces. **Ojo:** dos líderes (Paula y Ricardo) dicen que una reunión de 14 a 16 personas no es para decidir, que las decisiones de verdad se toman después entre 3 o 4, y que votar con veinte "es dar la sensación de que todos participaron". Antes de diseñar votaciones conviene validar qué reuniones grandes son para decidir.

> Evidencia: "No hay forma de que cada uno marque su prioridad sin que se transforme en conversación. Hablamos veinte minutos. Al final decidí yo" — Martina Rojas · "En un review de catorce no se puede decidir, y no hace falta" — Paula Benítez

## Señales débiles

- **Compliance:** en Lucía (España, pagos), las herramientas externas con datos de clientes están prohibidas y aprobar una nueva toma meses; "lo nativo es lo único que tengo". Coincide con 5 menciones en la encuesta.
- **Desconocimiento de lo nativo:** Andrés no sabía que Teams tiene notas de reunión, Valeria que tiene pizarra, Ricardo que se pueden abrir otras herramientas dentro de la reunión.
- **Saltar entre ventanas** cuesta durante toda la reunión, no solo al entrar (Javier).
- **Acceso:** 3 de 10 pierden 5 minutos o más en reuniones internas (Javier por filiales con licencias distintas, Tomás por invitados sin licencia, Valeria por cuentas personales de Google). Los que entran con SSO no tienen fricción (Martina, Diego, Sofía).
- **Demasiadas reuniones:** Ricardo tiene 27 horas a la semana; fuera del alcance de esta oportunidad.

## Contraste con la encuesta

Las entrevistas explican el *por qué* de los números de la encuesta: el 24% de "no quedó registrado" y el 23% de "en un chat fuera de Teams" se ven como actas que hace el líder y como decisiones que viven en hilos de Slack (Javier, Martina). Las 24 menciones de "Otro" en Q9 sobre el recap son el insight 2. El 43% que dejó Whiteboard se explica por los insights 3 y 5.
