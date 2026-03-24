# Ex. No: 15D - Build a Heap Tree Using Python

## AIM:
To write a Python program to build a heap tree using appropriate Python package and function.

---

## ALGORITHM:

1. **Start the program.**
2. Import the `heapq` module.
3. Define a function `heaptree(H)` that takes a list `H` as input.
4. Use `heapq.heapify(H)` to convert the list into a min-heap.
5. Print the created heap.
6. **End the program.**

---

## PROGRAM:

```
#Reg.No: 212222060292
#Name: Vijay Aravind S
#Add Your Code Here
from binarytree import heap,build,Node
def heaptree(L):
  x=L
  t=build(x)
  for i in t.values:
    print(i,"-->",end='')
  print("\nHeight : ",t.height)
  print("Is min heap? : ",t.is_min_heap)
  print("Is complete tree? : ",t.is_complete)
```

## OUTPUT
<img width="1183" height="283" alt="image" src="https://github.com/user-attachments/assets/d65487ea-ff33-4ab1-b883-b5bcc99d7433" />

## RESULT
Therefore, the output is the example to write a Python program to build a heap tree using appropriate Python package and function.
