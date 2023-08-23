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
Principales: Tienen objetivos de usuario que se satisfacen mediante el uso del sistema.<br>
De apoyo: Son aquellos que brindan proporcianan un servicio al sistema. Ejemplo: Pasarela de pago.

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

