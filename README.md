#include <stdio.h>

void main()
{
    int battery;

    printf("Enter battery percentage: ");
    scanf("%d", &battery);

    if (battery >= 50)
    {
        printf("Normal");
    }
    else
    {
        if (battery >= 20)
        {
            printf("Warning");
        }
        else
        {
            printf("Critical");
        }
    }

    return 0;
}
