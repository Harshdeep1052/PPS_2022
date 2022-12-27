## Program35: To write a code to understand the use of strcat function
```c
#include <stdio.h>
#include<string.h>
int main()
{
char a[50] = "The fox ";
char b[50] = "jumped";
strcat(a,b);
printf("%s\n",a);
return 0;
}
```
**Output**: 
```
The fox jumped
```
