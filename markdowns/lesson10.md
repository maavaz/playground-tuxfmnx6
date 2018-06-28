# Processamento Condicional

### Estrutura Condicional Composta

+ Existem situações onde é necessário agrupar um conjunto de comandos onde a Condição é avaliada **Verdadeira** e um conjunto de comandos onde a Condição é avaliada **Falsa**
+ Em linguagem C o código equivalente para essa estrutura de decisão é:
```
 if (condição)
 {
    Comando(s) para condição Verdadeira;
 }
 else
 {
    Comando(s) para condição Falsa;
 }
 ```
 + O **else** simboliza a negação da condição do ```if```, logo está ligado ao conjunto de comandos que será executado quando a condição for **Falsa**.
 + A Estrutura Condicional Composta representa uma bifurcação,i.e., ou executo os comandos associados a condição Verdadeira ou executo os comandos associados a condição Falsa, mas nunca os dois.
![bifurcacao](/markdowns/bifurcação.png)
---
+ A imagem abaixo representa o exemplo de funcionamento da estrutura ```IF Composto```, para as 2 situações (Verdadeira e Falsa).

![programa](/markdowns/gif_IF_Composto.gif)

---
+ Exemplo de Programa com estrutura condicional composta: 
    + selecione o botão **Run** para execução do programa;
    + Modifique os valores das variáveis A e B para criar situações diferentes da apresentada;

``` C runnable
#include <stdio.h>
int main(void)
{
    int A, B, Soma;
    printf("Digite um numero inteiro: ");
    scanf("%d", &A);
 
    printf("Digite um numero inteiro: ");
    scanf("%d", &B);
 
    Soma = A + B;
    printf("O Valor da soma = %d\n", Soma);
 
    if(Soma > 10)
    {
       printf("O valor da soma e maior que 10\n");
    }
    else
       {
           printf("Valor menor ou igual a 10\n");
       }
 
    return(0);
}
```
***OBS:*** A estrutura condicional aninhada, será apreentada mais para frente...
