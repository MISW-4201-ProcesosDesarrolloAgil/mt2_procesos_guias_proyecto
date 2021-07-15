## Ejemplo. División de historias de usuario

Después de revisar las historias de usuario del *product backlog* en el ejemplo de [Mercados Orgánicos](https://miro.com/app/board/o9J_lQKbLXc=/), se ha detectado que las siguientes historias de usuario pueden ser candidatas para dividirse. Encuentre a continuación el análisis realizado a cada una:

### Caso 1. Seleccionar información de envío
---
<br>
Se sabe por el dueño de producto que la información de envío corresponde a la fecha y la dirección de envío, por lo cual es posible que la historia de usuario no cumpla con la característica *Small* (pequeña) de INVEST [1].

Para aclarar esto, se aplica el primer patrón para división de historias de usuario propuesto por *Humanizing Work*, identificar los pasos del flujo de trabajo [2]:

1.	Seleccionar fecha de envío.
2.	Crear dirección de envío.
3.	Listar direcciones de usuario.
4.	Actualizar dirección de envío.
5.	Eliminar dirección de envío.
6.	Seleccionar dirección de envío.

Como se puede observar en el listado de pasos, para seleccionar la dirección de envío es necesario al menos crearla y listarla, sin embargo, es posible que un usuario tenga varias direcciones y que desee actualizarlas o incluso eliminarlas en algún momento.

Ahora se procede a evaluar el resultado obtenido, encontrando las siguientes conclusiones:

  * Los pasos 2, 3, 4 y 5 corresponden a elementos de un CRUD de direcciones que se pueden convertir en nuevas historias de usuario.
  * Los pasos 1 y 6 se pueden unir en una sola historia de usuario pues comparten la misma interface y su complejidad no es mayor.

### Caso 2. Consultar pedidos
---
<br>
La consulta de pedidos es una funcionalidad que a primera vista puede tener muchas variaciones dependiendo del criterio de búsqueda y por lo tanto una complejidad mayor.

Para aclarar esto, se solicita apoyo del dueño de producto y se aplica el tercer patrón para división de historias de usuario, variaciones de las reglas comerciales [2].

Al profundizar en la historia de usuario con el dueño de producto, se identifica que el productor debe poder:

1.	Consultar pedidos por fecha de entrega.
2.	Consultar pedidos por fecha de confirmación.
3.	Consultar pedidos por estado.

Cada una de estas historias cumplen con las características INVEST [1] y por lo tanto pueden agregarse al *product backlog*.


### Referencias
---
<br>
[1] *Rubin, K. (2012). Chapter 5. Requirements and User Stories en Essential Scrum: A Practical Guide to the Most Popular Agile Process. Estados Unidos: Addison-Wesley Professional.*

[2] *Lawrence, R. Green, P. (11 de julio de 2021). The Humanizing Work Guide to Splitting User Stories. https://www.humanizingwork.com/the-humanizing-work-guide-to-splitting-user-stories/*
