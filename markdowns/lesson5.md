# Entrada de Dados
+ A entrada de dados permite que um programa possa receber dados vindo de dispositivos de entrada (pex. teclado, disco). 
+ `scanf()` tem a função de mover para a variável associada ao comando, os valores digitados no teclado.
+ Para execução do comando de entrada é obrigatória a presença da diretiva: <strong>#include<stdio.h></strong>. 
+ O comando `scanf()` utiliza os caracteres de formatação para representar os tipos de dados dos valores que deverão ser digitados. <br />
 
**SINTAXE DO COMANDO** <br />
#### **scanf("%?", &variável);**<br />

+ O caracter **?** deve ser substituído por:
  - **d** quando o valor digitado é do tipo inteiro.
  - **f** quando o valor digitado é do tipo float.
  - **c** quando o valor digitado é do caracter alfanummérico.
+ O comando `scanf` move o valor digitado pelo usuário (teclado) para a variável associada. 
+ É obrigatório o uso do caracter `&(E comercial)` na frente da variável que irá receber o valor digitado.

<strong>ATENÇÃO:</strong> Os <strong>"Snippets"</strong> denominados `IDE` exibem um interpretador interativo online (https://repl.it/) para que você aluno execute e modifique os exemplos disponibilizados, além de permitir que faça os exercícios apresentados.

<strong>Vamos tentar?</strong>

@[IDE]({"stubs": ["./www/ExemploEntrada"],"command": "sh /project/target/www/entrada.sh"
})

