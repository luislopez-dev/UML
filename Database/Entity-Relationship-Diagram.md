# Diagrama De Entidad-Relación (ERD)

### Cardinalidad

Define la relación en un contexto númerico. En particular en mínimos y máximos. 

![Captura de pantalla (190)](https://github.com/luislopez-dev/UML/assets/48783255/0f1324ef-8af5-48eb-adca-4fb3426933c7)


### Conceptos

1. Llave primaria compuesta: Dos llaves foraneas que crean una sola llave primaria. 
2. Tabla puente: Permite una relación intermedia de uno a muchos. Ejemplo: entidad de pedido.

### Ejemplo:

![ER-Diagram](https://github.com/luislopez-dev/UML/assets/48783255/6fb22e13-ac95-4093-9dd8-e512483361f9)

```sql

CREATE TABLE [Cliente] (
  [Cliente_id] Type,
  [Nombre] Type,
  [Apellido] Type,
  [Calle] Type,
  [Ciudad] Type,
  [Teléfono] Type,
  PRIMARY KEY ([Cliente_id])
);

CREATE TABLE [Pedido] (
  [Numero_pedido] Type,
  [Cliente_id] Type,
  [Nombre_cliente] Type,
  [A_calle] Type,
  [A_ciudad] Type,
  [A_estado] Type,
  [Fecha_envio] Type,
  [Producto_id] Type,
  PRIMARY KEY ([Numero_pedido])
);

CREATE TABLE [Producto] (
  [Producto_id] Type,
  [Cantidad] Type,
  [Tipo_producto] Type,
  PRIMARY KEY ([Producto_id])
);

CREATE TABLE [Envio] (
  [Producto_id] Type,
  [Pedido_id] Type,
  [Hora_cargo_tarjeta] Type,
  [Hora_empacado] Type,
  [Fecha_envio] Type,
  PRIMARY KEY ([Producto_id], [Pedido_id])
);



```
