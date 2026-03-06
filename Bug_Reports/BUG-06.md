ID: BUG-CHK-09  
Título: El sistema permite ingresar códigos postales inválidos

Prioridad: Media  
Severidad: Media  
Módulo: Formulario de checkout  
Entorno: Google Chrome Versión 145.0.7632.117 (64 bits)

Pasos para reproducir

1.- Acceder al checkout.  
2.- Ingresar un código postal inválido (ej: 00000 o letras).  
3.- Continuar con el proceso.  

Resultado esperado

El sistema debería validar el formato del código postal y mostrar un error si es inválido.

Resultado actual

El sistema acepta códigos postales inválidos sin validación.
