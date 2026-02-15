# Experiment 15: Subarrays Divisible by K

## Problem Statement

Given an integer array `nums` and an integer $k$, print the number of non-empty **subarrays** that have a sum divisible by $k$.

A **subarray** is a contiguous part of an array.

## Input Format

* The first line contains two integers $n$ (size of the array) and $k$.
* The second line contains $n$ space-separated integers.

## Output Format

Print the count of subarrays whose sum is divisible by $k$.

### Example 1

**Input:**

```text
6 5
4 5 0 -2 -3 1
```

**Output:**

```text
7
```

**Explanation:**
The subarrays with sum divisible by 5 are:
* [4, 5, 0, -2, -3, 1] (sum 5)
* [5] (sum 5)
* [5, 0] (sum 5)
* [5, 0, -2, -3] (sum 0)
* [0] (sum 0)
* [0, -2, -3] (sum -5)
* [-2, -3] (sum -5)

### Example 2

**Input:**

```text
4 2
4 5 0 -2
```

**Output:**

```text
4
```
