# O que é um Programa de Computador?

Um programa de computador é um conjunto de instruções escrito numa linguagem de programação que representa um algoritmo para a resolução de algum problema. 
Estas instruções são escritas através de um conjunto de códigos (símbolos e palavras) que formam a linguagem de programação. Este conjunto de códigos possui regras de estruturação lógica e sintática própria. 

# Algoritmo X Programa C

Apresentaremos abaixo um exemplo de um algoritmo para somar dois números inteiros, escritos em pseudocódigo, e sua representação na escrita na Linguagem de programação C:

# Pseudocódigo                                                  
                                                               
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

# Programa C
  ``` C
  #include<stdio.h>
  int main() { 
  int num1, num2, resultado; 
  printf("\nDigite o primeiro Número:");
  scanf("%d", &num1); 
  printf("\nDigite o segundo Número:");
  scanf("%d", &num2);
  resultado = num1 = num2;
  printf("\n\nSoma = d", resultado);
  }
  ``` 
