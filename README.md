# EX-02-2a-Looping
## AIM:
Write a C program to print  even numbers ranging from M to N (including M and N values).
## ALGORITHM:
1. Declare two integer variables to store the values of M and N.
2. Use the printf function to prompt the user to enter the values of M and N.
3. Use the scanf function to read the values of M and N from the user.
4. Use a loop (for or while) to iterate from M to N.
5. Inside the loop, check if the current number is even.
6. If the current number is even, print it.
7. Continue the loop until you have iterated through all numbers from M to N.
## PROGRAM:
```
#include<stdio.h>
int main()
{
    int a,i,b;
    scanf("%d %d",&a,&b);
    for(i=a;i<=b;i++)
    {
        if(i%2==0)
        printf("%d ",i);
    }
 
    return 0;
}
```
## OUTPUT:
![image](https://github.com/Yogabharathi3/EX-02-2a-Looping/assets/118899387/65f8dd73-a4fa-4538-9cf6-ed8dfc7ba009)

## RESULT:
Thus the program to print  even numbers ranging from M to N (including M and N values) has been executed successfully
