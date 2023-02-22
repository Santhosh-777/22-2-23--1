#include<stdio.h>
int main()
{
    int i,even=0;
    i=1;
    while(i<=10)
    {
        printf("%d",i);
        if(i%2!=0)even++;
        i++;
    }
    printf("\neven sum=%d",even);
}
