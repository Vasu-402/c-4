#include <stdio.h>

int main() {
    int n,i,j,count=1;
    printf("enter the row of the matrix:");
    scanf("%d",&n);
    for (i=1;i<=n;i++)
    {
          for (j=1;j<=i;j++)
          {
              printf("%d\t",count++);
          }
              printf("\n");
    }
    return 0;
}
