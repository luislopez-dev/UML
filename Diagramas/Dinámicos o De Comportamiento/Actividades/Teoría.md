# Diagrama de Actividades

Permite detallar flujos de trabajo desde el punto de inicio hasta el punto final detallando los puntos
de decisión, bifurcaciones y rutas de decisión.

Son utilizados para representar el comportamiento interno de una operación, un caso de uso o un 
proceso de negocio (Workflow).

Tiene la facultad de expandirse y mostrar quien tiene la responsabilidad en un proceso. 

Elementos principales:

![Diagrama de actividades - Elementos principales](https://github.com/luislopez-dev/UML/assets/48783255/49f74b26-9bbc-4b26-8aae-2eb641009029)

Nodo decisión - fusión

![Nodo decisión - fusión](https://github.com/luislopez-dev/UML/assets/48783255/9d9589bb-55f7-4201-ae20-612306153561)

Nodo-bifurcación-unión

![Nodo-bifurcación-unión](https://github.com/luislopez-dev/UML/assets/48783255/d63514fd-fecb-4444-8d7f-dccb1aa23937)

Ejemplo - Nodo-bifurcación-unión

![Ejemplo - Nodo Bifurcación - Unión](https://github.com/luislopez-dev/UML/assets/48783255/94d26688-d0ad-4510-9de4-5af1601d9c0c)

Nodo Objeto

![Nodo objeto](https://github.com/luislopez-dev/UML/assets/48783255/28fc0f8e-6d75-4c49-ac4f-28cd027bb32f)

## Señales

### * Señales de envio y recepción: Permite enviar o recibir un mensaje / evento.

![Captura de pantalla (174)](https://github.com/luislopez-dev/UML/assets/48783255/89ac8afa-a8a7-4f8a-ab83-207d1bf0f662)

![send-receive-img-2](https://github.com/luislopez-dev/UML/assets/48783255/61724283-18ec-4c4d-b04d-b198f513832f)

## Región de actividad interrumpible

Permite marcar el grupo de acciones cuya ejecución puede interrumpirse por una excepción, 
y la/las acciones a tomar para manejar dicha excepción. 

![Captura de pantalla (183)](https://github.com/luislopez-dev/UML/assets/48783255/431a8e50-2f36-4831-92f2-1a01edddbd4f)

### * Señales de tiempo: Permite representar cada cuanto se ejecutará una determinada actividad.

![señales de tiempo-teoría](https://github.com/luislopez-dev/UML/assets/48783255/320f543f-bc07-4012-8c14-023cba491288)

### Ejemplo:

![señales de tiempo-ejemplo](https://github.com/luislopez-dev/UML/assets/48783255/ec4ebb5c-d3bc-4d32-b37f-44431d862306)

## PARTICIONES O MARCOS DE REPONSABILIDAD

Son franjas que pueden ser horizontales o verticales, sirven para expandir el diagrama de actividades y mostrar quien tiene la 
responsabilidad en un proceso. Representan a un determinado objeto o sujeto. Cada uno muestra el nombre de un responsable 
y las actividades que se encuentran a su cargo.

﻿![particiones-ejemplo](https://github.com/luislopez-dev/UML/assets/48783255/4b7d02d0-9c07-43f7-99da-54312ce92ca0)

# Ejercicio diagrama de actividades:


## Problema:

Una empresa dedicada al comercio de ropa para damas ha reunido a su personal para realizar el levantamiento de su proceso de venta en línea. Tu trabajo es apoyarles en el modelado del diagrama de actividades. A la reunión ha asistido personal del área de ventas, atención al cliente, facturación, bodega e inventario.
Iniciada la reunión, la persona de ventas indica que el proceso comienza cuando el usuario ingresa a la tienda virtual, selecciona los productos a comprar, y paga el valor de compra, la persona de ventas indica que antes de realizar el pago el usuario puede ver el detalle de la factura mediante la tienda virtual, pero las facturas canceladas no son enviadas directamente a la bodega para su despacho, por políticas internas de la empresa cada factura generada por compra en línea es revisada de forma manual por una persona de ventas. Las ordenes de compra que tienen factura revisada son enviadas al área de bodega para su despacho, la persona de la bodega indica que lo primero que realiza tras recibir las ordenes de compra es revisar si existe el producto en stock debido a que en ocasiones dos o más usuarios compra el mismo producto en línea de manera simultánea generando falta de producto en la bodega. Si el producto existe en stock el despacho es realizado, pero si el producto no existe la empresa tiene una política de compensación al usuario el cual consiste en: generar a favor del consumidor un cupón del 20% de descuento para su próxima compra, tarea que está a cargo de la persona de ventas, mientras que la persona de atención al cliente llama vía telefónica al usuario y le informa de la demora así como su respectiva bonificación, por otro lado cuando suceden este tipo de casos la persona de inventario realiza una adquisición inmediata del producto. Finalmente, cuando el producto se encuentra listo en bodega se realiza el despacho.
La administración ha solicitado adicional que en el diagrama de actividades se especifique los estados de la orden de compra para una mejor comprensión de cómo evoluciona este a lo largo del proceso.


# Pasos para la resolicón de un diagrama de actividades:

## 1. Leer detenidamente el problema poniendo mayor atención a todo lo que involucre lógica de negocio:

1.1 Actores
1.2 Acciones
1.3 Puntos de decisión

## 2. Identificar los actores: usuario, persona de ventas, persona de bodega, persona de atención al cliente, persona de inventario. 

## 3. Colocar a los actores en la herramienta de modelado

![Captura de pantalla (181)](https://github.com/luislopez-dev/UML/assets/48783255/3fcd6411-f719-4233-8a56-9d2434d11fdc)

## 4. Identificar las acciones y puntos de decisión:

4.1 Identificar las acciones:_

a. Usuario: ingresa a la tienda virtual, selecciona los productos a comprar, paga el valor de la compra y ve el detalle de la factura.  
b. Persona de ventas: Revisa de forma manual cada una de las facturas generadas por compra en lina
c. Tras esto, Persona de bodegas: recibe las ordenes de compra y revisa si el producto existe o no en stock, si el producto existe realiza el despacho, 
d. pero si no existe, la persona de ventas genera a favor del consumidor un cupon por el 20% de descuento para su próxima compra 
e. la persona de atención al cliente llama vía telefónica al usuario
f. y la persona de inventario realiza una adquisición inmediata del producto 

4.2 Identificar los Puntos de decisión: 

¿Existe un producto en stock?

Las acciones son los pasos que realiza cada actor dentro de un proceso o actividad y los puntos de decisión son las condiciones
que hacen que el flujo de negocio sigan un camino u otro en base a al resultado de la evaluación de dicha condición. 

## 5. Colocar las acciones y puntos de decisión en la herramienta de modelado

![Activity Diagram - exercise - step - 5](https://github.com/luislopez-dev/UML/assets/48783255/c33b7d1d-0196-439b-a309-8184856f5c79)

## 6. Idéntificar nodo objeto y estados que este tomapra en el transcurso del tiempo

#### Nodo objeto: Orden de compra

![Activity Diagram - EXERCICE- STEP 6](https://github.com/luislopez-dev/UML/assets/48783255/320a0f22-f135-4433-ab97-ea41ba1a7dd8)


