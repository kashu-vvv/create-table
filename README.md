# create-table
#include<stdio.h>
void main()
{
    int i,j;
    for(i=1;i<=10;i++)
    {
        for(j=1;j<=10;j++)
        {
            if(i*j<10)
            {
                printf("0%d ",j*i);
            }else{
            printf("%d ",i*j);
        }}
    printf("\n");
    }
 }                                                            
