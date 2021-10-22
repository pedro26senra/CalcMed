//CALCMED


#include <stdio.h>
#include <stdlib.h>
#include <Windows.h>
#include <conio.h>


int main()
{
	float nota1, nota2, nota3, nota4, media;

	printf("Seja bem vindo ao CalcMed: ");

	printf("Digite a nota da APOL1: ");
	scanf("%f",&nota1);


	printf("Digite a nota da APOL2: ");
	scanf("%f", &nota2);


	printf("Digite a nota da PROVA: ");
	scanf("%f", &nota3);

	printf("Digite a nota da ATIVIDADE PRATICA: ");
	scanf("%f", &nota4);


	media = (nota1 + nota2 + nota3 + nota4) / 4;


	if (media >= 7)

	{
		printf("Voce foi aprovado! Sua media final ‚ %2.2f", media);

	}

	if (media < 7 && media >= 5)

	{
		printf("Voce ficou no exame... Sua media final ‚ %2.2f", media);


		


			if (media < 5)

			{
				printf("Voce foi reprovado... Sua media final ‚ %2.2f", media);

			}

		
	}
	system("pause");
	return 0;

}
