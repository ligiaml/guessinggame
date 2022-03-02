#include <stdio.h>

#define NUMERO_DE_TENTATIVAS 3
	int main(){
	

printf("**********************************\n");
printf("*Bem-vindo ao jogo de Adivinhacao*\n");
printf("**********************************\n");
printf("(Voce tem 3 chances para acertar)\n\n");

	int numerosecreto;
	int chute;
	numerosecreto=42;
	int i;
	for(i=1; i<=NUMERO_DE_TENTATIVAS; i++){
	
		printf("\nQual o seu %do. chute?", i);
		scanf("%d",&chute);
			
			if(chute<0){
				printf("Voce nao pode chutar numeros negativos\n");
				i--;
				continue;
			}
				
		printf("Seu %do. chute foi %d.",i,chute);
		
		int acertou=chute==numerosecreto;
		int maior=chute>numerosecreto;
		if(acertou){
			 printf(" Parabens voce acertou! :D \n");
			 break;
		}else if(maior){
			printf("Seu chute foi maior que o numero secreto!\n");
		}else{
			printf("Seu chute foi menor que o numero secreto!\n");
		}
 		} printf("Fim de jogo, obrigada por jogar! \n\n");
system("pause");
return(0);
}
