#include <stdio.h>
Int main() {
    Int num, originalNum, remainder, result = 0;
    Printf(“Enter a three-digit integer: “);
    Scanf(“%d”, &num);
    originalNum = num;

    while (originalNum != 0) {
       // remainder contains the last digit
        Remainder = originalNum % 10;
        
       Result += remainder * remainder * remainder;
        
       // removing last digit from the orignal number
       originalNum /= 10;
    }

    If (result == num)
        Printf(“%d is an Armstrong number.”, num);
    Else
        Printf(“%d is not an Armstrong number.”, num);

    Return 0;
}
