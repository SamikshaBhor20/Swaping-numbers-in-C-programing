// # Swaping-numbers-in-C-programing
// Swapping of 2 number without using a temporary variables in C programming.

#include<stdio.h>
int main()
{
  int a,b;
  printf("Enter any two numbers(before swaping): ");
  scanf("%d%d",&a,&b);
  a=a+b;
  b=a-b;
  a=a-b;
  printf("Numbers after swaping: ");
  return 0;
 }
  
