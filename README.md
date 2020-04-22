# Project
#include <stdio.h>

//Compiler version gcc  6.3.0

int main()
{
  int n,num1,num2, result;
  char option;
  do{
   printf("\n What operation do you want to do?\n");
   printf("press 1 for addition\n");
   printf("press 2 for subtraction\n");
   printf("press 3 for multiplication\n");
   printf("press 4 for division\n");
   scanf("%d",&n);
   printf("Enter the first number\n");
   scanf("%d",&num1);
   printf("Enter the second number\n");
   scanf("%d",&num2);
   switch(n)
   {
    
   case 1: result=num1+num2;
   printf("addition of two numbers is %d", result);
   break;
   case 2: result=num1-num2;
   printf("subtraction of two numbers is %d", result);
   break;
   case 3: result=num1*num2;
   printf("multiplication of two numbers is %d", result);
   break;
   case 4: result=num1/num2;
   printf("division of two numbers is %d", result);
   break;
   default:printf("wrong input");
  }
  
  
  printf("\n If you want to continue press Y");
  
 scanf("%s",&option);
  
  }
  
   
  while(option='Y');
  getch();
  return 0;
  
  }
    
