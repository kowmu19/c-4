# c-4
square no.pattern 1

#include <stdio.h>
int main()
{
    int n;
    printf("enter the size of matrix: ");
    scanf("%d",&n);
    for(int i=1;i<=n;i++){
        for(int j=1;j<=n;j++){
            printf("%d",i);
        }
        printf("\n");
    }
    return 0;
}

