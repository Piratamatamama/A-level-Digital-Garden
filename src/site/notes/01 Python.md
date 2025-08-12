---
{"dg-publish":true,"permalink":"/01-python/"}
---


```Python
import micropip
await micropip.install('numpy')  
import numpy as np
a = np.random.rand(3,2)
b = np.random.rand(2,5)

print(a@b)
```


1. [[oop\|oop]]
	1. BASIC:
		1. instantiation of object and use of object to use method
		2. initialised to zero dont need to include in parameter list within()
		3. declare as array/list
		4. append list
		5. pseudocode declaration of data type
	 2. inheritance
	 3. override parent's method
	 4. overload
	 5. containment
2. range
	1. inclusive
	2. exclusive
	3. for _ in range()
3. [[file\|file]]
	1. f=open('filename.txt', 'r')
	2. with open('filename.txt', 'r') as f:
	3. f.read()
	4. f.readline()
	5. f.read().strip()
	6. f.write('write this string\n')
	7. \n to add new line
	8. f.close()
	9. import os
	10. if os.path.exists('filename.txt')
4. adt: 
	1. [[stack\|stack]]
	2. [[queue\|queue]]
	3. [[linked list\|linked list]]
	4. [[binary tree\|binary tree]]
	5. [[Implement ADT from another ADT\|Implement ADT from another ADT]]
5. search: 
	1. linear
	2. [[binary search\|binary search]]
6. sort: 
	1. [[bubble sort\|bubble sort]]
	2. [[insertion sort\|insertion sort]]
7. string manipulation
	1. print('blabla', end=' ')
	2. slicing
8. [[miscellaneous important stuff\|miscellaneous important stuff]]
- after return, function stops
- thought input as class 'str' unless explicitly use int()
- input checking
1. [[Recursion\|Recursion]]
2. [[big o notation\|big o notation]]
3. [[error\|error]]

## Past years:
[[9618_41_mj_24\|9618_41_mj_24]]
9618_41_mj_23
[[9618_42_mj_24\|9618_42_mj_24]]