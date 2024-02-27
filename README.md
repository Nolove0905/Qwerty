#include <stdio.h>

int main()
{
    int x, y;

    printf("Введите значение x: ");
    scanf("%d", &x);

    y = (x + 5) / (x - 5);

    printf("Значение выражения  y = (x + 5) / (x - 5) равно: %d\n", y);

    return 0;
}
