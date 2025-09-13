# desafio-super-trunfo2
#include <stdio.h>

int main() {
    // Variáveis para a primeira carta
    char codigo1[4];
    int populacao1;
    float area1;
    float pib1;
    int pontos_turisticos1;
    
    // Variáveis para a segunda carta
    char codigo2[4];
    int populacao2;
    float area2;
    float pib2;
    int pontos_turisticos2;
    
    // Cadastro da primeira carta
    printf("=== CADASTRO DA PRIMEIRA CARTA ===\n");
    
    printf("Digite o código da cidade (ex: A01): ");
    scanf("%3s", codigo1);
    
    printf("Digite a população: ");
    scanf("%d", &populacao1);
    
    printf("Digite a área (em km²): ");
    scanf("%f", &area1);
    
    printf("Digite o PIB (em bilhões): ");
    scanf("%f", &pib1);
    
    printf("Digite o número de pontos turísticos: ");
    scanf("%d", &pontos_turisticos1);
    
    printf("\n");
    
    // Cadastro da segunda carta
    printf("=== CADASTRO DA SEGUNDA CARTA ===\n");
    
    printf("Digite o código da cidade (ex: B02): ");
    scanf("%3s", codigo2);
    
    printf("Digite a população: ");
    scanf("%d", &populacao2);
    
    printf("Digite a área (em km²): ");
    scanf("%f", &area2);
    
    printf("Digite o PIB (em bilhões): ");
    scanf("%f", &pib2);
    
    printf("Digite o número de pontos turísticos: ");
    scanf("%d", &pontos_turisticos2);
    
    printf("\n");
    
    // Exibição dos dados da primeira carta
    printf("=== CARTA 1 ===\n");
    printf("Código: %s\n", codigo1);
    printf("População: %d habitantes\n", populacao1);
    printf("Área: %.2f km²\n", area1);
    printf("PIB: %.2f bilhões\n", pib1);
    printf("Pontos Turísticos: %d\n", pontos_turisticos1);
    
    printf("\n");
    
    // Exibição dos dados da segunda carta
    printf("=== CARTA 2 ===\n");
    printf("Código: %s\n", codigo2);
    printf("População: %d habitantes\n", populacao2);
    printf("Área: %.2f km²\n", area2);
    printf("PIB: %.2f bilhões\n", pib2);
    printf("Pontos Turísticos: %d\n", pontos_turisticos2);
    
    return 0;
}
