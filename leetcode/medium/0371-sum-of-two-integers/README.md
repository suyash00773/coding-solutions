# Sum of Two Integers

![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow)

## Problem

Given two integers `a` and `b`, return  *the sum of the two integers without using the operators*  `+`  *and*  `-`.

 

 **Example 1:** 

```
Input: a = 1, b = 2
Output: 3

```

 **Example 2:** 

```
Input: a = 2, b = 3
Output: 5

```

 

 **Constraints:** 

- -1000 <= a, b <= 1000

## Solution

**Language:** C++  
**Runtime:** 0 ms (beats 100.00%)  
**Memory:** 7.9 MB (beats 33.44%)  
**Submitted:** 2026-10-14T17:44:18.832Z  

```cpp

class Solution {
public:
    int getSum(int a, int b) {
        while (b != 0) {
            unsigned int carry = (unsigned int)(a & b) << 1;
            a = a ^ b;
            b = (int)carry;
        }
        return a;
    }
};

```

---

[View on LeetCode](https://leetcode.com/problems/sum-of-two-integers/)