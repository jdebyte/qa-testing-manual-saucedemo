ID: BUG-CHK-15  
Título: El sistema permite finalizar compra sin productos en el carrito

Prioridad: Crítica  
Severidad: Crítica  
Módulo: Checkout  
Entorno: Google Chrome Versión 145.0.7632.117 (64 bits)  

Pasos para reproducir

1.- Iniciar sesión en la aplicación.  
2.- Asegurarse de que el carrito esté vacío.  
3.- Ir al checkout.  
4.- Intentar finalizar la compra.  

Resultado esperado

El sistema no debería permitir finalizar la compra si el carrito está vacío.

Resultado actual

El sistema permite completar la compra aun cuando el carrito no tiene productos.
