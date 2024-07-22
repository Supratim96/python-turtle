#importing turtle
from turtle import*

#basic setup
title('Olympic symbol')
bgcolor('white')
pencolor('black')
pensize(5)

#center black circle
circle(80)

#setting the position for the pen
penup()
setposition(-200,0)
pendown()

#left blue circle
pencolor('blue')
circle(80)

#setting the position for the pen
penup()
setposition(200,0)
pendown()

#coding the red circle
pencolor('red')
circle(80)

#setting the position for the pen
penup()
setposition(-100,-100)
pendown()

#coding the yellow circle
pencolor('yellow')
circle(80)

#setting the position for the pen
penup()
setposition(100,-100)
pendown()

#coding the green circle
pencolor('green')
circle(80)

hideturtle()
done()
