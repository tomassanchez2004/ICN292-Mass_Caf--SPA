# 2. Procesos BPMN

## 2.1 BPMN TO-BE

![BPMN TO-BE](../assets/BPMN%20to-be.png)

El proceso TO-BE incorpora "InventaFood", un software que automatiza la gestión de inventario de la cafetería. El sistema descuenta automáticamente los ingredientes al registrar ventas, genera alertas cuando el stock baja del mínimo y actualiza las existencias al recibir compras. La dueña configura el sistema y supervisa las compras y el control semanal del inventario.

## 2.2 Breve explicación de las mejoras

La mejora principal es crear un software basado en la idea de Fudo, pero enfocado en gestionar el inventario. InventaFood permite vincular cada producto vendido con los ingredientes y las cantidades necesarias para prepararlo, de modo que el uso de materias primas se registre automáticamente en el inventario. Así, el stock se mantiene actualizado sin depender solo de revisiones o registros hechos a mano.

La solución automatiza lo que ocurre después de cada venta. Cuando se selecciona un producto vendido, InventaFood identifica automáticamente sus ingredientes y cantidades, los descuenta del inventario, aplica la merma configurada y actualiza el stock. La dueña es responsable de configurar previamente los productos, ingredientes, cantidades y mermas, de modo que el sistema tenga la información necesaria para hacer estos cálculos.

El sistema también incluye un control mediante niveles mínimos de stock que van a ser determinados por la dueña. InventaFood revisa el inventario y envía una alerta cuando un ingrediente baja del mínimo establecido. Esto permite que la dueña identifique qué necesita reponer y prepare la lista de compras con anticipación, sin depender solo de revisiones manuales y de esta manera no pierden el tiempo
Otra mejora es la gestión de compras y la entrada de productos. La información sobre lo que hay que reponer sirve de apoyo para hacer las compras de los martes y viernes. Además, cuando llegan los productos, la dueña registra su entrada en InventaFood, lo que actualiza el stock y permite seguir el historial de movimientos del inventario

Finalmente, se incorpora un control general del inventario los viernes, mediante la comparación entre el inventario físico y el inventario registrado en InventaFood. Cuando existen diferencias, estas pueden ser identificadas y corregidas solo por la dueña dentro del sistema. Por lo tanto, la propuesta permite controlar tanto los niveles de stock como las diferencias entre las existencias físicas y las registradas.

En términos de medición y control, el proceso propuesto permite disponer de información sobre los niveles de stock de los ingredientes, los productos que requieren reposición y las diferencias detectadas durante la revisión general del inventario. Con esta información, la cafetería puede mejorar la planificación de sus compras y contar con datos más confiables para apoyar las decisiones relacionadas con el inventario.
