# Quicksort-and-Merg
Quicksort and Mergsort

Comparing Quicksort and Mergsort

Mergesort is a divide an conquer algorithm, where it divides input array in two halves and calls itself for two halves and then merges the two sorted halves while Quicksort is also a divide and conquer algorithm but it picks an element aspivot and partitions the given array around the picked pivot also Quicksort is usually faster than Mergesort.
As we see through the result we find out Quicksort is faster but also in some cases Mergesort ends up faster and those cases are when the lenght is high and range is low thats for mregesort.
comparison of both results below:

Length=10 Range=10 - Quicksort: 0.000132 , Mergesort: 0.000230, Length=10 Range=100 - Quicksort: 0.000129 , Mergesort: 0.000220, Length=10 Range=200 - Quicksort: 0.000121 , Mergesort: 0.000281, Length=10 Range=1000 - Quicksort: 0.000140 , Mergesort: 0.000223,  Length=100 Range=10 - Quicksort: 0.002560 , Mergesort: 0.003391, Length=100 Range=100 - Quicksort: 0.001825 , Mergesort: 0.003413,  Length=100 Range=200 - Quicksort: 0.001491 , Mergesort: 0.003480, Length=100 Range=1000 - Quicksort: 0.001841 , Mergesort: 0.003346, Length=1000 Range=10 - Quicksort: 0.124680 , Mergesort: 0.045843,  Length=1000 Range=100 - Quicksort: 0.034858 , Mergesort: 0.046083,  Length=1000 Range=200 - Quicksort: 0.027447 , Mergesort: 0.046133,  Length=1000 Range=1000 - Quicksort: 0.024663 , Mergesort: 0.046087,  Length=10000 Range=10 - Quicksort: 14.542730 , Mergesort: 0.760508,  Length=10000 Range=100 - Quicksort: 1.374629 , Mergesort: 0.648589,  Length=10000 Range=200 - Quicksort: 0.937674 , Mergesort: 0.627409,  Length=10000 Range=1000 - Quicksort: 0.403089 , Mergesort: 0.602369

Quicksort seems to be more efficient/faster when the lists are smaller but when the length goes up merge sort becomes more efficient/faster in smaller ranges.so overall Quicksort is faster with small lists and mergesort is fatser when lists gets larger.

