# ICN292 - Sistema de Información para la Gestión de Inventario
## Mass Café SPA - La Cantina del Café
Este proyecto corresponde a la Entrega 1 del ramo ICN292 / Sistemas de Información para la Gestión y tiene como objetivo analizar una problemática real de una PYME y proponer un Sistema de Información para la Gestión que permita mejorar el proceso seleccionado.

El proyecto se desarrolla para Mass Café SPA, nombre de fantasía **La Cantina del Café**, y se centra en la gestión de inventario de productos e ingredientes.
## 1. Caso PYME
**Nombre legal:** Mass Café SPA  
**Nombre de fantasía:** La Cantina del Café  
**Actividad:** Cafetería de especialidad, con venta de almuerzos y bollería.  
**Ubicación:** Bellavista 0372, Providencia, Santiago.  
**Sucursal:** Única sucursal.

La información utilizada para el proyecto fue obtenida mediante una entrevista realizada a la dueña de la cafetería el 4 de septiembre de 2026, respaldada mediante un acta firmada.

La cafetería cuenta con atención presencial, actualmente utiliza Fudo para registrar sus ventas y planillas en papel para llevar el control del inventario.
Durante el levantamiento de información se identificaron distintos procesos de la cafetería, seleccionándose la gestión de inventario como el proceso principal para el desarrollo del proyecto.

Este proceso fue seleccionado debido a que, según la información entregada por la dueña, es el más crítico, el que consume mayor cantidad de tiempo y el que genera mayores dificultades para la operación del local.
## 2. Problema identificado
Actualmente, la gestión del inventario se realiza principalmente mediante planillas en papel y la información no se actualiza oportunamente. Esto genera diferencias entre el stock registrado y el stock real.
Fudo permite registrar las ventas, pero no permite identificar con suficiente detalle los ingredientes utilizados en cada venta. Por ejemplo, una venta de café con leche no permite determinar exactamente qué tipo y cantidad de café o leche fueron utilizados.
Debido a esto, la cafetería tiene dificultades para conocer cuánto stock queda, qué productos o ingredientes deben reponerse y cuánto se pierde por mermas o vencimiento de productos.

La revisión general del inventario se realiza los viernes y puede tomar aproximadamente 4 horas. Aparte, durante la semana se realizan revisiones parciales y pueden ser necesarias compras adicionales cuando algún producto o ingrediente se termina.
Según la información entregada durante la entrevista, actualmente se producen aproximadamente 2 quiebres de stock por semana.
### Consecuencias principales
- Mayor tiempo dedicado a las revisiones de inventario.
- Compras adicionales durante la semana.
- Viajes adicionales para conseguir productos o ingredientes faltantes.
- Pérdidas de productos por vencimiento y mermas.
- Posibles quiebres de stock y ventas perdidas.
- Dificultades para tomar decisiones de compra.
- Diferencias entre la información registrada y el stock disponible realmente.

## 3. Objetivo del SIG
El objetivo de nuestra intervención es mejorar la gestión de inventario de Mass Café SPA, permitiendo mantener información más oportuna sobre el ingreso, salida y disponibilidad de productos e ingredientes.
El sistema busca relacionar las ventas con los ingredientes utilizados, controlar los niveles mínimos de stock, registrar compras, mermas y generar alertas cuando algún producto o ingrediente este cerca de su stock mínimo para asi apoyar a las decisiones de reposición.

Con esto, se espera reducir el trabajo manual asociado al control de inventario y facilitar la toma de decisiones relacionadas con las compras.
## 4. Actores y alcance
### Actores principales
- Dueña: Tendrá acceso completo al sistema, pudiendo consultar y modificar el inventario, registrar compras y mermas, configurar productos, ingredientes y niveles mínimos, además de revisar las alertas y necesidades de reposición.
- Trabajadores de barra: Podrán registrar las ventas realizadas y consultar el inventario correspondiente a su área. además de realizar las ventas a los clientes.
- Trabajadores de cocina: Podrán consultar el inventario correspondiente a su área.
### Alcance
El sistema considera:
- Registro de productos e ingredientes.
- Registro de ingresos de inventario.
- Registro de salidas asociadas a ventas.
- Actualización del stock.
- Relación entre productos e ingredientes.
- Registro de mermas.
- Configuración de niveles mínimos.
- Alertas de reposición.
- Consulta de inventario por área.
- Registro de compras.
- Apoyo a la elaboración de una lista de reposición.
- Control de acceso según el rol del usuario.
- Consulta del historial de movimientos de inventario.
No se consideran como parte principal del proyecto procesos como contabilidad, recursos humanos o administración general de la cafetería.
## 5. Requerimientos del sistema
### Requerimientos funcionales
Entre los principales requerimientos funcionales se encuentran:
- Registrar productos e ingredientes.
- Registrar ingresos de productos e ingredientes.
- Registrar salidas asociadas a las ventas.
- Actualizar el stock según las operaciones realizadas.
- Consultar el stock disponible.
- Definir niveles mínimos para los artículos.
- Generar alertas cuando el stock alcance o se aproxime al nivel mínimo.
- Generar una lista de reposición.
- Registrar mermas.
- Permitir a la dueña consultar y modificar el inventario completo.
- Permitir a los trabajadores consultar el inventario correspondiente a su área.
- Consultar el historial de inventario.

### Requerimientos no funcionales

Los requerimientos no funcionales establecen características que debe cumplir el sistema para que pueda ser utilizado de manera adecuada.

Se consideran principalmente:

- **Control de acceso:** el sistema debe restringir las funciones disponibles según el rol del usuario. La dueña tendrá acceso completo, mientras que los trabajadores tendrán acceso limitado a las funciones correspondientes a su área.
- **Actualización oportuna:** la información del inventario debe actualizarse después de registrar una venta, compra, merma o ajuste, evitando depender de registros manuales realizados posteriormente.
- **Accesibilidad:** el sistema debe poder utilizarse desde computadores y dispositivos móviles, considerando la forma en que trabajan los usuarios de la cafetería.
- **Facilidad de uso:** la interfaz debe ser simple y fácil de utilizar para que los trabajadores puedan registrar las operaciones sin que el sistema dificulte el trabajo diario.
- **Consistencia de la información:** los movimientos registrados deben mantener coherencia entre las operaciones realizadas y el stock disponible, evitando diferencias innecesarias entre el inventario del sistema y el inventario real.

### Relación de los requerimientos con el problema

Los requerimientos fueron definidos directamente a partir de las dificultades identificadas en la gestión actual del inventario.

La falta de actualización oportuna se aborda mediante el registro de ingresos, salidas y ventas y mediante la actualización del stock.

Las diferencias entre el stock registrado y el stock real se abordan mediante el control de movimientos y la consistencia de la información.

La dificultad para identificar los ingredientes utilizados en cada venta se aborda relacionando los productos con sus ingredientes y permitiendo descontar del inventario las cantidades correspondientes.

Las compras adicionales y las dificultades para saber qué comprar se abordan mediante los niveles mínimos, las alertas de reposición y la lista de reposición.

El problema de las mermas se aborda mediante el registro de las pérdidas de productos e ingredientes.

Finalmente, las diferencias de acceso entre la dueña y los trabajadores se abordan mediante el control de acceso según roles.

Los requerimientos fueron priorizados utilizando **MoSCoW**, identificando aquellos que son indispensables para el funcionamiento de la solución y aquellos que pueden incorporarse posteriormente.

---

## 6. Modelamiento BPMN

### AS-IS

El modelo AS-IS representa la forma en que actualmente se realiza la gestión de inventario en la cafetería.

El proceso comienza con la revisión del inventario por parte de los trabajadores y la dueña. Luego se identifican los productos o ingredientes que faltan o que se encuentran bajo el nivel mínimo definido, se prepara una lista de compras y se realizan las compras correspondientes.

Posteriormente se reciben los productos adquiridos y se registran en las planillas de inventario cuando existe disponibilidad de tiempo.

Este proceso depende principalmente de registros manuales y revisiones periódicas, por lo que la información puede quedar desactualizada.

### TO-BE

El modelo TO-BE representa el proceso de gestión de inventario utilizando el sistema propuesto.

La dueña configura los productos, ingredientes, cantidades utilizadas y niveles mínimos. Los trabajadores pueden registrar las ventas realizadas y el sistema identifica automáticamente los ingredientes asociados al producto vendido.

A partir de la venta, el sistema descuenta las cantidades correspondientes del inventario y verifica si algún artículo se encuentra bajo su nivel mínimo.

Cuando corresponde, se genera una alerta de reposición que puede ser revisada por la dueña para apoyar la planificación de las compras.

Las compras realizadas también se registran en el sistema, actualizando el stock cuando los productos o ingredientes son recibidos.

Además, las mermas pueden registrarse para mantener el inventario actualizado.

### Breve explicación de las mejoras

El principal cambio entre el proceso AS-IS y el TO-BE es el reemplazo de gran parte del registro manual por un sistema que mantiene la información de inventario de manera más oportuna.

La solución permitirá:

- Actualizar automáticamente el inventario a partir de las ventas.
- Relacionar cada producto vendido con los ingredientes utilizados.
- Registrar las entradas provenientes de las compras.
- Registrar las mermas y pérdidas de productos o ingredientes.
- Mantener información actualizada sobre el stock disponible.
- Controlar los niveles mínimos de inventario.
- Generar alertas cuando sea necesario realizar una reposición.
- Facilitar la elaboración de una lista de compras.
- Permitir a la dueña revisar y ajustar el inventario cuando sea necesario.
- Permitir que los trabajadores consulten la información correspondiente a su área.

Con estas mejoras se busca disminuir el trabajo manual, reducir las compras adicionales y los quiebres de stock y facilitar las decisiones relacionadas con la reposición del inventario.

Los diagramas AS-IS y TO-BE y sus archivos editables se encuentran en la carpeta `assets/`.

---

## 7. Modelo Entidad-Relación

El modelo entidad-relación preliminar representa los principales datos necesarios para soportar el proceso TO-BE.

Las principales entidades consideradas son:

- Producto
- Ingrediente
- Configuracion_Producto
- Venta
- Detalle_Venta
- Detalle_Venta_Ingrediente
- Inventario_de_articulos
- Movimiento_Inventario
- Compra
- Detalle_Compra
- Proveedor
- Usuario
- Área
- Alerta_Reposicion

El modelo permite relacionar los productos con los ingredientes que utilizan, registrar las ventas y sus detalles, controlar el inventario, registrar movimientos, compras y mermas y generar alertas de reposición.

La entidad `Inventario_de_articulos` permite centralizar el stock de productos e ingredientes, mientras que `Movimiento_Inventario` permite mantener un historial de los cambios realizados.

De esta manera, el modelo de datos permite respaldar las principales actividades definidas en el proceso TO-BE.

---

## 8. Arquitectura y tecnologías

La solución se plantea mediante una arquitectura compuesta por una interfaz web, una lógica del sistema y una base de datos.

### Stack tecnológico propuesto

- **Frontend:** React + Vite
- **Backend:** Node.js + Express
- **Base de datos:** PostgreSQL
- **Entorno de ejecución:** Docker + Docker Compose

La interfaz web permitirá a los usuarios interactuar con el sistema.

El backend procesará las operaciones realizadas, como ventas, compras, mermas y movimientos de inventario.

PostgreSQL almacenará la información relacionada con productos, ingredientes, ventas, inventario, compras, usuarios y movimientos.

Docker y Docker Compose se utilizarán para facilitar la ejecución del sistema en un entorno local reproducible.

La información almacenada permitirá obtener indicadores relacionados con la gestión de inventario y apoyar la toma de decisiones.

---

## 9. Indicadores y resultados esperados

Para evaluar el problema identificado se consideran indicadores relacionados con la gestión del inventario.

Entre los principales aspectos a evaluar se encuentran:

- Tiempo utilizado en las revisiones de inventario.
- Cantidad de compras adicionales durante la semana.
- Cantidad de quiebres de stock.
- Cantidad de mermas.

Como situación inicial, la revisión general del inventario puede tomar aproximadamente **4 horas** y se producen aproximadamente **2 quiebres de stock por semana**.

La solución busca que la información de inventario esté disponible de manera más oportuna y facilite las decisiones de reposición.

Durante la Entrega 2 se podrán obtener datos del sistema que permitan evaluar los cambios producidos en estos indicadores.

---

## 10. Plan y relación con la Entrega 2

La Entrega 1 corresponde al diagnóstico y diseño preliminar de la solución.

Los resultados obtenidos en esta etapa servirán como base para la Entrega 2, donde se desarrollará e implementará el sistema.

Los principales hitos considerados son:

- Configuración del entorno y estructura inicial del proyecto.
- Implementación de la base de datos y modelo de datos.
- Desarrollo del backend y lógica de inventario.
- Desarrollo de la interfaz web.
- Integración de ventas, inventario, compras y alertas.
- Pruebas del sistema y corrección de errores.
- Evaluación de los indicadores y elaboración de resultados.
- Documentación y preparación de la entrega final.

También se consideraron riesgos relacionados con dificultades durante el desarrollo o integración del software, pérdida o inconsistencia de información, problemas de acceso según el rol del usuario y manejo de datos personales, considerando las disposiciones asociadas a la **Ley 21.719**.

---

## 11. Estructura del repositorio

```text
ICN292-Mass_Caf--SPA/
│
├── README.md
│
├── docs/
│   ├── 00-caso-pyme.md
│   ├── 01-requerimientos.md
│   ├── 02-bpmn.md
│   ├── 03-er-preliminar.md
│   ├── 04-arquitectura.md
│   └── 05-plan-E2.md
│
├── assets/
│   ├── BPMN AS-IS.bpm
│   ├── BPMN AS-IS.png
│   ├── BPMN to-be.bpm
│   ├── BPMN to-be.png
│   ├── arquitectura.drawio
│   ├── arquitectura.png
│   ├── er-preliminar.drawio
│   ├── er-preliminar.png
│   └── otros recursos y evidencias
│
└── informe/
    └── documentos correspondientes a la entrega
