# Entrada de Dados
A entrada de dados permite que um programa possa receber dados vindo de fora (pex. teclado, disco). A partir do teclado, é comum a utilização da comando (função) <strong>scanf()</strong> que tem por objetivo, enviar para o programa todos os caracteres digitados no teclado  para dentro de uma variável associada ao <strong>scanf()</strong>. Assim, temos a entrada de dados mais primitiva do C, porém, bastante funcional. <br />
O funcionamento da função <strong>scanf()</strong> é parecido com o funcionamento da função <strong>printf()</strong> que nós já estudamos. A principal diferença é que agora estamos manipulando o fluxo de entrada de dados, enquanto que com a <strong>função printf()</strong>, estávamos manipulando a saída de informações, ou seja, o Fluxo de Saída.<br />
Semelhantemente ao <strong>printf</strong>, para execução do comando de entrada é obrigatória a presença da diretiva: <strong>#include<stdio.h></strong>. <br />
Além disso, o comando também utiliza os caracteres de formatação para a(s) variável(eis) associada(s). A seguir, exibimos um exemplo do comando <strong>scanf()</strong>:https://tech.io/snippet

```
 #include<stdio.h> 
 int main(){
    int x;
    printf("Digite um valor inteiro");
    scanf("%d", &x);  <------ Após o ususário digitar um valor inteiro no teclado, esse é movido para a variável x
    printf("Você digitou: %d", x);
 }
``` 
O comando <strong>scanf</strong> move o valor digitado pelo usuário (teclado) para dentro da variável associada. É obrigatório o uso do caracter <strong>&(E comercial)</strong> na frente da variável que irá receber o valor digitado.

OBS: Para realizar os testes e exercícios de programação sugerimos utilizar o IDE <strong>DEVC++</strong> (https://sourceforge.net/projects/orwelldevcpp/files/latest/download).

<strong>ATENÇÃO:</strong> Os <strong>"Snippets"</strong> denominados <strong>"IDE"</strong> exibem um interpretador interativo online (https://repl.it/) para que você aluno execute e modifique os exemplos disponibilizados, além de permitir que faça os exercícios apresentados.

<strong>Vamos tentar?</strong>

@[IDE]({"stubs": ["./www/ExemploEntrada"],"command": "sh /project/target/www/entrada.sh"
})

@[IDE]({"command": "sh /project/target/www/entrada.sh"})
