# Linear-Search

A sequential search technique known as "linear search" starts at one end of a list and runs through each item in turn until the desired element is located; if not, the search continues until the end of the data set.

Working of a Linear Search
Step 1: First, read the search element (Target element) in the array.

Step 2: Set an integer i = 0 and repeat steps 3 to 4 till i reaches the end of the array.

Step 3: Match the key with arr[i].

Step 4: If the key matches, return the index. Otherwise, increment i by 1.

NOTE:- We can also utilize linear search using a recursive function. In this case, the iteration is done using a recursion.

![234093709-b35c86dd-37ba-460c-999c-6f1082e0595e](https://user-images.githubusercontent.com/125882453/234394549-b8add4a4-1e33-41af-b52e-8c3dd4e1508c.png)



Advantages of Linear Search:

1. Linear search is simple to implement and easy to understand.

2. Linear search can be used irrespective of whether the array is sorted or not. It can be used on arrays of any data type.

3. Does not require any additional memory.

4. It is a well suited algorithm for small datasets.

Drawbacks of Linear Search:

1. Linear search has a time complexity of O(n), which in turn makes it slow for large datasets.

2. Not suitable for large arrays.

3. Linear search can be less efficient than other algorithms, such as hash tables.

When to use Linear Search?

1. When we are dealing with a small dataset.

2. When you need to find an exact value.

3. When you are searching a dataset stored in contiguous memory.

4. When you want to implement a simple algorithm.

