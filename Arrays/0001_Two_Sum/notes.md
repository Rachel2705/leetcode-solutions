# Notes

## Mistakes I Made

- Initially thought of using two nested loops, which results in O(n²) time complexity.
- Needed to understand why the complement is checked before storing the current number.

## Key Learnings

- A hash map (dictionary) allows fast lookups in O(1) average time.
- Store previously seen numbers and their indices.
- Calculate the complement using:
  ```python
  need = target - num
  ```
- If the complement already exists in the dictionary, the answer is found.

## Python Concepts Used

- Dictionary
- enumerate()
- if key in dictionary

## Things to Remember

- Brute force with nested loops → O(n²).
- One loop with a hash map → O(n).
- Dictionary lookup is O(1) on average.

## Revision Questions

- Why do we check the complement before storing the current number?
- Why is the optimized solution O(n)?
- What happens if we use two nested loops instead of a dictionary?