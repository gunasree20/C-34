# C-34
Pointers with functions 
#include <stdio.h>
void update(int *P){
    *p = 50;
}

int main()
{
   int a=100;
   printf("given value:%d\n",a);
   update(&a);
   printf("update value:%d\n",a);
    return 0;
}
