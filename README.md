# Patikadev-data-structures-and-algorithms
Insertion Sort, Selection Sort, Merge Sort, Binary Search Tree

***

[22,27,16,2,18,6]

**Insertion Sort aşamaları:**
1. [**2**,27,16,**22**,18,6]
2. [2,**6**,16,22,18,**27**]
3. [2,6,16,**18**,**22**,27]

**Big-O Notation:**

Best Case: O($n$)

Average Case: O($n^2$)

Worst Case: O($n^2$)

**Time Complexity of number 18:**

Average Case.

***

[7,3,5,8,2,9,4,15,6]

**Selection Sort ilk 4 aşama:**
1. [**2**,3,5,8,**7**,9,4,15,6]
2. [2,3,**4**,8,7,9,**5**,15,6]
3. [2,3,4,**5**,7,9,**8**,15,6]
4. [2,3,4,5,**6**,9,8,15,**7**]

***

[16,21,11,8,12,22]

**Merge Sort aşamaları:**
1. [16,21,11] --- [8,12,22]
2. [16] -- [21,11] --- [8] -- [12,22]
3. [16] -- [21] - [11] --- [8] -- [12] - [22]
4. [16] -- [11,21] --- [8] -- [12,22]
5. [11,16,21] --- [8,12,22]
6. [8,11,12,16,21,22]

**Big-O Notation:**

O($n * logn$)

***

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

**Binary Search Tree**

```
      root = 6
            /\
           5  7
          /    \
         1      8
        /  \     \
       0    3     9
            /\
           2  4
```
