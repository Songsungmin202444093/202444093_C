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

#include <stdio.h>
int main()
{
    int i=1;

    while(i<=5) // while(1) <- 항상 참이기에 무한반복 while ('a') 0 이외의 값은 모두 참이기에 무한반복
    
    {
        i++; // while 증감식 필수 없을 시 무한반복
        printf("%d", i);
    }
}

signed는 디폴트값 -127~128
unsigned는 0~255
