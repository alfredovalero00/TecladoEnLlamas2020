
# Solución Día 2

Para la solución del día 2 he utilizado Angular.

## Compilación
Basta con ejecutar el comando *npm install* en el directorio del 'package.json'. Y una vez instalados los módulos ejecutar *ng serve*.

## Estructura
Antes de nada, sólo hay una carpeta source, ya que utilizo el mismo programa para dar salida a las dos soluciones.

He creado un servicio *input.service* que mediante una llamada 'Get' al archivo local (situado en **assets/resources/input.txt**) obtiene el contenido del mismo. (En caso de error se muestra por pantalla)

El componente *workflow.component* se encarga de dibujar las distintas secciones de las soluciones.

La clase *Present* contiene los atributos de los regalos (medidas y áreas).

Posteriormente en la clase principal *app.component*se realiza el procesamiento de la información para aportar las dos soluciones.  