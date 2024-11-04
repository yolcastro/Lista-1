#include <stdio.h>

int main(){
    float valor;
    printf("Digite o valor da hora:\n");
    scanf("%f", &valor);

    float horas;
    printf("Digite o valor de horas trabalhadas no mês:\n");
    scanf("%f", &horas);

    float percentual;
    printf("Escreva o percentual de desconto do INSS:\n");
    scanf("%f", &percentual);

    float salario_bruto, desconto, salario_liquido;
    salario_bruto = valor*horas;
    desconto = salario_bruto*(percentual/100);
    salario_liquido = salario_bruto - desconto;

    printf("Salário bruto: %.2f\n", salario_bruto);
    printf("Salário líquido: %.2f\n", salario_liquido);

    return 0;
}
