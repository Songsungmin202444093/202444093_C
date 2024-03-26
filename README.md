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

#include <stdio.h>
int main(void)
{
    short num1;
    int num2;
    long long num3;
    long num4

    printf("자료형의 크기를 구하는 함수 : sizeof( ) 함수\n");
    printf("1.short형 변수 : %d바이트\n", sizeof(num1));
    printf("2.int형 변수 : %d바이트\n", sizeof(num2));
    printf("3.long long형 변수 : %d 바이트 \n", sizeof(num3));
    printf("4.long형 변수 : %d 바이트 \n",sizeof(num4));
    printf("1바이트는 8비트입니다.\n");
    printf("4.short형 변수 : %d비트\n", sizeof(num1)*8);
    printf("5.int형 변수 : %d비트\n", sizeof(num2)*8);
    printf("6.long long형 변수 : %d비트\n", sizeof(num3)*8);
    return 0;

}

#include <stdio.h>
int main(void)
{
    unsigned short a,b, result;

    printf("unsigned  short형 유효 범위 : 0~65,535\n");
    printf("1.첫 번째 정수 입력 : ");
    scanf_s("%hu", &a);
    printf("두 번째 정수 입력 : ");
    scanf_s("%hu", &b);

    result = a - b;
    printf("뺄셈 연산 : %hu - %hu = %hu\n", a, b, result);
    return 0;

}
플로우
