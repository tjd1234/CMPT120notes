# Algorithms Quiz

Draft! Questions may change, have mistakes, etc.

Assumed to be the last topic in the course.

## Question 1

Which one of the following is NOT a required feature of any algorithm? An
algorithm should:

x be precise enough to be carried out by a computer without any interpretation
x have a finite number of instructions
x solve a particular computational problem
* be the most efficient method for solving a particular computational problem

## Question 2

Suppose you do linear search for the number 5 on a list of n numbers. In the
worst case, how many item comparisons will be made?

x n-1
* n
x n+1
x n/2 if n is even, and (n-1)/2 if n is odd

## Question 3

Which Python list method searches for an item in the list using linear search?

* index
x find
x search
x linear_search

## Question 4

Suppose L is a list of at least 100 numbers, and you want to find a target value
x.

i) To use binary search, L[0] <= x <= L[-1] must be true
ii) To use binary search, L must be sorted in ascending order

x i) and ii) are both true
x i) and ii) are both false
x i) is true, ii) is false
* i) is false, ii) is true

## Question 5

What should ??? be replaced with in the following function so that it correctly
implements binary search?

def binary_search(x, lst):
    """Returns an index i such that list[i] == x.
    If x is not in lst, returns -1.
    lst must be in sorted order, from smallest to biggest.
    """
    lo = 0
    hi = len(lst) - 1
    while lo <= hi:
        ???

        if lst[mid] == x:
            return mid        # x found at location mid
        elif x < lst[mid]:
            hi = mid - 1
        else:                 # lst[mid] < x
            lo = mid + 1
    return -1                 # x not in lst


* mid = (lo + hi) // 2
x mid = (hi - lo) // 2
x mid = hi // 2
x mid = (lo + hi - 1) // 2


## Question 6

In the worst case, about how many item comparisons does binary search do to find
a given target item in a sorted list of n items?

x n
* log (n)
x n log (n)
x n^2


## Question 7

In the worst case, about how many item comparisons does selection sort do to
sort a list of n items?

x n
* log (n)
x n log (n)
x n^2

## Question 8

Suppose it takes selection sort 1 second to sort a list of 1000 items. About how
many seconds would you expect it to take to sort 2000 items?

x 2
* 4
x 8
x 10

## Question 9

In the worst case, about how many item comparisons does mergesort do to sort a
list of n items?

x n
x log (n)
* n log (n)
x n^2

## Question 10

About how many item comparisons would the merge algorithm from mergesort do to
merge a list of m items with a list of n items?

* m + n
x m * n
x (m + n)log(m + n)
x log(m + n)
