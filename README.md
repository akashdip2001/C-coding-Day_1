# C-cording-Day-Day_1-
C cording Day Day_1 

---
1) Write a C program to display "AOT"
```
       #include<stdio.h>
       int main()
       {
        printf("AOT");
       return 0;
       }
 ```
 ---
 2) Write a C program to display your name
 ```
       #include<stduo.h>
       int main()
       {
          printf("Akashdip Mahapatra");
          return 0;
          }
```
---
3) Write a C program to display following - <br/>
  AOT <br/>
  B.Tech <br/>
  1st Sem <br/>
  ```
  #include<stdio.h>
  int main()
  {
       printf("\tAOT \n \tB.Tech \n \t1st Sem"); 
       // \n for next line & \t for little space.
       return 0;
   }
   ```
---
4) Write a C program to take two integers from user and also show their sum.   
   ```
   #include<stdio.h>
   int main()
   {
       int a,b;
        printf("Enter Two integers \n");
        scanf("%d %d",&a,&b);
   
       printf("Two integers is %d & %d and there Sum is %d",a,b,a+b);
       
       //or
       //int c = a+b;
       //printf("Two integers is %d & %d and there Sum is %d",a,b,c);
       
   return 0;
   }
   ```
---
5) same ⬆️ ( c = a-b )
---
6) Write a C program to take a floating-point number from user and show its value.
``` #include<stdio.h>
   int main()
   {
       float a,b;
        printf("Enter Two integers \n");
        scanf("%f %f",&a,&b);
   
       printf("Two integers is %f & %f ",a,b);
       print 0;
    }
 ```
 ---
 7) Write a C program to take a character variable from user and show its value.
 ```
       #include<stdio.h>
       int main()
       {
              char name;
              printf("Enter your name \n");
              scanf("%c",&name);
       
              printf("The first later of your name is %c",name);
       return 0;
       }
       
