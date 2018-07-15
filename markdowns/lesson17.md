# Vamos Treinar
----
----
###### Exercício 1
----
Faça uma programa em C que imprima a soma dos numeros inteiros entre 5 e 10 (inclusive). 

@[IDE]({"stubs": ["./www/condicional"],"command": "sh /project/target/www/condicional1.sh"
})
::: Solução
``` C  
#include <stdio.h>
int main() {
 int i;
 int soma;
 soma = 0; // Inicializa a variavel soma
 for(i=5; i < 11; i++) {  // a variavel i gera os numeros de 5 a 10
    soma = soma + i;
 }
 printf("A soma dos numeros de 5 a 10 é igual a %d", soma);
}
```
:::
----
###### Exercício 2
----
Faça uma programa em C que imprima os números inteiros entre 1.000 e 2.000(inclusive)que divididos por 11 produzam resto igual a 5. 

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
