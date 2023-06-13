# Selection Sort Project
The solution to the project given on the Patika.dev education platform related to data structures and algorithms topic.
QUESTION 1

Write down the steps of the sorting type for the given array.

[2,27,16,22,18,6] == n comparisons
[2,6,16,22,18,27] == (n-1) comparisons
[2,6,16,22,18,27] == (n-2) comparisons
[2,6,16,18,22,27] == (n-3)comparisons
[2,6,16,18,22,27] == (n-4)comparisons
[2,6,16,18,22,27] == 1 comparisons

QUESTION 2

Write the Big-O notation.

I performed a total of (n^2+n)/2 operations. In Big O Notation, we consider the dominant term.

Big O notation = O(n^2)

QUESTION 3

After the array is sorted, which of the following cases does the number 18 fall into? Write it down.

[2,6,16,18,22,27]
The number we are looking for is in a position close to the middle, so it falls within the Average Case scenario.

QUESTION 4

Write the first 4 steps of the [7,3,5,8,2,9,4,15,6] array according to Selection Sort.

[2,3,5,8,7,9,4,15,6]
[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
