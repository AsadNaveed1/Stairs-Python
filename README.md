# Stairs-Python

# Q6: Stairs
Weight: 10%

Last update: 20 Sep, 7am

Let there be n stairs. A person standing at the bottom wants to reach the top. The person can climb either 1 stair or p stairs at a time, where p is a prime number. Count the number of ways, the person can reach the top. You program should be able to handle integers in the range 0 < n < 50.

Examples:

```

Let n = 1. The person can take 1 step to reach the top. There is only 1 way to reach the top.

Let n = 2. The person can take 1 step + 1 step, or 2 steps to reach the top. There are 2 ways to reach the top. Using a different notation: For n = 2 we have (1, 1), (2), i.e., 2 ways to reach the top.

For n = 3 we have (1, 1, 1), (1, 2), (2, 1), (3), i.e., 4 ways to reach the top. 

For n = 6 we have (1, 1, 1, 1, 1, 1), (1, 1, 1, 1, 2), (1, 1, 1, 2, 1), (1, 1, 1, 3), (1, 1, 2, 1, 1), (1, 1, 2, 2), 
(1, 1, 3, 1), (1, 2, 1, 1, 1), (1, 2, 1, 2), (1, 2, 2, 1), (1, 2, 3), (1, 3, 1, 1), (1, 3, 2), (1, 5), (2, 1, 1, 1, 1), 
(2, 1, 1, 2), (2, 1, 2, 1), (2, 1, 3), (2, 2, 1, 1), (2, 2, 2), (2, 3, 1), (3, 1, 1, 1), (3, 1, 2), (3, 2, 1), (3, 3), (5, 1), i.e., 26 ways to reach the top.

Hints:

For n=6, steps can be 1, 2, 3, 5. Thus, for n=6, the ways to reach the top is the sum of cases when n=6-1, n=6-2, n=6-3, n=6-5. 

When you exceed the time limit of test cases, you may try a faster method.

Sample runs:

2
2
4
7
6
26
10
343
42
294537572513
49
26513100110722

```
