#include<stdio.h>
int main()
{
    int r,n,t=0,original;
    printf("Enter a number");
    scanf("%d",&n);
    original=n;
    do{
        r=n%10;
        t=t+r*r*r;
        n=n/10;

    }
    while(n!=0);
    if(t==original)
    printf("its a armstrong no.");
    else
    printf("its not armstrong no.");
    return 0;
}
