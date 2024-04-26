#include <stdio.h>

int main() {
    float baseMayor, baseMenor, altura, area;

    printf("Radio de la base: ");
    scanf("%f", &baseMayor);

    printf("Base menor: ");
    scanf("%f", &baseMenor);

    printf("Altura: ");
    scanf("%f", &altura);

    area = ((baseMayor + baseMenor) * altura) / 2;

    printf("área: %.2f\n", area);

    return 0;
}
