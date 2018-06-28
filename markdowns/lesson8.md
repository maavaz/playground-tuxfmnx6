# Processamento Condicional
+ O processamento Condicional introduz a estrutura de decisão ```IF``` que possibilita agrupar um conjunto de comandos (1 ou mais) a uma ou mmais condições.
+ A execução desse conjunto de comandos dependerá da avaliação (verdadeira ou Falsa) da(s) condição(ões).
+ As condições são representadas através de expressões relacionais. 
+ As expressões relacionais permitem a comparação de valores de mesmo tiopo e possui resultado em valores Verdadeiros ou Falsos. 

**Operadores Relacionais:**
```
== igual
!= diferente
>  maior
>= maior ou igual
<  menor
<= menor ou igual
```
**Exemplo de Expressões relacionais**
```
A expressão 3 > 2 possui valor verdadeiro. 
A expressão 4 < 1  possui valor falso.
```
** Testando os conhecimentos....
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

+ A estrutura condicional pode ser: Simples, Composta ou Aninhada.

### Estrutura condicional Simples
+ Esse tipo de estrutura só permite a execução dos comandos associados a(s) condição(ões) avaliada(s) verdadeira, do contrário (condição avaliada Falsa), esse conjunto de comandos não será executado.

![programa](/markdowns/gif_IF_Simples.gif)
