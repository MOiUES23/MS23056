Resta de tres enteros (16 bits)

Asignatura: Diseño y Estructura de Computadoras  
Carnet: MS23056 
Ejercicio: Resta de tres enteros

Descripción:
Este programa en ensamblador realiza la resta de tres números de 16 bits. 
El resultado se convierte a ASCII y se imprime en pantalla ademas soporta resultados negativos.

Datos utilizados:
num1 = 15  
num2 = 7  
num3 = 3  
Resultado esperado: 5

Instrucciones utilizadas:
- mov, sub, movsx, div, add, cmp, neg, jmp
- int 0x80 para llamadas al sistema

Compilación y ejecución en Linux:
nasm -f elf32 resta_tres.asm -o resta_tres.o  
ld -m elf_i386 resta_tres.o -o resta_tres  
./resta_tres

Salida esperada:
Resultado: 5

Comandos para compilar y Ejecutar:

nasm -f elf32 resta_tres.asm -o resta_tres.o
ld -m elf_i386 resta_tres.o -o resta_tres
./resta_tres
