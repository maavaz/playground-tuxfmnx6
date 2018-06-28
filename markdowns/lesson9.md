# Processamento Condicional

* As estruturas condicionais podem ser: Simples, Compostas ou Aninhadas.
---

### Estrutura condicional Simples
+ Esse tipo de estrutura só permite a execução dos comandos associados a(s) condição(ões) avaliada(s) verdadeira, do contrário (condição avaliada Falsa), esse conjunto de comandos não será executado.
+ Em linguagem C o código equivalente para essa estrutura de decisão é:
```
 if (condição)
 {
    instrução ou instruções para condição verdadeira;
 }
```
+ A imagem abaixo representa o exemplo de funcionamento da estrutura ```IF Simples```.
+
![programa](/markdowns/gif_IF_Simples.gif)

---
Exemplo de Programa com estrutura condicional simples

``` C runnable
#include <stdio.h>
#include <stdlib.h>
int main(void)
{
    int A, B, Soma;
 
    A = 4;
    B = 6;
    Soma = A + B;
    printf ("O Valor da soma = %d", Soma);
 
    if(Soma >= 10)
    {
        printf("\n\nEstou dentro da Estrutura IFSimples, logo:\n valor da soma é maior ou igual a 10\n");
    }
 
    return(0);
}
```
