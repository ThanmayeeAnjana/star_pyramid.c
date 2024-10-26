#include <stdio.h>

int main() {
    int n,i,j;
    printf("Enter how many rows are needed\n");
    scanf("%d",&n);
   
   for(i=1;i<=n;i++)
   {
     for(j=n;j>=1;j--)
     {
       if(i>=j)
         printf(" *");
       else
         printf(" ");
     }
        printf("\n");
    }
    return 0;
   }
