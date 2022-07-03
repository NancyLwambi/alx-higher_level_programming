0. Write a function that prints all integers of a list.

1.Write a function that retrieves an element from a list like in C.

2.Write a function that replaces an element of a list at a specific position (like in C).

3.Write a function that prints all integers of a list, in reverse order

4.Write a function that replaces an element in a list at a specific position without modifying the original list (like in C).

5.Write a function that removes all characters c and C from a string.

6.Write a function that prints a matrix of integers.

7.Write a function that adds 2 tuples.

8.Write a function that returns a tuple with the length of a string and its first characte

9.Write a function that finds the biggest integer of a list.

10.Write a function that finds all multiples of 2 in a list.

11.Write a function that deletes the item at a specific position in a list.

12.Write a function in C that checks if a singly linked list is a palindrome.

13.Write a function in C that checks if a singly linked list is a palindrome.




##  1. Secure access to an element in a list

Write a function that retrieves an element from a list like in C.

. Prototype: def element_at(my_list, idx):

. If idx is negative, the function should return None

. If idx is out of range (> of number of element in my_list), the function should return None

. You are not allowed to import any module

. You are not allowed to use try/except


```guillaume@ubuntu:~/0x03$ cat 1-main.py

#!/usr/bin/python3

element_at = __import__('1-element_at').element_at



my_list = [1, 2, 3, 4, 5]

idx = 3

print("Element at index {:d} is {}".format(idx, element_at(my_list, idx)))



guillaume@ubuntu:~/0x03$ ./1-main.py

Element at index 3 is 4

guillaume@ubuntu:~/0x03$ 