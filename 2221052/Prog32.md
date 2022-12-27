## Program32: Write a program to perform binary search
```c
#include <stdio.h>
int main()
{
int len,target;
int left,right,mid;
printf("Enter size of array\n");
scanf("%d",&len);
int arr[len];
printf("Enter elements [must be in ascending order]\n");
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
left=0;
int i = 0;
right=len-1;
while(left!=right)
{
mid = (left+right)/2;
if(arr[mid]==target)break;
else if(arr[mid]>target)
{
right=mid-1;
}
else
{
left=mid+1;
}
i++;
if(i>10)break;
}
printf("\nLocation of %d in array = %d\n",target,mid);
}
```
**Output**: 
```
Enter size of array 5
 Enter elements [must be in ascending order] 
Enter element at index 0 -> 12 
Enter element at index 1 -> 13
 Enter element at index 2 -> 14
 Enter element at index 3 -> 17 
Enter element at index 4 -> 20
 Enter element to search -> 14 
Entered array is : 12 13 14 17 20 
Location of 14 in array = 2
```
