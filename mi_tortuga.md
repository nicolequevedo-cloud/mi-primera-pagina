## Tarea 2 - Ejercicios de la unidad 1 movimiento de una tortuga 

#Ejercicio 1 y 2
En este paso hicimos y creamos la tortuga para que su dirección fuera hacia abajo con el siguiente codigo:

import turtle

t = turtle.Turtle()   # Crea una tortuga

t.right(90)           # Gira 90° hacia la derecha (dirección hacia abajo)
t.forward(100)        # Avanza 100 píxeles en esa dirección

turtle.done()         # Mantiene la ventana abierta



# Ejercicio 3 
Con el siguiente codigo podemos hacer que la tortuga gire 90 grados hacia la derecha:



import turtle

t = turtle.Turtle()   # Crea la tortuga

t.forward(90)         # Avanza 90 píxeles hacia la derecha
t.right(90)           # Gira 90° hacia la derecha (ahora mira hacia abajo)
t.forward(60)         # Avanza 60 píxeles hacia abajo

turtle.done()         # Mantiene la ventana abierta


# Ejercicio 4 y 5
en este paso juntamos los anteriores codigos y le ponemos la funcion left (realiza lo que ya esta hecho pero en forma de cadena) para que la tortuga baje en forma de escalerita con los siguientes codigo:


import turtle

t = turtle.Turtle()

t.forward(90)     # 1: Línea hacia la derecha
t.right(90)       
t.forward(60)     # 2: Línea hacia abajo

t.left(90)
t.forward(90)     # 3: Línea hacia la derecha

t.right(90)
t.forward(60)     # 4: Línea hacia abajo

t.left(90)
t.forward(90)     # 5: Línea hacia la derecha

t.right(90)
t.forward(60)     # 6: Línea hacia abajo

turtle.done()
https://github.com/nicolequevedo-cloud/Nicole-Quevedo/blob/main/Captura%20de%20pantalla%202025-11-23%20172010.png



### Referencia IA
ChatGPT: https://chat.openai.com




