# Catedra-REDIS
Base de datos
  Gestión de pedidos
  Se requiere un software para la gestión de pedidos. Dicho software debe cumplir con una 
  serie de requerimientos que se enumeran a continuación: Administrar clientes (id, 
  dirección, teléfono y correo electrónico), los cuales realizan pedidos de productos en línea 
  a través de un carrito de compras que tiene una fecha de creación para validar su expiración 
  que solo dura 24 horas. Al agregar un producto al carrito se debe considerar la cantidad y 
  el precio del producto en ese momento, a lo cual se le denomina línea de producto. 
  Un carrito de compras puede almacenar muchas líneas de producto, permitiendo así que 
  durante las 24 horas de disponibilidad se puedan adjuntar varios de estos. En cuanto al 
  cliente este puede ser una persona natural o jurídica, donde a la persona natural se le pedirá 
  el documento de identidad, el primer nombre, el segundo nombre, el primer apellido y el 
  segundo apellido. 
  En el caso del tipo jurídico se le solicitará la razón social y el NIT, un pedido podrá ser enviado 
  únicamente cuando ya se hubiese realizado el pago por parte del cliente. Para despachar el 
  pedido se necesita la dirección de destino, fecha de envío, la empresa de mensajería y se 
  debe mantener un estado si se ha finalizado o no. El pago de un cliente se realiza en línea y 
  se debe almacenar con la fecha, el id del cliente, el id del pedido y la cantidad pagada. A 
  partir de lo anterior, proceder con la construcción de diseños e implementación de base de 
  datos solicitada al principio de este enunciado
