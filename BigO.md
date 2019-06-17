# Big O
It is an efficiency of time algorithm.

O(n) n could be the time, memory.

Run time 
- It is a property of an algorithm. It is the maximum number of steps the algorithm can run for, as a function of the length of the input.

Time complexity 
- It is a property of a computational problem. It is, essentially, the running time of the fastest possible algorithm for that problem.

Run Time (slow -> fast)
1. O(X!)
2. O(2^x)
3. O(X^2)
4. O(x log x)
5. O(X)
6. O(log x)

Addition and Multiplication of Run Time
- Addition : O(A + B)
    - Do B after A is done
```Java
    for(int a : arrA) { 
        print(a)
    }
    for(int b : arrB) { 
        print(b)
    }
```
- Multiplication : O(A * B)
    - Do B everytime A runs
```Java
    for (int a : arrA) {
        for (int b : arrB) {
             print(a + "," + b);
        }
    }
```

#### ArrayList
-  Characteristics
    - It is a global arrays.
    - It is able to change the size. It will automatically increase 
    the size of the arrayList when adding an element into the list.
    - When the list is full, it doubles the size of the original list and 
    copies all the elements to the new list. 
    - Costs O(2X) time to insert X number of elements.
    - Costs O(1) time to insert one element.

##### Log N 
- Characteristics
    - Mostly been used when using binary search.
    - 2^k = N 
    - log2N = K
    - 
    -

