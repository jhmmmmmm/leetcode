# Binary Search

## Three templates

> template 1 --- is used to search for an element or condition which can be determined by accessing a single index in the array.

**Distinguishing Syntax:**
* Initial Condition: left = 0, right = length-1
  * if this a array, probably use 0 and (length - 1). Sometimes left = 1, right = n is used, too. Depends on the scenarios of the problems, but this is not the key.
* Termination: left > right --> equal to `while(left <= right)`
* Searching Left: **right = mid-1**
* Searching Right: **left = mid+1**
---
**Related exercises:**
- Sqrt(x)
- Guess Number Higher or Lower
- Search in Rotated Sorted Array
  - a little bit different, fisrtly, to find out which point the rotation happens, then divide the array into two parts, then use the syntax mentioned above

---

> template 2 ---  is an advanced form of Binary Search. It is used to search for an element or condition which requires accessing the current index and its immediate right neighbor's index in the array.

**Distinguishing Syntax:**
* Initial Condition: left = 0, right = length
  * Sometimes left = 1, right = n is used, too. Depends on the scenarios of the problems, but this is not the key.
* Termination: left == right --> equal to `while(left < right)`
* Searching Left: **right = mid**
* Searching Right: **left = mid+1**
* **Post-processing required. Loop/Recursion ends when you have 1 element left. Need to assess if the remaining element meets the condition.**
---
**Related exercises:**
- First Bad Version
- Find Peak Element
- Find Minimum in Rotated Sorted Array


