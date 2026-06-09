# EX 16 C program to find minimum between three fraction numbers using conditional operator.
## DATE:
## AIM:
To write a C program to find minimum between three fraction numbers using conditional operator.

## Algorithm
Start.
Define a variables a,b,c,min.
Write program to find minimum numbers.
Read the value using scanf.
Ask the user to make an input.
Print out the answer.
End.
## Program:
```
#include <stdio.h>
int main() {
float a, b, c, min;
scanf("%f%f%f", &a, &b, &c);
min = (a < b) ? ((a < c) ? a : c) : ((b < c) ? b : c);
printf("Minimum between %.3f, %.3f and %.3f = %.3f\n",a,b,c, min);
return 0;
}
```

## Output:

<img width="1151" height="220" alt="image" src="https://github.com/user-attachments/assets/5eab7e2c-84e1-48c1-a312-3c1cd2072ca3" />


## Result:
Thus the program was executed and the output was verified successfully.
