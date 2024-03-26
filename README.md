# 202444093_C

중첩 반복문

#include <stdio.h>
int main()
{
    for(int i=5; i>=1; i--)
    {
        for(int j=1; j<=i; j++)
        {
            printf("*");
        }
        printf("\n");
    }
}

#include <stdio.h>
int main()
{
    for(int i=5; i<=5; i++)
    {
        for(int j=1; j<=i; j++)
        {
            printf("*");
        }
        printf("\n");
    }
}

#include <stdio.h>
int main()
{
    for(int i=5; i<=5; i++)
    {
        for(int j=1; j<=5; j++)
        {
            printf("*");
        }
        printf("\n");
    }
}
