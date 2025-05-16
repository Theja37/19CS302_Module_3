# EX 15 C program that reads a one-dimensional array of integers and replaces all even elements with 'E'.
## AIM:
To write a C program that reads a one-dimensional array of integers and replaces all even elements with 'E'.

## Algorithm
1. Start.
2. Declare a array size value of type int.
3. Prompt the user to enter a value.
4. Read the value using scanf.
5. Initialize array elements.
6. Replace all even elements to E
7. End.

## Program:
```c
#include <stdio.h>
int main() {
 int arr[100], n;
 scanf("%d", &n);
 for (int i = 0; i < n; i++) {
 scanf("%d", &arr[i]);
 }
 for (int i = 0; i < n; i++) {
 if (arr[i] % 2 == 0)
 printf("E ");
 else
 printf("%d ", arr[i]);
 }
 printf("\n");
 return 0;
}
```

## Output:

![image](https://github.com/user-attachments/assets/2cd9652a-333c-42c5-8f33-a6491770b499)


## Result:
Thus the program was executed and the output was verified successfully.
