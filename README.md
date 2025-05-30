# MS23056
PORTAFOLIO

Portafolio - Unidad 2  
Diseño y Estructura de Computadoras  
Carnet: MS23056 
Ciclo I/2025

Descripción:
Este repositorio contiene la solución a los ejercicios asignados en la Guía de Trabajo de la Semana 10. 
Los programas están desarrollados en lenguaje ensamblador NASM y fueron probados en sistemas GNU/Linux con soporte para arquitectura de 32 bits. 
Cada ejercicio incluye su propio archivo README con explicación específica.

Contenido:

1. resta.asm  
   Calcula la resta de tres números enteros de 16 bits.
   Se incluye manejo de resultados negativos y conversión a ASCII para su impresión.

2. multiplicacion.asm  
   Multiplica dos números de 8 bits y muestra el resultado.
   Usa instrucciones básicas de multiplicación sin signo.

3. division.asm  
   Divide dos números de 32 bits (dividendo y divisor) e imprime el cociente.
   Utiliza una subrutina para convertir el resultado a ASCII antes de mostrarlo.

Requisitos:
- NASM instalado
- Compatibilidad con binarios de 32 bits 

Compilación y ejecución:
Para cada ejercicio se debe ejecutar:

nasm -f elf32 archivo.asm -o archivo.o  
ld -m elf_i386 archivo.o -o archivo  
./archivo

Ejemplo:

nasm -f elf32 suma.asm -o suma.o  
ld -m elf_i386 suma.o -o suma  
./suma

