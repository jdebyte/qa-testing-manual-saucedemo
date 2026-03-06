ID: BUG-CHK-07  
Título: El campo de nombre permite ingresar caracteres especiales

Prioridad: Media  
Severidad: Media  
Módulo: Formulario de checkout  
Entorno: Google Chrome Versión 145.0.7632.117 (64 bits)  

Pasos para reproducir

1.- Acceder al proceso de checkout.
2.- En el campo de nombre, ingresar caracteres especiales (ej: @#$%&).
3.- Intentar continuar.

Resultado esperado

El sistema debería mostrar un mensaje de validación y no permitir caracteres especiales.

Resultado actual

El sistema permite ingresar caracteres especiales sin mostrar error.
