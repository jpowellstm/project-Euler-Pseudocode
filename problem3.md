## Problem
The prime factors of 13195 are 5, 7, 13 and 29.

What is the largest prime factor of the number 600851475143 ?

## Pseudocode
```
define function 'smallest_prime_factor' with one input 'number'
    initaialise a variable 'max' to the square root of 'number + 1
    cast 'max' into an integer
    if 'number' is bigger than 2
        loop 'i' from 2 to 'max'
            if number is divisible by 'i' return 'i'
    return 'number'

define function 'compute' with no inputs
    initialise variable 'n' to 600851475143
    initalise variable 'p' to 1
    loop until 'p' is equal to 'n'
        let 'p' = smallest_prime_factor('n')
	if 'p' is less than 'n' replace 'n' by 'n' divided by 'p'
	else return 'n'
```
