# first-n-even-no.
#include <stdio.h>

int printEven(int num){ 
    printf("%d\n", num);
    if (num == 10) { 
        return num;
    }
    else{ 
        return printEven(num + 2); 
    }
}
