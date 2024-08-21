# quest-9

#include <stdio.h>

int main() {
    int numero, fatorial = 1;

    
    printf("Digite um número inteiro positivo: ");
    scanf("%d", &numero);

    
    if (numero < 0) {
        printf("Fatorial não é definido para números negativos.\n");
        return 1; 
    }

    
    for (int i = 1; i <= numero; i++) {
        fatorial *= i;
    }

    
    printf("O fatorial de %d é %d\n", numero, fatorial);

    return 0;
}
