#include <stdio.h>
int main (void) 
{
  int gal;
  float miles;
  float mpg;
  float avgmpg;
  int totalgal = 0;
  float totalmiles = 0;
  
  printf("Please enter the # of gallons (type -1 to end)\n");
  scanf("%d", &gal);
  while( gal != 1 ){
    
    printf("Please enter the # of miles driven\n");
      scanf("%.2f", &miles);
      
      mpg = miles/gal;
      totalgal = totalgal + gal;
      totalmile = totalmile + miles;
      
      printf("Your mpg is %.2f_\n", mpg)
      
      printf("Please enter the # of gallons (type -1 to end) \n");
      scanf("%d", &gal);
      }
      avgmpg = totalmiles/totalgal;
      
      printf("Your avgmpg is %.2f_\n");
      
      exit 0;
}      
      
      
    
  
