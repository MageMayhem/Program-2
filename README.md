#include <stdio.h>
int main (void) {
    int miles;
    float gallons = -1, mg, overall = 0, avg = 0;
    while (gallons != 0){
        printf("Enter gallons used : ");
        scanf("%f", &gallons);
        if (gallons == 0){
            printf("\n\n The overall miles/gallons was : %f\n", overall/avg);
            exit(0);
        }
        
        printf("Enter miles driven :");
        scanf("%d", &miles);
        mg = miles/gallons;
        printf("The miles/gallons for this tank was : %f\n", mg);
        overall += miles;
        avg += gallons;
    }
    return 0;
}
