#include<stdio.h>
int add(int a,int b)
{int c;
c=a+b;
return c;
}
int main()
{int a,b,sum;
printf("enter two integers:");
scanf("%d%d",&a,&b);
sum=add(a,b);
printf("sum of %d and %d is:%d",a,b,sum);
return 0;
}