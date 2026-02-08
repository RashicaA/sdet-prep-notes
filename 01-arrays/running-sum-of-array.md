# Running Sum of 1D Array

## Problem Statement
Given an array `nums`, return an array `runningSum` where  
`runningSum[i] = sum(nums[0] + nums[1] + ... + nums[i])`.

---

## Approach
- Create a new array to store the running sum.
- Initialize the first element with `nums[0]`.
- Traverse the array from index `1` to `n-1`.
- At each index, add the current element to the previous running sum.

---

## Example
Input:
nums = [1,2,3,4]
Output:
[1,3,6,10]


---

## Pseudocode
runningSum[0] = nums[0]
for i from 1 to n-1:
runningSum[i] = runningSum[i-1] + nums[i]
---

## Time & Space Complexity
- **Time Complexity:** O(n)
- **Space Complexity:** O(n)

---

## Key Learnings
- Arrays are accessed using zero-based indexing.
- Traversing an array using a loop is fundamental.
- Running sum problems help build prefix sum concepts.
- Clear logic is more important than optimization at this stage.