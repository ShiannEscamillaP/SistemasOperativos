## Objetivo

Crear dos llamados a sistema una para apagar y otra para reiniciar y crear sus respectivos programas

## Herramientas
git make gcc

## Conceptos
*1) Llamadas al sistema:* 
+ La formal que el kernel (SO) de acceso al HW
+ Se implemente mediante interrupciones de software (trap), ie: la aplicación se interrumpe para que el kernel se ejecute.

*2) Modo kernel:*
+ Es el bit/registro que activa el CPU para acceder al HW
+ Solo hay un programa que se ejecuta con este bit, es el kernel

*3) Interrupciones*
+ Es la forma que el HW interactua con el CPU

## Que aprendi
Aprendimos a crear nuestros propios métodos báscos en el sistema operativo xv-6. Las llamadas que creamos fueron las de apagar y a reiniciar. Para esto buscamos en google el código, pues ahí se encontraban la memoria a la que se tenía que escribir. Estudiamos mas a fondo algunos de los archivos que se deben modificar o actualizar cuando agregamos una función al sistema operativo. Tuvimos que hacer diferentes debugging, pues primero no se encontro el dato correcto a mandar o no incluiamos todas las librerías en los archivos de C que creamos. 

https://github.com/ShiannEscamillaP/SistemasOperativos/blob/master/Makefile
