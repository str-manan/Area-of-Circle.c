#include <stdio.h>

int main()
{
    float radius, area;

    printf("Enter the radius: ");
    scanf("%f", &radius);

    area = PI * radius * radius;

    printf("Area of the circle = %.2f\n", area);

    return 0;
}# Area-of-Circle.c