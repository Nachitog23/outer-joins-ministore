¿Por qué usaste LEFT JOIN para la Consulta 1 y no INNER JOIN? ¿Qué se perdería si usaras INNER JOIN?

Se utiliza LEF JOIN para que salgan todos los resultados de productos, incluso los que no tienen ventas. En caso de usar INNER JOIN solo saldrían los datos de resultados coincidentes entre ambas tablas.

¿Por qué usaste RIGHT JOIN para la Consulta 2? ¿Qué tabla está a la izquierda y cuál a la derecha en tu consulta?

Utilice RIGHT JOIN para que me devuelva todos los datos de las ventas. Incluido el producto NULL. La tabla izquierda es productos y la tabla derecha es Ventas.

¿Qué representan los valores NULL en cada resultado? Explicá con un ejemplo concreto de los datos qué significa que venta_id sea NULL en la Consulta 1 y que producto_id de productos sea NULL en la Consulta 2.

Los valores NULL significa que no hay resultados al hacer coincidir las tablas. En el caso de la venta_id sea null significa que no hay ventas para este producto, mientras que en producto_id es null significa que no hay producto asociado a ese id.

¿Cuándo usarías FULL OUTER JOIN en un caso real de negocio?

lo usaria en caso que quiera ver todos los datos de las ventas que hay y ver que información nos falta.