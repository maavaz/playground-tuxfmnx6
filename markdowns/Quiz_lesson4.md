# Testando os conhecimentos....
-------
?[De acordo com os valores movidos para as variáveis nos comandos abaixo, indique a linha que contém a declaração na sua forma correta em C: letra = 'm'; numero1 = 13;   numero2 = 8.98;](single)
-[ ] int letra;<br/> float numero1; <br/>char numero2; 
-[ ] char letra;<br/> char numero1;<br/> float numero2;
-[x] char letra;<br/> int numero1;<br/> float numero2;
-[ ] int letra;<br/> char numero1;<br/> char numero2;   

?[Qual a sintaxe correta para declaração de uma variável?](single)
-[ ] tipo variável!
-[x] tipo variável;
-[ ] variável tipo;
-[ ] tipo = variável;

?[Para que o programa abaixo possa exibir o conteúdo das variáveis soma e divisao corretamente, que caracteres de formatação devem ser colocados no lugar do caracter interrogação ***?***
*substitua os caracteres acima para executar o programa e depois responda a essa pergunta]
-[ ] a e b
-[ ] d e c
-[x] d e f
-[ ] f e c

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

```
Considerando um programa iniciado pelos comandos:
             float a  = 20;
             float b  = 12;
             float c  = 32;
             c  = a + b;
             b  = c -  a;
             a  = c / 4;
             b  = (b / 2) + 2;
             c  = c / ( a / 2);
```		     
?[informe os valores que estarão contidos nas variáveis a, b, c após a execução do trecho de comandos, acima:]
-[ ] a = 5, b = 5 e c= 5.
-[ ] a = 4, b = 3 e c= 2.
-[x] a = 4, b = 4 e c= 4.

