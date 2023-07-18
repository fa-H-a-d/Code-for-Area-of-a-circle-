#include <stdio.h>

int main() {
    float A, r;
    printf("Enter the radius of a circle: ");
    scanf("%f", &r);
    
    A = 3.1416 * (r * r);
    printf("The area of the circle is: %f\n", A);
    
    return 0;
}
