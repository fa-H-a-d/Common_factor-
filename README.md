#include <stdio.h>

int main() {
    int num1, num2;

  
    printf("Enter the first number: ");
    scanf("%d", &num1);
    printf("Enter the second number: ");
    scanf("%d", &num2);

    printf("Common factors of %d and %d are:\n", num1, num2);

    
    for (int i = 1; i <= num1 && i <= num2; i++) {
        if (num1 % i == 0 && num2 % i == 0) {
            printf("%d\n", i);
        }
    }

    return 0;
}
