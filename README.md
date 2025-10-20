# Program-5-a
## C-Module 5
## EX_NO-05)a)-Pointers
### Date: 19-10-2025
### Name: Anish D
### Register Number:25010086
## AIM:
Write a C program to check whether the number 8887 is even number or odd number using pointers.
## ALGORITHM:
1. Start the program.
2. Declare an integer variable to store the input number and an integer pointer variable.
3. Read the integer value from the user using scanf.
4. Assign the address of the integer variable to the pointer.
5. Check if the value pointed to by the pointer is even using the modulus operator (%):

    a. If it is even, print "<number> is even."

    b. Otherwise, print "<number> is odd."

6. End the program.
## PROGRAM:
```
#include<stdio.h>
int main()
{
    int num,*p1;
    scanf("%d",&num);
    p1=&num;
    if(*p1%2==0)
    printf("%d is even.",num);
    else
    printf("%d is odd.",num);
}
```
## OUTPUT:
<img width="842" height="289" alt="Screenshot 2025-10-20 083200" src="https://github.com/user-attachments/assets/32154267-7939-4bc5-84c7-1326442e306d" />

## RESULT:
Thus the program to check whether the number 8887 is even number or odd number using pointers has been executed successfully
