# Testando os conhecimentos....

?[De acordo com os valores movidos para as variáveis nos comandos abaixo, indique a linha que contém a declaração na sua forma correta em C: letra = 'm'; numero1 = 13;   numero2 = 8.98;](single)
-[] int letra;<br/> float numero1; <br/>char numero2; 
-[] char letra;<br/> char numero1;<br/> float numero2;
-[x]char letra;<br/> int numero1;<br/> float numero2;
-[] int letra;<br/> char numero1;<br/> char numero2;              

?[Qual a sintaxe correta para declaração de uma variável?](single)
-[]tipo variável!
-[x]tipo variável;
-[]variável tipo;
-[]tipo = variável;


```C runnable
#include<stdio.h>
int main(){
int a, b, soma;
float d, divisao;
a = 2;
b = 4;
soma = a + b;
d = 20.0;
divisao = d / a;
printf("c = %?",soma);
printf("e = %?",divisao);

return 0;
}
```
?[Para que o programa acima possa exibir o conteúdo das variáveis soma e divisao corretamente, que caracteres de formatação devem ser colocados no lugar do caracter interrogação? *modifique o programa acima para executá-lo e depois responda a essa pergunta](single)
-[] a e b
-[]d e c;
-[x]d e f;
-[]f e c;
