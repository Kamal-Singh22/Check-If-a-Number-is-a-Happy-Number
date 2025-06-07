# Check-If-a-Number-is-a-Happy-Number
A happy number is a number defined by the following process: Starting with any positive integer, replace the number by the sum of the squares of its digits, and repeat the process until the number equals 1 (where it will stay), or it loops endlessly in a cycle which does not include 1.

Explanation:
We track all previously seen numbers in a Set to detect a cycle.

If a number repeats, it's not happy.

If we reach 1, the number is happy.

getSumOfSquares() calculates the sum of squares of digits.
