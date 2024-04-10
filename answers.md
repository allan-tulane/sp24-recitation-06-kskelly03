# CMPS 2200 Recitation 06
## Answers

**Name:**_________Kevin Skelly________________
**Name:**_________Zach Goodman________________


Place all written answers from `recitation-07.md` here for easier grading.



- **2)**
W(n) = W(n-1) + W(n-2) + 1 ---> O(2^n)
- **3)**
S(n) = S(n-1) + 1 ---> O(n)
- **4)**
The function seems to be generating the fibonacci sequence starting from the first number and repeatedly adding one. This is due to the recurrence repeatedly returning 1. This results in the fibonacci sequence being generated beginning with the first value. 
- **6)**
The maximum times that fib_top_down() will be called for any value of i is i+1. This means that the work and span are both O(n)
- **8)**
The maximum number of times that F_i will be called n-2 times. This algorithm and cannot parallelized. The work will be O(n) and span O(n)