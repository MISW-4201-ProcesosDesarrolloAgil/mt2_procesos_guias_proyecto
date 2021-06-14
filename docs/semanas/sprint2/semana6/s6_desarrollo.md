| Inception |   | Sprint 1 |   | Sprint 2 |   | Cierre |
|-----------|---|----------|---|----------|---|--------|
| [Semana 2](/mt2_procesos_guias_proyecto/semanas/inception/semana2/semana2)        | [Semana 3](/mt2_procesos_guias_proyecto/semanas/inception/semana3/semana3) | [Semana 4](/mt2_procesos_guias_proyecto/semanas/sprint1/semana4/semana4) | [Semana 5](/mt2_procesos_guias_proyecto/semanas/sprint1/semana5/semana5) | **[Semana 6](/mt2_procesos_guias_proyecto/semanas/sprint2/semana6/semana6)** | [Semana 7](/mt2_procesos_guias_proyecto/semanas/sprint2/semana7/semana7) | [Semana 8]()      |nt1/semana7/semana7) | Semana 8      |/semana7/semana7) | [Semana 8]()      |

## Sprint 2. Desarrollo

### Objetivos

---
* Iniciar la ejecución de las tareas de desarrollo propuestas para el segundo sprint.
* Hacer seguimiento al avance de actividades del sprint mediante la realización de *Daily meetings* y la actualización del tablero Kanban.


### Descripción actividad

---
#### ![](./../../../assets/images/individuo.png) Actividad individual

* Revisar la distribución de historias de usuario (HU) en el tablero del sprint.
* Desarrollar cada una de las historias a su cargo implementando *Test-driven development* (TDD) y pair programming (en las HU más complejas).
  * Para dejar evidencia del uso de TDD, se debe realizar commit al repositorio al definir las pruebas, al implementar el código y al realizar *recfactoring* del código.
  * Implementar la generación de datos aleatorios en las pruebas unitarias.
* Crear un script de GitHub Actions para integrar el código que pasa exitosamente las pruebas unitarias en el repositorio de acuerdo con el flujo de trabajo definido.

#### ![](./../../../assets/images/grupo.png) Actividad grupal

* Seguimiento:
  * Definir en equipo el horario y periodicidad que más se ajuste para la realización de *Daily meetings* (se recomienda hacerlas mínimo 3 veces por semana en el mismo horario).
  * Realizar las *Daily meetings* en los horarios definidos y teniendo en cuenta el instructivo disponible en Recursos.
  * Cargar las evidencias de la realización de *Daily meetings* en la wiki del proyecto.

* BadSmells:
  * Realizar la lectura del capítulo 3 del libro [Refactoring: Improving the Design of Existing Code, Martin Fowler](https://moodleinstitucional.uniandes.edu.co/pluginfile.php/45336/mod_label/intro/RefactoringCapitulo1-3.pdf).
  * Identificar al menos 3 bad smells en el código de la aplicación y corregirlos.
  * Elaborar una presentación donde se expliquen los bad smells identificados y muestren el antes y el después del código corregido.
  * Cargar la presentación en la wiki del proyecto.


### Recursos
---

* [Refactoring: Improving the Design of Existing Code, Martin Fowler](https://moodleinstitucional.uniandes.edu.co/pluginfile.php/45336/mod_label/intro/RefactoringCapitulo1-3.pdf)
* [Instructivo para conducir sesiones de *Daily meeting*](../semana4/s4_daily_meeting)

### Entregables

---
URL al repositorio del equipo en GitHub.

### Criterios de evaluación

---
* Todas las pruebas unitarias funcionan correctamente
* Se evidencia en el historial del respositorio el desarrollo usando TDD y las correcciones de bad smells identificados
* El resultado de la integración continua es exitoso
