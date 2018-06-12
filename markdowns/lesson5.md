# Entrada de Dados
+ A entrada de dados permite que um programa possa receber dados vindo de dispositivos de entrada (pex. teclado, disco). 
+ `scanf()` tem a função de mover para a variável associada ao comando, os valores digitados no teclado.
+ Para execução do comando de entrada é obrigatória a presença da diretiva: <strong>#include<stdio.h></strong>. 
+ O comando `scanf()` utiliza os caracteres de formatação para representar os tipos de dados dos valores que deverão ser digitados. <br />
+ 
**SINTAXE DO COMANDO**
![scanf](/markdowns/scanf.png)

A seguir, exibimos um exemplo do comando <strong>scanf()</strong>:
```
 #include<stdio.h> 
 int main(){
    int x;
    printf("Digite um valor inteiro");
    scanf("%d", &x);  <------ Após o ususário digitar um valor inteiro no teclado, esse é movido para a variável x
    printf("Você digitou: %d", x);
 }
``` 
+O comando <strong>scanf</strong> move o valor digitado pelo usuário (teclado) para dentro da variável associada. 
+É obrigatório o uso do caracter <strong>&(E comercial)</strong> na frente da variável que irá receber o valor digitado.

<strong>ATENÇÃO:</strong> Os <strong>"Snippets"</strong> denominados <strong>"IDE"</strong> exibem um interpretador interativo online (https://repl.it/) para que você aluno execute e modifique os exemplos disponibilizados, além de permitir que faça os exercícios apresentados.

<strong>Vamos tentar?</strong>

@[IDE]({"stubs": ["./www/ExemploEntrada"],"command": "sh /project/target/www/entrada.sh"
})

