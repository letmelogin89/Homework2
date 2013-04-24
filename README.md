Homework3 part 1
=========
HW3. Part1 :I forked the HW2(prime_fac(num)) by declaring %cython and declaring the type of objects(ex: int)

When I timed my original python code and cython code, it made a significant difference. It ran way faster in cython.

ex) 
%timeit prime_fac(12131988)
result: 5 loops, best of 3: 564 ms per loop

%timeit prime_fac_c(12131988)
result: 25 loops, best of 3: 13.7 ms per loop



Homework2
=========

Takes a number greater than 1 and finds the prime factors.

Examples: 

prime_fac(any number greater than 1)


prime_fac(200)

will give you [2,2,2,5,5]
