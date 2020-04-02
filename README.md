
# Birthday-Chocolate-Question
Birthday Chocolate Question From HackerRank

Lily has a chocolate bar that she wants to share it with Ron for his birthday. Each of the squares has an integer on it. She decides to share a contiguous segment of the bar selected such that the length of the segment matches Ron's birth month and the sum of the integers on the squares is equal to his birth day. You must determine how many ways she can divide the chocolate.

Consider the chocolate bar as an array of squares, ```s = [2, 2, 1, 3, 2] ```. She wants to find segments summing to Ron's birth day, ```d = 4``` with a length equalling his birth month, ``` m = 2 ``` In this case, there are two segments meeting her criteria: ``` [2, 2] ``` and ``` [1, 3]``` 

#### Function Description
Complete the _birthday_ function in the editor below. It should return an integer denoting the number of ways Lily can divide the chocolate bar.

**birthday has the following parameter(s):**
-   _s_: an array of integers, the numbers on each of the squares of chocolate
-   _d_: an integer, Ron's birth day
-   _m_: an integer, Ron's birth month

**Output Format**
Print an integer denoting the total number of ways that Lily can portion her chocolate bar to share with Ron.

// Complete the birthday function below.

```js
function birthday(s, d, m) {
}
console.log(birthday([2,2,1,3,2], 4, 2), 'Should be [2, 2], [1, 3]');

console.log(birthday([1, 2, 1, 3, 2], 3, 2), 'Should be [1, 2], [2, 1]');

console.log(birthday([1, 1, 1, 1, 1, 1], 3, 2), 'Should be 0');

console.log(birthday([4], 4, 1), 'Should be [4]');
```
