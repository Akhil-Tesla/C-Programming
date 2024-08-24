# C Programming
Programs for C Language 



          #include<stdio.h>
           int main()
          {
            printf("Hello World\n");
             return 0;
           }



Include function includes the header file which is <stdio.h>
Stdio stands for standard Input and Output  ( .h ) represents the header file


The int  defines main functions Type 
 Int  literally means integer returns
 something . in the int  main function we can include any type of the data type
Like float, double, char etc but best option is Void which returns Null   0

**Input and Output**


printf is used to display the output of the given data in C 


          #include<stdio.h>
           int main(){
            int a=3,b=6;
            int x=a+b;
            printf("sum = %d",x);
            }

Scanf is used to take input from the user 
To access the address of the input C uses ampersand (&) to store the address.

FORMAT SPECIFIERS 

•To access the address of the given data and to write the data into variables C uses these format specifiers for assigning address 
For int %d or %i
    Float %f
    String %s
    Char %C

Program 

          #include<stdio.h>
           int main(){
            int a =1;
            float b=2;
            char c='a';
           printf(" %d\n%f\n%c",a,b,c);
           }

**Manipulation of data types** 

To do math in C we use int , float data types 
 * Addition (+)
 * Subtraction(-)
 * Multiplication(*)
 * Division (/)
 * floor Division(//)

program 

        #include<stdio.h>
        int main(){
          int a=3,b=2;
          printf("sum = %d",a+b);
          printf("Subtraction = %d",a-b);
          print("Multiple = %d",a*b);
          float x= 36.14;
          float y= 6.2;
           printf("division =%f",x/y);

           return 0;
        }


- For taking input we use scanf function to take input from user 

     
            #include<stdio.h>
              int main(){
             printf("Enter two numbers ");
            int a , b,c; //declaring variables 
            scanf("%d %d",&a,&b);
               c=a+b;
            printf("\nsum of numbers is %d",c);
            }
# Operators

The operators for manipulating data in C divided into 
1.Arithmetic operatord 
2.Conditional operators
3.Logical operators 
4.Bitwise operators 


# Variables

*Variables* : Anything that stores the value .

* int cars= 10 ,
* float speed = 143.789 ,
* double pi = 3.1428579631274639 ,
* char letter ='L',
* string = "I am Ironman";

A variable can be anything that can store the values of specified format 

## Control flow

* if
* else if
* else
* switch cases


### Loops
* for loop
* while loop
* do while loop
