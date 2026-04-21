---
status: completado
tipo: html
progreso: "100"
---
### [[Índice de programación]]
### [[Dashboard]]
### [[Atajos]]

# 🎯Objetivo:

Entender el uso de anidación y sangría para las listas con [[Elementos]] ordenados y no ordenados.

![[Pasted image 20260421194211.png]]

---
# Tecnologías:

- ## HTML

---
# Ejercicio:

A
B
B1
B2
B2a
B2aa
B2ab
B2b
B2c
B3
B31
B32
C

--- 
# Solución: 

```
<ul>

    <li>A</li>

    <li>

        B

        <ol>

            <li>B1</li>

            <li>

                B2

                <ul>

                    <li>

                        B2a

                        <ul>

                            <li>B2aa</li>

                            <li>B2ab</li>

                        </ul>

                    </li>

                    <li>B2b</li>

                    <li>B2c</li>

                </ul>

            </li>

            <li>

                B3

                <ol>

                    <li>B31</li>

                    <li>B32</li>

                </ol>

            </li>

        </ol>

    </li>

    <li>C</li>

</ul>
```