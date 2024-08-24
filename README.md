# Descripción del proyecto

Este proyecto es una sencilla herramienta diseñada para descifrar una contraseña hash utilizando el algoritmo SHA-256. Se basa en la técnica de fuerza bruta a través de un diccionario de posibles contraseñas.

## ¿Cómo funciona?

La herramienta toma un archivo de texto que actúa como diccionario, el cual contiene una lista de contraseñas posibles. Para cada contraseña, se calcula su hash utilizando el algoritmo SHA-256 y se compara con el hash objetivo. Si se encuentra una coincidencia, se imprime la contraseña original.

## ¿Qué es un hash?

Un hash es una representación única de un dato o archivo a través de una secuencia alfanumérica de longitud fija. En este caso, el hash es generado por SHA-256, un algoritmo criptográfico ampliamente utilizado para proteger contraseñas y otros datos sensibles.

## Uso

Coloca el hash que deseas descifrar en el código.
Prepara un archivo de texto que funcione como diccionario, con una lista de contraseñas, una por línea.
Ejecuta el programa e ingresa la dirección del archivo del diccionario cuando te lo solicite.
Si la contraseña está en el diccionario, ¡el programa te la revelará!

## Requisitos

Python 3.x 

Un archivo de texto con posibles contraseñas

## Notas

Esta herramienta es educativa y no debe ser utilizada con fines malintencionados. Está diseñada para demostrar cómo funciona el proceso de descifrado de contraseñas basadas en hashes y la importancia de utilizar contraseñas robustas.
