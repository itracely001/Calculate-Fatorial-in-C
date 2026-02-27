// Calculate-Fatorial-in-C
//you can enter a number like a user to calculte factorial
#include <stdio.h>
int main () {
    int a , b = 1;
    printf("Enter your value: ");
    scanf("%d",&a);
    for(int c = 1; c <= a ;c ++){
        b *= c ;
    }
    printf("The value of C: %d",b);
}
