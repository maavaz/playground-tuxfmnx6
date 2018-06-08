# Entrada de Dados
A entrada de dados permite que um programa possa receber dados vindo de fora (pex. teclado, disco). A partir do teclado, é comum a utilização da comando (função) <strong>scanf()</strong> que tem por objetivo, enviar para o programa todos os caracteres digitados no teclado  para dentro de uma variável associada ao <strong>scanf()</strong>. Assim, temos a entrada de dados mais primitiva do C, porém, bastante funcional. <br />
O funcionamento da função <strong>scanf()</strong> é parecido com o funcionamento da função <strong>printf()</strong> que nós já estudamos. A principal diferença é que agora estamos manipulando o fluxo de entrada de dados, enquanto que com a <strong>função printf()</strong>, estávamos manipulando a saída de informações, ou seja, o Fluxo de Saída.<br />
Semelhantemente ao <strong>printf</strong>, para execução do comando de entrada é obrigatória a presença da diretiva: <strong>#include<stdio.h></strong>. <br />
Além disso, o comando também utiliza os caracteres de formatação para a(s) variável(eis) associada(s). A seguir, exibimos um exemplo do comando <strong>scanf()</strong>:

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

<strong>ATENÇÃO:</strong> Por questões de limitações da ferramenta o comando <Strong> Scanf()</strong> não pode ser executado. Portanto, esse comando sempre aparecerá como comentário (você pode executar o programa no IDE DEV C++) e, quando for necessário a entrada de dados, utilizaremos o comando de atribuição para mover os valores desejados.
No exemplo abaixo o comando <strong>scanf("%d", &x);</strong> está sendo substituído pelo comando <strong>x = 10;</strong>. (<strong> esse valor (10) pode ser modificado por você antes da execução!!!</strong>).

<strong>Vamos tentar?</strong>
[Entrada de Dados](https://repl.it/@MarcoVaz/Entrada-de-Dados)

@[]({
  "stubs": ["entradadedados.html"],
  "command": "open -s /project/target/www/entradadedados.html"
})


  console.log('TECHIO> open -s /project/target/www HelloWorld.html');

<HTML>
<iframe height="400px" width="100%" src="https://repl.it/@MarcoVaz/Entrada-de-Dados?lite=true" scrolling="no" frameborder="no" allowtransparency="true" allowfullscreen="true" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals"></iframe>
</HTML>

@[Entrada de Dados]({"stubs": ["comandoentrada.cpp"],"command": "sh /project/target/run.sh"})




# Processamento Sequencial
Os comandos/instruções em um programa C são executados um após o outro, na seqüência escrita (de cima para baixo) do início ao fim. A figura abaixo exibe um exemplo de execução de um programa C representando o processamento sequencial.

![programa](/markdowns/ExecucaoProgramac.gif)
