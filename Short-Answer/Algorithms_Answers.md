#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) The runtime is O(n) (linear). This means that the number of operations will increase linearly along with an increase in the input n. It runs through the data one time no matter how large the input n is. 


b) The runtime is O(n log n)(quadratic). It has a nested for/while loop and it's being doubled with each loop.
O(log n). O(n) * O(log n) = O(n log n)

c) The runtime is O(n) (linear). It's recursive, it decrements n (number of bunnies) and counts the ears of the bunnies removed until it reaches 0. 

## Exercise II

 
I would use a binary search tree to solve this. 

1. Start at the midpoint of the list of floor numbers and drop egg. If it breaks from initial midpoint, set new max to left of it. However, if it doesn't break, find new maximum height and set minimum to right of initial midpoint.
2. With each iteration, you'll move to a side of the binary three until you reach a midpoint where the egg does not break and you're right below the max value(lowest loor where egg will break). 

The runtime complexity is O(log n) since the number of floors is being halved by each iteration. 