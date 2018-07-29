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
  - **c** quando o valor digitado é do caracter alfanumérico.
+ O comando `scanf` move o valor digitado pelo usuário (teclado) para a variável associada. 
+ É obrigatório o uso do caracter `&(E comercial)` na frente da variável que irá receber o valor digitado.

<b>ATENÇÃO1:</b>
O comando <b>scanf</b> não elimina o caracter <b>Enter('\0')</b>, portanto em variáveis do <b>tipo char</b> esse caracter é lido no comando <b>scanf</b> seguinte. Logo, em comandos de leitura de variáveis do tipo char, coloque a função <b>getchar()</b> antes do commando para solucionar o problema. Veja o exemplo abaixo:
```C
#include<stdio.h>
int main(){
 int numero;
 char carac;
 printf("\ndigite um numero:");
 scanf("%d", &numero);
 printf("\ndigite um caracter:");
 getchar();                       // <--- tente retirar esse comando
 scanf("%c",&carac);
 printf("\nnumero digitado foi: %d", numero);
 printf("\ncaracter digitado foi:%c", carac);

}

---
<strong>ATENÇÃO2:</strong> Os <strong>"Snippets"</strong> denominados `IDE` exibem um interpretador interativo online (https://repl.it/) para que você aluno execute e modifique os exemplos disponibilizados, além de permitir que faça os exercícios apresentados.

<strong>Vamos tentar?</strong>

@[IDE]({"stubs": ["./www/ExemploEntrada"],"command": "sh /project/target/www/entrada.sh"
})

