---
status: en_progreso
---

- ### [[Índice de programación]]
- ### [[Dashboard]]
- ### [[Atajos]]

## #Fundamentos

Define el cuerpo de una página web. 

Proviene de HyperText Markup Language
- **HyperText**: Proviene del texto que puede conectarnos con otro documento dentro de una página web, estas piezas de texto son hiper texto o hiper links. 
- **Markup Language**: Proviene de lo que se ve en la revisión de un manuscrito, solo que se usan diferentes marcas ( #tags ) para definir cada elemento a través de la página web.

La estructura de este código se basa en #tags con contenido que forman [[Elementos]]

Los #tags son las instrucciones o etiquetas que le dicen al navegador como debe mostrar un contenido. Mientras que los [[Elementos]] son el conjunto de tags con contenido inscrito dentro del tag.

Recordamos que los #tags se componen de:
- **Tag de apertura:** `< >`
- **Tag de cierre:** `</>`
- **Excepción**: `<img src="">` aquí los [[Elementos]] son la fuente ( `src=""` ) ya que ese sería el contenido.

---
## [[Elementos]]
## [[Rutas del Archivo]]

---
# Estructura (Boilerplate):

Al igual que las cartas o a diferentes documentos, los archivos HTML para la creación de página tienen una estructura principal y es la siguiente:

```
<!DOCTYPE html>
<html lang="en">

<head>
	<meta charset="UTF-8">
	<title>My website</title>
</head>

<body>
</body>

</html>
```

Vamos a desglosar y definir cada linea:

- `<!DOCTYPE html>`: como lo dice ahí, se le especifica al navegador que tipo de documento es. Esto se usa para decirle al navegador que se está usando HTML 5 (La versión más reciente de HTML). La raíz del archivo.

- `<html lang="en">`: Es la raíz del archivo, todo el contenido está dentro de este elemento, se añade el tipo de lenguaje en el que está escrito el contenido. En este caso inglés, esto ayuda también al lector de pantalla para los discapacitados pronunciar bien el texto generando mejor comprensión al usuario.

- `<head>`: Es la parte invisible de la página web, pero que permite que se muestre el contenido de manera correcta pero no incluye texto, ni imagen que pueda ver el usuario. Dentro del head se pueden adicionar diferentes secciones que permiten la configuración de la página web. 
	- `<meta charset="UTF-8">` : Esta es una etiqueta muy importante dentro del head, indica al navegador cómo interpretar los caracteres de la página para que letras especiales, símbolos y emojis se muestren correctamente. UTF-8 es la codificación estándar utilizada en la web moderna puesto que permite representar todos los caracteres del mundo (letras, símbolos y emojis) usando números que las computadoras pueden entender.
	- `<title> </title>`: Es el título de la pestaña del navegador.
	- 