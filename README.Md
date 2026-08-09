SUMMARY:
Linear Search and Binary Search are two commonly used searching algorithms for finding an element in a list or array.
Linear Search checks each element one by one from the beginning until the required element is found or the list ends.
It can be used on both sorted and unsorted data. Its best-case time complexity is O(1), while its average-case and worst-case time complexities are O(n).
Binary Search is a more efficient searching algorithm that works only on a sorted array.
It compares the search element with the middle element and repeatedly divides the search space into half. 
Its best-case time complexity is O(1), while its average-case and worst-case time complexities are O(log n).

CONCLUSION:
From the comparison, Binary Search is generally faster than Linear Search for large datasets because it reduces the search space by half in every step.
However, Binary Search requires the data to be sorted, whereas Linear Search can work directly on unsorted data.
