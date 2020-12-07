# SWAPPING-OF-2-NUMBERS-.
A C program To perform the swapping of 2 numbers without using a temporary variable.

#include<stdio.h>
int main()
{
 int a=10,b=20;
 printf("The values of a and b before swapping of 2 numbers \n");
 printf("The value of a is :%d \n",a);
 printf("The value of b is :%d \n",b);
 a=a+b;
 b=a-b;
 a=a-b;
 printf("The values of a and b after swapping of 2 numbers \n");
 printf("The value of a is :%d \n",a);
 printf("The value of b is :%d",b);
}
