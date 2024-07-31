# Chapter 4 Quiz

Draft! Questions may change, have mistakes, etc.

## Question 1

Suppose the turtle graphics turtle is pointing straight up (north), and then
turtle.right(100) is called. Select all the commands that could be called next
to make the turtle point straight up again.

x turtle.left(260)
* turtle.left(-260)
x turtle.right(-260)
* turtle.right(260)

## Question 2

Consider this code:

import turtle

for i in range(1, 4):
    turtle.forward(100)
    turtle.right(90)    # line 1

Consider these statements:

i) The code draws a square.
ii) If the 90 in line 1 were changed to 60, then the code would draw a triangle.

x i) and ii) are both true
* i) and ii) are both false
x i) is true, but ii) is false
x ii) is true, but i) is false

## Question 3

Consider this code:

import turtle

def shape(length, reps, angle):
    for i in range(reps):
        turtle.forward(length)
        turtle.right(angle)

i) shape(100, 4, 90) draws a square
ii) shape(100, 10, 360 // 5) draws a 5-pointed star

X i) and ii) are both true
x i) and ii) are both false
x i) is true, but ii) is false
* ii) is true, but i) is false

## Question 4

If we want polygon(n, length) to draw a regular polygon with n sides, what
should replace the ??? ?

def polygon(num_sides, length):
    angle = ???
    for i in range(num_sides):
        turtle.forward(length)
        turtle.right(angle)


* 360 / num_sides
x 360 * num_sides
x num_sides / 360
x num_sides * 360

## Question 5

Suppose the function polygon(n, l) draws a regular polygon with n sides each of
length l. Select all the choices that draw a regular triangle with sides of
length 100.

* polygon(3, 100)
x polygon(100, 3)
* polygon(num_sides=3, length=100)
* polygon(length=100, num_sides=3)

## Question 6

Consider this function:

def flower(length, shape_func):
    for i in range(12):
        shape_func(length)
        turtle.right(30)

For flower(length, f) to draw something, f must be a function that draws
something using turtle graphics. What else must be true of f?

i) f must have exactly 1 parameter
ii) f must be named shape_func

x i) and ii) are both true
x i) and ii) are both false
* i) is true, but ii) is false
x ii) is true, but i) is false

## Question 7

Suppose polygon(n, l) draws a regular polygon with n sides each of length l. If
we want the circle function to draw a circle with a given radius, what should
replace the ??? ?

def circle(radius):
    circumference = 2 * math.pi * radius
    num_sides = 40
    length = ???
    polygon(num_sides, length)

* circumference / num_sides
x circumference * num_sides
x num_sides / circumference
x num_sides * circumference

## Question 8

Consider these statements:

i) It's possible to change the thickness of the turtle's pen.
ii) It's possible to change the color of the turtle's pen.

* i) and ii) are both true
x i) and ii) are both false
x i) is true, but ii) is false
x ii) is true, but i) is false

## Question 9

Consider these statements:

i) A docstring goes after the function header.
ii) A docstring goes before the function body.

* i) and ii) are both true
x i) and ii) are both false
x i) is true, but ii) is false
x ii) is true, but i) is false

## Question 10

How can you see the docstring of a function named f?

* help(f)
x docstring(f)
x print(f.docstring)
x print(f.help)