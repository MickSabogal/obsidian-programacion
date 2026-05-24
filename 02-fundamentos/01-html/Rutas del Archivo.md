---
status: completado
---
- ### [[Índice de programación]]
- ### [[Dashboard]]
- ### [[Atajos]]

# #Fundamentos:

Las rutas de archivo son como una ubicación única para el archivo o carpeta dentro del ordenador, entonces lo que se hace con la maquina es básicamente lo mismo que se hace con una persona al darle una instrucción para que encuentre un lugar en especifico.

Existen dos tipos de ruta:

- ### #Absoluta:
	- Puede ser la más sencilla, puesto que esta es la dirección completa de un archivo por lo cual siempre inicia desde la raíz.
	-  `C:\Users\Juan\Documents\foto.png`
- ### #Relativa:
	- Para el desarrollo web, esta es más usada porque es una ubicación basada en la ubicación actual. En programación se busca relativo al archivo o a la carpeta actual.
	- Una de las ventajas es que no importa si se mueven las carpetas, siempre serán válidas.
	- Para poder navegar de una manera más rápida y simplificadamente se utilizan los siguientes caracteres.
 >[!CARACTERES]
>`..`: significa **Subir una carpeta**. Básicamente es salir de la carpeta donde te encuentras y al añadir `/` entras en la otra que buscas.

 - Ejemplo:
``` project/
			│
			├── index.html
			├── css/
			│   └── style.css
			└── images/
		    └── logo.png
```
- En este caso, si nos encontramos en `style.css` y quieres acceder a `images/logo.png` se haría de la siguiente manera:
			-`../images/logo.png`
		- Salimos de `css` y luego se añade el lugar donde queremos ir, en este caso `images/logo.png`
 >[!CARACTERES]
>`.` representa la **carpeta actual** y se usa para indicar que un archivo o carpeta está en el mismo directorio desde donde se está trabajando.

