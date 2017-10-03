# Lab 3 Answers
## by Larisa Kreismanis and Nathan Bullock

## TestIterator.java Answers
1. //TODO also try with a LinkedList - does it make any difference?
- The LinkedLists and ArrayLists performed at very similar speeds with very little difference.

2. //TODO what happens if you use list.remove(77)?
- The .remove() method removes the element of the index passed into the parenthesis of .remove().  The method .remove(77) would therefore try to remove the element at index 77, which would consequently produce an error.

## TestList.java Answers
1. list.remove(5); // what does this method do?
- The .remove(5) will remove the element at index 5.

2. list.remove(Integer.valueOf(5)); // what does this one do?
- The list.remove(Integer.valueOf(5)) will remove the object that is valued to 5.

##TestPerformance.java Answers
1. // which of the two lists performs better as the size increases?
- After testing, LinkedLists have proven to perform better as the size increases when adding or removing elements.  However, ArrayLists proved to be more efficient when specific elements were required to be manipulated.

## ArrayList and LinkedList Testing Performance Times
https://docs.google.com/spreadsheets/d/1oHhvTz075MFZ3yOxvy3ygcAmBkmBO-q5bKRM73S5TAc/edit?usp=sharing
