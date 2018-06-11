# O que é um Programa de Computador?

+ Um programa de computador é um conjunto de instruções escrito numa linguagem de programação representando a resolução de algum problema (algoritmo). 
+ As instruções são escritas através de um conjunto de códigos (símbolos e palavras) que formam a linguagem de programação. 
+ Esse conjunto de códigos possui regras de estruturação lógica e sintática própria. 

# Algoritmo X Programa C

Abaixo é mostrado um exemplo de um algoritmo para somar dois números inteiros, escritos em pseudocódigo, e sua representação escrita na Linguagem de programação C:

# Pseudocódigo                                                  
```                                                               
Algoritmo "Soma dois Numeros"                                  
Var                                                              
   Inteiro: num1, num2, resultado                                
escreva("Digite o primeiro Número:")                           
leia(num1)                                                                                                     
escreva("Digite o segundo Número:")                            
leia(num2)                                                    
resultado <- num1 + num2                                       
escreva ("Soma = ", resultado)                                 
FimAlgoritmo                                                   
```
# Programa C
  ``` C
  #include<stdio.h>
  int main() { 
  // Programa que calcula a soma de dois números inteiros
  int num1, num2, resultado; 
  printf("\nDigite o primeiro Número:");
  scanf("%d", &num1); 
  printf("\nDigite o segundo Número:");
  scanf("%d", &num2);
  resultado = num1 + num2;
  printf("\n\nSoma = d", resultado);
  }
  ``` 
# Por dentro do Programa C
Um programa C consiste de uma ou mais partes chamadas funções. Um programa em C consiste de pelo menos uma função chamada main. Esta função marca o ponto de início de execução do programa.
Programas C tem a seguinte estrutura geral:
![Anatomia](/markdowns/anatomiaC.png)

<ul>
  <li><strong>biblioteca de funções C</strong> - correspondem a definições que dizem respeito a operações realizadas pelo compilador para geração de código correpondente ao arquivo indicado (pex. sdtio.h). Geralmente iniciam com uma cerquilha (#) e não são comandos da linguagem C.</li>
<li><strong>cabeçalho do programa principal</strong> - main() é a função principal de um programa em C, contendo o código que será inicialmente executado quando o programa em si for executado. Todo programa em C deve conter a função main(), do contrário será gerado um erro durante o processo de geração do programa (mais especificamente, na etapa de ligação).</li>
<li><strong>Declaração de variáveis</strong> - A declaração de variável é feita quando é necessário manipular dados no programa. Para se declarar uma variável é necessário associá-la a um tipo de dados.</li>
<li><strong>área de código/comandos</strong> -  área onde escrevemos os comandos da linguagem para a solução dos problemas</li>
</ul>  
