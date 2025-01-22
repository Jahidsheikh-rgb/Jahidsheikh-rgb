// Online C compiler to run C program online
#include <stdio.h>

int main() {
    int x,y;
    scanf("%d",&x);
    scanf("%d",&y);
    
    if(x==y){
        printf("Number1 and Number2 are equal");
    }
    else
    printf("Number1 and Number2 are not equal");


    return 0;
}

2
// Online C compiler to run C program online
#include <stdio.h>

int main() {
    int x,y;
    scanf("%d",&x);
    //scanf("%d",&y);
    
    if(x%2==0){
        printf("%d is an even integer",x);
    }
    else
   printf("%d is an odd integer",x);


    return 0;
}

3

// Online C compiler to run C program online
#include <stdio.h>

int main() {
    int x,y;
    scanf("%d",&x);
    //scanf("%d",&y);
    
    if(x>0){
        printf("%d is a positive number",x);
    }
    else
     printf("%d is a negative number",x);

    return 0;
}

4
// Online C compiler to run C program online
#include <stdio.h>

int main() {
    int x,y;
    scanf("%d",&x);
    //scanf("%d",&y);
    
    if(x%4==0&&x%100!=0||x%400==0){
        printf("%d is a leap year",x);
    }
    else
     printf("%d is a  not leap year",x);

    return 0;
}

5
// Online C compiler to run C program online
#include <stdio.h>

int main() {
    int x,y;
    scanf("%d",&x);
    //scanf("%d",&y);
    
    if(x>=18){
        printf("Congratulation! You are eligible for casting your vote.",x);
    }
    else
     printf("You are not eligible for casting your vote",x);

    return 0;
}
6
// Online C compiler to run C program online
#include <stdio.h>

int main() {
    int x,n;
    scanf("%d",&x);
    //scanf("%d",&y);
    
     if (x > 0) {
        n = 1;
    } else if (x == 0) {
        n = 0;
    } else {
        n = -1;
    }
    printf("The value of n = %d",n);

    return 0;
}

7

// Online C compiler to run C program online
#include <stdio.h>

int main() {
    int x,n;
    scanf("%d",&x);
    //scanf("%d",&y);
    
     if (x < 150) {
        printf("The person is Dwarf.");
    }
    else if (x >=150 && x<165) {
        printf("The person is average.");
    } 
    else if (x>=165){
        printf("The person is taller.");
    }
    else 
    printf("The person is abnormal.");
    

    return 0;
}

8
// Online C compiler to run C program online
#include <stdio.h>

int main() {
    int a,b,c;
    scanf("%d",&a);
    scanf("%d",&b);
    scanf("%d",&c);

    
     if (a>=b&&a>=c) {
        printf("%d is largast number.",a);
    }
    else if (b>=c&&b>=c) {
        printf("%d is largast number.",b);
    } 
    else {
        printf("%d is largast number.",c);
    }
  
    

    return 0;
}
9
// Online C compiler to run C program online
#include <stdio.h>

int main() {
    int a,b,c;
    scanf("%d",&a);
    scanf("%d",&b);
    //scanf("%d",&c);

    
     if (a>0&&b>0) {
        printf("The coordinate point (%d,%d ) lies in the First quadrant.",a,b);
    }
    else if (a<0&&b>0) {
        printf("The coordinate point (%d,%d) lies in the 2nd quadrant.",a,b);
    } 
    else if (a<0&&b<0) {
        printf("The coordinate point (%d,%d) lies in the 3rd quadrant.",a,b);
    } 
    else if (a>0&&b<0) {
        printf("The coordinate point (%d,%d) lies in the 4th quadrant.",a,b);
    } 
  
    

    return 0;
}
10
// Online C compiler to run C program online
#include <stdio.h>

int main() {
    int a,b,c;
    scanf("%d",&a);
    scanf("%d",&b);
    scanf("%d",&c);

    
     if (a>=65&&b>=55&&c>=50 &&((a+b+c)>=190||(a+b)>=140)) {
        printf("The candidate is eligible for admission."); }
    
    else
      printf("The candidate is not eligible for admission.");

  
    

    return 0;
}

11
// Online C compiler to run C program online
#include <stdio.h>

int main() {
    double  a,b,c;
    scanf("%lf",&a);
    scanf("%lf",&b);
    scanf("%lf",&c);
    
    double x = b*b - 4*a*c;

    
     if (x<0&&a==0) {
        printf(" Root are imaginary;."); }
    
    else {
        double y = (-b - x)/2*a;
        double z = (-b + x)/2*a;
        
        printf("X = %lf",y);
        printf("X = %lf",z);
        
    }
     

  
    

    return 0;
}

12
#include <stdio.h>

int main() {
    int a, b , c;
    float avg , p;
    scanf("%d %d %d",&a, &b , &c);
     avg = a+b+c;
     p = avg /3;
     
     printf("avg is %0.2f",avg);
     printf("per..  is %0.2f",p);
      if (p >=80) printf(" 1st");
      else printf(" 2nd");


    return 0;
} 

13

// Online C compiler to run C program online
#include <stdio.h>

int main() {
    int a ; 
     scanf("%d", &a);

     
     
     if(a<0) printf("Freezing weather");
     else if(a>0 &&a<10) printf("Very Cold weather");
      else if(a>10 &&a<20) printf("Cold weather");
       else if(a>20 &&a<30) printf("Normal in Temp");
        else if(a>30 &&a<40) printf("Its Hot");
         else if(a>=40) printf("Its Very Hot");

    return 0;
}

14

#include <stdio.h>

int main() {
    int a, b ,c ; 
     scanf("%d %d %d", &a, &b, &c);
if (a == b && b ==c) printf("equilateral triangle");
else if (a != b && b !=c&& c != a) printf("scalene triangle ");
else  printf("isosceles triangle ");




    return 0;
}

15

#include <stdio.h>

int main() {
    int a, b, c;
    scanf("%d %d %d", &a, &b ,&c);
    int x = a+b+c;
    if (x == 180) printf(" The triangle is valid.");
    else printf("The triangle is not valid.");
    return 0;
}
16
#include <stdio.h>

int main() {
    int a, b, c;
    scanf("%d %d %d", &a, &b ,&c);
    int x = a+b+c;
    if (x == 180) printf(" The triangle is valid.");
    else printf("The triangle is not valid.");
    return 0;
}

17

[06:38, 1/22/2025] Jahid Sheikh: Accha pakhi
[06:49, 1/22/2025] Jahid Sheikh: #include <stdio.h>

int main() {
    char a;
    scanf("%c ", &a); 

    if (a>='A' && a<='Z' || a>='a' && a<='z') 
        printf("character.");
    else if (a>=0 && a<=9) 
        printf("digit");
    else 
        printf("special character "); 
    return 0;
}
18

#include <stdio.h>

int main() {
    char a;
    scanf("%c", &a); 

    if (a=='A' || a=='E' || a=='I' || a=='O'|| a=='U'|| a=='a' || a=='e' || a=='i' || a=='o'|| a=='u'){
        printf("vowel "); }
    
    else 
        printf(" consonant"); 
    return 0;
}

19

#include <stdio.h>

//. Write a C program to calculate profit and loss on a transaction.
int main() {
    int b , a, x, y;
    scanf("%d %d", &a, &b); 
    
     y = b - a; 
    
    if (y >=0) printf("profit");
    
    else printf("loss");
         
        
        
    
   
    return 0;
}

20
#include <stdio.h>

int main() {
    int customer_id, units;
    char customer_name[50];
    float bill, surcharge, total_bill;

   
    printf("Enter Customer ID: ");
    scanf("%d", &customer_id);

    printf("Enter Customer Name: ");
    scanf(" %[^\n]", customer_name); 

    printf("Enter units consumed: ");
    scanf("%d", &units);

   
    if (units <= 199) {
        bill = units * 1.20;
    } else if (units >= 200 && units < 400) {
        bill = units * 1.50;
    } else if (units >= 400 && units < 600) {
        bill = units * 1.80;
    } else {
        bill = units * 2.00;
    }

   
    if (bill > 400) {
        surcharge = bill * 0.15;
        bill += surcharge;
    }

    
    if (bill < 100) {
        bill = 100;
    }

    
    printf("\nCustomer ID: %d\n", customer_id);
    printf("Customer Name: %s\n", customer_name);
    printf("Units Consumed: %d\n", units);
    printf("Bill Amount: Rs. %.2f\n", bill);

    return 0;
}
21
#include <stdio.h>

int main() {
    char a;
    float x;
    scanf("%c", &a);
//     E	Excellent
// V	Very Good
// G	Good
// A	Average
// F	Fail

    if (a == 'E') {
        printf("Excellent");
    } else if (a == 'V') {
        printf("Very Good");
    } else if (a == 'G') {
        printf("Good");
    } else if  (a == 'A') {
        printf("Average");
    }
    else if  (a == 'F') {
        printf("fail");
    }

    

    return 0; }
    
