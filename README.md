# program-2E
C module 2
EX NO-2)E)a C Program to print odd numbers that range from M to N (including M and N values) in reverse order
DATE:19/10/23
NAME:JADE ADRINA J
REF NO:25017000
AIM:TO WRITE C Program to print odd numbers that range from M to N (including M and N values) in reverse order
ALGORITHM:
1)Take n amd m as input from the user.2)run the numbers in reverse order using for loop.3) check if the number is not divisible by 2 using if condition.4)print the odd numbers using printf() function.
PROGRAM:
```
#include<stdio.h>
int main()
{
  int i,n,m;
  scanf("%d %d",&n,&m);
  for(i=m;i>=n;i--)
  {
      if(i%2!=0)
      {
          printf("%d ",i);
      }
  }
  return 0;
}
```
OUTPUT:
<img width="555" height="189" alt="Screenshot 2025-10-19 210711" src="https://github.com/user-attachments/assets/96a30f77-787f-45ee-a94b-f5a9f756c5f0" />
RESULT:
Thus,a  C Program to print odd numbers that range from M to N (including M and N values) in reverse order.
