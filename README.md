# Math-Functions
#include<stdio.h>
#include<math.h>

int main(void){
    int x= 16;    //        SQRT simple sqrt's whats in the parenthesys
    int sum = sqrt(x);
    printf("%d\n", sum);

    int y = 20;
    int result = log(y);  //        simple logs what is parenthesys
    printf("%d\n", result);

    float z = 8.56;        //the ceil is the next whole number up from the integer
    int result2 = ceil(z);
    printf("The ceiling of %.2f is %d\n", z, result2);

    double a = 4.5;
    int result3 = floor(a);     //      similar to ceil it takes the closets lower whole number as floor
    printf("The floor of %.2f is %d\n", a, result3);

    double base = 5;
    double power = 3;  
    double result4 = pow(base, power);         //pow similar to all 1st number in() is base, 2nd number is what its to the power of
    printf("%.2f", result4);
}
