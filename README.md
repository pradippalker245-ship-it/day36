# day36
my c langauge pratices 
#include <stdio.h>

int add(int, int);   // Declaration

int main()
{
    int result;

    result = add(10, 20);   // Function Call

    printf("%d", result);

    return 0;
}

int add(int a, int b)      // Definition
{
    return a + b;
}
