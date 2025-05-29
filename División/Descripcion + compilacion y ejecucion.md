División de dos enteros (32 bits)

Asignatura: Diseño y Estructura de Computadoras  
Carnet: MS23056UNO  
Ejercicio: División de dos enteros

Descripción:
Este programa realiza la división de dos números enteros de 32 bits. 
El cociente se convierte a formato ASCII mediante una subrutina y se muestra por consola.

Datos utilizados:
num1 = 100  
num2 = 5  
Resultado esperado: 20

Instrucciones utilizadas:
- mov, cdq, idiv, call, push, pop, div, add, int 0x80

Compilación y ejecución en Linux:
nasm -f elf32 division.asm -o division.o  
ld -m elf_i386 division.o -o division  
./division

Salida esperada:
El resultado es: 20

Compilaciion y ejecucion:

nasm -f elf32 division.asm -o division.o

ld -m elf_i386 division.o -o division

./division

