#include <stdio.h>

int main(){
    int dias;
    printf("Digite quantos dias o funcionário trabalhou:\n");
    scanf("%d", &dias);

    float bruto;
    bruto = (float)dias*50.25;

    float bonus;
    if (dias > 20){
    bonus = bruto*0.30;
    }
    else if (dias > 10){
    bonus = bruto*0.20;
    }

    float liquido;
    liquido = bruto + bonus;
    liquido = liquido - 0.10*liquido;

    printf("Salário líquido: %.2f\n", liquido);

    return 0;
}
