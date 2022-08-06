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

La empresa SoftOne está desarrollando la versión web de la aplicación “E-porra”, una aplicación de escritorio para administrar apuestas de carreras de cualquier tipo (caballos, formula 1, atletismo, etc.). La versión web contará con nuevas funcionalidades y está dirigida a un público objetivo más amplio.

SoftOne ya tiene desarrollada una versión inicial de la aplicación web. Esta versión tiene implementadas las mismas funcionalidades de la aplicación de escritorio y las funcionalidades que permiten el inicio de sesión con usuario y contraseña, al usuario administrador de la aplicación.

Al iniciar sesión, el usuario administrador ve una pantalla principal con la descripción de “E-porra”, acompañada de un listado de las carreras que tiene registradas. El administrador tiene la opción de crear, editar, terminar o borrar una carrera, esto último siempre que no tenga apuestas asociadas. Crear una nueva carrera requiere indicar el nombre de la carrera y los competidores. Para cada competidor, la aplicación solicita su nombre y la probabilidad que tiene de ganar la carrera (un valor entre 0 y 1). 

Cuando el usuario administrador ve el detalle de una carrera, tiene la opción de crear apuestas asociadas a la misma. Para esto debe ingresar el valor apostado, el nombre del apostador y el competidor al que le apostó. El usuario administrador puede ver el listado completo de las apuestas de una carrera, crearlas, editarlas o eliminarlas.

Cuando se termina una carrera, el usuario administrador puede marcarla como terminada y registrar el competidor ganador para generar el reporte de pagos a realizar.

SoftOne quiere participar en una ronda de inversión y esto requiere evolucionar E-Porra para convertirlo en un Producto Mínimo Viable (MVP, por sus siglas en inglés) completamente usable y funcional. Esto implica realizar mejoras a su interfaz web y a la navegación entre pantallas, e incluir nuevas funcionalidades para cautivar a posibles inversionistas.  SoftOne ha decidido contactar a la Universidad de los Andes con el fin de conseguir un equipo que le ayude a mejorar su aplicación y lograr su objetivo de presentarse a la ronda de inversión.

Las nuevas funcionalidades que se quieren desarrollar son:

- Ampliar apuestas a otras categorías de deportes, por ejemplo, futbol, baloncesto, tenis, etc. El usuario administrador debe poder:
  - Crear, editar, eliminar y ver el listado de deportes existentes.
  -	Crear un evento en cualquiera de las categorías de deporte y ver el listado de eventos registrados.
- Habilitar el registro de apostadores. Al iniciar sesión, el usuario apostador debe poder:
  - Administrar su cuenta.
    - Registrar o actualizar su información de perfil
    - Depositar dinero
    - Retirar dinero
    - Ver el balance y filtrarlo por fecha o tipo de movimiento
  - Apostar
    - Ver el listado de eventos activos
    -	Filtrar la lista de eventos por deporte
    -	Ver el detalle de un evento
    -	Registrar una apuesta. Al ingresar el valor apostado, el sistema debe calcular y mostrar el pago potencial en caso de ganar
  -	Ver notificaciones
    -	El apostador debe recibir una notificación cada vez que gana en una apuesta


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


