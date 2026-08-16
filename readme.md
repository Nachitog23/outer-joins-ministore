¿Por qué usaste LEFT JOIN para la Consulta 1 y no INNER JOIN? ¿Qué se perdería si usaras INNER JOIN?

Utilice LEFT JOIN para que me salgan todos los productos, incluidos los que no tenian ventas. Si hubiera utilizado INNER JOIN, lo productos sin ventas no me hubieran salido, por lo que solo tendriamos en el listado quienes tuvieran una coincidencia entre ambas tablas.

¿Por qué usaste RIGHT JOIN para la Consulta 2? ¿Qué tabla está a la izquierda y cuál a la derecha en tu consulta?

Utilice RIGHT JOIN para que me salgan todas las ventas, incluida la de un producto que no estaba registrado. La tabla de la izquierda es producto y la de la derecha las ventas.

¿Qué representan los valores NULL en cada resultado? Explicá con un ejemplo concreto de los datos qué significa que venta_id sea NULL en la Consulta 1 y que producto_id de productos sea NULL en la Consulta 2.

El valor NULL reprensenta que es un dato inexistente. En caso que venta_id sea NULL significa que no existe un registro de venta para dicho producto, mientras que en el segundo caso significa que dicho producto no esta registrado en el sistema y no lo puede relacionar.

¿Cuándo usarías FULL OUTER JOIN en un caso real de negocio?

Lo utilizaria en un caso que quiera saber todas las ventas realizadas y en caso que haya algun producto que no esta en sistema. De esta manera me saldría NULL y podria buscar la información para rellenarla en el sistema y se complete correctamente.