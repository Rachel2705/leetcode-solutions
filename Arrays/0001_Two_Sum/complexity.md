# Complexity

## Brute Force
- Time: O(n²)
- Space: O(1)

Reason:
- Compare every pair of elements using two nested loops.

## Optimized
- Time: O(n)
- Space: O(n)

Reason:
- Traverse the array once while storing previously seen numbers in a hash map (dictionary).
- Dictionary lookups take O(1) on average.