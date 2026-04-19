---
status: en_progreso
---
- ### [[Índice de programación]]
- ### [[Dashboard]]
- ### [[Atajos]]

# Fundamentos

## Elementos de encabezado

Representan la jerarquía de los títulos en una página web y van desde `<h1>` hasta `<h6>`, donde `<h1>` es el nivel más alto y `<h6>` el más bajo.

#Estructura:

	`<h1>Soy un título de nivel 1</h1>`

![[Pasted image 20260414015201.png]]

#Recomendaciones:
- No usar más de una vez `<h1>`, ya que es el título principal de la página web.
- No saltar la jerarquía (por ejemplo, de `<h1>` a `<h3>` sin usar `<h2>`).

## Ejercicio desarrollado

### [[Heading Elements]]

---

## Elemento de párrafo

- Al igual que los #Elementos de encabezado, tiene etiquetas de apertura y cierre. Se utiliza para indicar al navegador que muestre el contenido como un párrafo. Esto es importante semánticamente, especialmente para usuarios que utilizan lectores de pantalla, ya que ayuda a entender el flujo del contenido.

#Estructura:

`<p>Soy un párrafo</p>`

![[Pasted image 20260414191401.png]]

```
<p>
To see a World in a Grain of Sand<br />
And a Heaven in a Wild Flower,<br />
Hold Infinity in the palm of your hand<br />
And Eternity in an hour.<br />
</p>
```


## Ejercicio desarrollado

### [[Paragraph Elements]]

---

## Elementos nulos

Existen #Elementos como `<img>` que son una excepción, ya que no contienen contenido interno. Otros #Elementos donde está prohibido colocar contenido son `<hr />` y `<br />`.

- ### `<hr />` : Línea horizontal

	Este elemento se usa para crear una línea horizontal que separa secciones de contenido.
	
	#Estructura :
```
	<p>Sección 1</p>
	<hr /> 
	<p>Sección 2</p>
```

- ### `<br />`: Elemento de quiebre

	Este elemento se utiliza cuando quieres separar las líneas dentro de un parágrafo para uso semántico o estructural.
	
	#Estructura :
	
```
<p>
To see a World in a Grain of Sand<br />
And a Heaven in a Wild Flower,<br />
Hold Infinity in the palm od your hand<br />
And Eternity in an hour.<br />
</p>
```

- #Recomendaciones: - No usar el `<br />` para separar párrafos cuando no es necesario, y que esto hace que los lectores de pantalla para ciegos entren en conflicto y pierdan el sentido del contenido. Es mejor crear varios [[Elementos]] `<p>` - Tanto para el `<br />` y el `<hr />` se recomienda tener siempre el `/` para ayudar visualmente al cerebro de que es un elemento nulo.

---

## Elementos de lista

Como su nombre lo indica, estos elementos se usan para enlistar [[Elementos]] y se pueden hacer de 2 formas, Lista no ordenada y Lista ordenada.

#Estructura : Para las listas la estructura va acompañada de este elemento `<li>` para adicionar los [[Elementos]] dentro de la lista.

 - ### Lista no ordenada: 
	 Se usan para enlistar [[Elementos]] que no requieren una jerarquía como por ejemplo una lista de productos para hacer el mercado. 
	 
	 #Estructura
```
	 <ul>
		 <li>Leche</li>
		 <li>Pan</li>
		 <li>Huevos</li>
	 </ul>
```

- ### Lista ordenada