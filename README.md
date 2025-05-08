// print Hello World 

#include<stdio.h>
int main(){
    printf("Hello World");
}

// check number is Prime 

#include<stdio.h>
int main(){
    int a,flag=1;
    scanf("%d",&a);
    for(int i=2;i<=sqrt(a);i++){
       if(a%i==0){
          printf("Not Prime");
          flag=0;
          return 0;
        }
    }
    if(flag)
    printf("Prime");
}

// sum of all even numbers between 1 and 100

#include<stdio.h>
int main(){
    int a,sum=0;
    scanf("%d",&a);
    for(int k=1;k<=100;k++){
       if(k%2==0){
           sum+=k;
       }
    }
    printf("%d",sum);
}

// swap two numbers without using a third variable

#include<stdio.h>
int main(){
    int a,b;
    scanf("%d %d",&a,&b);
    a=a+b;
    b=a-b;
    a=a-b;
    printf("%d %d",a,b);
}
