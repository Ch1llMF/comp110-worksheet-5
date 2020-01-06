# comp110-worksheet-5
Base repository for COMP110 worksheet 5

a) The algorith searches through the list ensuring that nothing has been duplicated in the list. 

b)As the list starts from 0 both times this means that the time it will take depends on n and as there are 2 loops this means that effectively it will be n x n as n is the size the list in both loops.

c) The algorithm before would compare each and every number in the list so if you had 1 it would go through all of them and then when you got to 2 it would go through all the previous numbers as well. However this is pointless as the first loop would have already compared 1 to 2 so by making it i - 1 this means that this won't happen.

d) As it will only have to search through the numbers ahead of the number that it is currently at in the list this means the algorithm doesn't waste time going through the same parts of the list over and over again therefore halving the time.

e)

f) O(n log n) Source: https://wiki.python.org/moin/TimeComplexity

g)

h) Algorithm 2 as O(n log n) is faster in bigger lists compared to n^2

i) If it is a shorter list then n^2 is actually faster than O(n log n)
