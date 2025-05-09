#include<stdio.h>

int main() {
  int choice;
  do {
    printf("\nWelcome to Simple Calculator\n");
    printf("\nChoose one of the following options:");
    printf("\n1. Add");
    printf("\n2. Subtract");
    printf("\n3. Multiply");
    printf("\n4. Divide");
    printf("\n5. Modulus");
    printf("\n6. Power");
    printf("\n7. Exit");
    printf("\nNow, enter your choice: ");
    scanf("%d", &choice);
  } while (choice != 7);

  return 0;
}
    
