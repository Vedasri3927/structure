	#include <stdio.h>

struct Employee {
    int id;
    float salary;
};
int main() {
    struct Employee e;

    printf("25331A05D6\n");
    
    printf("Enter Employee ID:\n");
    scanf("%d",&e.id);
    printf("Enter Salary:\n");
    scanf("%f", &e.salary);
    printf("\nEmployee Details\n");
    printf("ID: %d\n",e.id);
    printf("Salary: %.2f\n",e.salary);
    return 0;
}
