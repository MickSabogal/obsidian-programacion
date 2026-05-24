---
status: en_progreso
---

- ### [[Índice de programación]]
- ### [[Dashboard]]
- ### [[Atajos]]

## #Fundamentos

Define el cuerpo de una página web. 

Proviene de HyperText Markup Language
-  **HyperText**: Proviene del texto que puede conectarnos con otro documento dentro de una página web, estas piezas de texto son hiper texto o hiper links. 
- **Markup Language**: Proviene de lo que se ve en la revisión de un manuscrito, solo que se usan diferentes marcas ( #tags ) para definir cada elemento a través de la página web.

La estructura de este código se basa en #tags con contenido que forman [[Elementos]]

Los #tags son las instrucciones o etiquetas que le dicen al navegador como debe mostrar un contenido. Mientras que los [[Elementos]] son el conjunto de tags con contenido inscrito dentro del tag.

Recordamos que los #tags se componen de:
- **Tag de apertura:** `< >`
- **Tag de cierre:** `</>`
- **Excepción**: `<img src="">` aquí los [[Elementos]] son la fuente ( `src=""` ) ya que ese sería el contenido.

---
## [[Elementos]]

---
## #RutasDeArchivo

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
