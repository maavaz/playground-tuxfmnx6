# Vamos Treinar

----
###### Exercício 1
----
Faça uma programa em C que leia um conjunto de numeros inteiros e imprima apenas os números pares. O programa termina quando for lido o valor zero. 

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
Faça uma programa em C que leia as informações das contas dos clientes de um Banco. O programa deverá ler o número da conta e o saldo do cliente.Para contas com saldo de pelo menos 10.000,00 reais o valor do pacote de serviços é igual a 0,1%, do contrário 0,3%. Para cad conta, calcule e exiba o valor da taxa de serviços e o novo saldo. O programa termina quando o número da conta é igual a -1. 

@[IDE]({"stubs": ["./www/condicional"],"command": "sh /project/target/www/condicional1.sh"
})
::: Solução
``` C  
#include <stdio.h>
int main() {
 int i;

 for(i=1000; i < 2001; i++) {  // a variavel i gera os numeros de 1000 a 2000
    if (i % 11 == 5) {
      printf("\n%d", i);
    }
 }

}
```
:::
----
###### Exercício 3
----
Uma loja utiliza o código 'V' para vendas à vista e 'P' para vendas à prazo. Faça uma programa em C leia o código e o valor das compras efetuadas por 15 clientes. Para cada cliente, calcule o valor a pagar, pois para as compras à vista é dado um desconto de 5% e para as compras à prazo mostre o valor da parcela. O parcelamento das compras à prazo é em 3X.



@[IDE]({"stubs": ["./www/condicional"],"command": "sh /project/target/www/condicional1.sh"
})
::: Solução
``` C  
#include <stdio.h>
int main() {
 int i;

 for(i=1000; i < 2001; i++) {  // a variavel i gera os numeros de 1000 a 2000
    if (i % 11 == 5) {
      printf("\n%d", i);
    }
 }

}
```
:::
