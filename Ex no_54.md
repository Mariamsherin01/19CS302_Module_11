# EX 54 C program to calculate_the_maximum function
## AIM:
To write a C program to calculate_the_maximum function

## Algorithm
1. Initialize max_and, max_or, max_xor to 0.
2. For each pair (a, b) where 1 ≤ a < b ≤ n:
    a. Compute and_val = a & b.
    b. If and_val < k and and_val > max_and, update max_and = and_val.
    c. Compute or_val = a | b.
    d. If or_val < k and or_val > max_or, update max_or = or_val.
    e. Compute xor_val = a ^ b.
    f. If xor_val < k and xor_val > max_xor, update max_xor = xor_val.
3. After checking all pairs, print max_and, max_or, and max_xor each on separate lines.



## Program:
```
/*
C program to calculate_the_maximum function
Developed by: Mariam Sherin
RegisterNumber: 212222060143
#include<stdio.h>
void calc(int n,int k){
    int a=0,o=0,x=0,i,j;
    for(i=1;i<=n;i++){
        for(j=i+1;j<=n;j++){
            if((i&j)>a && (i&j)<k){
                a=i&j;
            }
            if((i|j)>o && (i|j)<k){
                o=i|j;
            }
            if((i^j)>x && (i^j)<k){
                x=i^j;
            }
        }
    }
    printf("%d\n%d\n%d",a,o,x);
}
int main(){
    int a,b;
    scanf("%d%d",&a,&b);
    calc(a,b);
}
```
## Output

![image](https://github.com/user-attachments/assets/f1223147-e431-4469-a78f-fe5dad5358ee)


## Result
