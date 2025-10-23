# CMPS 2200 Reciation 5
## Answers

**Name:**______Dylan Sawransky___________________


Place all written answers from `recitation-05.md` here for easier grading.







- **1b.**
Selection sort shows that O(n^2) is not useful for large inputs because of its time complexity

Quicksort with fixed pivot shows O(n log n) average case performance but can become O(n²) in worst case scenarios when the pivot selection is unlucky

Quicksort with random pivot keeps O(n log n) expected performance across all inputs because the randomization makes it less likely you get the worst case 

Selection sort is O(n^2) because it still has to make the same number of comparisons

Quicksort with fixed pivots has worst case behavior because it always chooses the smallest element to pivot making unbalanced partitions

Quicksort with random pivot keeps O(n log n) performance because of the random pivots 



- **1c.**

Timsort is better than both forms of quicksort especially with large inputs

Timsort has O(n log n) performance but with better constants and cache efficiency than quicksort

If the list is sorted Timsort has basically O(n) runtime



