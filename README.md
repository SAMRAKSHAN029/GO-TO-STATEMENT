# GO-TO-STATEMENT
#include <stdio.h>

int main() {
    no:
    int number;
    printf("Enter an integer: ");
    scanf("%d", &number);
    if (number % 2 == 0) {
        printf("%d is even.\n", number);
    } else {
        printf("%d is odd.\n", number);
    }
goto no;
    return 0;
}
