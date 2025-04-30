# Ex8 Deque
## DATE: 25.04.2025
## AIM:
To write a C function to count the number of elements present in the deque.

## Algorithm
1. Start the program.
2. Include required libraries.
3. Define a function to count the number of elements in the deQueue.
4. Run a loop from zero index to maximum index value and increment count if the value is not equal to zero. Return the counted value.
5. End the program.

## Program:
```
/*
Program to count the number of elements present in the deque
Developed by: SRISHANTH J
RegisterNumber: 212223240160
*/

#include<stdio.h>
int count(int *arr) {
  int c = 0, i;
  for(i=0;i<MAX;i++)
  {
      if(arr[i]!=0)
      c++;
  }
  return c;
}
```

## Output:
![Screenshot 2025-04-30 093823](https://github.com/user-attachments/assets/e8f7cc03-db00-4886-afd0-e30b6bb4d985)


## Result:
Thus, the C code to count the number of elements present in the deque is implemented successfully.
