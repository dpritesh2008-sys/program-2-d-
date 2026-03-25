# program-2-d-
C module 2
EX NO:2-d) Calculate the sum of digits of a number. 
Date:25/3/2026
Name: Ritesh DP 
Ref no: 25015366

AIM: To write a C program to calculate the sum of digits of a number.

ALGORITHM:

1) Get a input number from the user.
2) separate the digits using modulo operator amd add the digits using loop.


PROGRAM:
```
#include<stdio.h>
int main()
{
    int num,sum=0;
    scanf("%d",&num);
    do{
    sum+=num%10;
    num=num/10;}
    while(num>0);
    printf("%d",sum);
}
```
OUTPUT:
<img width="322" height="145" alt="Screenshot 2025-10-19 224317" src="https://github.com/user-attachments/assets/8d49f839-cf5e-4063-bfb6-ef76466c67d5" />

RESULT:
Thus the C program to find the sum of digits of a number is executed successfully.






