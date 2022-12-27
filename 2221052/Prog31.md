## Program31: Write a program to create
```c
#include <stdio.h>
int main()
{
int len,target,ind;
printf("Enter size of array\n");
scanf("%d",&len);
int arr[len];
printf("Enter elements:\n");
for(int i=0;i<len;i++)
{
printf("Enter element at index %d -> ",i);
scanf("%d",&arr[i]);
}
printf("Enter element to search -> ");
scanf("%d",&target);
printf("\nEntered array is :\n");
for(int i=0;i<len;i++)
{
printf("%d\t",arr[i]);
}
printf("\n");
for(int i=0;i<len;i++)
{
if(arr[i] == target)ind=i;
}
printf("\nLocation of %d in array = %d\n",target,ind);
}
return 0;
}
```
**Output**:
```
 Enter size of array 4 
Enter elements: Enter element at index 0 -> 22
 Enter element at index 1 -> 44 
Enter element at index 2 -> 55 
Enter element at index 3 -> 66
 Enter element to search -> 44 
Entered array is : 22 44 55 66 
Location of 44 in array = 1
```
