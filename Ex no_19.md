# EX 19 C program to perform basic left and right shift operations on a given integer and display the result.
## AIM:
To write a C program to perform basic left and right shift operations on a given integer and display the result.

## Algorithm
1. Assign the value 22 to a variable.
2. Perform a left shift by 1 bit and store the result.
3. Perform a right shift by 1 bit and store the result.
4. Print the original, left-shifted, and right-shifted values.
5. End the program.
 

## Program:
```
/*
C program to perform basic left and right shift operations on a given integer and display the result.
Developed by: KAMALI.S
RegisterNumber:  212222060109
#include <stdio.h>

int main() {
    int num = 22; // Original number
    int leftShift, rightShift;

    // Perform left shift (multiply by 2)
    leftShift = num << 1;

    // Perform right shift (divide by 2)
    rightShift = num >> 1;

    printf("Original number: %d\n", num);
    printf("After left shift (<<1): %d\n", leftShift);
    printf("After right shift (>>1): %d\n", rightShift);

    return 0;
}

*/
```

## Output:

![image](https://github.com/user-attachments/assets/e4f085c3-2b2f-4b25-8088-5a72122e7825)


## Result:
Thus the program was executed and the output was verified successfully.
