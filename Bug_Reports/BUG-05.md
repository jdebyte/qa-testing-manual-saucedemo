ID: BUG-CHK-08  
Título: El campo de nombre permite ingresar números

Prioridad: Media  
Severidad: Media  
Módulo: Formulario de checkout  
Entorno: Google Chrome Versión 145.0.7632.117 (64 bits)  

Pasos para reproducir

1.- Acceder al proceso de checkout.  
2.- En el campo nombre, ingresar números (ej: Juan123).  
3.- Continuar con el formulario.  

Resultado esperado

El sistema debería mostrar un error de validación y bloquear números en el campo nombre.

Resultado actual

El sistema permite ingresar números en el campo nombre sin validación.
