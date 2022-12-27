## Program34: To write aa program to print right angled star pattern
```c
#include<stdio.h>
int main()
{
int i,j;
for (i=1;i<=4;i++)
{
for(j=0;j<i;j++)
{
printf("%c", '*');
}
printf("\n");
}
return 0;
}
```
**Output** :
```
*
**
***
****
```
