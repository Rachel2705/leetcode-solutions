# 0001. Two Sum

## Problem

Find the indices of two numbers in an array whose sum equals the given target.

## Approach

- Use a hash map (dictionary) to store previously seen numbers and their indices.
- For each number, calculate the complement (`target - num`).
- Check if the complement already exists in the hash map.
- If it exists, return the stored index and the current index.
- Otherwise, store the current number and its index.

## Algorithm

1. Create an empty dictionary.
2. Iterate through the array.
3. Compute the complement.
4. If the complement exists in the dictionary, return the answer.
5. Otherwise, store the current number and continue.

## Why This Works

The dictionary stores numbers that have already been visited. If the required complement has already been seen, the current number and the complement together form the target sum.