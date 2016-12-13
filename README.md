# gh1
#README.md
#include<stdio.h>
int main() {
	int calorias, prato, sobremesa, bebida;
	printf("Prato: (1.Vegetariano 2.Peixe 3.Frango 4.Porco)\n)");
	scanf("%d", &prato);
	printf("Sobremesa: (1.Abacaxi 2.Sorvete diet 3. Mousse diet 4. Mousse chocolate)\n");
	scanf("%d", &sobremesa);
	printf("Bebida: (1.Cha 2.Suco de laranja 3.Suco de melao 4.Refrigerante)\n");
	scanf("%d", &bebida);
	{if(prato == 1)
		calorias = 180;
	else if (prato ==2)
		calorias =230;
	else if (prato == 3)
		calorias = 250;
	else if (prato == 4)
		calorias = 350;
		else
		printf("Escolha invalida.");
	}
	{if (sobremesa == 1)
		calorias = calorias+ 75;
	else if (sobremesa == 2)
		calorias = calorias + 110;
	else if (sobremesa == 3)
		calorias = calorias + 170;
	else if (sobremesa == 4)	
		calorias = calorias + 200;	
		else
		printf("Escolha invalida.");		
	}
	{ if (bebida == 1)
		calorias = calorias + 20;
	else if (bebida == 2)
		calorias = calorias + 70;
	else if (bebida == 3)
		calorias = calorias + 100;
	else if (bebida == 4)
		calorias = calorias + 120;		
		else
		printf("Escolha invalida.");
	}
	printf("%d Calorias: ", calorias);
}   
