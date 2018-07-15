# Processamento com Repetição
---
### Processamento com um número pré-determinado de repetições.
---
+ Esse tipo de processamento também pode ser representado pela estrutura do ```while```
+ O problema de representar esse tipo de processamento com essa estrutura é que tudo é feito manualmente pelo programador.
![for](/markdowns/for.png)

+ O exemplo a seguir exibe os números de 1 até 5 (Veja a diferença com a estrutura for).
```C runnable
#include<stdio.h>
int main() 
{
int i;
i = 1;
while (i <= 5)
{
   printf("%d ", i);
   i++;
}
}
```
 

