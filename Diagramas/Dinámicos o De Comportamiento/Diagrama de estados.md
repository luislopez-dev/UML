# Diagrama de estados

Muestra los estados por los cuales puede pasar una entidad u objeto en el transcuros del tiempo.

Un diagrama de estados captura los cambios de estado por un solo objeto, por lo tanto se debe crear un diagrama de estado por cada objeto.

¿Qué se necesita previamente para realizar un diagrama de estados?

Conocer el flujo total del proceso que vamos a implementar o a automatizar, 
por eso se debe haber realizado previamente un diagrama de actividades.

#### Pasos para realizar diagrama de actividades:

1. Tener listo el diagrama de actividades de todo el proceso de negocio a implementar:

Un diagrama de actividades nos permitirá: <br>
a. Tener una visión transversal y completa del flujo de negocio, y <br>
b. Nos facilitará la identificación de los objetos o entidades que requieran la generación de diagramas de estado.

![Diagrama de actividades madeFor  diagrama de estados](https://github.com/luislopez-dev/UML/assets/48783255/4bbe4491-41fc-46a2-83d8-3b565589ed5c)

<br>

2. Identificar los objetos o entidades involucradas en el proceso de negocio: <br>

2.1. Orden de compra <br>
2.2. Producto <br>
2.3. Cupon de descuento <br>

![Diagrama sin título drawio](https://github.com/luislopez-dev/UML/assets/48783255/8230b75e-3e14-48e8-af4c-b71692523dbd)

3. Identificar los estados y transiciones para el objeto o entidad 1 (Orden de compra)

Transiciones: Son acciones o condiciones que debe cumplirse para que una entidad pase a un estado a otro.
<br>

3.1. REGISTRADA <br>
3.2. PENDIENTE_DESPACHO <br>
3.3. DESPACHADA <br>
3.4. EN_CAMINO <br>
3.5. REGRESA_A_BODEGA <br>
3.6. ENTREGADA <br>

![Diagrama sin título drawio (1)](https://github.com/luislopez-dev/UML/assets/48783255/0b992cf7-8fa9-4649-be3f-ae6cf10c3b16)

4. Colocar estados y transiciones en herramienta de modelado

![Diagrama de estados - ORDENES](https://github.com/luislopez-dev/UML/assets/48783255/c908b875-461d-4e8c-ab4b-fda17e4c84c5)

5. Identificar los estados y transiciones para el objeto o entidad 2 (Producto)

Transiciones: Son acciones o condiciones que debe cumplirse para que una entidad pase a un estado a otro. <br>

5.1 DISPONIBLE <br>
5.2 RESERVADO <br>
5.3 VENDIDO <br>

![Activity Diagram0_0](https://github.com/luislopez-dev/UML/assets/48783255/6e822ba1-0386-4596-a594-d5af3e3e508f)

![Diagrama sin título drawio (3)](https://github.com/luislopez-dev/UML/assets/48783255/b0efdb58-80a5-4083-8556-af901f80cec1)

6. Colocar estado y transiciones en la herramienta de modelado



