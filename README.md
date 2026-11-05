# Reto · Proyecto intermodular · DAW (2.º de DAW)

**CIFP Zornotza LHII · curso 2026-27 · módulo 0616 Proyecto intermodular (Proyecto de desarrollo de aplicaciones web) · 50 h · grado superior**

> Este repositorio es el enunciado del reto. Lo que construyáis se publica en la web de proyectos del centro:
> [`CIFPZornotzaLHII/proyectos_intermodulares`](https://github.com/CIFPZornotzaLHII/proyectos_intermodulares).

## Qué es el proyecto intermodular

Es el módulo que une todo lo demás: en vez de aprender una cosa por módulo, cogéis una necesidad real y la
resolvéis usando lo que sabéis de varios módulos a la vez. Se evalúa con los resultados de aprendizaje (RA) del
módulo, que son estos:

| RA | Qué tenéis que demostrar |
|---|---|
| RA1 | Identifica necesidades del sector productivo y las relaciona con proyectos tipo que las puedan satisfacer. |
| RA2 | Diseña un proyecto relacionado con las competencias del título, incluyendo y desarrollando las fases que lo componen. |
| RA3 | Planifica la ejecución del proyecto: plan de intervención y documentación asociada. |
| RA4 | Define los procedimientos de seguimiento y control de la ejecución del proyecto. |

## El reto

Un cliente real o realista (un comercio, una asociación, el propio centro) necesita una aplicación web. Vuestro grupo
identifica la necesidad, diseña la solución, la planifica, construye un **MVP que funciona** y define cómo se hace
el seguimiento y control del proyecto. El MVP tiene que estar desplegado (servidor del aula, Isard o similar) y
ser usable en la demo: registro o login si procede, datos reales o de prueba, al menos un flujo completo de principio
a fin.

El módulo de proyecto no evalúa cuánto código habéis escrito, sino si sabéis llevar un proyecto web de la necesidad al
despliegue: análisis, diseño, plan, ejecución controlada y presentación.

## Qué tiene que entregar cada grupo

- **Landing page** de presentación del proyecto con las seis secciones que se evalúan: necesidad, solución, planificación, demo, seguimiento y control, equipo. Se publica en la web del centro (plantilla en el repo de la web).
- **Tarjeta** en la web de proyectos: la carpeta `proyectos/<ciclo>/<tu-proyecto>/` con `proyecto.json` (título, resumen, equipo, portada, vídeo, repo). La etiqueta de grado la pone la web.
- **Vídeo de presentación de 5 minutos** en el que se ve al equipo hablando y la pantalla, en este orden: solución, planificación, mini demo, seguimiento y control. Se enlaza (YouTube o Drive del centro), no se sube al repo.
- **Documento de planificación** y **registro de seguimiento** (plantillas en `plantillas/`), enlazados desde la landing.
- **MVP funcional** relacionado con tu ciclo: algo que se pueda usar de verdad en la demo, aunque sea pequeño. Un prototipo en papel o una presentación no vale.

### Cómo se publica

1. Fork de [`CIFPZornotzaLHII/proyectos_intermodulares`](https://github.com/CIFPZornotzaLHII/proyectos_intermodulares) y clonarlo.
2. Copiar `proyectos/_plantilla/` a `proyectos/WG/<nombre-del-proyecto>/` y rellenar `proyecto.json` y `index.html`.
3. Abrir una **pull request** que solo toque esa carpeta. El robot comprueba las reglas; el profesor la acepta y el servidor se actualiza solo.
4. El vídeo puede llegar en una segunda pull request cuando esté grabado.

Guía paso a paso: [`proyectos/LEEME.md`](https://github.com/CIFPZornotzaLHII/proyectos_intermodulares/blob/main/proyectos/LEEME.md).

## Fases y horas (50 h del módulo)

| Fase | Horas | Qué se hace | Entregable / hito |
|---|---|---|---|
| 0 · Arranque | 2 | Equipos, lectura del reto, elección de idea (de `IDEAS.md` o propia, aprobada por el profesor) | Equipo e idea registrados |
| 1 · Análisis | 6 | Necesidad real, cliente o sector, cómo se hace ahora, alternativas | Ficha de análisis (sección 1 de la planificación) |
| 2 · Diseño y planificación | 8 | Alcance, requisitos, diseño o arquitectura, tareas con estimación, riesgos, recursos y presupuesto | **Hito 1**: planificación aprobada |
| 3 · Ejecución | 22 | Construir el MVP, integrando lo que se trabaja en los otros módulos. Registro de seguimiento semanal | **Hito 2**: revisión intermedia con demo parcial |
| 4 · Cierre | 8 | Landing, vídeo, pull request, registro de seguimiento final | Proyecto publicado en la web |
| 5 · Defensa | 4 | Presentación ante el equipo docente: vídeo (5 min) + preguntas (5 min) | Defensa |

Las 50 h son las del módulo. El trabajo técnico del MVP se apoya en lo que hacéis en los otros módulos del ciclo (es un proyecto *intermodular*); en estas horas se analiza, planifica, integra, documenta, publica y defiende.
Las fechas concretas de cada hito las fija el profesor al inicio del curso y se anotan en `CALENDARIO.md`.

## Evaluación

La nota sale de la rúbrica de [`EVALUACION.md`](EVALUACION.md): planificación, ejecución (MVP), seguimiento y control, publicación (landing y tarjeta) y vídeo + defensa. Cada RA está asociado a uno o varios entregables, así que si falta un entregable, falta un RA.

## Ideas

Veinte ideas de partida, pensadas con las tecnologías que trabajáis en el ciclo, en [`IDEAS.md`](IDEAS.md). Podéis
proponer otra: la condición es que tenga un cliente o necesidad identificable y que se pueda construir un MVP en el tiempo del módulo.

## Plantillas

- [`plantillas/planificacion.md`](plantillas/planificacion.md): documento de planificación (análisis, alcance, tareas, riesgos, presupuesto).
- [`plantillas/seguimiento.md`](plantillas/seguimiento.md): registro semanal de seguimiento y control.
- [`plantillas/guion-video.md`](plantillas/guion-video.md): guion del vídeo de 5 minutos.

## Normas

- **Equipos** de 2 o 3 personas. Cada persona tiene tareas asignadas y visibles en la planificación: en la defensa se pregunta a cada uno por lo suyo.
- **Honestidad en el seguimiento.** Un plan que "salió perfecto" sin desviaciones es sospechoso. Se valora detectar el problema, decidir y dejarlo escrito.
- **Inteligencia artificial.** Se puede usar para investigar, redactar y programar, con dos condiciones: se indica dónde se ha usado y tenéis que ser capaces de explicar y modificar lo que entreguéis. En la defensa se comprueba.
- **Plagio.** Copiar un proyecto ajeno (o entregar algo que no entendéis) suspende el módulo.
- **Vídeos y ficheros grandes** no se suben al repositorio: se enlazan.
- **Idioma.** Landing, vídeo y defensa en el idioma del grupo (castellano o euskera); la terminología técnica en inglés se usa con naturalidad (RA de comunicación).

## Calendario

Fechas de cada hito en [`CALENDARIO.md`](CALENDARIO.md) (las fija el profesor al inicio del curso).
