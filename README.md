#include <stdio.h>

int main() {
    int A, r;
    printf("Enter the radius of a circle: ");
    scanf("%d", &r);
    A = 3.1416 * (r * r);
    printf("The area of the circle is: %d\n", A);
    return 0;
}
