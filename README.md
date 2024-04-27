# SABBIRGAME - Sabbir and Game

Sabbir is a little boy. he loves to play. One day his friend Taskin suggested a new interesting game. There are n levels in the game. One should pass all the levels with a positive life-point. In some level one can increase his life-point by defeating the villain of the game or lose some life-point when one can't defeat the villain. Sabbir knows the points he is going to lose or increase in each level. Determine the minimum life-point Sabbir should have initially (at the starting of the game) to pass all the levels with a positive life point.

Input

Input consists of at most 100 test cases.

First line consists of a single integer T (1 <= T <= 100) number of test cases.

Each test case is consists of two lines. first line consists of an integer n (1 <= n <= 1000)

Second line consists of n space separated integer a1, a2 ... an-1, an (-107 <= ai <= 107)

Output

for each test case print an integer in one line , the minimum life-point Sabbir will need initially.

Example

Input:

3
3
5 -8 3
4
1 2 -3 5
3
1 0 3

Output:

4
1
0

Explanation

First case, if Sabbir have 4 life-points at first. Sabbir will have 9 points after playing 1st level, he will have 1 point after playing 2nd level, he will have 4 points after playing 3rd level... his points never becomes less than 1 (remains positive). If he starts with a lower point (less than 4) initially, he will die at the 2nd level and can't pass all the levels. So, 4 is the minimum answer.
