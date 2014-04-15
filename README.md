## Iterators Lab

This lab builds on an implementation of ```SortedArray```.  A ```SortedArray``` is an array that always maintains the sorted order of its elements.  Here is some example use of ```SortedArray```:

```
arr = SortedArray.new([9,11,23,4,5,6,-10])
while i < arr.length
  puts arr[i]
  i += 1
end

```

Below is the output of the code:

```
-10
4
5
6
9
11
23
```
__NOTICE__ that the array is printed in sorted order.  Since our SortedArray class always maintains order.

The objective is to implement the iterator methods in the sorted array class so that the tests pass.

### Bonus

Implement `SortedArray#inject`. See if you can get it to work exactly
like `Array#inject`. 
