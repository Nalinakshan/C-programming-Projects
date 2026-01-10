#include<stdio.h>
#include <ctype.h>

int main(){
    printf("\n-----------------------------------------------\n");

    char type;
    float itemp;
    float otemp;

    printf("\nEnter which scale you want to use (C or F): ");
    scanf("%c", &type);
    type = toupper(type);
    printf("\nEnter Temperature: ");
    scanf("%f", &itemp);

    if (type == 'C')
    {
        otemp = itemp*1.8 + 32;
        printf("The temperature in Fahrenheit is: %f \n", otemp);
    }
    else if (type == 'F')
    {
        otemp = ((itemp-32)*5)/9;
        printf("The temperature in Celsius is: %f \n", otemp);
    }
    else
    {
        printf("Enter a valid Unit of temperature!\n");
    }
    return 0;
}
