# Calculadora Simples
projeto simples de calculadora

#include <stdio.h>
#include <stdlib.h>

int main()
{
    int N, i, produto;
    printf ("deseja a tabuada para qual valor?");
    scanf("%d", &N);

    for (i = 1; i <= 10; i++){
        produto = N * i;
        printf("%d x %d =%d\n", N,i, produto);
    }

    return 0;
}
