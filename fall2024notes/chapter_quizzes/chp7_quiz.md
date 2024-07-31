# Chapter 7 Quiz

Draft! Questions may change, have mistakes, etc.

## Question 1

What does this print?

for letter in "tree":
    print(letter, end='!')

* t!r!e!e!
x t!
  r!
  e!
  e!
x tree!
x t
  r
  e
  e
  !

## Question 2

How many of these 3 functions correctly return True if the passed-in word has an
x or X, and False if it does not?

def has_x1(word):
    for letter in word:
        if letter == 'x' or letter == 'X':
            return True
    
    return False

def has_x2(word):
    return 'x' in word or 'X' in word

def has_x3(word):
    for letter in word:
        if letter in 'xX':
            return True
    return False

x 0
x 1
x 2
* 3


## Question 3

How do you open a file so that it can be read line-by-line?

* file_object = open('filename.txt')
x file_object = read('filename.txt')
x import io
  file_object = io.open('filename.txt')
x import io
  file_object = io.read('filename.txt')


## Question 4

Consider this code, where data.txt is a non-empty text file:

file_object = open('data.txt')

How do you print the first line of data.txt?

* print(file_object.readline())
x print(file_object.read())
x print(file_object.readline(0))
x print(file_object.readline(1))

## Question 5

Consider this code, where data.txt is a non-empty text file:

file_object = open('data.txt')

???

Which one of these code fragments can replace ??? so that the entire contents of
data.txt are printed without any extra blank lines?

* for line in file_object:
     print(line.strip())
x for line in file_object.read():
     print(line.strip())
x for line in file_object:
     print(line)
x for line in file_object.read():
     print(line)

## Question 6

This code prints the number of lines in the non-empty text file data.txt:

file_object = open('words.txt')

for line in file_object:
    line_count += 1
print(line_count)

x true
* false

## Question 7

Which one of these is an incorrect way to increment the accumulator n by 1 in
Python?

x n = n + 1
x n -= -1
x n += 1
* n++

## Question 8

Consider these two functions:

def count_vowels1(s):
    count = 0
    for letter in s:
        if letter in 'aeiou':
            count += 1
    return count

def count_vowels2(s):
    count = 0
    for vowel in 'aeiou':
        if vowel in s:
            count += 1
    return count

Suppose we want to count the number of characters in a string that are lowercase
vowels (a, e, i, o, or u). For example, 'keepsake' has 4 vowels.

i) count_vowels1(s) returns the correct count of lowercase vowels for all strings s
ii) count_vowels2(s) returns the correct count of lowercase vowels for all strings s

x i) and ii) are both true
x i) and ii) are both false
* i) is true, ii) is false
x i) is false, ii) is true

## Question 9

Which statement prints string s without any leading or trailing whitespace
characters?

* print(s.strip())
x print(s, begin='', end='')
x print(s.remove(' \n'))

## Question 10

Consider this code:

file_object = open('data.txt')

How can you explicitly close `data.txt`?

* file_object.close()
x close(file_object)
x close('data.txt')
x file_object = close('data.txt')
