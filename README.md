#include<stdio.h>
#include<conio.h>
void main()
{
long long n;
int dec=0,i=0,rem,b=1;
clrscr();
printf("Enter a binary number: ");
scanf("%lld",&n);
while(n!=0)
{
rem=n%10;
dec+=rem*b;
n/=10;
b=b*2;
}
printf("decimal=%d",dec);
getch();
}
