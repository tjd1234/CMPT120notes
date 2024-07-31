# Chapter 5 Quiz

Draft! Questions may change, have mistakes, etc.

## Question 1

What does this print?

This question is automatically marked. Write exactly what is printed, without
any extra characters.

n = (8 % 6) + (8 % 7) + (9 % 6) + (10 % 6)
print(n)

Answer: 10

## Question 2

What does this print?

print('Shoe' == 'shoe')
print((11 // 3) == (11 / 3))

x True
  True
* False
  False
x True
  False
x False
  True

## Question 3

What does this print?

x = 3
y = 5
z = 7

print(x < y < z)

* True
x False
x nothing: the code has a syntax error

## Question 4

What does this print?

a = 2
b = 5

print(2*a < b or a > b)

* True
x False
x nothing: the code has a syntax error

## Question 5

What does this print?

c = 3
d = 2.1
if c - 1 >= d
    print(c)
print(d)

x 3
  2.1
x 2.1
x 3
* nothing: the code has a syntax error

## Question 6

What does this print?

x = 6

if (x + 1) % 2 == 3:
    print('yellow')
  else:
    print('orange')
print('light')

x yellow
  light

x orange
  light

x light

* nothing: the code has a syntax error


## Question 7

What does this print?

This question is automatically marked. Write exactly what is printed, without
any extra characters. If you think there is an error, then write **error**.

def dd(x):
    if x == 0:
        return x
    elif x < 0:
        return x-1
    else:
        return x+1

print(dd(2) + dd(-2))

Answer: 0

## Question 8

Consider this code, where a and b are ints:

if a == b or a != b:
    print('cow')
elif a < b or a > b:
    print('cat')
else:
    print('dog')

i) there are values of a and b that make the code print 'cat'
ii) there are values of a and b that make the code print 'dog'

x i) and ii) are both true
* i) and ii) are both false
x i) is true and ii) is false
x i) is false and ii) is true

## Question 9

Consider this function:

def word(x, y):
    if x == y:
        print(5)
    else:
        if x < y:
            print(6)
        else:
            print(7)

i) word('a', 'A') prints 5
ii) word('bug', 'chop') prints 6

x i) and ii) are both true
x i) and ii) are both false
x i) is true and ii) is false
* i) is false and ii) is true

## Question 10

Consider this function:

def f(n):
    if n < 5:
        print(n)
    else:
        print(n)
        f(n-1)

If you call f(8), what is the last number printed?

x 3
* 4
x 5
x nothing: the code crashes or runs forever
