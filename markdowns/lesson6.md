# Processamento Sequencial
+ Os comandos/instruções em um programa C são executados um após o outro, na seqüência escrita (de cima para baixo) do início ao fim. 
+ A figura a seguir exibe a execução de um programa C representando o processamento sequencial.

![programa](/markdowns/ExecucaoProgramac70.gif)

# Exercícios Processamento Sequencial
+ A melhor maneira de aprendermos a programar é fazendo exercícios. 
+ Apresentamos três enunciados de problemas que você deverá resolver utilizando a programação C.  
+ Os  programas deverão ser desenvolvidos utilizando o `IDE Repl.it` apresentado abaixo.
+ As soluções dos programas estão abaixo do enunciado, mas aconselhamos a vê-las somente após tentar desenvolver sua própria solução. 
---
###### Exercício 1  
---
Faça um programa C para reajustar o salário atual de um funcionário. Para isso, o programa deve ler o valor do salário e o percentual de reajuste. Calcular e escrever o valor do salário reajustado.  

::: Solução

``` C
int main() {

  float salario_atual, salario_novo;
  float percentual;        

  printf("\nDigite o salario atual do funcionario:"); 
  scanf("%f", &salario_atual );  

  printf("\nDigite o percentual de reajuste:"); 
  scanf("%f", &percentual );  

  salario_novo = salario_atual + salario_atual * percentual/100; 
  printf("\nSalario reajustado é: %f", salario_novo);
}
```
:::
---
###### Exercício 2 
---
Um determinado prêmio de loteria saiu para um bolão de três amigos. Uma lei garante que todo prêmio de loteria deva pagar um imposto de 7% para os cofres estaduais. Do total descontado o imposto, os amigos irão dividir o  prêmio da seguinte maneira:
+ O primeiro ganhador recebera 46%;
+ O segundo recebera 32%;
+ O terceiro recebera o restante;

Faça um programa C que leia o valor total do prêmio, calcule o desconto, o valor que cada um tem direito e imprima o total do prêmio, o premio descontado o imposto e a quantia recebida por cada um dos ganhadores.
::: Solução
``` C
int main(){

 float ganhador1, ganhador2, ganhador3;
 float premio, premiodesc;

 printf("\nDigite o Valor Total do Premio:");
 scanf("%f", &premio);

 premiodesc = premio - premio * 0.07;

 ganhador1 = premiodesc * 0.46;
 ganhador2 = premiodesc * 0.32;
 ganhador3 = premiodesc - (ganhador1 + ganhador2);

 printf("\nValor Premio Total: %f",premio);
 printf("\nValor Premio Descontado: %f",premiodesc);
 printf("\n============Ganhadores=====================\n");
 printf("\nValor Premio primeiro ganhador: %f",ganhador1);
 printf("\nValor Premio segundo  ganhador: %f",ganhador2);
 printf("\nValor Premio terceiro ganhador: %f",ganhador3);
 printf("\n\n\n %f", ganhador1+ganhador2+ganhador3);
}
```
:::
