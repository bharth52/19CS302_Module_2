# EX 10 C program to find the factorial of a given number using a function with arguments and return type.

## AIM:
To write a C program to find the factorial of a given number using a function with arguments and return type.

## Algorithm
1.Read an integer input (a) from the user.
2.Initialize fact as 1.
3.Loop from i = 1 to a, multiplying fact by i in each iteration.
4.Store the final factorial value in fact.
5.Print the computed factorial value.    

## Program:
```
/*
Program to find the factorial of a given number using a function with arguments and return type.
Developed by: 
RegisterNumber:  
*/
#include <stdio.h>
void fact()
{
    int a,i;
    long int fact=1;
    scanf("%d",&a);
    for(i=1;i<=a;i++)
    {
        fact = fact*i;
        
    }
    printf("Factorial value is: %ld",fact);
    
    
}
int main()
    {
      fact();  
    }
```

## Output:
![image](https://github.com/user-attachments/assets/d5d7e561-6477-412e-ba50-7c2a1f079fa7)



## Result:
Thus the program was executed and the output was verified successfully.
