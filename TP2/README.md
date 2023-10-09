# TDA-I-Fiuba
Trabajo práctico 1 Programación Dinámica. Teoría de Algoritmos I - curso Buchwald

# Integrantes
- Tobías Serpa
- Carolina Mauro
- Valentina Adelsflugel

# Instrucciones para correr el TP
Las soluciones fueron implementadas en Python utilizando una notebook para que sea más fácil de leer y explicar
cada paso.

A continuación dejamos la manera de ejecutar el trabajo:


Desde Visual Studio Code. Abrir el repositorio. Al querer ejecutar las celdas, se solicitará tener instalado un kernel de Python, de no tener ninguno, seguir los pasos que sugiere VSCode y hacer click en el botón de `install` de la ventana emergente que nos muestra. Si no se posee el gestor de paquetes `pip`, deberá ser previamente instalado, por ejemplo para Ubuntu: `sudo apt-get install python3-pip`.

# Instrucciones para realizar una prueba con un set propio

En el final del archivo, implementamos una porción de cógido en la cual un usuario puede testear nuestra solución, con un set propio. Algunos detalles a tener en cuenta:

0 - Correr todas las celdas previas antes para que estén definidas.

1 - El set debe cumplir con el formato esperado:
En la primera línea el valor de la cantidad de días a considerar (n)
En las siguientes n líneas, las ganancias de dichos días (e_i).
En las siguientes n líneas, la energía con la que se cuenta al día 1, 2, 3, ..., n de estar entrenando sin haber descansando previamente (s_i).

Ejemplo:
3 
5
15
6 
20
15
5

2 - Es necesario cambiar el path en la variable path customizado. Hecho esto ya es posible ejecutar el código.

3 - Esta porción de código devolverá al usuario el mejor plan de entrenamiento, es decir, el plan que brinda la ganancia máxima.
