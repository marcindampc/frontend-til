The flat() method creates a new array with all sub-array elements concatenated into it recursively up to the specified depth.
``` const arr = [1, 2, 3, 4, [5, 6, [7, 8]]];
arr.flat() // [1, 2, 3, 4, 5, 6, Array(2)];
```
