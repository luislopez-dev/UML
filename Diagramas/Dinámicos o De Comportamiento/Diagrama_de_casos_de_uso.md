# Diagramas de caso de uso

Se usa para plasmar el comportamiento del sistema desde el punto de vista del usuario.

Muestra lo siguiente:

1. La aplicación o sistema a crear
2. Las funcionalidades que compondrán o conformarán el sistema
3. Los usuarios (actores) que interactuarán con cada una de las funconalidades del sistema

Nos permite:

1. Conocer la aplicación o sistema a crear
2. Identificar los componentes principales del sistema
3. Identificar la interacción entre los usuarios y el sistema

Elementos principales:

1. Sistema: Es lo que vamos a construir. Ejemplo: Tienda virtual, Sistema bancario, aplicación movil, etc.

2. Casos de uso: Son funcionalidades o acciones que  podremos realizar en el sistema. Están representados por un ovalo con el nombre del caso de uso dentro de ella. Deben ir siempre en el rectangulo (sistema) y el nombre debe iniciar con un verbo en infinitivo.

#### Ejemplo: Sistema de gestión de bodega 

Casos de uso: <br>

a. Administrar los catalogos de los productos <br>
b. Administrar las adquisiciones de los productos <br>
c. Registrar el despacho de lso productos <br>
d. Registrar devoluciones que hacen los clientes <br>
e. Consultar el stock en linea <br>

3. Actores: Son alguien o algo que utilizará nestro sistema (personas, sistemas, organizaciones). Está representado por
un icono de una persona, y deben ir siempre fuera de nuestro rectángulo pues son entidades externas del sistema.

#### Tipos de actores: <br>
* Principales: Tienen objetivos de usuario que se satisfacen mediante el uso del sistema.<br>
* De apoyo: Son aquellos que brindan proporcianan un servicio al sistema. Ejemplo: Pasarela de pago.

4. Relaciones

Permite mostrar la interacción entre un actor y un caso de uso, o entre un caso de uso y otro caso de uso. <br>

#### Tipos de relaciones

* Relaciones entre actores y casos de uso: <strong>Asociación</strong>

* Relaciones entre casos de uso:

* Generalizacion: Un caso de uso también se puede especializar en uno o más casos de uso hijos.
* Inclusión: es una relación mediante la cual se re-usa un caso encapsulado en distintos contextos a través de su invocación desde otros casos de uso.
* Extensión: es una relación que amplia la funcinalidad de un caso de uso mediante la extensión de sus secuancias de acciones. 


<br>

![Diagrama - casos de uso - elementos](https://github.com/luislopez-dev/UML/assets/48783255/373b79f8-e68a-4dba-8afe-fd99f3c70809)

<br>

## Ejercicio

### Problema:

Una empresa dedicada a la venta de artículos de belleza, a solicitado que se desarrolle un aplicativo para la venta en línea de sus productos.
Durante la reunión de levantamiento de requerimientos los solicitantes han indicado que dicho aplicativo debe permitir al cliente ver el catálogo de todos sus productos, seleccionar el producto que desee y agregarlo a un carrito para la compra. Los solicitantes han indicado que el sistema debe verificar la disponibilidad del producto antes de realizar las actividades anteriores. Una vez que el cliente ha finalizado la selección de sus productos, el sistema debe presentar en pantalla el detalle de la factura para que el cliente pueda continuar con el pago, los mecanismos habilitados para ello serán: Transferencia Bancaria y Pago con Tarjeta. Efectuado el pago el sistema deberá remitir automáticamente la factura al correo electrónico del cliente.
La empresa ha indicado también que el sistema debe incluir, una opción de consulta de compras realizada para el cliente, un módulo de administración de precios y descuentos para el administrador de la tienda, y finalmente, que se incluya como parte de la opción de pago una funcionalidad que permita al cliente ingresar sus cupones de descuento que reciben por compras frecuente o compras mayores a 300 dólares.

### Pasos para la resolución: 

1. Leer detenidamente el problema poniendo mayor atención a todo lo que involucre: funciones, actores y ralaciones.

2. Identificar el sistema

Aplicativo para la venta en línea

![Diagrama casos de uso - ejercicio -Paso 1](https://github.com/luislopez-dev/UML/assets/48783255/e7c0ce3a-78dc-4bda-91b3-f086e9b4352c)

3. Identificamos las funcionalidades (casos de uso): <br>

a. Visualizar productos <br>
b. Agregar producto a carrito <br>
c. Realizar pago <br>
d. Consultar compras realizadas <br>
e. Administrar precios y descuentos <br>
f. Verificar disponibilidad <br>
g. Enviar factura electrónica <br>
h. Procesar cupón de descuento <br>


![Diagrama de casos de uso - ejercicio - paso 5](https://github.com/luislopez-dev/UML/assets/48783255/345e7186-15e1-434f-9f6d-a5720a56b05b)

4. Identificar actores: <br>

Cliente y administrador de tienda virtual

   
5. Identificar relaciones entre actores y casos de uso

![5](https://github.com/luislopez-dev/UML/assets/48783255/79312d13-51e5-4b0c-95de-f7cf3b2e2318)


6. Identificar relaciones entre casos de uso

![6](https://github.com/luislopez-dev/UML/assets/48783255/498729bc-bcae-40d7-a0ff-2b7520b2136c)
