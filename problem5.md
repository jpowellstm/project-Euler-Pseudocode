## Problem
2520 is the smallest number that can be divided by each of the numbers from 1 to 10 without any remainder.

What is the smallest positive number that is evenly divisible by all of the numbers from 1 to 20?

## Pseudocode
```
import the python 'fractions' library
define the function 'compute' with no inputs
    initialise the variable 'ans' to be 1
    loop i from 1 to 21
        call the gcd method from the fractions library with inputs 'i' and 'ans'
        initialise this to a variable 'gcd'
        let 'ans' be 'ans' times 'gcd'
    retunr 'ans'

call the function compute and print it
```
