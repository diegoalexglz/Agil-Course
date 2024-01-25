# Introducción a la gestión ágil de proyectos

## Proyecto

> Definible

- Procesos claros
- Alcance definido

> De alta incertidumbre

- Cambios constantes
- Complejidad y riesgo alto

El enfoque ágil se diseñó para los proyectos de alta incertidumbre, abordándolos y adaptándose mediante la inspección y retroalimentación en ciclos pequeños.

## Base

Los métodos ágiles, al igual que Kanban, son subconjuntos de Lean.

- LEAN
  - KANBAN
  - AGIL
    - AUP
    - Crystal
    - DSDM
    - FDD
    - Scrum
    - ScrumBan
    - XP

Esto es porque Ágil y Kanban se fundamentan en 3 conceptos de Lean:

1.  Centrarse en el valor
2.  Lotes pequeños
3.  Eliminar residuos

# Selección del ciclo de vida

> Predictivo o tradicional (Secuencial)

En él, el alcance, plazo y costos se planifican por adelantado. Establece los requisitos de manera muy detallada para evitar tener cambios futuros (por ejemplo, la construcción de un hotel). Son útiles cuando hay certidumbre, un equipo estable y bajo riesgo.

1. Requerimientos

2. Diseño

3. Ejecución

4. Verificación

5. Puesta en marcha

Analizar -> Diseñar -> Construir -> Probar -> Entregar

> Iterativo

En él, las actividades del proyecto se repiten en fases (iteraciones), y en cada una de ellas se incrementa el entendimiento del producto. Son útiles para proyectos con cambios frecuentes y alta complejidad. (Se puede imaginar como una pintura que se hace en las siguientes fases: contornos, formas, sombras, color)

​			<- Prototipo <-	<- Refinar <-

Analizar -> Analizar diseño -> Construir prueba -> Entregar

> Incremental

Proporciona entregables terminados que el cliente puede utilizar de inmediato sin estar el proyecto completo. (Se puede imaginar como un conjunto habitacional. No es necedario que todos los departamentos estén listos para que se entregue, sino que se pueden entregar uno a uno.)

> Ágil

Utiliza los enfoques **iterativo** (fases) e **incremental** (entregables parciales) para refinar el trabajo y hacer entregas con mayor frecuencia.

# Triángulo ágil

## Triple restricción de un proyeto



​		*Alcance*

*Coste*			*Tiempo*

Este triángulo indica que, si se mantiene fija alguna de las variables, las otras dos tendran que cambiar inevitablemente (se estimarán).

Así, pues:

<table style="width: 70%; text-align: center; vertical-align: middle; border-collapse: collapse;">
    <thead>
        <tr>
            <th width="33%"> </th>
            <th width="33%">Cascada</th>
            <th width="33%">Ágil</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>FIJOS</td>
            <td>Alcance</td>
            <td>Tiempo y costo</td>
        </tr>
        <tr>
            <td>ESTIMADOS</td>
            <td>Tiempo y costo</td>
            <td>Alcance</td>
        </tr>
</table>

Esto significa que, por ejemplo, para un determinado proyecto Ágil, se definen el tiempo y el costo, pero el alcance (no del proyecto, sino del entregable inmediato) se define para cada iteración (sprint).

# Manifiesto ágil

## Valores ágiles

1.  Valorar a los **individuos** por encima del proceso y las herramientas
2.  Valorar el **producto** por encima de la documentación
3.  Valorar la **colaboración con el cliente** por encima de la negociación de contrato
4.  Valorar la **respuesta ante el cambio** por encima de seguir un plan

## Principios

1. Satisfacer al cliente
2. Aprovechar los cambios
3. Entregar con frecuencia software que funcione
4. Colaborar con los desarrolladores
5. Personas motivadas
6. Conversar cara a cara
7. Medir el progreso con el software que funciona
8. Ritmo sostenible y constante de trabajo
9. Excelencia técnica
10. Simplicidad
11. Equipos auto-organizados
12. Mejora continua

# Pilares del PM4R Agile

> Transparencia

Las fases del producto pueden observarse por cualquier persona.

> Inspección

Se hacen comprobaciones de cuán bien avanza el proyecto.

> Adaptación

Se hacen mejoras al proceso.

> Compromiso con el resultado

Se hace todo lo necesario para cumplir la meta.

NOTA: Los tres primeros (transparencia, inspección y adaptación) son también los pilares de **Scrum**.

# Roles en un proyecto ágil (según PM4R)

Patrocinador -> Dueño del producto --------> Super líder ágil

​												|

​										     Líderes ágiles

​												|

​											   Equipos

> Sponsor

Provee los recursos, puede ser el cliente o una gerencia. Es el portavoz frente a la alta gerencia sobre el estado del proyecto y decide si éste continúa o se cancela.

> Dueño del producto

Único (una sola persona, no un comité) con autoridad para decidir sobre las características y funcionalidades que tendrá el producto. Es el enlace entre el cliente y el equipo del proyecto.

> Súper líder ágil

Coordina a los diferentes equipos ágiles (es como el coordinador del proyecto). Es el enlace entre el equipo, el dueño y el patrocinador.

> Líder ágil

Es el dueño del proeso. Gestiona los obstáculos o impedimentos que tiene el equipo (es como el scrum master).

Protege al equipo de interrupciones, lo limita a menos de 9 personas y provee lo que sea necesario para hacer el trabajo, pero NO es un elemento de control para la toma de decisiones.

> Equipo

Definen la forma de ejecutar el trabajo. Son auto-dirigidos,  auto-organizados y multifuncionales.

Usualmente, en un proyecto de desarrollo se tiene a **un equipo y a un líder ágil por cada componente** del proyecto.

# Herramientas ágiles (según PM4R)

## Lista de trabajo priorizado (Product Backlog)

Sirve para obtener de forma ordenada las necesidades del producto. Es decir:

1. Conocer los trabajos que se deben realizar.
2. Conocer el orden en el que se ejecutan.

Es responsabilidad del dueño del producto mantener actualizada la lista de trabajos prioritarios. Se actualiza en cada sprint y siempre es posible agregar nuevos componentes.

- Los requerimientos principales son más detallados y se colocan en la parte superior. (Gráficamente, son bloques más delgados)
- Los elementos menos urgentes o que aportan menos valor a la sprint a desarrollar se colocan en la parte inferior. (Gráficamente, son bloques más gruesos)

Cada elemento del product backlog se abrevia como **PBI** (product backlog item) y se define por:

|---->	Features	----->	User stories, Use cases, Free form text 

|---->	Defects

|---->	Technical work

|---->	Knowledge acquisition

, sin embargo, un elemento no debe detallarse mucho, porque se convertiría en un alcance, y dejaría de ser ágil.

## Plan PM4R Agile (desglose EDT)

Permite descomponer los trabajos priorizados en partes más pequeñas conocidas como tareas.

Por ejemplo, permite desglosar un trabajo destinado a hacerse en 3 meses,  en tareas más pequeñas destinadas a cada sprint de 2 semanas (S1-S6).

Ayuda a estimar mejor el tiempo y el costo, y a controlar el avance.

## Sprint

Son ciclos de duración de 2 semanas que se repiten dentro de un plan ágil desarrollado a lo largo de 3 meses.

Una sprint se compine de las siguientes etapas:

Diseño -> Construcción -> Pruebas -> Revisión -> Lanzamiento

## Trabajo del sprint

Es el resultado que se obtiene de las dos semanas que dura el sprint.

# Actividades en un proyecto ágil PM4R

Las actividades son espacios de tiempo en los que **el equipo se reúne** para priorizar, planificar y revisar el trabajo.

Para el PM4R son:

1. Análisis de los elementos existentes de planificación del proyecto
2. Selección de los trabajos priorizados
3. Desarrollo del plan PM4R Agile
4. Ejecución del Sprint
5. Revisión del sprint
6. Retrospectivas del sprint

Toda actividad se compone de 4 grupos:

- Talento humano (participantes de la reunión)
- Entradas  (info necesaria para la actividad)
- Técnicas
- Salidas (lo que se obtendrá al final de la actividad)

## Análisis de los elementos existentes de planificación del proyecto

- Talento humano: sponsor, equipo, contratistas, interesados.
- Entradas: PEP (Plan de Ejecución Plurianual), POA (Plan Operativo Anual), EDT (Estructura Desglose de Trabajo).
- Técnicas: reuniones, criterio de los expertos.
- Salidas: EDT revisada o mejorada.

## Selección de los trabajos priorizados

Su objetivo es seleccionar de la EDT los trabajos prioritarios para los próximos 3 meses.

- Talento humano: sponsor, dueño del producto, líder ágil, equipo, contratistas.
- Entradas: EDT, cronograma, presupuesto.
- Técnicas: reuniones, criterio de los expertos.
- Salidas: lista de trabajos priorizados.

## Desarrollo del plan PM4R Agile

Su objetivo es desarrollar el plan a usar para los próximos 3 meses y 6 sprints.

- Talento humano: dueño del producto, súper líder ágil, líderes ágiles, equipo, contratistas.
- Entradas: lista de trabajos priorizados.
- Técnicas: reuniones, descomposición, **estimación análoga** (aquella que se basa en experiencias de proyectos similares anteriores), estimación paramétrica, criterio de los expertos.
- Salidas: plan PM4R agile.

## Ejecución del Sprint

- Talento humano: líder ágil, equipo, contratistas.
- Entradas: Plan PM4R, comunicación (correo, llamadas)
- Técnicas: reuniones, criterio de los expertos.
- Salidas: trabajos del sprint.

Acá, suele usarse el **tablero agile** o **kanban**, que contiene los trabajos **por hacer, en progreso y completados**.

## Revisión del sprint

El equipo presenta el trabajo al dueño del producto y al líder ágil para verificar si cumple con los criterios.

- Talento humano: dueño del poducto, líder ágil, equipo.
- Entradas: trabajos completados del sprint.
- Técnicas: inspección, reuniones, criterio de los expertos.
- Salidas: trabajos del sprint aprobados y rechazados.

## Retrospectivas del sprint

Permite discutir las cosas que se hicieron bien y mal durante el sprint, para crear un plan de mejoras y saber qué prácticas seguir utilizando, qué se debe dejar de hacer y qué se puede mejorar.

- Talento humano: dueño del poducto, líder ágil, equipo.
- Entradas: resultados del sprint.
- Técnicas:  reuniones, criterio de los expertos.
- Salidas: lecciones aprendidas, oportunidades de mejora.

# Metodología de 5 pasos

Es parecida a las actividades definidas anteriormente, pero ligeramente distinta.

1. Análisis de los elementos existentes de planificación del proyecto.
2. Selección de los trabajos priorizados.
3. Desarrollo del plan PM4R Agile.
4. Asignación de responsabilidades.
5. Implementación del plan PM4R Agile.

## Actividades previas

Antes de aplicar los 5 pasos, conviene:

- Entrevista con interesados claves del proyecto (gerentes, clientes, sponsor, beneficiarios del proyecto): para tener una idea de los desafíos y factores que puedan afectar al proyecto, además de los trabajos que serán prioritarios y críticos.

