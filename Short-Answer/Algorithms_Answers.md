#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n)

b) O(n log n)

c) O(n)

## Exercise II

The building is similar to a sorted list. Find the middle floor of the building and drop the egg. If it breaks, find the middle of the lower floors below the current middle floor and re-drop the egg from there. Repeat this process if the egg continues to break. Once you find a floor where the egg does not break, do the same process as above for the upper remaining floors until you arrive at the floor just below the upper most floor that breaks the egg. 

If you start this process and happen to reach the top floor without the egg breaking -- then there is no floor high enough to break the egg. Or, If you reach the bottom floor and the egg still breaks -- there is no floor low enough to keep the egg from breaking.

The runtime for the algorithm is O(log n)