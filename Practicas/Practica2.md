
## Objetivo
  Modificar el program sh.c para ejecutar el comando anterior 
  
## Herramientas
git
make
gcc

## Conceptos 
1) Como se crean los procesos
+ un programa padre (sh.c) ejecuta la llamada al sistema fork 
+ la llamada al sistema (fork) clona al proceso padre
+ el proceso hijo manda a llamar a exec para convertirse 

## Que aprendí
  Aprendimos a crear un proceso de manera práctica. El proceso que creamos es de los más básicos, ejecutar el último comando ejecutado al presionar la tecla "P". Para esto tuvimos que modificar el archivo "sh.c". 

## Commit
https://github.com/ShiannEscamillaP/SistemasOperativos/blob/master/sh.c

## Como se relaciona con los conceptos anteriores
  Con esta práctica pudimos relacionar el concepto de llamadas al sistema que hemos visto previamente.  
  
