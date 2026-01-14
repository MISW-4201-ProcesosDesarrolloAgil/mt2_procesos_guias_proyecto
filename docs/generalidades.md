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

Con el auge en los últimos 10 años de las rentas de corta estancia (propiedades que se alquilan a través de plataformas como Airbnb o Booking) ha surgido una nueva actividad que es la administración del alquiler de estas propiedades. Los propietarios de las propiedades delegan en un administrador toda la gestión y la logística que se requiere para prestar un buen servicio a sus clientes.

La empresa 4201Software está desarrollando “Corta Estancia”, una aplicación web para la administración de rentas de corta estancia que facilita todas las tareas relacionadas con la administración y mantenimiento de las propiedades, la gestión de las reservas y la gestión de cuentas entre el propietario y el administrador.

4201Software ya tiene desarrollada una versión inicial de la aplicación que realizó un practicante. En esta primera versión se tienen las siguientes funcionalidades básicas: 

- Ingresar a la aplicación con usuario y clave. 
- Gestionar las propiedades administradas: agregar una nueva propiedad, editar la información de la propiedad y eliminar propiedades.
- Gestionar las reservas de la propiedad: agregar una reserva, editar la información de las reservas y eliminar reservas.
- Gestionar los ingresos y gastos de las propiedades: agregar, editar y eliminar gastos por mantenimiento, comisiones de administración, compras de suministros, etc. Agregar, editar y eliminar ingresos recibidos por reservas. Igualmente se cuenta con un reporte que presenta un resumen de los ingresos y gastos de la propiedad.

4201Software quiere participar en una ronda de inversión y esto requiere evolucionar “Corta estancia” para convertirlo en un Producto Mínimo Viable (MVP, por sus siglas en inglés) completamente usable y funcional. Esto implica incluir nuevas funcionalidades, mejorar la interfaz web y la navegación entre pantallas para cautivar a posibles inversionistas.  4201Software ha decidido contactar a la Universidad de los Andes con el fin de conseguir un equipo que le ayude a mejorar su aplicación y lograr su objetivo de presentarse a la ronda de inversión.

La evolución de la aplicación debe permitir lograr los siguientes objetivos:


- **Mejorar la interfaz gráfica de la aplicación** 

Se quiere que la aplicación tenga una mejor interfaz. La interfaz actual sigue un estilo de interfaz “Multiple Pages”  y se quiere que la interfaz sea más moderna y atractiva para los usuarios y que tenga un estilo “single page” que simplifique y mejore la navegación por la aplicación.

- **Agregar a la aplicación la planificación del mantenimiento de las propiedades** 

Se quiere que la aplicación pueda ayudar al administrador la gestión de las actividades de mantenimiento de las propiedades. Las actividades de mantenimiento comprenden varios tipos de actividades: los mantenimientos periódicos a la dotación que tiene la propiedad, por ejemplo mantenimiento anual a los electrodomésticos, revisiones cada tres meses de aires acondicionados, la limpieza y arreglo de la propiedad al finalizar una estadía, etc. El administrador debe poder programar estas actividades y hacer seguimiento a su ejecución.

- **Agregar un módulo para que los dueños de propiedades puedan consultar la información de su propiedad**  

Con el fin de tener transparencia frente a sus clientes, se quiere que los dueños de propiedades puedan ingresar a la plataforma y consultar la información de sus propiedades, deben poder revisar la información de su propiedad, las reservas y los  ingresos y egresos.   

- **Mejorar el módulo de ingresos y gastos**  

Los ingresos y gastos se deberían poder clasificar en diferentes categorías, con el fin de poder analizar el comportamiento de las propiedades por estas categorías y tener un indicador de eficiencia para cada propiedad. También se quiere mejorar el reporte incluyendo el resumen por categoría y el indicador de eficiencia. Y finalmente se quiere tener un reporte en el que un propietario pueda ver un resumen de todas sus propiedades.

Adicionalmente, 4201Software está evaluando la posibilidad de actualizar el stack tecnológico de la aplicación debido a que hay nuevas versiones de los frameworks y librerías que usan actualmente.


## Tecnologías para el desarrollo 
---

Las tecnologías que se utilizarán para desarrollar el proyecto son: Python con Flask como lenguaje de programación en el backend, Angular en el frontend,  SQLite para la base de datos y GIT para el control de versiones. Para el desarrollo del proyecto se tendrán en cuenta las siguientes herramientas:

| Elemento                  | Herramienta |
| ------------------------- | ----------- |
| Backend                | Python + Flask |
| Frontend                  | Angular     |
| Manejador de versiones    | Git         |
| Repositorio remoto        | Github      |
| Manejador de IC    | Github (actions) |
| Documentación del proyecto     | Wiki de GitHub |
| Gestión del proyecto      | Jira |

