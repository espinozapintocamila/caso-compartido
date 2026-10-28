---
status: framed
segment: Team Leads y mandos medios, empleados de la cuenta, que conducen 2 o más reuniones de Teams de más de 5 participantes por semana, en cuentas Business Premium de 100+ licencias, sector tecnología, operación en 3+ países, facturación > USD 100M (12.400 cuentas)
personas: diego-herrera, patricia-soto
reconstructed: 2026-10-28 — a partir de la encuesta y la guía del curso (`product/surveys/2026-10-21-1944-…`, `product/interview-guides/2026-10-21-2030-…`); el brief original no venía en el material
---

# Oportunidad: El trabajo colaborativo de las reuniones grandes se hace fuera de Teams

Los Team Leads de empresas de tecnología multipaís sacan de Teams el trabajo que el grupo hace junto en sus reuniones de más de 5 personas (aportar ideas, ordenar, votar, editar, revisar datos y decidir) y lo llevan a Miro, Notion, Jira u otras herramientas: parte del grupo queda mirando la pantalla de otro y la decisión termina repartida en varias herramientas. Importa ahora porque IT paga Teams y además herramientas paralelas, y eso frena que las cuentas suban a Business Max.

## Segmento y personas

- Diego Herrera (primary) — lo sufre: en casi todas sus reuniones pega links a Miro, Notion o Jira; la mitad del equipo abre el link y el resto se pierde mirando la pantalla compartida
- Marcela Fuentes (primary) — no lo sufre: comparte un Excel en pantalla y no trabaja con el grupo en herramientas externas; además, su empresa (retail) está fuera del segmento
- Patricia Soto (tertiary) — no lo sufre; decide el upgrade y ve que las áreas contratan Miro o Notion por su cuenta. Responde la creencia de viabilidad
- Javier Molina (negative) — no lo sufre: solo asiste a las reuniones
- Falta: Team Lead de una empresa de tecnología con equipos en 3 o más países, cuyas decisiones terminan en Jira o Confluence (la encuesta del curso lo llama "perfil Joaquín"; no está en `product/personas/`)

## Señales

| Señal | Origen | Fuente |
|---|---|---|
| En el 29% de las reuniones de más de 5 se comparte en el chat un enlace a una herramienta externa | unverified | `product/overview.md` (cifra del brief) |
| El 19% de los comentarios negativos post-reunión son sobre la colaboración durante la reunión | unverified | `product/overview.md` |
| Whiteboard se usa en el 5% de las reuniones; las notas de reunión, en el 8% | unverified | `product/overview.md` |
| El 37% de las organizaciones tiene además Slack o Google Chat activo en al menos un equipo | unverified | `product/overview.md` |
| "El equipo ya usa otras herramientas" es la tercera razón de las bajas de plan y no renovaciones | unverified | `product/overview.md` |
| Links a Miro, Notion y Jira en casi todas sus reuniones; la mitad del equipo se pierde | synthetic | persona diego-herrera |
| Las áreas contratan Miro o Notion por su cuenta y después piden integrarlas | synthetic | persona patricia-soto |
| Encuesta de 249 respuestas | survey (pendiente de análisis) | `product/surveys/2026-10-25-1800-respuestas-colaboracion-en-vivo-fuera-de-teams.csv` |
| 10 entrevistas | real (pendiente de extraer insights) | `product/interviews/2026-10-26-*.md` |

## Resultado de negocio

Comercial — upgrade: que las cuentas Business Premium del segmento suban a Business Max (USD 8 por usuario al mes).

## Restricciones

- El segmento son 12.400 cuentas; la telemetría solo ve los enlaces pegados en el chat, no las herramientas abiertas de otra forma (encuesta del curso).
- La gerencia de TI bloquea lo que sume tickets de soporte o herramientas paralelas (persona patricia-soto).
- Hay cuentas con operación en España: riesgo regulatorio en la Unión Europea (encuesta del curso, D1).
- La etapa del curso cierra el 25-11-2026.

## Creencias

Referencias a `product/overview.md` (registro único de creencias):

- [opportunity: colaboracion-en-vivo-fuera-de-teams] [value] Los Team Leads del segmento sacan el trabajo colaborativo de Teams porque la colaboración nativa no cubre lo que necesitan hacer en vivo, no por hábito, por invitados externos ni porque el artefacto ya viva afuera. (#3)
- [opportunity: colaboracion-en-vivo-fuera-de-teams] [value] El tablero o documento externo se crea para esa reunión, y no es algo que ya existía y sigue vivo afuera (si fuera lo segundo, el problema sería de integración, no de colaboración en vivo). (#4)
- [opportunity: colaboracion-en-vivo-fuera-de-teams] [value] Lograr que todos los participantes entren a la herramienta externa toma 5 minutos o más por reunión. (#5)
- [opportunity: colaboracion-en-vivo-fuera-de-teams] [value] Lo que más le cuesta al Team Lead es que el grupo converja a una decisión y que esa decisión quede registrada y se cumpla, y hoy eso ocurre fuera de Teams. (#6 — se cruza con #1 de `reuniones-sin-cierre`)
- [opportunity: colaboracion-en-vivo-fuera-de-teams] [viability] Si la colaboración en vivo de las reuniones de más de 5 queda cubierta dentro de Teams, las cuentas Business Premium del segmento suben a Business Max, porque IT deja de pagar herramientas paralelas. (#7)

## Agenda de investigación

| Creencia | Instrumento | Decisión que destraba | Para cuándo |
|---|---|---|---|
| #3, #4, #5, #6 | Encuesta ya hecha: `/analyze-survey` con el CSV y `product/surveys/2026-10-21-1944-colaboracion-en-vivo-fuera-de-teams.md` | Si se sale de Teams por falta de función o por desconocimiento (#3), si el problema es de colaboración en vivo o de integración (#4), si el umbral de 5 minutos se cumple (#5) | Antes del 2026-11-04 |
| #3, #4, #6 | 10 entrevistas ya hechas: `/extract-insights` sobre `product/interviews/` | Qué actividad tendría que cubrir cualquier solución, y si la palanca es facilitar y registrar decisiones | Antes del 2026-11-04 |
| #7 | Entrevistas con TI (ronda aparte) · Datos del producto: tasa de upgrade de cuentas con apps como Miro integradas · `/research-market` sobre precios de Miro, FigJam y Loop | Si cubrir esto mueve el upgrade a Max | Antes del 25-11-2026 |

## Ideas candidatas (no evaluadas)

- Apps de Miro, FigJam y otras herramientas dentro de la reunión
- Whiteboard o Loop mejorados para trabajar en vivo
- Capacidades de IA para facilitar y registrar decisiones (las menciona la encuesta del curso)
