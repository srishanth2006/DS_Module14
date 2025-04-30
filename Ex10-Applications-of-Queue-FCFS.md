# Ex10 Applications of Queue – FCFS
## DATE: 25.04.2025
## AIM:
To write a C function to calculate the turnaround time of each process given their burst time and waiting time in First Come first Serve scheduling algorithm.
## Algorithm
1. Start the program.
2. Include required libraries.
3. Run a for loop to iterate through the waiting time and burst time for all processes.
4. Use the formula to obtain the turn around time.
5. End the program.

## Program:
```
/*
Program to find and display the priority of the operator in the given Postfix expression
Developed by: SRISHANTH J
RegisterNumber: 212223240160
*/

#include <stdio.h>
int turnaroundtime( int proc[], int n,int burst_time[], int wait_time[], int tat[]) {
   int i;
   for(i=0;i<n;i++)
   {
       tat[i]=burst_time[i]+wait_time[i];
   }
   return 0;
}
```

## Output:
![Screenshot 2025-04-30 093252](https://github.com/user-attachments/assets/15e7b4ed-bb48-49a1-80a4-1fcc4e450fd3)



## Result:
Thus, the C function to calculate the turnaround time of each process given their burst time and waiting time in First Come first Serve scheduling algorithm is implemented successfully.
