# Sum of Factorials Algorithm

## Problem Description
Write an algorithm that reads a natural number N and calculates the following sum:

S = 1! + 2! + 3! + ... + N!

## Algorithm

### Variables
- N: input number
- S: sum of factorials
- t: factorial counter
- P: factorial value
- i: loop counter

### Steps
Start
Read N
S ← 0
t ← 1

While t ≤ N do
P ← 1
i ← 1
While i ≤ t do  
    P ← P × i  
    i ← i + 1  
End While  

S ← S + P  
t ← t + 1  
End While

Print S
End

## Example
If N = 3:

1! = 1  
2! = 2  
3! = 6  

S = 9
