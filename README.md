# convert-tempreture-fahrenheit-to-celcius-using-function-in-c
#include<stdio.h>
float convertTemp(float c);
int main()
{
   float far=convertTemp(0);
    printf("\n%f",far);
    return 0;
}
float convertTemp(float c)
{
    float far=c*(9.0/5.0)+32;
    return far;
}
