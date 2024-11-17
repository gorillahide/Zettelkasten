2024-08-15 19:07
Status: #child
Tags: 

# Insertion Sort

Insertion sort is an algorithm which solves the [[Sorting Problem]]. It sorts the array **in place**. See [[In-place Algorithm]]. Notably, it is a [[Stable Sorting Algorithm]].

Insertion short takes an array $A[1 \cdots n]$. It rearranges the array with at most a constant number of them stored at any time. The original input array, A, stores the sorted output when finished. 
![[Insertion Sort Example.png]]
![[Insertion Sort Example 2.avif]]
### Pseudocode

![[Insertion Sort Python Code.png]]
In essence, the key starts as the second element of the array and the index is the first element. As long as the first element is smaller than the second, it moves forward. Otherwise, they are swapped. This is repeated n times.

### Properties
O($n^2$ ) worst case time complexity.
O($n$) best care time complexity.
Best used on small $n$ 
Its space complexity is O($log(n)$)
# References
[[Introduction to Algorithms 3rd Edition]]
