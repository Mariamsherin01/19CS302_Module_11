# EX 53 C program to Count the number of words in a Sentence.
## AIM:
To write a C program to Count the number of words in a Sentence.

## Algorithm
1. Read the input sentence as a string.
2. Initialize a word count variable to 0.
3. Traverse through each character of the string:
   - Whenever a space character is encountered, increment the word count.
4. After traversal, if the string is not empty, add 1 to the word count (for the last word).
5. Output the total word count.


## Program:
```
/*
C program to Count the number of words in a Sentence.
Developed by: Mariam Sherin
RegisterNumber: 212222060143
#include<stdio.h>
#include<string.h>
int main()
{
 int c=1;
 char x[50];
 scanf("%[^\n]",x);
 for(int i=0;i<strlen(x);i++)
 {
     if(x[i]==' ')
     {
         c++;
     }
 }
 printf("Total number of words in the string is :%d",c);
}
*/
```

## Output:

![image](https://github.com/user-attachments/assets/111a85dc-6f2b-4c44-8475-340ba070b4b6)


## Result:
Thus the program was executed and the output was verified successfully.
