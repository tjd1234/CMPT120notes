# Chapter 10 Quiz

Draft! Questions may change, have mistakes, etc.

## Question 1

Which one of these is a dictionary?

* {'cat': 1, 'dog': 2, 'bird': 3}
x [['cat', 1], ['dog', 2], ['bird', 3]]
x [('cat', 1), ('dog', 2), ('bird', 3)]
x {['cat', 1], ['dog', 2], ['bird', 3]}

## Question 2

Consider these statements:

i) The keys of a dictionary must be unique.
ii) The values of a dictionary must be unique.

x i) and ii) are both true
x i) and ii) are both false
* i) is true, ii) is false
x i) is false, ii) is true

## Question 3

If k is not a key in dictionary d, what happens when you call d[k]?

* a KeyError exception is raised
x None is returned
x 0 is returned
x False is returned

## Question 4

Consider these statements about dictionaries:

i) Given a key, finding the associated value is very fast.
ii) Given a value, finding the associated key is very fast.

x i) and ii) are both true
x i) and ii) are both false
* i) is true, ii) is false
x i) is false, ii) is true

## Question 5

Consider these statements about a dictionary d:

i) d.keys() returns all the keys in d
ii) d.values() returns all the values in d

* i) and ii) are both true
x i) and ii) are both false
x i) is true, ii) is false
x i) is false, ii) is true

## Question 6

Consider these statements about a dictionary d:

i) the expression x in d returns True if x is a value in d, and False otherwise

ii) if k is a key in d, then d[k] is a value in d

x i) and ii) are both true
x i) and ii) are both false
x i) is true, ii) is false
* i) is false, ii) is true

## Question 7

What is the name of the general technique dictionaries use to quickly find a
value given a key?

* hashing
x indexing
x searching
x mapping

## Question 8

What does this print?

d = {'cat': 1, 'dog': 2, 'bird': 3}
d['dog'] = 4
print(d['dog'])

* 4
x [2, 4]
x nothing: an error occurs when 4 is assigned


## Question 9

Given a dictionary d with integer values, this function returns the sum of the
values:

def sum_vals(d):
    total = 0
    for val in d:
        total += val
    return total

x true
* false

## Question 10

Suppose d1 and d2 are dictionaries, where the keys and values of each are
strings.

The following function returns True if d1 and d2 both have exactly the same
key:value pairs, and False otherwise:

def same_pairs_in_both(d1, d2):
    for key in d1:
        if not (key in d2 and d1[key] == d2[key]):
            return False
    return True

x true
* false
