# Vamos Treinar

----
###### Exercício 1
----
Faça um programa em C que leia um conjunto de numeros inteiros e imprima apenas os números pares. O programa termina quando for lido o valor zero. 

@[IDE]({"stubs": ["./www/condicional"],"command": "sh /project/target/www/condicional1.sh"
})
::: Solução
``` C  
#include <stdio.h>
int main() {
 int num, resto;
printf("\nDigite um valor inteiro: ");
scanf("%d", &num);
while (num != 0)
 {
   resto = num%2;
   if (resto == 0){
     printf("\n%d e PAR", num);
   }
   printf("\nDigite um valor inteiro: ");
   scanf("%d", &num);
 }

}

```
:::
----
###### Exercício 2
----
Faça um programa em C que leia as informações das contas dos clientes de um Banco. O programa deverá ler o número da conta e o saldo do cliente.Para contas com saldo de pelo menos 10.000,00 reais o valor do pacote de serviços é igual a 0,1%, do contrário 0,3%. Para cad conta, calcule e exiba o valor da taxa de serviços e o novo saldo. O programa termina quando o número da conta é igual a -1. 

@[IDE]({"stubs": ["./www/condicional"],"command": "sh /project/target/www/condicional1.sh"
})
::: Solução
``` C  
#include <stdio.h>
int main() {
 int conta;
 float saldo, taxa;
printf("\nDigite o numero da conta: ");
scanf("%d", &conta);
while (conta != -1)
 {
   printf("\nDigite o saldo da conta: ");
   scanf("%f", &saldo);

   if (saldo >= 10000){
     taxa = saldo * 0.001;
   }
   else {
     taxa = saldo * 0.002;
   }
   printf("\n\n saldo atual = %f", saldo - taxa);
   printf("\n\n taxa Servicos = %f", taxa);
   printf("\nDigite o numero da conta: ");
   scanf("%d", &conta);
 }

}

```
:::
----
###### Exercício 3
----
Foi feita uma pesquisa em uma escola para saber a média de idade dos alunos. Faça um programa em C que, para cada aluno, leia a sua idade, calcule e exiba a média das idades e a quantidade de alunos que responderam a pesquisa.



@[IDE]({"stubs": ["./www/condicional"],"command": "sh /project/target/www/condicional1.sh"
})
::: Solução
``` C  
#include <stdio.h>
int main() {
float idade;
float media, soma, cont;
soma=0;
cont=0;
printf("\nDigite a sua idade: ");
scanf("%f", &idade);
while (idade != -1)
 {
    soma = soma + idade;
    cont = cont +1 ;
   printf("\n\nDigite a sua idade: ");
   scanf("%f", &idade);
 }
media = soma /cont;
printf("\n\nmedia = %f \n\nquantidade pessoas = %f", media, cont);
}

```
:::
