## 01. Factorial

The problem can be found at the following link: [Question Link](https://www.geeksforgeeks.org/problems/factorial5739/1)

### Problem Description

**Task:** Given a positive integer, n. Find the factorial of n.Examples :Input: n = 5

#### Examples

##### Example 1

- **Output:**
```text
24
```
- **Explanation:** 1 x 2 x 3 x 4 = 24

### Time and Auxiliary Space Complexity

- **Expected Time Complexity:** O(n)
- **Expected Auxiliary Space Complexity:** O(1)

### Accepted Solutions (1)

#### Solution 1 (Python)

- **Submitted:** 2026-11-21 15:43:25
- **Status:** Correct
- **Marks:** 1

```python
class Solution:
    def factorial(self, n: int) -> int:
        if n == 0 or n == 1:
            return 1
        result = 1
        for i in range(2, n + 1):
            result *= i
        return result
```

*Generated on: 11/21/2026, 4:14:06 PM*