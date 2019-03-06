# exercicio
trabalho de escola (Nava)

#include <stdio.h>
#include <stdlib.h>
#include <math.h>
#include <string.h>

int main(void)
{
  int i,a;
  char seunome[10];
  
  printf ("Digite seu nome:\n");
  gets (seunome);
  a = strlen (seunome);

  for (i=1; i<=a; i++)
  {
    printf ("\n%s",seunome);
  }
return 0;
}
