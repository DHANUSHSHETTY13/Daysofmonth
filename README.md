#include<stdio.h>
int main()
{
    int n;

    printf("ENTER THE NUMBER B/W 1 - 12 =");

    scanf("%d",&n);

    if(n==1||n==3||n==5||n==7||n==9||n==11)

        printf("31 DAYS");

    else if(n==4||n==6||n==8||n==10||n==12)

        printf("30 DAYS");

    else if(n==2)

        printf("28 or 29 DAYS");
}

