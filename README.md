# TDA-I-Fiuba
Repositorio para los trabajos prácticos de la materia Teoría de Algoritmos I - curso Buchwald

# Integrantes
- Tobías Serpa
- Carolina Mauro
- Valentina Adelsflugel

# Instrucciones para correr el TP
Las soluciones fueron implementadas en Python utilizando una notebook para que sea más fácil de leer y explicar
cada paso.

A continuación dejamos dos maneras de ejecutar el trabajo:

1 - Con Google Colaboratory. Para eso, disponibilizamos un [Google Drive](https://drive.google.com/drive/folders/1wRNXcW8VwG5C0YxKx8YDU4X0FBCjrc9p?usp=sharing) con todo el ambiente ya configurado para que lo puedan correr. 

2 - Desde Visual Studio Code. Abrir el repositorio. Al querer ejecutar las celdas, se solicitará tener instalado un kernel de Python, de no tener ninguno, seguir los pasos que sugiere VSCode y hacer click en el botón de `install` de la ventana emergente que nos muestra. Si no se posee el gestor de paquetes `pip`, deberá ser previamente instalado, por ejemplo para Ubuntu: `sudo apt-get install python3-pip`.

Nosotros a lo largo del TP utilizamos la alternativa 2 dado que se ejecuta más rápido.

# Instrucciones para realizar una prueba con un set propio

En el final del archivo, implementamos una porción de cógido en la cual un usuario puede testear nuestra solución, con un set propio. Algunos detalles a tener en cuenta:

0 - Correr todas las celdas previas antes para que estén definidas.

1 - El set debe cumplir con el formato esperado:
    | S_i,A_i |
| ------- |
|   1,2   |
|   3,6   |




2 - Es necesario cambiar el path en la variable path customizado. Hecho esto ya es posible ejecutar el código.

3 - Esta porción de código devolverá al usuario el menor tiempo posible en el que es posible analizar su set de vídeos.
