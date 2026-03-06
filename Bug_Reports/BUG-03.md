ID: BUG-CART-16  
Título: El sistema permite iniciar checkout con el carrito vacío

Prioridad: Alta  
Severidad: Alta  
Módulo: Checkout  
Entorno: Google Chrome Versión 145.0.7632.117 (64 bits)  

Pasos para reproducir

1.- Iniciar sesión en la aplicación.
2.- Asegurarse de que el carrito esté vacío.
3.- Intentar proceder al checkout.

Resultado esperado

El sistema debería bloquear el proceso de checkout y mostrar un mensaje indicando que el carrito está vacío.

Resultado actual

El sistema permite continuar al proceso de checkout aun cuando el carrito está vacío.
