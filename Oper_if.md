#include <stdio.h>
#include <Windows.h>

int main(void) {
    int var;
    printf_s("Enter an integer: ");
    scanf_s("%d", &var);
    if (var % 2 == 0 & var != 0); {
        printf_s("This integer is even");
    }
    if (var == 0); {
        printf_s("This ineger is ZERO");
    }
    else {
        printf_s("This integer is odd");
    }
}
