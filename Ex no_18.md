# EX 18 C program to find frequency of a character in the given input.
## DATE:
## AIM:
To write a C program to find frequency of a character in the given input.

## Algorithm
Start.
Define the required variable.
Write program to find frequency of a character.
Read the value using scanf.
Ask the user to make an input.
Print out the answer.
End
## Program:
```
#include<stdio.h> 
#include<string.h> 
int main()
{
int i,count=0,len;
char str[100],val[100]; 
scanf("%s %s",str,val); 
len=strlen(str); 
for(i=0;i<len;i++){
if(str[i]==val[0]) 
count++;
}printf("%d",count);}
```

## Output:

<img width="278" height="296" alt="image" src="https://github.com/user-attachments/assets/dec5e667-1ce5-4f85-b94c-4c7f680e4f8a" />


## Result:
Thus the program was executed and the output was verified successfully.
