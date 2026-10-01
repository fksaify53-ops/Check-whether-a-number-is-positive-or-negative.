# Check-whether-a-number-is-positive-or-negative.
only using 'if' condition.

//Write a program to check whether a number is positive or negative using only if condition.
#include <stdio.h>

int main()
{
  int n;
  printf("Enter the number: ");
  scanf("%d",&n);
    if(n>=0){
      printf("n is positive");
    }
    if(n<0){
        printf("n is negative");
    }

    return 0;
}