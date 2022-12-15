## Program13(a) : Write a program to show the use of break statement
```c
#include <stdio.h>
int main() 
{
int i = 0;
while (i < 10) 
{
if (i == 4) 
{
break;
}
printf("%d\n", i);
i++;
} 
return 0;
}
```
**Output** :
```
0
1
2
3
```
## Program13(b): Write a program to show the use of continue statement
```c
#include <stdio.h>
int main() 
{
int i = 0;
while (i < 10) 
{
if (i == 4) 
{
i++;
continue;
}
printf("%d\n", i);
i++;
} 
return 0;
}
```
**Output**:
```
0 1 2 3 5 6 7 8 9
```

