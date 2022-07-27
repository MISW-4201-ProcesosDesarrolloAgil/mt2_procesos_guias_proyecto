## Generalidades
---

El objetivo del proyecto del curso es aplicar un proceso de desarrollo definido a partir de los principios y prácticas propuestas por los marcos de trabajo ágiles para desarrollar un proyecto de software. 

El proyecto consiste en evolucionar un producto que ya tiene algunas funcionalidades desarrolladas y su alcance está definido a partir de los requerimientos documentados en el [enunciado](/mt2_procesos_guias_proyecto/generalidades#enunciado) abajo descrito. El proyecto se desarrolla en equipos de 4 estudiantes. El proceso está basado en Scrum e incluye varias prácticas de ingeniería de software y de otros marcos ágiles.

Las **semanas 2 y 3** corresponden a la fase de inicio. Durante esta fase los equipos tendrán que preparar todos los elementos necesarios y suficientes para iniciar el desarrollo: 

- Se conforma el equipo de trabajo
- Se establece el alcance del producto alineado con el contexto organizacional
- Se explora la estrategia de arquitectura
- Se trabaja en las historias de usuario iniciales y se hace una planeación inicial
- Se define un plan de riesgos sencillo
 
Las **semanas 4 y 5** corresponden al primer sprint de desarrollo y las **semanas 6 y 7** corresponden al segundo sprint de desarrollo. Durante estos ciclos los equipos tendrán que:

- Realizar la planeación del sprint
- Desarrollar las historias de usuario utilizando las siguientes prácticas:
  -  Manejo de Git como sistema de control de versiones
  -  Flujos de trabajo en Git
  -  Pair programming
  -  Pruebas unitarias
  -  Generación aleatoria de datos (pruebas unitarias)
  -  Test-Driven Development (TDD)
  -  Integración Continua con GitHub Actions
- Cumplir con las ceremonias (eventos) y artefactos definidos por el marco Scrum 
- Realizar seguimiento mediante un tablero Kanban

Durante la **Semana 8** se realiza el cierre del proyecto y una retrospectiva de todo el proceso.

## Enunciado
---

Lorenzo es un melómano y coleccionista de música que ha pasado toda su vida recopilando álbumes musicales; periódicamente se reúne con sus amigos para compartir su música y hablar sobre las historias alrededor de las canciones o curiosidades de los artistas. Con el tiempo, Lorenzo notó que cada vez era más difícil encontrar sus canciones y por esto desarrolló Ionic, una aplicación para organizar su colección y buscar de forma fácil y rápida sus álbumes o canciones utilizando  el título o nombre de un intérprete.

Ionic permite que Lorenzo inicie sesión con usuario y contraseña para ver el listado de los álbumes en su colección, en caso de querer crear uno nuevo, la aplicación solicita la información del título, año de producción, descripción, los artistas que interpretaron las canciones, las canciones que contiene y el medio sobre el cual está grabado (discos, casetes o CD). El sistema permite hacer esto en cualquier momento, además de modificar sus datos, e incluso borrar los álbumes si ingresa alguno repetido o que se dañó y ya no se puede escuchar.

Cuando Lorenzo elige un álbum de la lista, puede ver su información y las canciones que tiene. Para las canciones del álbum, Ionic almacena su título, su intérprete y su duración, en minutos y segundos. La aplicación también permite editar esta información e incluso borrarla.

Cuando Lorenzo mostró Ionic a sus amigos, estos quedaron encantados y le sugirieron ajustar Ionic para que todos puedan ingresar y utilizarlo, de esta forma, además de servir a Lorenzo para encontrar canciones, podrían compartir información entre todos. Carlos, quien hace parte de este grupo de amigos, pensó que con su ayuda Lorenzo podría convertir esta iniciativa en un emprendimiento para conectar a más melómanos y monetizar el trabajo realizado. Por esto, inició la búsqueda de convocatorias de emprendimiento a las cuales aplicar.

Después de consultar, Carlos le propuso a Lorenzo evolucionar Ionic para convertirlo en un Producto Mínimo Viable (MVP, por sus siglas en inglés) completamente usable y funcional. Esto implica realizar mejoras a su interfaz web y a la navegación entre pantallas, e incluir nuevas funcionalidades para cautivar a posibles inversionistas.

Carlos propuso las siguientes funcionalidades:

* **Compartir con amigos**

Se espera que los usuarios registrados en la aplicación puedan compartir sus álbumes y canciones con las personas registradas en la aplicación. 

* **Generar hilos de conversación**

Los usuarios deben poder comentar la información de los álbumes y canciones generando hilos de conversación sobre temas relevantes o curiosidades.

* **Notificaciones**

Los usuarios podrán saber cuándo las canciones y álbumes compartidos por ellos han sido comentados y quién lo hizo mediante notificaciones.

* **Puntuación**

Dependiendo de la calidad de los comentarios recibidos, los usuarios podrán calificarse entre sí. El promedio de las calificaciones recibidas se verá reflejado en el perfil del usuario.

* **Canciones favoritas**

Los usuarios podrán seleccionar una canción como favorita y deseleccionarla cuando deseen. Este criterio será tenido en cuenta al buscar canciones pues las canciones favoritas que cumplan con el criterio de búsqueda aparecen siempre en las primeras posiciones.

* **Filtrado**

Los usuarios podrán filtrar álbumes y canciones por nombre, intérprete o género.

Aunque Lorenzo le parece muy llamativo, no cuenta con los conocimientos ni con el tiempo para desarrollar las nuevas funcionalidades, es por esto que ha decidido contactar a la Universidad de los Andes, con el fin de conseguir un equipo que le ayude a mejorar su aplicación y lograr su objetivo.


## Tecnologías para el desarrollo 
---

Las tecnologías que se utilizarán para desarrollar el proyecto son: Python con Flask como lenguaje de programación en el backend, Angular en el frontend,  SQLite para la base de datos y GIT para el control de versiones. Para el desarrollo del proyecto se tendrán en cuenta las siguientes herramientas:

| Elemento                  | Herramienta |
| ------------------------- | ----------- |
| Backend                | Python + Flask |
| Frontend                  | Angular     |
| Manejador de versiones    | Git         |
| Repositorio remoto        | Github      |
| Manejador de IC    | Github (actions), Jenkins  |
| Documentación del proyecto     | Wiki de GitHub |
| Gestión del proyecto      | Jira |


