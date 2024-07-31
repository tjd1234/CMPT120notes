# Chapter 9 Quiz

Draft! Questions may change, have mistakes, etc.

## Question 1

All the values on a non-empty Python list must have the same type.

x True
* False

## Question 2

Suppose L is a non-empty list, and consider this code:

L[0] = 'tree'

* this sets the first element of L to 'tree', no matter what was in L[0] before

x this sets the first element of L to 'tree' only if L[0] was originally a
string value; otherwise it will cause an error

x this is always an error because you cannot change the value of an element in a
list

## Question 3

What does this print?

names = ['Alice', 'Bob', 'Charlie']
rest = names[1:]
rest[-1] = 'David'
print(names[-1])

* Charlie
x David
x Bob
x Alice

## Question 4

If len(L) is 5, what is len(L * 4) ?

x 4
x 9
* 20
x nothing: there's an error in the code

## Question 5

Consider these statements:

i) This code prints [3, 5, 6]:
a = [3, 5]
a = a + 6
print(a)

ii) This code prints [3, 5, 6]:
a = [3, 5]
a.append(6)
print(a)

x i) and ii) are both true
x i) and ii) are both false
x i) is true, ii) is false
* i) is false, ii) is true

## Question 6

If L is a non-empty list, which expression always removes its last element?

* L.pop()
x L.pop(len(L))
x L.remove()
x L.remove(len(L))

## Question 7

Which string method could you use to make a comma-separated value string of the
elements of a given list?

* join
x split
x csv
x extend

## Question 8

Suppose a.split() is a valid Python expression, and consider these statements:

i) a must be a string
ii) the entire expression returns a list

* i) and ii) are both true
x i) and ii) are both false
x i) is true, ii) is false
x i) is false, ii) is true

## Question 9

Suppose L is a non-empty list of strings, and consider these statements:

i) this prints the strings of L in alphabetical order
L.sort()
for s in L:
   print(s)

ii) this prints the strings of L in alphabetical order
for s in sorted(L):
   print(s)

* i) and ii) are both true
x i) and ii) are both false
x i) is true, ii) is false
x i) is false, ii) is true

## Question 10

What does this print?

def arrange(lst):
    lst.sort()

a = [4, 6, 1]
arrange(a)
print(a)

* [1, 4, 6]
x [4, 6, 1]
x []
x nothing: there's an error in the code
