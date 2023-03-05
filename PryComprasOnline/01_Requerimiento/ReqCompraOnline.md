# Caso de uso 1: Realizar una compra en línea

## Descripción

El caso de uso describe el proceso de realizar una compra en línea a través de una plataforma de comercio electrónico.

## Actores

- Usuario registrado
- Sistema de comercio electrónico
- Proveedor de servicios de pago

## Flujo básico

1. El usuario inicia sesión en la plataforma de comercio electrónico.
2. El usuario busca el producto deseado y lo agrega al carrito de compras.
3. El usuario verifica el contenido del carrito de compras y confirma la compra.
4. El sistema de comercio electrónico muestra una página de resumen de la compra y solicita la información de envío y facturación.
5. El usuario proporciona la información de envío y facturación.
6. El sistema de comercio electrónico muestra una página de confirmación de la compra y redirige al usuario a la plataforma de pago.
7. El proveedor de servicios de pago procesa la transacción y redirige al usuario de regreso a la plataforma de comercio electrónico.
8. El sistema de comercio electrónico muestra una página de confirmación final de la compra.

## Extensiones

- El usuario puede agregar o eliminar productos del carrito de compras en cualquier momento antes de confirmar la compra.
- Si el proveedor de servicios de pago no puede procesar la transacción, el sistema de comercio electrónico muestra un mensaje de error al usuario.

## Precondiciones

- El usuario debe estar registrado en la plataforma de comercio electrónico.
- El usuario debe tener una forma válida de pago registrada en la plataforma de comercio electrónico.
- El producto deseado debe estar disponible en la plataforma de comercio electrónico.

## Postcondiciones

- El producto deseado se reserva en el inventario de la plataforma de comercio electrónico.
- El usuario recibe una confirmación de compra por correo electrónico.
- El proveedor de servicios de envío recibe una solicitud de envío del producto.

