#include "stdio.h"
int main()
{
 int j = 0;
 for ( ; j < 10 ; )
 { 
   if (j < 10)
     printf("Geeks", j++);
   else
     continue;
   printf(“Quiz”);
 }
 return 0;
}
