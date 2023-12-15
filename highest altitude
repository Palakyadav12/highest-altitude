#include<conio.h>
#include<stdio.h>
void main()
{
    int a[1001],i,n,l=0,sum=0 ;
    printf("Enter the total no. of Atitudes:");
    scanf("%d",&n);
    for(i=0;i<n;i++)
    {
        printf("Enter the Altitude %d:",i+1);
        scanf("%d",&a[i]);
    }
    for(i=0;i<n;i++)
    {
        sum=sum+a[i];
        if (l<sum)
        {
            l=sum;
        }
    }
    printf("Highest Altitude is %d",l);
    getch();
}
