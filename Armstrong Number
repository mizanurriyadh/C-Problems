// C progmarame for checking Armstrong Number

#include <stdio.h>
#include <math.h>
int main() {
    int number, originalNumber, remainder, temp, result=0, digits=0;
    printf("Enter a number: ");
    scanf("%d", &originalNumber);
    temp = originalNumber;
    
    // Counting number of digits
    while(temp!=0){
        digits++;
        temp = temp/10;
    }
    number = originalNumber;
    // Armstrong Number Checking
    while(number!=0){
        remainder = number%10;
        result = result + pow(remainder,digits); 
        number = number/10;
    }
    
    if(result == originalNumber){
        printf("Yes \n");
    }else{
        printf("NO \n");
    }
}


/* Sample Output 1 -
   Enter a number: 378
   NO 
   
   Sample Output 2 -
   Enter a number: 371
   Yes
   
   Sample Output 2 -
   Enter a number: 8208
   Yes
*/
