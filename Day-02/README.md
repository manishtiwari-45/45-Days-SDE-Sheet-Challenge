# Day 02

📅 Date: 2 June 2026

## Problems Solved

### 1. Maximum Subarray (Kadane's Algorithm)

**Platform:** LeetCode

**Difficulty:** Medium

### Approach

Maintained a running sum while traversing the array.

Whenever the running sum became negative, it was reset because carrying a negative contribution would only reduce future subarray sums.

Tracked the maximum subarray sum throughout the traversal.

### Complexity

* Time Complexity: O(n)
* Space Complexity: O(1)

### Key Learning

Kadane's Algorithm shows how local decisions can lead to a globally optimal solution. Instead of checking every subarray, we can intelligently discard negative contributions.

---

### 2. Sort Colors (Sort an Array of 0's, 1's and 2's)

**Platform:** LeetCode

**Difficulty:** Medium

### Approach

Used the Dutch National Flag Algorithm with three pointers:

* low
* mid
* high

The array was partitioned into three sections and sorted in a single traversal without using extra space.

### Complexity

* Time Complexity: O(n)
* Space Complexity: O(1)

### Key Learning

Partitioning techniques can solve many sorting problems efficiently. Understanding pointer movement is more important than memorizing the algorithm.

---

### 3. Best Time to Buy and Sell Stock

**Platform:** LeetCode

**Difficulty:** Easy

### Approach

Maintained the minimum stock price encountered so far and continuously calculated the maximum profit possible at each position.

Updated the answer whenever a better profit was found.

### Complexity

* Time Complexity: O(n)
* Space Complexity: O(1)

### Key Learning

Optimization problems often require maintaining the correct state while traversing the array only once.

---

## Concepts Practiced

✔ Greedy Algorithms

✔ Running Sum Technique

✔ Three Pointer Technique

✔ Array Traversal

✔ State Tracking

✔ In-place Modification

✔ Optimization Strategies

---

## Day Summary

Today's problems reinforced the importance of identifying patterns that enable linear-time solutions.

Although the brute-force approaches were straightforward, the optimal solutions relied on maintaining useful information while traversing the array only once.

The most valuable takeaway was learning how a small amount of state information can dramatically reduce time complexity.

---

## Statistics

Problems Solved: 3

Easy: 1

Medium: 2

Hard: 0

Total Problems Solved So Far: 6

---

## Screenshots

### Kadane's Algorithm

![Kadane's Algorithm](./screenshots/kadanes-algorithm.png)

### Sort Colors

![Sort Colors](./screenshots/sort-colors.png)

### Best Time to Buy and Sell Stock

![Stock Buy and Sell](./screenshots/stock-buy-sell.png)
