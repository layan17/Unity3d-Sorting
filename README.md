# Unity3d-Sorting
Different Sorting Simulator using Unity 3d

## Type of sorting created are:
### Bubble Sort
* First Pass: 
  * ( 5 1 4 2 8 ) –> ( 1 5 4 2 8 ), Here, algorithm compares the first two elements, and swaps since 5 > 1. 
  * ( 1 5 4 2 8 ) –>  ( 1 4 5 2 8 ), Swap since 5 > 4 
  * ( 1 4 5 2 8 ) –>  ( 1 4 2 5 8 ), Swap since 5 > 2 
  * ( 1 4 2 5 8 ) –> ( 1 4 2 5 8 ), Now, since these elements are already in order (8 > 5), algorithm does not swap them.
* Second Pass: 
  * ( 1 4 2 5 8 ) –> ( 1 4 2 5 8 ) 
  * ( 1 4 2 5 8 ) –> ( 1 2 4 5 8 ), Swap since 4 > 2 
  * ( 1 2 4 5 8 ) –> ( 1 2 4 5 8 ) 
  * ( 1 2 4 5 8 ) –>  ( 1 2 4 5 8 ) 
* Third Pass: 
  * ( 1 2 4 5 8 ) –> ( 1 2 4 5 8 ) 
  * ( 1 2 4 5 8 ) –> ( 1 2 4 5 8 ) 
  * ( 1 2 4 5 8 ) –> ( 1 2 4 5 8 ) 
  * ( 1 2 4 5 8 ) –> ( 1 2 4 5 8 ) 
## Shuttle Sort
The Shuttle Sort is similar to the Bubble Sort - in each pass through the numbers, we compare the nth and (n+1)th numbers. It is different in that if we have to swap them, indicated by dashes in the table below. We then compare the smallest of this pair with the preceding number, and swap if necessary. Each time a swap is made, we compare with the previous number.

