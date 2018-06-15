# Processamento Sequencial
+ Os comandos/instruções em um programa C são executados um após o outro, na seqüência escrita (de cima para baixo) do início ao fim. 
+ A figura a seguir exibe a execução de um programa C representando o processamento sequencial.

![programa](/markdowns/ExecucaoProgramac70.gif)

# Exercícios Processamento Sequencial
+ A melhor maneira de aprendermos a programar é fazendo exercícios. 
+ Apresentamos três enunciados de problemas que você deverá resolver utilizando a programação C.  
+ Os  programas deverão ser desenvolvidos utilizando o `IDE Repl.it` apresentado abaixo.
+ As soluções dos programas estão abaixo do enunciado, mas aconselhamos a vê-las somente após tentar desenvolver sua própria solução. 

#### Exercício 1  
#### Faça um programa C para reajustar o salário atual de um funcionário. Para isso, o programa deve ler o valor do salário e o percentual de reajuste. Calcular e escrever o valor do salário reajustado.  
::: Solução:

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
# teste
