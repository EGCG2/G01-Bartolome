# G01-Bartolome
Correspondiente a la practica opcional de Gradle de EGC
Se han añadido diferentes dependencias

La hemos añadido mediante la incorparación de las etiquetas ```dependencies { compile ...``` en build.gradle:

### Plugin

Se ha añadido el plugin de:
  1. -  **checkstyle** (apply plugin: 'checkstyle') con el podemos ver los fallos de estilo en el codigo java, una vez ejecutemos gradle build, pero no ha bastado con insertar esto, se ha tenido que añadir la tarea de generar el informe obteniendo antes el tipo de informe en /config.
  Finalmente el informe se genera en: ```"build/reports/checkstyle.html"```
