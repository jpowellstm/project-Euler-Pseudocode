## Problem 
If we list all the natural numbers below 10 that are multiples of 3 or 5, we get 3, 5, 6 and 9. The sum of these multiples is 23.

Find the sum of all the multiples of 3 or 5 below 1000.


## Psuedocode
```
define function 'compute' with no inputs 
    initialise variable 'sum' to zero
    
    loop 'number' from 1 to 10000
        if 'number' is divisible by 3 or 5 add 'number' to 'sum'    
    
    return 'sum' from function

call function 'compute' and print it
```
