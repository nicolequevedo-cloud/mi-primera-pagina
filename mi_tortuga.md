## Tarea 2 - Ejercicios de la unidad 1 movimiento de una tortuga 

#Ejercicio 1 y 2
En este paso hicimos y creamos la tortuga para que su dirección fuera hacia abajo con el siguiente codigo:


import turtle
t = turtle.Turtle()   # Crea una tortuga
t.right(90) 
t.forward(100)
turtle.done()  

# Ejercicio 3 
Con el siguiente codigo podemos hacer que la tortuga gire 90 grados hacia la derecha:
 

import turtle
t = turtle.Turtle()
t.forward(90)
t.right(90)          # Gira 90 grados a la derecha
t.forward(60)
turtle.done()

# Ejercicio 4 y 5
en este paso juntamos los anteriores codigos y le ponemos la funcion left (realiza lo que ya esta hecho pero en forma de cadena) para que la tortuga baje en forma de escalerita con los siguientes codigos:


import turtle
t = turtle.Turtle()
t.forward(90)
t.right(90)          # Gira 90 grados a la derecha
t.forward(60)
t.left(90)
t.forward(90)
t.right(90)          # Gira 90 grados a la derecha
t.forward(60)
t.left(90)
t.forward(90)
t.right(90)          # Gira 90 grados a la derecha
t.forward(60)
turtle.done()

### Referencia IA
ChatGPT: https://chat.openai.com

