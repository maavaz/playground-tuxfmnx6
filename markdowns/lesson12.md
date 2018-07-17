# Processamento com Repetição
+ O processamento com repetição permite que um conjunto de comandos associados a uma condição possam ser repetidos n vezes.
+ Enquanto a condição associada for verdadeira, o conjunto de comandos é executado várias vezes.
+ Há dois tipos de processamento com repetição: 
    + Processamento com um número pré-determinado de repetições.
    + Processamento com sinalizador de parada.
+ Estas estruturas de repetição são também conhecidas como laços (do inglês loops).

---
### Processamento com um número pré-determinado de repetições.
---
+ Esse tipo de processamento é representado pela estrutura do ```for```
![for](/markdowns/for.png)


+ Antes de apresentarmos um exemplo, vamos revisitar a forma de representar incrementos/decrementos em C:
    + Vale Lembrar: 
        +  a representação do incremento de 1 unidade em uma variável em C, é feito da seguinte maneira: ```var++```, isso é a mesma coisa que:```var = var + 1```
        +  a representação do decremento de 1 unidade em uma variável em C, é feito da seguinte maneira: ```var--```, isso é a mesma coisa que:```var = var - 1```
+ O exemplo a seguir exibe os números de 1 até 5.
```C runnable
#include<stdio.h>
int main() 
{
int i;
for (i=1; i <= 5; i++)
{
   printf("%d ", i);
}
}
```
 

