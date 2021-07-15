## Problem 4
A palindromic number reads the same both ways. The largest palindrome made from the product of two 2-digit numbers is 9009 = 91 × 99.

Find the largest palindrome made from the product of two 3-digit numbers.

## Pseudocode
```
define function 'compute' with no inputs
    initialise a variable 'ans' to be 0
    loop 'i' from 100 to 1000
        loop 'j' from 100 to 1000
           initialise a variable 'prod' to 'i' times 'j'
           cast prod to a string
           reverse the string
           if the string is equal to the reverse of the string and 'prod' is greater than 'ans' then let 'ans' = 'prod'
    return 'ans'

call the function 'compute' and print it     
```

## Solution
```
def compute():
    ans = 0
    for i in range(100, 1000)
        for j in range(100, 1000)
            if str(i * j) == str(i * j)[ : : -1]) and i*j > ans:
                ans = i*j
	
     return ans
```
