# 11-.-LOOPS
#include <stdio.h> 
  int main () 
{ 
       int i, j; 
    
   for(i=2; i<100; i++) {  
   for(j=2; j <= (i/j); j++) 
        if(!(i%j)) break;   
        if(j > (i/j)) printf("%d is prime\n", i); 
   } 
  
   return 0;
   }
   
   DO WHILE
#include <stdio.h> 
  int main () 
{ 
      int a = 10; 
 
      do    { 
       printf("value of a: %d\n", a);    
       a = a + 1; 
   }while( a < 20 ); 
  
   return 0; 
} 

   
