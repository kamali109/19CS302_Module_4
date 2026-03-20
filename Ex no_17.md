# EX 17 C Program to copy a  string  into another string without using strcpy() ,and find the total number of words in a given strings using for loop.
## AIM:
To write a C Program to copy a  string  into another string without using strcpy() ,and find the total number of words in a given strings using for loop.

## Algorithm
1. Read the input string from the user.
2. Copy each character from the input string to another string using a for loop until the null character is reached.
3. Count the total number of characters in the string (excluding newline if present).
4. Null-terminate the copied string.
5. Print the copied string and the total character count.


## Program:
```
/*
 C Program to copy a  string  into another string without using strcpy() ,and find the total number of words in a given strings using for loop.
Developed by: KAMALI.S
RegisterNumber: 212222060109
#include <stdio.h>
#include <string.h>
 
int main()
{
  	char S1[100], S2[100];
  	int i,j,c=0;
 
   scanf("%[^\n]",S1);
   scanf("%[^\n]",S2);
   for(i=0;S1[i]!='\0';i++)
   {
       S2[i]=S1[i];
   }
   S2[i]='\0';
   printf("s2:%s",S2);
   for(j=0;S2[j]!='\0';j++)
   {
       c++;
   }
   printf("\nTotal words=%d",c);
}
*/
```

## Output:

![image](https://github.com/user-attachments/assets/038a05b4-ee59-4b67-acdb-f7d1a3d4b079)


## Result:
Thus the program was executed and the output was verified successfully.
