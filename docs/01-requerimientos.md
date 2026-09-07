# Requerimientos del SIG
## 1) Objetivo del SIG
El objetivo del sistema es mejorar la gestión de inventario de Mass Café SPA mediante un control más oportuno del ingreso, salida y disponibilidad de productos e ingredientes, reduciendo la pérdida de tiempo por trabajo manual, además de facilitar y optimizar las decisiones de compra.
El sistema deberá permitir mantener información actualizada del stock, identificar productos próximos a alcanzar su nivel mínimo y relacionar las ventas con los ingredientes utilizados.
## 2) Actores y roles
Dueña: Tendrá acceso completo al sistema, pudiendo consultar y actualizar el inventario, registrar compras y mermas, configurar niveles mínimos y revisar las necesidades de reposición.

Trabajadores de barra: Podrán consultar el inventario correspondiente a su área.

Trabajadores de cocina: Podrán consultar el inventario correspondiente a su área.
## 3) Alcance
### In
- Registro de cantidad actual de productos e ingredientes.
- Registro de ingresos y salidas de productos e ingredientes.
- Actualización oportuna del stock.
- Registro de mermas de productos e ingredientes.
- Definición de niveles mínimos.
- Relación entre ventas y productos e ingredientes utilizados en ellas.
- Descuento de productos e ingredientes utilizados al realizar una venta.
- Alertas de productos próximos a quedar sin stock.
- Consulta del inventario según el área del trabajador.
- Consulta y modificación del inventario completo por parte de la dueña.
- Apoyo a la generación de listas de productos e ingredientes a reponer.
- Integración o cruce de información con las ventas registradas en Fudo, o reemplazo de Fudo por una solución que permita cubrir las necesidades del sistema de inventario.
### Out
- Gestión de proveedores como proceso independiente.
- Gestión contable de la cafetería.
- Gestión de recursos humanos.
- Administración general de las ventas como objetivo principal del proyecto, aunque se podrá evaluar el reemplazo de Fudo si resulta más viable para implementar solución propuesta.
## 4) Requerimientos funcionales
- RF01: El sistema debe permitir registrar productos e ingredientes que forman parte del inventario de la cafetería. 
- RF02: El sistema debe permitir registrar el ingreso de productos e ingredientes al inventario. 
- RF03: El sistema debe registrar las salidas de productos e ingredientes asociadas a las ventas y actualizar el stock disponible según los productos e ingredientes utilizados. 
- RF04: El sistema debe permitir consultar el stock disponible de productos e ingredientes.
- RF05: El sistema debe permitir definir un nivel mínimo de stock para cada producto o ingrediente. 
- RF06: El sistema debe generar una alerta cuando un producto o ingrediente alcance o se aproxime a su nivel mínimo de stock. 
- RF07: El sistema debe permitir generar una lista de productos e ingredientes que requieren reposición.
- RF08: El sistema debe permitir registrar mermas de productos e ingredientes.
- RF09: El sistema debe permitir a la dueña consultar y modificar el inventario completo.
- RF10: El sistema debe permitir a los trabajadores consultar únicamente el inventario correspondiente a su área. 
- RF11: El sistema debe permitir consultar información histórica del inventario para apoyar las decisiones de compra.
## 5) Requerimientos no funcionales
- RNF01: El sistema debe contar con control de acceso según el rol del trabajador.
- RNF02: La información del inventario debe actualizarse oportunamente después del registro de una entrada, salida, merma o venta.
- RNF03: El sistema debe ser accesible desde dispositivos móviles de trabajadores y computadores de la cafetería.
- RNF04: El sistema debe ser simple y fácil de utilizar para trabajadores que actualmente realizan el proceso mediante planillas en papel. 
- RNF05: El sistema debe mantener la información de inventario almacenada de forma clara para evitar diferencias entre los registros y el stock disponible. 
## 6) Priorización y justificación de requerimientos
Se utiliza la metodología MoSCoW para priorizar los requerimientos:

- RF01:  Must, ya que es necesario contar con los productos e ingredientes que estarán contenidos en el inventario. 
- RF02: Must, ya que permite registrar las entradas de productos e ingredientes al inventario. 
- RF03: Must, ya que es fundamental para actualizar el stock según las ventas y los productos e ingredientes utilizados, respondiendo al problema identificado.
- RF04: Must, ya que permite conocer el stock disponible para facilitar el control del inventario.
- RF05: Must, ya que permite establecer los niveles mínimos utilizados para decidir cuándo reponer. 
- RF06: Must, ya que permite anticipar posibles quiebres de stock mediante alertas.
- RF07: Must, ya que apoya directamente las decisiones de compra y pedido a provedores. 
- RF08: Should, ya que permite registrar las mermas y obtener información sobre las pérdidas de productos e ingredientes.
- RF09: Must, ya que la dueña debe poder consultar el inventario completo y modificarlo mediante el ingreso de nuevos productos e ingredientes.
- RF10: Must, ya que es necesario separar el acceso de los trabajadores según su área.
- RF11: Could, ya que aporta información adicional para apoyar futuras decisiones de compra. 
- RNF01: Must, ya que permite controlar qué puede consultar cada trabajador según su cargo.
- RNF02: Must, ya que la falta de actualización oportuna del inventario es parte central del problema identificado.
- RNF03: Should, ya que permite utilizar el sistema desde dispositivos móviles de los trabajadores y computadores de la cafetería, facilitando el registro y consulta de inventario.
- RNF04: Should, ya que busca facilitar el uso del sistema por parte de los trabajadores.
- RNF05: Must, ya que es necesario mantener consistencia en la información para reducir diferencias entre el registro y el stock real disponible.
## 7) Requerimientos trazados al problema
- El inventario se registra manualmente y requiere mantener identificados los productos e ingredientes que forman parte del stock: RF01, RF02, RF03, RNF02 y RNF05.
- Existen diferencias entre el stock registrado y el stock real: RF03, RF04 y RNF05.
- Fudo registra las ventas, pero no permite identificar en detalle los productos e ingredientes utilizados en cada venta: RF03.
- No se sabe con precisión qué productos o ingredientes deben comprarse, dificultando las decisiones de compra: RF04, RF05, RF06, RF07 y RF11.
- Se realizan compras adicionales durante la semana cuando faltan productos: RF05, RF06 y RF07.
- Existen pérdidas de productos por vencimiento y mermas: RF08.
- La dueña necesita consultar y modificar el inventario completo: RF09.
- Los trabajadores necesitan consultar el inventario correspondiente a su área: RF10 y RNF01.
- Se requiere facilitar el uso del sistema dentro de la cafetería: RNF03 y RNF04.
