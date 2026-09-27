# Sum of Array

![Difficulty](https://img.shields.io/badge/Difficulty-Basic-red)

## Problem

Given an integer array  **arr[]**, return the sum of all elements of arr.

 **Examples:** 

```
Input: arr[] = [1, 2, 3, 4]
Output: 10
Explanation: 1 + 2 + 3 + 4 = 10.

```

```
Input: arr[] = [1, 3, 3]
Output: 7
Explanation: 1 + 3 + 3 = 7.

```

## Solution

**Language:** c(gcc5.4)  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-27T18:47:45.950Z  

```c(gcc5.4)
int arraySum(int arr[], int size) {
    // code here
    int sum = 0;
    for(int i =0; i<size; i++){
        sum += arr[i];
    }
    
    return sum;
}
```

---

[View on GeeksforGeeks](https://practice.geeksforgeeks.org/problems/sum-all-array-elements/1)