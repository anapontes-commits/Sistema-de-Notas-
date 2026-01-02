# Notas
Sistema de Notas de Alunos
#include <stdio.h>

int main() {
    float n1, n2, media;

    printf("Nota 1: ");
    scanf("%f", &n1);

    printf("Nota 2: ");
    scanf("%f", &n2);

    media = (n1 + n2) / 2;

    printf("Média: %.2f\n", media);

    if (media >= 6)
        printf("Situação: Aprovado\n");
    else
        printf("Situação: Reprovado\n");

    return 0;
}
