# Chapter 8 Quiz

Draft! Questions may change, have mistakes, etc.

## Question 1

How many of these are Python string literals?

"Hello, World!"
'Goodbye, Mars!'
"""See you soon, Venus!"""

x 0
x 1
x 2
* 3

## Question 2

What can ??? be replaced with so that 'e' is printed?

s = 'bottle'
print(???)

* s[5]
x s[6]
x s(5)
x s(6)

## Question 3

If s is a non-empty string, what does this print?

print(s[len(s)])

x the last character of s
x the second to last character of s
x whatever character happens to be in memory after the last character of s
* nothing: the code causes an IndexError

## Question 4

What does this print?

s = 'candy'
print(s[-len(s)] + s[-1])

* cy
x ay
x cd
x ad
x nothing: the code has an error

## Question 5

If s is a string, and s[m:n] is a valid non-empty slice of s, which characters
of s make up s[m:n] ? Assume both m and n are ints that are 0 or greater.

* s[m], s[m+1], ..., s[n-1]
x s[m], s[m+1], ..., s[n]
x s[m+1], s[m+1], ..., s[n-1]
x s[m+1], s[m+1], ..., s[n]

## Question 6

What does this print?

s = 'truck' * 20
print(len(s[70:80]))

x 9
* 10
x 11
x nothing: the code has an error

## Question 7

Which statement is true of Python strings?

x You can extend them by adding characters to their right end.
x You can shorten them by removing characters from their right end.
* You can't change their length or the characters in them.
x You can change characters in them, but you can't change its length.

## Question 8

Consider these statements:

i) A benefit of string immutability is that copying a string does not require
copying all the characters.
ii) A disadvantage of string immutability is that accessing the first character
is slower that if the string were mutable.

x i) and ii) are both true
x i) and ii) are both false
* i) is true, ii) is false
x i) is false, ii) is true

## Question 9

Consider these statements:

i) This statement opens the file data.txt for writing:
f = open('data.txt', 'w')

i) This statement opens the file data.txt for writing:
f = open('data.txt')

x i) and ii) are both true
x i) and ii) are both false
* i) is true, ii) is false
x i) is false, ii) is true

## Question 10

Suppose the file data.txt already exists. What happens if you open it for
writing using the statement:

f = open('data.txt', 'w')

* the file is opened for writing, and its contents are erased
x an error occurs because the file already exists
x the file is opened for writing, and the new data is appended to the end of the
file
