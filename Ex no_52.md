## Task

# Write a function int max_of_four(int a, int b, int c, int d) which reads four arguments and returns the greatest of them.

## Note

There is not built in max function in C. Code that will be reused is often put in a separate function, e.g. int max(x, y) that returns the greater of the two values.

## Input Format

Input will contain four integers - a,b,c,d , one on each line.

## Program

#include<stdio.h>
int max(int x,int y)
{
    int k;
    if(x>y)
    {
        k=x;
    }
    else
    {
        k=y;
    }
    return k;
}
int main()
{
    int a,b,c,d,f,g,h;
    scanf("%d",&a);
    scanf("%d",&b);
    scanf("%d",&c);
    scanf("%d",&d);
    f=max(a,b);
    g=max(c,d);
    h=max(f,g);
    printf("%d",h);
}

## Output Format

Print the greatest of the four integers.
Note: I/O will be automatically handled.

![image](https://github.com/user-attachments/assets/485e5236-4db6-4580-829e-06fd818167a5)

## Result

