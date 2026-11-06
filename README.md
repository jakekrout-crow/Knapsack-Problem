# Assignment: Knapsack Problem Implementation

## Introduction

This assignment challenges you to implement solutions for the classic 0/1 Knapsack Problem using two different dynamic programming approaches: memoization (top-down) and tabulation (bottom-up). You'll analyze and compare both implementations to understand their strengths and weaknesses.

### Starter Files

Create a new Jupyter Notebook for your implementation.

## Learning Outcomes

By completing this assignment, you'll be able to:

1. Implement a memoization-based solution for the 0/1 Knapsack Problem
2. Develop a tabulation-based solution for the 0/1 Knapsack Problem
3. Compare and analyze the time and space complexity of both approaches
4. Evaluate the advantages and disadvantages of each implementation
5. Make informed decisions about which approach to use based on specific scenarios

## Instructions

### Part 1: Memoization Implementation

Implement a memoization-based solution for the 0/1 Knapsack Problem that includes:
- A recursive function with memoization
- Proper handling of base cases
- A dictionary or array for storing computed results
- Input validation and error handling

Your implementation should accept:
- A list of weights
- A list of values
- Maximum weight capacity
- Return the maximum possible value

### Part 2: Tabulation Implementation

Implement a tabulation-based solution that includes:
- A bottom-up approach using a table
- Proper initialization of the table
- Systematic table filling
- Solution extraction
- Input validation and error handling

Your implementation should accept the same parameters as the memoization version.

### Part 3: Analysis and Comparison

Create a performance analysis function that:
- Measures execution time for both implementations
- Tracks memory usage
- Tests with different input sizes
- Records and compares results

Write a detailed analysis comparing both approaches, addressing:
- Time complexity
- Space complexity
- Code readability
- Maintenance considerations
- Specific scenarios where each approach excels

## Testing Requirements

Test your implementations using the following scenarios:

Basic test case:

```python
weights = [2, 3, 4, 5]
values = [3, 4, 5, 6]
capacity = 8
```

Edge cases:
- Empty input lists
- Capacity of 0
- Single item
- All items too heavy

Large test case:
- Generate a test case with 100 items
- Use random weights and values
- Test both implementations with this larger dataset


## Conclusion

This assignment provides hands-on experience with two fundamental dynamic programming approaches. Through implementation and analysis, you'll gain practical understanding of when to use each approach and how to evaluate their trade-offs in real-world scenarios.
