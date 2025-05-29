Multiplicación de dos enteros (8 bits)

Asignatura: Diseño y Estructura de Computadoras  
Carnet: MS23056UNO  
Ejercicio: Multiplicación de dos enteros

Descripción:
Este programa realiza la multiplicación de dos números de 8 bits sin signo.
El resultado se convierte a ASCII y se imprime por consola.

Datos utilizados:
num1 = 6  
num2 = 7  
Resultado esperado: 42

Instrucciones utilizadas:
- mov, mul, movzx, div, add, xor, test
- int 0x80 para impresión y salida

Compilación y ejecución en Linux:
nasm -f elf32 multiplicacion.asm -o multiplicacion.o  
ld -m elf_i386 multiplicacion.o -o multiplicacion  
./multiplicacion

Salida esperada:
Resultado: 42

Compilacion y ejecucion:

nasm -f elf32 multiplicacion.asm -o multiplicacion.o

ld -m elf_i386 multiplicacion.o -o multiplicacion

./multiplicacion

