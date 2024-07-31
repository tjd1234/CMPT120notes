# Chapter 6 Quiz

Draft! Questions may change, have mistakes, etc.

## Question 1

What does this print?

def middle(n):
    print(f'x = {n}')
    return n - 1
    print(f'n = {n}')

m = middle(5)
print(f'm = {m}')

* n = 5
  m = 4
x n = 5
  n = 5
  m = 4
x n = 5
  n = 4
  m = 4
x nothing: the program has an error  

## Question 2

What does this print?

def hello():
    print('hello')

x = hello()
print(x)

* hello
  None
x hello
x None
x it prints hello, and then crashes

## Question 3

How many paths of execution are there through this code?

def number_sign(x):
    if x < 0:
        return 'negative'
    elif x == 0:
        return 'zero'
    else:
        return 'positive'

x 0
x 1
x 2
* 3

## Question 4

What is dead code? Code that:

* can never be executed
x is guaranteed to cause an error if it is executed
x has been executed once and will never be executed again
x is executed only when the program crashes

## Question 5

Suppose the only possible values that function f(x) returns are either True or
False.

Which statement is true?

* f is definitely a boolean function
x f is definitely not a boolean function
x f may be a boolean function, depending on the type of x

## Question 6

Consider these functions:

def f1(s, t):
    if len(s) < len(t):
        return False
    else:
        return True
    
def f2(s, t):
    return len(s) >= len(t)

Consider these statements:

i) f1 and f2 are both boolean functions
ii) f1 and f2 are equivalent, i.e. they always return the same results for the
same input

x i) and ii) are both true
x i) and ii) are both false
* i) is true, ii) is false
x i) is false, ii) is true

## Question 7

Consider this recurrence relation:

T(0) = 1
T(n) = 2 * T(n - 1), for n > 0

What is T(5)?

x 2
x 4
* 8
x 16

## Question 8

What does this print?

def g(n):
    if n == 0:
        return 2
    else:
        return n + g(n - 1)

print(g(3))

x 3
x 5
x 6
* 8


## Question 9

This function calculates the nth Fibonacci number:

def fib(n):
    if n == 0:
        return 0
    elif n == 1:
        return 1
    else:
        return fib(n - 1) + fib(n - 2)

Consider these statements:

i) fib(-1) returns -1
ii) fib(n) is remarkably efficient for large values of n

x i) and ii) are both true
* i) and ii) are both false
x i) is true, ii) is false
x i) is false, ii) is true


## Question 10

What does this print?

def fib_mod(n):
    if n == 0:
        return 0
    elif n == 1:
        return 1
    else:
        # this next line is different than the usual Fibonacci function
        return 1 + fib_mod(n - 1) + fib_mod(n - 2)

print(fib_mod(3))

x 2
* 4
x 7
x 12