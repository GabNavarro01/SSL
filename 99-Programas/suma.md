## Ejemplos de funcionamiento de suma.c

```bash
> gcc suma.c -o suma

> .\suma.exe
uso: suma nro1 nro2

> .\suma.exe 1
uso: suma nro1 nro2

> .\suma.exe 1 3
la suma de 1 y 3 es 4  

> .\suma.exe 400 400
la suma de 400 y 400 es 800  

> .\suma.exe 1 a
nro1 y nro2 deben ser constantes numericas  

> .\suma.exe 1 2a
nro1 y nro2 deben ser constantes numericas  
```

## Tabla de Categorías Léxicas
<center>


| Número de línea | Lexema                      |   Token                    |
|:-----------------:|:-----------------------------:|:----------------------------|
| 1               | #include                    | palabraReservada           |
| 1               | <                           | operador                   |
| 1               | stdlib.h                    | literalCadena              |
| 1               | >                           | operador                   |
| 2               | #include                    | palabraReservada           |
| 2               | <                           | operador                   |
| 2               | stdio.h                     | literalCadena              |
| 2               | >                           | operador                   |
| 3               | #include                    | palabraReservada           |
| 3               | <                           | operador                   |
| 3               | ctype.h                     | literalCadena              |
| 3               | >                           | operador                   |
| 5               | int                         | palabraReservada           |
| 5               | esNumero                    | identificador              |
| 5               | (                           | carácterPuntuación         |
| 5               | const                       | palabraReservada           |
| 5               | char                        | palabraReservada           |
| 5               | *                           | operador                   |
| 5               | nro                         | identificador              |
| 5               | )                           | carácterPuntuación         |
| 6               | i                           | identificador              |
| 6               | =                           | operador                   |
| 6               | 0                           | constante                  |
| 6               | ;                           | carácterPuntuación         |
| 7               | while                       | palabraReservada           |
| 7               | (                           | carácterPuntuación         |
| 7               | nro                         | identificador              |
| 7               | [                           | carácterPuntuación         |
| 7               | i                           | identificador              |
| 7               | ]                           | carácterPuntuación         |
| 7               | !=                          | operador                   |
| 7               | '\0'                        | constante                  |
| 7               | )                           | carácterPuntuación         |
| 7               | {                           | carácterPuntuación         |
| 8               | if                          | palabraReservada           |
| 8               | (                           | carácterPuntuación         |
| 8               | !                           | operador                   |
| 8               | isdigit                     | identificador              |
| 8               | (                           | carácterPuntuación         |
| 8               | nro                         | identificador              |
| 8               | [                           | carácterPuntuación         |
| 8               | i                           | identificador              |
| 8               | ]                           | carácterPuntuación         |
| 8               | )                           | carácterPuntuación         |
| 8               | {                           | carácterPuntuación         |
| 9               | return                      | palabraReservada           |
| 9               | 0                           | constante                  |
| 9               | ;                           | carácterPuntuación         |
| 10              | }                           | carácterPuntuación         |
| 11              | i                           | identificador              |
| 11              | ++                          | operador                   |
| 11              | ;                           | carácterPuntuación         |
| 12              | }                           | carácterPuntuación         |
| 13              | return                      | palabraReservada           |
| 13              | 1                           | constante                  |
| 13              | ;                           | carácterPuntuación         |
| 19              | }                           | carácterPuntuación         |
| 16              | int                         | palabraReservada           |
| 16              | main                        | identificador              |
| 16              | (                           | carácterPuntuación         |
| 16              | int                         | palabraReservada           |
| 16              | argc                        | identificador              |
| 16              | ,                           | carácterPuntuación         |
| 16              | char                        | palabraReservada           |
| 16              | **                          | operador                   |
| 16              | argv                        | identificador              |
| 16              | )                           | carácterPuntuación         |
| 16              | {                           | carácterPuntuación         |
| 17              | if                          | palabraReservada           |
| 17              | (                           | carácterPuntuación         |
| 17              | argc                        | identificador              |
| 17              | !=                          | operador                   |
| 17              | 3                           | constante                  |
| 17              | )                           | carácterPuntuación         |
| 17              | {                           | carácterPuntuación         |
| 18              | puts                        | identificador              |
| 18              | (                           | carácterPuntuación         |
| 18              | "uso: suma nro1 nro2"       | literalCadena              |
| 18              | )                           | carácterPuntuación         |
| 18              | ;                           | carácterPuntuación         |
| 19              | exit                        | identificador              |
| 19              | (                           | carácterPuntuación         |
| 19              | 0                           | constante                  |
| 19              | )                           | carácterPuntuación         |
| 19              | ;                           | carácterPuntuación         |
| 20              | }                           | carácterPuntuación         |
| 21              | if                          | palabraReservada           |
| 21              | (                           | carácterPuntuación         |
| 21              | !                           | operador                   |
| 21              | esNumero                    | identificador              |
| 21              | (                           | carácterPuntuación         |
| 21              | argv                        | identificador              |
| 21              | [                           | carácterPuntuación         |
| 21              | 1                           | constante                  |
| 21              | ]                           | carácterPuntuación         |
| 21              | )                           | carácterPuntuación         |
| 21              | ||                          | operador                   |
| 21              | !                           | operador                   |
| 21              | esNumero                    | identificador              |
| 21              | (                           | carácterPuntuación         |
| 21              | argv                        | identificador              |
| 21              | [                           | carácterPuntuación         |
| 21              | 2                           | constante                  |
| 21              | ]                           | carácterPuntuación         |
| 21              | )                           | carácterPuntuación         |
| 21              | )                           | carácterPuntuación         |
| 21              | {                           | carácterPuntuación         |
| 22              | puts                        | identificador              |
| 22              | (                           | carácterPuntuación         |
| 22              | "nro1 y nro2 deben ser constantes numericas"       | literalCadena              |
| 22              | )                           | carácterPuntuación         |
| 22              | ;                           | carácterPuntuación         |
| 23              | exit                        | identificador              |
| 23              | (                           | carácterPuntuación         |
| 23              | -1                          | constante                  |
| 23              | )                           | carácterPuntuación         |
| 23              | ;                           | carácterPuntuación         |
| 24              | }                           | carácterPuntuación         |
| 25              | int                         | palabraReservada           |
| 25              | sum1                        | identificador              |
| 25              | =                           | operador                   |
| 25              | atoi                        | identificador              |
| 25              | (                           | carácterPuntuación         |
| 25              | argv                        | identificador              |
| 25              | [                           | carácterPuntuación         |
| 25              | 1                           | constante                  |
| 25              | ]                           | carácterPuntuación         |
| 25              | )                           | carácterPuntuación         |
| 25              | ;                           | carácterPuntuación         |
| 26              | int                         | palabraReservada           |
| 26              | sum2                        | identificador              |
| 26              | =                           | operador                   |
| 26              | atoi                        | identificador              |
| 26              | (                           | carácterPuntuación         |
| 26              | argv                        | identificador              |
| 26              | [                           | carácterPuntuación         |
| 26              | 2                           | constante                  |
| 26              | ]                           | carácterPuntuación         |
| 26              | )                           | carácterPuntuación         |
| 26              | ;                           | carácterPuntuación         |
| 27              | printf                      | identificador              |
| 27              | (                           | carácterPuntuación         |
| 27              | "la suma de %d y %d es %d" | literalCadena              |
| 27              | ,                           | carácterPuntuación         |
| 27              | sum1                        | identificador              |
| 27              | ,                           | carácterPuntuación         |
| 27              | sum2                        | identificador              |
| 27              | ,                           | carácterPuntuación         |
| 27              | sum1+sum2                   | identificador              |
| 27              | )                           | carácterPuntuación         |
| 27              | ;                           | carácterPuntuación         |
| 28              | return                      | palabraReservada           |
| 28              | 0                           | constante                  |
| 28              | ;                           | carácterPuntuación         |
| 29              | }                           | carácterPuntuación         |

</center>

```c
#include <stdlib.h>
#include <stdio.h>
#include <ctype.h>

int esNumero(const char *nro) {
	int i = 0;
    while (nro[i] != '\0') { 
        if (!isdigit(nro[i])) {
            return 0; //Retorno false
        }
        i++;
    }
    return 1; //Retorno true
}

int main(int argc, char **argv) {
	if (argc != 3) {
		puts("uso: suma nro1 nro2");
		exit(0);
	}
	if (!esNumero(argv[1]) || !esNumero(argv[2])) {
		puts("nro1 y nro2 deben ser constantes numericas");
		exit(-1);
	} 
	int sum1 = atoi(argv[1]);
	int sum2 = atoi(argv[2]);
	printf("la suma de %d y %d es %d", sum1, sum2, sum1+sum2);
	return 0;
}
```