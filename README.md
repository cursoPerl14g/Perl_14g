# Perl_14g
Repositorio del curso de Perl donde estarán las presentaciones, tareas y prácticas
## Tarea 1: FizzBuzz

El programa debe recibir un número como argumento, realizando una impresión de todos los números (menores o igual a él) en forma de lista. 

Si un numero es múltiplo de 2 delante de él debe imprimir Fuzz.

Si es múltiplo de 3 debe imprimir Buzz

Si es múltiplo de ambos (2 y 3) debe imprimir FizzBuzz

```bash
#Ejemplo de ejecución:
./fizzbuzz.pl 6
```
```
# Salida en terminal:
1
2 Fizz
3 Buzz
4 Fizz
5
6 FizzBuzz
```
## Tarea 2: Palíndromos
Hacer un programa que indique si las cadenas introducidas son o no son palíndromos.

Las cadenas que evaluará el programa pueden ser leídas de 2 formas:

1. Como argumentos del script

```bash
# Ejemplo de ejecución:
./t2_lapellido.pl anitalavalatina "no deseo ese don" readme "Sometamos o matemos" roma 
```
```bash
# Salida en terminal:
anitalavalatina : es palíndromo
no deseo ese don : es palindromo
readme : no es palindromo
Sometamos o matemos : es palindromo
roma : no es palindromo
```

2. Sin argumentos, en este caso evaluará las cadenas que se introduzcan mediante STDIN y terminar su ejecución cuando se introduzca la cadena: "ya no"

```bash
# Ejemplo de ejecución: 
./t2_lapellido.pl 
```
```bash
# Salida en terminal:
> adan nada
Es palindromo
> roma 
No es palindromo
> anitalavalatina 
Es palindromo
> ya no
```
## Tarea 3: Dibujo
Hacer un programa que dibuje un rombo incompleto.

El programa recibe como argumento el número de "*" que tendrá como base (central) para formar la figura.

```bash
# Ejemplo de ejecución:
./t3_lapellido.pl 6 
```
```bash
# Salida en terminal:
     *
     **
  ******
   ****
    **
     
```
```bash
# Ejemplo de ejecución: 
./t3_lapellido.pl 14
```
```bash
# Salida en terminal:
         *
         **
         ***
         ****
         *****
         ******
  **************
   ************
    **********
     ********
      ******
       ****
        **
```
```bash
# Ejemplo de ejecución: 
./t3_lapellido.pl 15
```
