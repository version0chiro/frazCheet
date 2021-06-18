# Questions

### Two Sum

Given an array of integers nums and an integer target, return indices of the two numbers such that they add up to target.

You may assume that each input would have exactly one solution, and you may not use the same element twice.

You can return the answer in any order.

| Sr.No | Input                          | Output |
| ----- | ------------------------------ | ------ |
| 1     | nums = [2,7,11,15], target = 9 | [0,1]  |
| 2     | nums = [3,2,4], target = 6     | [1,2]  |
| 3     | nums = [3,3], target = 6       | [0,1]  |


### Explantaion:

We can use BF for this by simply double for loops, how ever that will result in O(n^2) time complexity. To avoid this we can use a hash-map or unordered map, we can sovle this question in O(n)

1. Make a unordered map and loop through the array storing the element as key and index as value.
2. Now make a second pass through the arry and find if map has (target-nums[i]) nad if the index is not same as that of nums[i], we have found our solution.
3. To optimize the solution, we can also send in a one pass and search for target-nums[i] in the same loop as that of appending in the map.