# Poker Planning para el Proyecto CAT

## Definición
Poker Planning es una técnica ágil de estimación colaborativa usada en Scrum. El equipo (desarrolladores, product owner, etc.) usa cartas con valores de la secuencia Fibonacci (1, 2, 3, 5, 8, 13, etc.) para estimar el esfuerzo relativo de cada historia de usuario o tarea en "story points". Se discute cada ítem hasta llegar a un consenso, considerando complejidad, incertidumbre y esfuerzo.

## Justificación
Se utiliza porque fomenta la colaboración en equipo, reduce sesgos individuales y permite una planificación realista de sprints. En este proyecto, se relaciona con GitHub ya que estimamos los issues (basados en las historias de usuario) y los movemos en el board de Projects (To Do, In Progress, Done). Esto ayuda a priorizar el backlog, asignar recursos y alinear con el Diagrama de Gantt (desarrollo en sprints de 2 semanas). Además, evita subestimar tareas complejas como integraciones o pruebas.

## Estimaciones para los Issues/Historias
Basado en complejidad, tiempo estimado y dependencias. Usamos story points (bajo: 1-3, medio: 5-8, alto: 13+):

1. Registrar una solicitud de soporte: 5 puntos (medio esfuerzo, interfaz básica con formularios).
2. Asignar solicitudes a técnicos: 8 puntos (alto, lógica de asignación y notificaciones).
3. Seguimiento de estado de solicitudes: 3 puntos (bajo, actualizaciones simples en BD).
4. Gestionar prioridades de tickets: 2 puntos (bajo, selección de niveles).
5. Generar reportes mensuales: 13 puntos (alto, queries complejas y visualizaciones).
6. Consulta de estado por usuarios: 5 puntos (medio, dashboard personalizado).
7. Notificaciones por email: 8 puntos (alto, integración con servicios externos).
8. Integración con base de datos de usuarios: 13 puntos (alto, autenticación y seguridad).
9. Interfaz móvil responsive: 5 puntos (medio, CSS y testing en dispositivos).
10. Pruebas de seguridad: 8 puntos (alto, verificación de vulnerabilidades).

**Total estimado:** 70 story points. Para un equipo pequeño (2-3 personas), esto se puede distribuir en sprints de 2 semanas con una velocidad de ~20 puntos por sprint, alineado con la fase de desarrollo en el Gantt.
