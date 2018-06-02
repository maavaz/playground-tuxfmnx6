# Caracteres de controle (Escape) da linguagem C
 A linguagem C possui vários caracteres que desempenham tarefas bastante importantes na formação e exibição dos textos, mas não possuem representação em C. Todo Caractere de controle (Escape) é formado por uma barra invertida e outro caractere que definirá a ação. Para o propósito do curso apresentaremos apenas o caracter utilizado para pular uma linha na impressão ou escrita:

```
'\n' - Nova página (line feed)

```

Existe um conjunto de caracteres que podem ser utilizados, a medida que forem necessários iremos apresentá-los. Mas, caso queiram, podem pesquisá-los na Internet (Sequência de Escape).

# Instruções 
 Uma instrução em linguagem C é uma expressão seguida de um ponto e vírgula. Pode ser uma atribuição, uma chamada de função, um teste de desvio ou um teste de laço.
 
# Comando de Atribuição 
O Comando de atribuição é uma instrução que tem como objetivo mover um valor para dentro da variável. Em C, o comando de atribuição é representado pelo símbolo de igual (=).

Exemplo de instrução de atribuição:       

x = 12;

Note-se que o operando do lado esquerdo do operador de atribuição é sempre uma variável, e que o operando do lado direito deve ser de um tipo de dado compatível com o tipo da variável. Após a execução comando a variável <strong>x</strong> conterá (armazena) o valor 12.

 # Saída de Dados
 Para um programa exibir na tela do computador (ou impressora) os resultados precisamos usar um comando de Saída. Em C, não há um comando específico, mas uma função denominada **printf** que executa essa tarefa. 
 Para utilizarmos essa função é necessário incluirmos a diretiva **#include** para o arquivo **stdio.h**, como exibido abaixo:<br />
                                              **#include<stdio.h>**
 <ul>
  <li>EXIBINDO TEXTOS (MENSAGENS) NA TELA DO COMPUTADOR</li>
  Para que o comando exiba qualquer mensagem (Texto) que o usuário desejar, basta colocá-los entre aspas duplas, como no trecho de código abaixo (para executar selecione a tecla Run):
 ```C runnable
 #include<stdio.h> //Obrigatório para executar o comando printf
 int main(){
    
    printf("Isso é uma mensagem de exemplo para exibirmos textos!");
 }
``` 
<li>EXIBINDO NÚMEROS NA TELA DO COMPUTADOR </li>

</lu>
# Operações Aritméticas
Em C , nós podemos executar operações aritméticas usando variáveis e constantes como operandos separados pelos operadores aritméticos. Os operadores aritméticos em C são:

<H4> +  (adição) </H4>
<H4> -  (subtração) </H4>
<H4> *  (multiplicação) </H4>
<H4> /  (divisão) </H4>
<H4> %   (resto)  </H4>

Estas operações podem ser usadas como mostram os exemplos abaixo, assumindo que as variáveis necessárias já estão declaradas:
```
     celsius = (fahrenheit - 32) * 5.0 / 9.0;

     forca =  massa * aceleracao;

     i = i + 1;
```     
<strong> Vamos treinar? a seguir, temos uma série de Quiz para avaliarmos o que foi aprendido até o momento...</strong>
