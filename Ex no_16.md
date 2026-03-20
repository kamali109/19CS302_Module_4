# EX 16 C program to find minimum between three fraction numbers using conditional operator.
## AIM:
To write a C program to find minimum between three fraction numbers using conditional operator.

## Algorithm
1.Start and initialize a = -300, b = -400, c = 500.

2.Compare a and b using conditional operator: temp = (a < b) ? a : b.

3.Compare temp and c using conditional operator: min = (temp < c) ? temp : c.

4.Print min as the minimum number.

## Program:
```
/*
C program to find minimum between three fraction numbers using conditional operator.
Developed by: KAMALI.S
RegisterNumber: 212222060109
#include <stdio.h>

int main() {
    int a = -300, b = -400, c = 500;
    int min;

    // Using nested conditional operator to find the minimum
    min = (a < b) ? ((a < c) ? a : c) : ((b < c) ? b : c);

    printf("Minimum between %d, %d and %d = %d\n", a, b, c, min);

    return 0;
}


*/
```

## Output:

![image](https://github.com/user-attachments/assets/6c207600-3a5d-4ae7-8f1b-62ff32d6242f)


## Result:
Thus the program was executed and the output was verified successfully.
