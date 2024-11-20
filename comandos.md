## Ejercicio 3

### Paso 1

Crear un repositorio nuevo con el nombre libro y mostrar su contenido. Comprueba el estado del respositorio.

Primero al no tener vinculado el repositorio con GitHub
(Dentro de la carpeta ""libro")

    git config user.name "sergiofr13"
    git config user.email "sergio.ferreiro.ramos@gmail.com"

(Dentro de la carpeta creada "libro")

    git init

Para mostrar contenido:

    ls

Comprobar estado

    git status


### Paso 2

Crear un fichero indice.txt con el siguiente contenido:

    touch indice.txt
    nano indice.txt

(Agregamos el contenido)


### Paso 3

Realizar un commit con el mensaje “Añadido índice del libro”.

    git status

    git add comandos.md
    git add indice.txt

    git commit -m "Añadido indice del libro"



### Paso 4

Comprueba y explica el estado del repositorio.


    git status

Ahora al haber hecho el commit, no hay cambios nuevos.


### Paso 5

Cambiar el índice.txt para que contenga lo siguiente:

    nano indice.txt

Hacemos los cambios


### Paso 6

Hacer un commit de los cambios con el mensaje “Añadido 4: La bella y la bestia”. Comprueba el estado del repositorio.


    git status

    git add comandos.md
    git add indice.txt

    git commit -m "Añadido 4: La bella y la bestia"

    git status


### Paso 7

Muestra el historial del repositorio.

    git log


### Paso 8


Crea la carpeta capítulos y dentro de ella el fichero capitulo2.txt con el siguiente texto:


    mkdir capitulos
    cd capitulos
    touch capitulo2.txt
    nano capitulo2.txt

(Dentro metemos o texto)


### Paso 9

Hacer un commit con el mensaje “Añadido capitulo 2”

    git status

    git add capitulos/
    git add comandos.md

    git commit -m "Añadido capitulo 2"


### Paso 10

Volver a mostrar el historial de cambios.

    git log


### Paso 11

Crear el fichero capitulo3.txt en la carpeta capitulos con el siguiente texto:

    cd capitulos
    touch capitulo3.txt
    nano capitulo3.txt

(Metemos o texto)


### Paso 12

Ver el estado del repositorio de forma abreviada e indicar qué significa cada letra.

    git status -s

"M" Significa modificado (modificado en el índice o área de trabajo)
"A" Significa agregado (se añadio al área de preapración)
"??" Significa No rastreado (el archivo no está siendo siendo seguido por git)


### Paso 13

Modificar el índice.txt añadiendo “Capitulo 5: Forzen””

    nano indice.txt

(Añadimos el texto)


### Paso 14

Subir los cambios al repositorio ingorando el capitulo3.txt


.gitignore