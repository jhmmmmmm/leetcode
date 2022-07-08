# Binary Search

## Three templates

> template 1 --- is used to search for an element or condition which can be determined by accessing a single index in the array.

**Distinguishing Syntax:**
* Initial Condition: left = 0, right = length-1
  * if this a array, probably use 0 and (length - 1). Sometimes left = 1, right = n is used, too. Depends on the scenarios of the problems, this is not the key.
* Termination: left > right !!!
* Searching Left: right = mid-1 !!!
* Searching Right: left = mid+1 !!!
---
**Related exercises:**
- Sqrt(x)
  - use the syntax mentioned above
- Guess Number Higher or Lower
  - use the syntax mentioned above
- Search in Rotated Sorted Array
