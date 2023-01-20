## Generalidades
---

El objetivo del proyecto del curso es aplicar un proceso de desarrollo definido a partir de los principios y prácticas propuestas por los marcos de trabajo ágiles para desarrollar un proyecto de software. 

El proyecto consiste en evolucionar un producto que ya tiene algunas funcionalidades desarrolladas y su alcance está definido a partir de los requerimientos documentados en el [enunciado](/mt2_procesos_guias_proyecto/#enunciado) abajo descrito. El proyecto se desarrolla en equipos de 4 estudiantes. El proceso está basado en Scrum e incluye varias prácticas de ingeniería de software y de otros marcos ágiles.

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

La empresa SoftOne está desarrollando la versión web de la aplicación “En Forma”, una aplicación de escritorio que le permite a un entrenador gestionar todo lo relacionado con los ejercicios que realizan las personas que entrena. La versión web contará con nuevas funcionalidades y está dirigida a un público objetivo más amplio. 

SoftOne ya tiene desarrollada una versión inicial de la aplicación web. Esta versión tiene implementadas las mismas funcionalidades de la aplicación de escritorio y las funcionalidades que permiten el inicio de sesión con usuario y contraseña. 

Al ingresar a la aplicación el usuario ve una pantalla principal, en la que se muestra el listado de personas que está entrenando y opciones para agregar una nueva persona y para acceder a la lista de ejercicios disponibles en “En Forma”.   

En el listado, para cada persona tiene opciones para editar la información de la persona, para ver los entrenamientos que ha realizado, para dejar de entrenar a la persona y para borrar la información de la persona, siempre que no tenga entrenamientos registrados. Cuando se deja de entrenar a la persona, se registra la fecha y la razón por la cual no continuará con el entrenamiento. La opción de ver los entrenamientos muestra una lista de los ejercicios que ha realizado la persona con el nombre del ejercicio, la fecha, la cantidad de repeticiones que realizó y el tiempo que le tardó en hacerlo definido en horas, minutos y segundos. Adicionalmente, en esta pantalla puede agregar, editar y borrar los ejercicios entrenados, así como un botón que le mostrará un reporte con su IMC (Índice de masa corporal) y en cuál categoría del IMC se encuentra, además de un cálculo del consumo calórico por cada fecha en la que se ha entrenado. 

La opción para agregar una nueva persona permite registrar: el nombre y los apellidos, la fecha de inicio del entrenamiento, la talla, el peso, la edad, y las medidas en centímetros de brazos, pecho, abdomen, cintura y piernas. 

La opción para acceder a la lista de ejercicios disponibles en “En Forma”, muestra un listado con los ejercicios que se utilizan en los entrenamientos, y desde esta lista puede crear un ejercicio con su nombre, descripción, aproximado de calorías quemadas por repetición y un enlace a un video en YouTube, editar los ejercicios existentes, o borrarlos si el ejercicio nunca se ha usado en el entrenamiento de alguna persona.  

SoftOne quiere participar en una ronda de inversión y esto requiere evolucionar “En Forma” para convertirlo en un Producto Mínimo Viable (MVP, por sus siglas en inglés) completamente usable y funcional. Esto implica realizar mejoras a su interfaz web y a la navegación entre pantallas, e incluir nuevas funcionalidades para cautivar a posibles inversionistas.  SoftOne ha decidido contactar a la Universidad de los Andes con el fin de conseguir un equipo que le ayude a mejorar su aplicación y lograr su objetivo de presentarse a la ronda de inversión. 

Las nuevas funcionalidades que se quieren desarrollar deben permitir lograr los siguientes objetivos:  

- **Extender las funcionalidades para que la aplicación pueda ser usada por las personas que se entrenan** 

Se quiere que los clientes de los entrenadores puedan consultar la información de los entrenamientos que han realizado, gestionar su información personal y ver el reporte de sus entrenamientos. Cuando se agregue una nueva persona, además de la información básica se debe solicitar la información para crear una cuenta: usuario y contraseña. Con este usuario y contraseña el cliente podrá ingresar a la aplicación. 

- **Agregar a la aplicación el manejo de rutinas** 

Además de tener ejercicios disponibles para todos los entrenadores, se quiere que también se puedan registrar rutinas. Las rutinas son secuencias de ejercicios que tienen un propósito específico. Por ejemplo, existen diferentes rutinas para trabajar miembros superiores, o para hacer cardio. Los entrenadores pueden proponer nuevas rutinas y utilizarlas con sus clientes. Las rutinas propuestas pueden ser utilizadas por todos los entrenadores.  

- **Extender las funcionalidades para que un administrador pueda gestionar los entrenadores de la aplicación**  

Se quiere agregar funcionalidades que permitan a un administrador gestionar a los entrenadores. El administrador podrá agregar un entrenador, registrar su información personal (identificación, nombre y apellido, teléfono y dirección) y asignarle un usuario y contraseña. También podrá consultar la lista de entrenadores, editar la información o borrar un entrenador.  Adicionalmente, en la funcionalidad de registrarse en la aplicación se debe solicitar además del usuario y contraseña, la información personal del entrenador.  

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


