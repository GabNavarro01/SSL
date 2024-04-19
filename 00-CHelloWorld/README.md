# TP0

## Compilador
Para la resolución del tp, se instaló de manera sencilla [MinGW].
### ¿Qué es MinGW?
> MinGW (Minimalist GNU for Windows), anteriormente conocido como MinGW32, es una implementación de los compiladores GCC para la plataforma Win32, que permite migrar la capacidad de este compilador en entornos Windows. 
 ### 1. Instalar MinGW
Para proceder con la instalación, se debe ejecutar **como administrador** el `.exe` descargado. 

![Imagen](https://imgs.search.brave.com/jtttpYsrzt9FuF4f5WrYYOkDUl1TROsDW70hxaiv3S0/rs:fit:500:0:0/g:ce/aHR0cDovL3d3dy5j/b2RlYmluZC5jb20v/d3AtY29udGVudC91/cGxvYWRzLzIwMTYv/MTIvbWluZ3ctb24t/aW5zdGFsbGF0aW9u/LXNldHVwLWNvbXBs/ZXRlLWNsaWNrLWNv/bnRpbnVlLnBuZw)

Continuar hasta llegar a la pantalla de selección de componentes. Seleccionar
para instalar:
- Mingw32-base
- Mingw32-gcc-g++

![Imagen2](https://imgs.search.brave.com/W3rUn3iZAI1GZVNlWRuphcomk2Fbn9f-mdF5F4qaNFU/rs:fit:500:0:0/g:ce/aHR0cHM6Ly93d3cu/ZmRpLnVjbS5lcy9w/cm9mZXNvci9sdWlz/L2ZwL2RldnRvb2xz/L2NwcC9taW5ndy1p/bnN0YWxsMWIuanBn)

Luego, seleccionar en Installation -> Apply Changes y dejarlo correr hasta que finalice.

### 2. Añadir una Variable de Entorno

Para poder compilar C/C++ desde una terminal, se debe añadir una variable de entorno a Windows (en mi caso).
Esto se pude hacer de manera sencilla siguiendo [este video].

## Instalacion de IDE
Para el proyecto, se utilizara `vscode`, el cual puedes descargar [desde aquí].
Este nos permitirá:
1. Utilziar una terminal interactiva
2. Manejar repositorios de una manera sencilla
3. Codear de manera intuitiva y con la ayuda de distintas herramientas

## Git
No entraré demasiado en detalle sobre la hermosa herramienta que es **git**, pero puedes obtener el método de instalación [aquí].


## Obtener la versión del compilador
Para sabér en que "estándar" de GCC estaremos compilando, bastará con crear un `.c` y copiar esto:
```C
#include <stdio.h>

int main() {
    printf("%ld\n", __STDC_VERSION__);
    return 0;
}
```
Podemos compilar y ejecutar en Windows de esta manera:
```Bash
$ gcc filename.c –o filename
$ filename
```
En mi caso, el estándar a utilizar es;
```Bash
 > 201112
```
Lo que significa que estoy en `C11`.

#### ¡Espero que te haya servido!


[Mingw]: (http://sourceforge.net/projects/mingw/)
[este video]: (https://www.youtube.com/watch?v=GEZLjRSY_m8&t=180s)
[desde aquí]: (https://code.visualstudio.com/download)
[aquí]: (https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)