# Variáveis
Para que um programa possa manipular os dados, estes precisam estar armazenados em locais da memória do computador, denominado de <strong>variáveis</strong>. As variáveis podem ser definidas como locais de memória que servem para armazenar temporariamente (durante a execução do programa) dados (valores) que devem ser utilizados pelo programa. Esses dados podem ser informações vindas do meio exterior; ou resultados intermediários de alguma operação interna; ou valores que precisam ser exibidos na tela do computador como resultado da execução do programa. 
Imagine a memória do seu computador, como se fosse um escaninho (figura abaixo) onde cada local é utilizado para armazenar dados e podem ser identificados por um nome. 
![gavetas](/markdowns/gavetas.png)

Para se utilizada pelo programa, a variável precisa ser declarada. Para se declarar uma variável é necessário dar  um nome (as regras de formação do nome encontra-se descrito no item [Identificadores](/markdowns/lesson3.md)) e associá-la a um tipo de dado, conforme exemplo abaixo:
```
Exemplo:

int total, x;                   // as variáveis total e x irão armazenar valores do tipo Inteiro
char flag;                     // a varável flag irá armazenar valores do tipo caracteres, pex. 'a', 'z' ...
single salario, desconto;     // as variáveis salario e desconto irão armazenar valores do tipo single
```

# Instruções 
 Uma instrução em linguagem C é uma expressão seguida de um ponto e vírgula. Pode ser uma atribuição, uma chamada de função, um teste de desvio ou um teste de laço.
 
# Comando de Atribuição 
O Coamndo de atribuição é uma instrução que tem como objetivo mover um valor para dentro da variável. Em C, o comando de atribuição é representado pelo símbolo de igual (=).

Exemplo de instrução de atribuição:       

x = 12;

Note-se que o operando do lado esquerdo do operador de atribuição é sempre uma variável, e que o operando do lado direito deve ser de um tipo de dado compatível com o tipo da variável. Após a execução comando a variável <strong>x</strong> conterá (armazena) o valor 12.

 
# Operadores
