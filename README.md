# LeetCode 80 – Remove Duplicates from Sorted Array II

## Problem

Given a sorted integer array `nums`, remove some duplicates **in-place** so that each unique element appears at most twice.

The relative order of the elements should remain the same.

Return the number of elements remaining after removing the extra duplicates.

## Example

### Input

```text
nums = [1,1,1,2,2,3]
```

### Output

```text
5
```

The modified array becomes:

```text
[1,1,2,2,3]
```

## Approach

I used the **Two Pointer** technique.

Since the array is already sorted, I compare the current element with the element two positions behind the current valid position.

If they are different, the current element can be kept.

This ensures that every number appears at most twice.

## Complexity

* **Time Complexity:** `O(N)`
* **Space Complexity:** `O(1)`

## Language

**Python**

## LeetCode

**Problem:** 80. Remove Duplicates from Sorted Array II
**Difficulty:** Medium
**Topic:** Array, Two Pointers

## Author

T.Nandhini
