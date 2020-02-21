#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)  O(n)

The runtime is Linear in relation to n.

b) O(n^3)

Runtime function has multiple 4 loops. Most likely a linear approach that walks through each array.
As we step through each array the runtime will most likely be notated as 

c) O(n)

given one recursive call when this function is called, this is O(n) time complexity.

## Exercise II

If we imagine that our buiding with n floors, like a sorted array. And we need to find the last safe floor f, where if we go one floor up the egg we drop will break. We need to create searching algorithim so we make the least amount of passes with broken eggs. In this case we can use a binary-search algorithm to solve the task. We can start by dividing n by 2, and dropping an egg from there. If the egg break, we can then leave out the values larger than n/2, and divide by 2 again to drop another egg. If egg breaks, we again leave out values greater than n/2/2,and keep the until egg doesnt break. So the time complexity will be O(logn) and O(n) for space complexity(when done with iterations).

