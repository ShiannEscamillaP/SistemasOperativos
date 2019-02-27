## Objetivo 
Modificar el programa init para que muestre un programa de bienvenida 

## Herraminetas
gcc

## Conceptos 
 
 1)
 *Instancia de un programa 
 *Tiene tres partes: 
 **Stack: guarda las variables y las llamadas a funciones
 **Heap: memoria dinámica  (malloc o new )
 **Código 
 
 + Se crea mediante dos llamadas a sistema: 
 + fork clona
 + exec cambia el código 
 
 + Tiene un estado: 
 + Corriendo  
 + Durmiendo 
 + Espera
 + Completado
 + Zombie
 
 
2) El programa init 

+ Es el programa encargado de inicializar al SO para dejarlo listo para usarse 
+ Es el unico proceso que crea el SO
 ## Que aprendí
Aprendimos lo que es un proceso y modificamos el código del init o proceso padre para que mande un mensaje de bienvenida al inicio

## Commit 
https://github.com/ShiannEscamillaP/SistemasOperativos/blob/master/init.c
