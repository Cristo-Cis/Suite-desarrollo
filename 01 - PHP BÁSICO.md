# Inicio del servidor
La introducción a PHP es que tenemos que tener instalado un servidor que se llama **Laragon**, una vez instalado lo tenemos que abrir:
![[Pasted image 20230824154445.png]]
Esta es la interfaz de Laragon. Ya estando en  la interfaz de Laragon lo único que tenemos que hacer es dar clic a "iniciar" y automáticamente se inicia el servidor.
Entramos a https://localhost para ver el index de Laragon.
# Creación de un nuevo proyecto
Para crear un nuevo proyecto lo primero que se hace es crear una carpeta donde se quedaran guardados todos los archivos que se crearán a lo largo del proyecto.
En Laragon lo primero que se hará es dar clic en el botón que dice **"root"** (tiene un ícono de una carpeta) y crear la carpeta ahí:
![[Pasted image 20230824163409.png]]
Mi proyecto se llama **"PHP-BASICO"**, esa carpeta la abriremos en Visual Studio Code.
![[Pasted image 20230824163527.png]]
estando ahí crearé un nuevo archivo llamado **index.php**, ahí escribiremos el siguiente comando para imprimir en pantalla cualquier texto que queramos.
  

`<?php
`print("Hola mundo");
`?>

Se escribe el siguiente código para hacer el clásico "Hola mundo", se mostrará lo siguiente en pantalla:
![[Pasted image 20230824164909.png]]

# Variables y constantes

Una **variable** es un espacio de memoria reservado para almacenar un valor, con el objeto de poder visualizarlo, modificarlo u operar con él cuando se lo necesite durante la ejecución de un programa.
Para definir una variable en php se utiliza el signo $.
![[Pasted image 20230824202423.png]]

Como podemos ver, hay varios tipos de variables, ya sean de cadenas, enteros, booleano, float, etc.
En pantalla, se vera así:
![[Pasted image 20230824204412.png]]

Se ve de esta manera porque lo que necesitamos es hacer un salto de línea.
Para hacer un salto de línea se requiere la siguiente línea de código.
![[Pasted image 20230824204707.png]]

Ya una vez puesta esa línea de código, el resultado se verá así:
![[Pasted image 20230824204818.png]]

# Operaciones aritméticas
Las operaciones aritméticas son: **suma, resta, multiplicación, división, potenciación, división entera**. Los operadores lógicos son: "y", "o", "no" y "o exclusivo".
No tiene mucho que resumir este apartado, ya que en las líneas de código