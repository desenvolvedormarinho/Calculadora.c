# Calculadora.c
Projeto de Calculadora Aluno Unip DF 2020

"Resultado => ");
	
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
