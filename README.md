# Colorful-Python
A python which have five colors. Don't suspect your eyes, it's a python certainly.
from turtle import *
penup()
fd(-250)
pendown()
pensize(25)
seth(-40)
for i in range(1,5):
    if i is 1:
        pencolor("red")
    elif i is 2:
        pencolor("orange")
    elif i is 3:
        pencolor("yellow")
    else:
        pencolor("green")
    circle(40,80)
    circle(-40,80)
pencolor("purple")
circle(40,80/2)
fd(40)
circle(16,180)
fd(40*2/3)
