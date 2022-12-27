## Program37: To write a program of user defined function sum()
```c
#include<stdio.h>
int sum(int a, int b)
{
return a+b;	
}
int main()
{
int num1,num2,add;
printf("Enter 1st number: ");
scanf("%d",&num1);
printf("Enter 2nd number:");
scanf("%d",&num2);
printf("%d",sum(num1,num2));
return 0;
}
```
Output: 
```
Enter 1st number:2 
Enter 2nd number:4 6
```
