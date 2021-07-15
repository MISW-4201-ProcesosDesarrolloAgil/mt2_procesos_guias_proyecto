## Ejemplo. División de historias de usuario

Después de revisar las historias de usuario del *product backlog* en el ejemplo de [Mercados Orgánicos](https://miro.com/app/board/o9J_lQKbLXc=/), se ha detectado que las siguientes historias de usuario pueden ser candidatas para dividirse. Encuentre a continuación el análisis realizado a cada una:

### Caso 1. Seleccionar información de envío
---

Se sabe por el dueño de producto que la información de envío corresponde a la fecha y la dirección de envío, por lo cual es posible que la historia de usuario no cumpla con la característica Small (pequeña) de INVEST.

Para aclarar esto, se aplica el primer patrón para división de historias de usuario propuesto por *Humanizing Work*[1], identificar los pasos del flujo de trabajo:

1.	Seleccionar fecha de envío
2.	Crear dirección de envío
3.	Listar direcciones de usuario
4.	Actualizar dirección de envío
5.	Eliminar dirección de envío
6.	Seleccionar dirección de envío

Como se puede observar en el listado de pasos, para seleccionar la dirección de envío es necesario al menos crearla y listarla, sin embargo, es posible que un usuario tenga varias direcciones y que desee actualizarlas o incluso eliminarlas en algún momento.

Ahora se procede a evaluar el resultado obtenido, encontrando las siguientes conclusiones:
  * Los pasos 2, 3, 4 y 5 corresponden a elementos de un CRUD de direcciones que se pueden convertir en nuevas historias de usuario.
  * Los pasos 1 y 6 se pueden unir en una sola historia de usuario pues comparten la misma interface y su complejidad no es mayor.

### Paso 2.
---
