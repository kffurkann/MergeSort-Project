# Merge Sort Project
Merge Sort operates on the "divide and conquer" principle.

## [16, 21, 11, 8, 12, 22] --> Merge Sort

- *Write the stages of the above array according to the sort type.*
- *Write the Big-O notation.*

## Answers
```
   [16,21,11,8,12,22]
           / \
  [16,21,11] [8,12,22]
       / \        / \
  [16][21,11] [8][12,22]
   |    / \    |   / \
 [16][21][11] [8][12][22]
    |   \ /     |   \ /
  [16][11,21] [8][12,22]
      \  /       \  /
  [11,16,21][8,12,22]
           \  /
   [8,11,12,16,21,22]

```
- The time complexity of Merge Sort is: O(n log n)
