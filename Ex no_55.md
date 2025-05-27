# EX 55 C program to create an array of size  dynamically, and read the values from stdin. 
## AIM:
To write a C program to create an array of size  dynamically, and read the values from stdin.

## Algorithm
1. Read an integer n (the number of elements in the array).
2. Dynamically allocate memory for n integers.
3. If memory allocation fails, exit the program with an error.
4. Read n integers from the user and store them in the array.
5. Initialize a sum variable to 0.
6. Iterate through the array:
   a. For each element, add it to the sum.
7. Print the final sum.
8. Free the dynamically allocated memory.


## Program:
```
/*
C program to create an array of size  dynamically, and read the values from stdin.
Developed by: Mariam Sherin
RegisterNumber: 212222060143
#include<stdio.h>
#include<stdlib.h>
int main()
{
    int n,sum=0;
    scanf("%d",&n);
    int *arr;
    arr=(int*)malloc(n* sizeof(int));
    for(int i=0;i<n;i++)
    {
        scanf("%d",&arr[i]);
        sum+=arr[i];
    }
    printf("%d",sum);
    free(arr);
}
*/
```

## Output:

![image](https://github.com/user-attachments/assets/0d34680f-bab9-44a9-9bb3-62c2e53580b2)


## Result:
Thus the program was executed and the output was verified successfully.
