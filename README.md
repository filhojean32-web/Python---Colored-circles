That code is a python code to make mono a color background,multi color circles that a pen just get drawning one after another. You can change circles sizes,background color,add more colors,change the size of the pen and any other variations you want. Have fun!

https://pastebin.com/RT7UVcGd

import turtle

t = turtle.Turtle()
s = turtle.Screen()
s.bgcolor("green")

colors = ['white', 'red', 'blue', 'yellow', 'black','orange']

for i in range(400):
    
    t.color(colors[i % len(colors)])
    t.circle(130)
    t.left(78)
    t.right(80)
    t.forward(45)
    t.backward(68)
    
turtle.done()


    