# HCF-GCD-in-C
#include <stdio.h>
int main()
{   int i,a,b,min,abtakkahcf;
   printf("Enter two numbers for checking HCF:\n");
   scanf("%d %d",&a,&b);
   min=a<b?a:b;
    for(i=1;i<=min;i++)
   {
       if(a%i==0 && b%i==0)
       abtakkahcf=i;
   }
   printf("The HCF OF %d and %d is %d",a,b,abtakkahcf);
    return 0;
}
