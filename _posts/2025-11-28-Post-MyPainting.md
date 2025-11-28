---
layout: posts
title: Test blog post
---

- We wrote some code
- We built our website
- We pushed

# Fatima's First Computer Art Project

[My Painting](../assets/images/MyPainting.jpg "My Painting")

``` python
import turtle
import random


turtle.bgcolor("purple")

def rectangle(l, a, c, x, y, o):
    f = turtle.Turtle()
    f.penup()
    f.setpos(x, y)
    f.pendown()
    f.fillcolor(c)
    f.begin_fill()
    f.fd(l)
    f.left(a)
    f.fd(o)
    f.left(a)
    f.fd(l)
    f.left(a)
    f.fd(o)
    f.end_fill()

turtle.speed(0)
turtle.tracer(0)
turtle.setheading(90)
turtle.speed(0)
turtle.penup()
turtle.pendown()
# turtle.penup()
# turtle.setpos(0, -400)
# turtle.pendown()
rectangle(10000,90, "Saddle brown", -700, -340, 35)

rectangle(10000,90, "sienna4" , -700, -305, 35)
rectangle(10000,90, "sienna" , -700, -270, 35)
rectangle(10000,90, "sienna3" , -700, -235, 35)
rectangle(10000,90, "skyblue4" , -700, 280, 80)
rectangle(10000,90, "skyblue3" , -700, 200, 80)
rectangle(10000,90, "skyblue2" , -700, 120, 80)
rectangle(10000,90, "skyblue1" , -700, 40, 80)
rectangle(10000,90, "skyblue" , -700, -40, 80)
rectangle(10000,90, "light blue1" , -700, -120, 80)
rectangle(10000,90, "light blue1" , -700, -200, 110)

def rain(n):
    for i in range(n):
        x = random.randint(-480, -320)
        y = random.randint(-200,200)
        turtle.pencolor("thistle3")
        turtle.pensize(3)
        turtle.penup()
        turtle.setpos(x, y)
        turtle.pendown()
        turtle.setheading(90)
        turtle.right(25)
        turtle.forward(10)

rain(40)
def bird():

    turtle.pensize(4)
    turtle.pencolor("black")
    turtle.setheading(125)
    turtle.fd(20)
    turtle.backward(20)
    turtle.right(70)
    turtle.fd(20)
turtle.penup()
turtle.setpos(120, 180)
turtle.pendown()
bird()

def bird():

    turtle.pensize(4)
    turtle.pencolor("black")
    turtle.setheading(125)
    turtle.fd(20)
    turtle.backward(30)
    turtle.right(70)
    turtle.fd(30)
turtle.penup()
turtle.setpos(110, 180)
turtle.pendown()
bird()

turtle.penup()
turtle.setpos(130, 180)
turtle.pendown()
bird()

turtle.penup()
turtle.setpos(140, 180)
turtle.pendown()
bird()
turtle.penup()
turtle.setpos(100, 180)
turtle.pendown()
bird()

turtle.penup()
turtle.setpos(80, 150)
turtle.pendown()
bird()
turtle.penup()
turtle.setpos(90, 150)
turtle.pendown()
bird()
turtle.penup()
turtle.setpos(100, 150)
turtle.pendown()
bird()
turtle.penup()
turtle.setpos(110, 150)
turtle.pendown()
bird()

turtle.penup()
turtle.setpos(60, 120)
turtle.pendown()
bird()

turtle.penup()
turtle.setpos(70, 120)
turtle.pendown()
bird()
turtle.penup()
turtle.setpos(80, 120)
turtle.pendown()
bird()

turtle.penup()
turtle.setpos(90, 120)
turtle.pendown()
bird()

turtle.penup()
turtle.setpos(40, 90)
turtle.pendown()
bird()

turtle.penup()
turtle.setpos(50, 90)
turtle.pendown()
bird()

turtle.penup()
turtle.setpos(60, 90)
turtle.pendown()
bird()

turtle.penup()
turtle.setpos(70, 90)
turtle.pendown()
bird()
def Tree(l, a, s):
    if l > 10:
        t = turtle
        t.pensize(s+2)
        t.pencolor("brown")
        t.fd(l)
        t.left(a)
        Tree(0.8 *l, a, s)
        t.right(2 * a)
        Tree(0.8 * l, a, s)
        t.left(a)
        t.backward(l)
    elif l <= 10:
        turtle.pencolor("red")
        turtle.dot(8)
        turtle.pensize(s-5)
turtle.tracer(0)
turtle.setheading(90)
turtle.speed(0)
turtle.penup()
turtle.setpos(-350, -240)
turtle.pendown()

Tree(100, 25, 5)




def tree(l, a, s):
    if l > 10:
        t = turtle
        t.pensize(s+2)
        t.pencolor("brown")
        t.fd(l)
        t.left(a)
        tree(0.8 *l, a, s)
        t.right(2 * a)
        tree(0.8 * l, a, s)
        t.left(a)
        t.backward(l)
    elif l <= 10:
        turtle.pencolor("pink")
        turtle.dot(8)
        turtle.pensize(s-5)

turtle.setheading(90)
turtle.speed(0)
turtle.penup()
turtle.setpos(-500, -240)
turtle.pendown()
tree(50, 30, 6)

turtle.penup()
turtle.setpos(-200, -240)
turtle.pendown()
tree(50, 30, 6)


def sun(r):
    turtle.pencolor("dark goldenrod2")
    turtle.dot(r)
turtle.setheading(90)
turtle.speed(0)
turtle.penup()
turtle.setpos(0,300)
turtle.pendown()
sun(100)

def cloud(r, x, y,c):
    w = turtle.Turtle()
    w.pencolor(c)
    w.penup()
    w.setpos(x, y)
    w.pendown()
    w.dot(r)



cloud(90, -50, 280, "white")
cloud(90, -90, 300, "white")
cloud(90, -130, 280, "white")
cloud(90, 50, 280, "white")
cloud(90, 90, 300, "white")
cloud(90, 130, 280, "white")
cloud(100, 400, 300, "snow3")
cloud(100, 360, 300, "snow3")
cloud(100, 440, 300, "snow3")
cloud(100, 320, 290, "snow3")
cloud(100, 480, 290, "snow3")

cloud(100, -480, 290, "snow3")
cloud(100, -320, 290, "snow3")
cloud(100, -440, 300, "snow3")
cloud(100, -360 , 300, "snow3")
cloud(100, -400, 300, "snow3")

def rain(n):
    for i in range(n):
        x = random.randint(320, 480)
        y = random.randint(-200,200)
        turtle.pencolor("thistle3")
        turtle.pensize(3)
        turtle.penup()
        turtle.setpos(x, y)
        turtle.pendown()
        turtle.setheading(90)
        turtle.right(25)
        turtle.forward(10)

rain(80)


t = turtle.Turtle()
fall_colors = ["#FF7F00", "#FF4500", "#FFB000", "#D2691E", "#B22222", "#F4A460"]

def draw_leaf(size=30, color="orange"):
    t.color(color)
    t.begin_fill()

    t.left(45)
    t.circle(size//3, 90)
    t.circle(size//4, 90)
    t.right(90)
    t.circle(size//4, 90)
    t.circle(size//3, 90)
    t.left(45)

    t.end_fill()

for _ in range(60):
    t.penup()


    x = random.randint(-600, 600)   
    y = random.randint(-340, -250)    
    
    t.goto(x, y)

    t.setheading(random.randint(0, 360))

    t.pendown()

    color = random.choice(fall_colors)

    draw_leaf(random.randint(25, 40), color)
def bird():
    turtle.setheading(45)
    turtle.fd(20)
    turtle.backward(20)
    turtle.right(70)
    turtle.fd(20)




turtle.mainloop()

      

```
