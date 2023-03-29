#define _CRT_SECURE_NO_WARNINGS
#include<stdio.h>

int main(void) {
   int A ;
   int B ;
   scanf("%d%d", &A, &B);
   if (A >= 1, B <= 10000) {
      printf("%d\n", A + B);
      printf("%d\n", A - B);
      printf("%d\n", A * B);
      printf("%d\n", A / B);
      printf("%d\n", A % B);
   }
}
