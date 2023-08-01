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

La empresa SoftOne está desarrollando “Recetario”, una aplicación que permite gestionar todo lo relacionado con las recetas y platos que ofrecen en un restaurante. SoftOne tiene desarrollada una versión inicial de la aplicación web. 

Luego de ingresar, al abrir la página principal, el administrador del restaurante puede ver la lista de recetas que tiene registradas, así como las opciones para agregar una nueva receta y acceder a la lista de ingredientes que puede utilizar para las recetas. 

La opción para ver la lista de ingredientes muestra el listado de ingredientes que comúnmente utilizan en el restaurante, incluyendo para cada uno su nombre, unidad, valor por unidad, sitio de compra y calorías que aporta por unidad. A partir de esta lista podrá agregar un nuevo ingrediente si lo necesita, y editar o borrar alguno, siempre que este ingrediente no se está utilizando en alguna de las recetas. 

Por cada receta en el listado, el administrador puede consultar cómo es su preparación según la receta actual, editar una receta, eliminarla del listado o planear una preparación para un número específico de personas. 

Al agregar una nueva receta, el administrador registra su nombre, tiempo de preparación en horas, para cuantas personas es, los ingredientes a utilizar con sus medidas y la descripción detallada de su preparación. Cuando se edita una receta, se puede cambiar cualquiera de estos datos, incluso, se pueden adicionar o quitar ingredientes. 

Adicionalmente, cuando se elige la opción Preparar de una receta, el sistema preguntará el número de personas para quienes se realizará la preparación, y mostrará una pantalla donde se muestra la cantidad de personas a las que se les va a preparar la receta, la cantidad de calorías por porción, se calcula el costo de los ingredientes y la cantidad de ingredientes proporcional a la cantidad de personas, y se muestra la descripción detallada de la preparación. 

Con el fin de participar en una ronda de inversionistas SoftOne quiere evolucionar la aplicación para convertirla en un Producto Mínimo Viable (MVP, por sus siglas en inglés) completamente usable y funcional, para que pueda ser usada por una cadena de restaurantes donde se tienen varios administradores y varios chefs que gestionan las recetas de la cadena. Esto implica incluir nuevas funcionalidades y posiblemente realizar mejoras a su interfaz web y a la navegación entre pantallas para cautivar a posibles inversionistas.  SoftOne ha decidido contactar a la Universidad de los Andes con el fin de conseguir un equipo que le ayude a mejorar su aplicación y lograr su objetivo de presentarse a la ronda de inversión.  

Adicionalmente, SoftOne está evaluando la posibilidad de actualizar el stack tecnológico de la aplicación debido a que hay nuevas versiones de los frameworks y librerías que usan actualmente.  

Las nuevas funcionalidades que se quieren desarrollar deben permitir lograr los siguientes objetivos:  

- **Administrar varios restaurantes**
Se espera que en cada restaurante se puedan tener chefs asociados donde se puedan registrar las recetas que allí manejan y que se puedan compartir recetas entre los restaurantes.  

- **Gestionar compras por restaurante**
El propósito de esta mejora es que se pueda elegir el menú de una semana, y a partir de ese menú se sepa el conjunto de recetas que se ofrecerán la próxima semana y en qué posibles cantidades, de manera que se pueda obtener el número de compras a realizar conforme con el número de platos a preparar del menú a la semana.  

- **Analítica de datos para gestión de compras**
De acuerdo con la ubicación de cada restaurante y de las preferencias del chef o del dueño, que se tengan sitios definidos y opcionales para la compra de ingredientes. Estos sitios deben estar clasificados según su relación calidad, costo y disponibilidad de los productos. 


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


