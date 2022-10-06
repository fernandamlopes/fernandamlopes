- 👋#include <stdio.h>
#include <math.h>

int main ()
	{
	
		printf("\n\t-Unilasalle \n\t-Analise e Desenvolviento de Sistemas \n\t-Fernanda Madeira Lopes - 202221633\n");
	
 		float x=0, y=0, result=0;
		int op=0, raiz=0, z=0, potencia=0;
	
	
						
		 	printf("\n\tSelecione uma operacao: \n\t1-Raiz Quadrada \n\t2-Soma \n\t3-Subtracao \n\t4-Multiplicacao \n\t5-Divisao \n");
			scanf("%i", &op);
				
			if(op!=1)	//condicional para uso da raiz no calculo
			{
			
				printf("\n\t-Digite um numero: \n");
			scanf("%f",&x);
			
			printf("\n\t-Digite outro numero: \n");
			scanf("%f",&y);
			}
					
			switch(op)  //switch das opcoes ecolhidas
			{
				
				case 1:
					printf("\n\t-Digite um numero: \n");
			scanf("%i",&z);
			
			potencia = pow(z, 2);
			raiz = sqrt(z);
			
			printf("\n\t-Potencia: %i ", potencia); // o resultado mostra a potencia da raiz do numero escolhido
			printf("\n\t-Raiz: %i ", raiz);		   //  o resultado mostra a raiz do numero escolhido
				
				case 2:
					result = x+y;
					printf("\n\t-O resultado e: %0.2f", result);		//soma	
				break;
				
				case 3:
					result = x-y;
					printf("\n\t-O resultado e: %0.2f", result);	   //subtracao	
				break;
				
				case 4:
					result = x*y;
					printf("\n\t-O resultado e: %0.2f", result);	  //multiplicacao			
				break;
				
				case 5:					
					result = x/y;
					printf("\n\t-O resultado e: %0.2f", result);	//divisao			
				break;
				
				default:
					printf("\n\t-Digite uma opcao valida\n");
						
			}
			
		return 0;
			
				
		}	
		
		
	
