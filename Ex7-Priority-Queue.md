# Ex7 Priority Queue
## DATE: 25.04.2025
## AIM:
To formulate the C code to display the elements of the priority queue after insertion and deletion operation.

## Algorithm
1. Start the program.
2. Include required libraries.
3. Scan the number of elements to be inserted and deleted.
4. Run loop accordingly and call insert and delete function iteratively.
5. End the program.

## Program:
```
/*
Program to o display the elements of the priority queue after insertion and deletion operation
Developed by: BALAJI S
RegisterNumber: 212223040024

#include <stdio.h>
int size = 0;
int main() {
    int m,k,e,r,e1;
  int array[10];
  scanf("%d",&m);
  for(k=0;k<m;k++)
  {
      scanf("%d",&e);
      insert(array,e);
  }
  scanf("%d",&r);
  for(k=0;k<r;k++)
  {
      scanf("%d",&e1);
      deleteRoot(array,e1);
  }
  printf("Max-Heap array after insertion and deletion: ");
  printArray(array,size);
}
```

## Output:
![Screenshot 2025-04-30 093643](https://github.com/user-attachments/assets/c5a3da78-0bf4-45dd-a0ec-7bef6a308a84)



## Result:
Thus, the C program to display the elements of the priority queue after insertion and deletion operation is implemented successfully
