# att10.05

#include <stdio.h>
#include <stdlib.h>

int main(){
	float num1;
	float num2;
	
	printf("Digite um numero aleatorio: ");
	scanf("%f", &num1);
	printf("Digite outro numero aleatorio: ");
	scanf("%f", &num2);
	
	float resultado = num1 / num2;
	
	printf("A divisao dos dois numeros digitados e: %f", resultado);
	
return 0;
}
