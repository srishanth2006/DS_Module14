# Ex6 Dequeue Elements from Circular Queue
## DATE: 25.04.2025
## AIM:
To write a C program to delete three elements from the filled circular queue.

## Algorithm
1. Start the program.
2. Include the required libraries.
3. Check if the queue is empty and return if it is.
4. Follow the deletion logic for circular queue and return the deleted element.
5. End the program

## Program:
```
/*
Program to delete three elements from the filled circular queue
Developed by: SRISHANTH J
RegisterNumber: 212223240160
*/

int deQueue() {
    int element;
    if(isEmpty())
    {
        printf("Queue is empty\n");
        return -1;
    }
    else
    {
        element = items[front];
        if(front==rear)
        {
            front=-1;
            rear=-1;
        }
        else
        {
            front=(front+1)%SIZE;
        }
        return element;
    }
}
```

## Output:
![Screenshot 2025-04-30 093514](https://github.com/user-attachments/assets/29d42a2a-5365-44c4-9b85-472cfe3c82d9)


## Result:
Thus, the C program to delete three elements from the filled circular queue is implemented successfully.
