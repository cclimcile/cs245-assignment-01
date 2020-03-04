# cs245-assignment-01

Hybrid Sort:

For my hybridSort, when the array is minimised to a length of 100, I choose to use my quadratic sort on it.
This is because at len >= 100, insertionSort is faster than quickSort. Based on the graph of O(n^2) and O(nlogn) from n = 0 ot n = 100, we can see that n^2 is quicker, however, once n is > 100, nlogn is quicker. Hence, since n starts of as 1,000,000, where n is significantly huge, it makes sense to use quickSort.

Moreover, I chose to use insertionSort for my quadratic sort as it had a runtime of n^2 and was easiest to implement. Furthermore, insertion sort scales easily and thus, sorting 100 tasks would have been feasible.


External Sort:

For this porgram, I made use of a k-merge method similar to mergeSort's 2-merge method. This allowed me to sort a temp arr of k size for ceil(n/k) different arrays easily. 
