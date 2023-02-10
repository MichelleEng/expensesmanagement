# expensesmanagement
#include <stdio.h> 

int main() 
{ 
    float expense; 
    float totalExpenses = 0;
 
    printf("Enter expense amount: "); 
    scanf("%f", &expense); 
 
    // Keep looping until user enters a negative value 
    while (expense >= 0) { 
        totalExpenses += expense; 
 
        printf("Enter expense amount: "); 
        scanf("%f", &expense); 
    } 
 
    printf("Total expenses: %.2f\n", totalExpenses); 
 
    return 0; 
}

