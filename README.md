# fahreheit_convert
#include <stdio.h>
int main( )
{
   float C, F;
   printf("Escreva a Temperatura em graus Celsius: ");
  scanf("%f", &C);
  F = ((9 * C) / 5) + 32;
  printf("Temperatura Fahrenheit = %.2f .\n", F);
  return 0;
}
