# switch.-c
Calculator

#include<stdio.h>
#include<conio.h>

 int main ()
 { 
    int a,b,addition,substraction,multiplication,choice,exit;
    printf ("\n1.addition");
       printf ("\n2.substraction");
      printf ("\n3.multiplication");
       printf("\n4. exit");
       
        printf ("\n\n enter your choice");
      scanf("%d",&choice);
      
     switch (choice)
  {   
   case 1: 
      
        printf("enter two no :");
        scanf("%d%d",&a,&b);
        
        addition= a+b;
        printf("solution : %d",addition);
   break ;
   
      case 2: 
     
        printf("enter two no :");
        scanf("%d%d",&a,&b);
        
        substraction= a-b;
        printf("solution: %d",substraction);
   break;
   
      case 3: 
   
        printf("enter two no :");
        scanf("%d%d",&a,&b);
        
        multiplication= a*b;
        printf("solution : %d",multiplication);
        
   
 } 
 
 }
 
