# python-questao3
#include <stdio.h> 
 
void main() { 
  float nota1, nota2,  media; 
 
  printf("Informe a 1a. nota:\n"); 
  scanf("%f", ¬a1); 
 
  printf("\nInforme a 2a. nota:\n"); 
  scanf("%f", ¬a2);
 
  media = (nota1 + nota2 ) / 2; 
 
  printf("\nMedia final = %.2f", media); 
 
  if (media >= 7.0) 
     printf(" (aluno aprovado)."); 
  else if ((media >= 5.0) && (media < 7.0)) 
          printf(" (aluno em recuperacao)."); 
       else 
   printf(" (aluno reprovado).");
   }
