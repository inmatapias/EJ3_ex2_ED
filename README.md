# EJ3_ex2_ED
- Sincroniza tu directorio del ejercicio anterior con un repositorio sin inicializar de GitHub llamado EJ3_ex_ED_2022.

Lo haremos mediante el siguiente comando (clonando el repositorio): git clone https://github.com/inmatapias/EJ2_ex2_ED/edit/main/README.md

- Crear una nueva rama “refactorizacion” y mostrar las ramas del repositorio.

Crearemos la nueva rama a través del siguiente comando: git branch refactorizacion.
Mostraremos las ramas del repositorio mediante el siguiente comando: git -a.

- Crear el fichero refactorizacion.txt y añadir el texto siguiente.

Lo haremos a través del siguiente comando: echo "Refactoring is a systematic process of improving code without creating new functionality that can transform a mess into clean code and simple design."

- Añadir los cambios a la zona de intercambio temporal.

Usaremos el comando: git add.

- Hacer un commit con el mensaje “Añadido concepto de refactorizacion”.

Lo haremos empleando el siguiente comando: git commit -m "Añadido de refactorizacion".

- Mostrar la historia del repositorio incluyendo todas las ramas.

Usaremos el siguiente comando: git log -b

- Crear la rama “patrones”.

git branch patrones

- Crear el fichero patrones.txt y añadir la siguiente referencia

echo "Los patrones de diseño (design patterns) son soluciones habituales a problemas comunes en el diseño de software." >  patrones.txt

- Añadir los cambios a la zona de intercambio temporal.

git add

- Hacer un commit con el mensaje “Añadida primera definición de patrones de diseño”

git commit -m "Añadida primera definición de patrones de diseño”

- Mostrar la historia del repositorio incluyendo todas las ramas.

git log -b

- Fusionar la rama patrones con la rama master.

git merge patrones

- Mostrar la historia del repositorio incluyendo todas las ramas.

git log -b

- Eliminar la rama patrones.




