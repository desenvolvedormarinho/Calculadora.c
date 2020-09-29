# Calculadora.c
Projeto de Calculadora Aluno Unip DF 2020
#include <stdio.h>

int main(){
	float n1, n2;
	char op;
	
	printf("Calculadora\n");
	printf("Bem vindo, Insira o primeiro numero: ");
	
	fflush(stdin);
	scanf("%f",&n1);
	
	printf("Informe a operacao + - * /: ");
	scanf(" %c" , &op);
	
	printf("\n Informe o segundo numero: ");
	scanf("%f",&n2);
	
	printf("------------\n");
	printf("Resultado => ");

	
	switch (op){
		case '+':
			printf("%.0f\n",n1 + n2);
		break;	
			
			case '-':
				printf("%.1f\n",n1 - n2);
			break;
				case '*':
					printf("%.1f\n",n1 * n2);
				break;
					case'/':
						if(n2 == 0){
							printf("Operacao invalida\n");
							
						}else{
							printf("%.1f \n",n1 / n2);
							
						}
					
					break;
						default:
							printf("Operacao Invalida");
					
								
							
					
	}
	
	return 0;
	
}
