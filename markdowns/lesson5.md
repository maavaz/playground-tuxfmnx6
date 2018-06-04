# Entrada de Dados
A entrada de dados permite que um programa possa receber dados vindo de fora (pex. teclado, disco). A partir do teclado, é comum a utilização da comando (função) <strong>scanf()</strong> que tem por objetivo, enviar para o programa todos os caracteres digitados no teclado  para dentro de uma variável associada ao <strong>scanf()</strong>. Assim, temos a entrada de dados mais primitiva do C, porém, bastante funcional. 
O funcionamento da função <strong>scanf()</strong> é parecido com o funcionamento da função <strong>printf()</strong> que nós já estudamos. A principal diferença é que agora estamos manipulando o fluxo de entrada de dados, enquanto que com a <strong>função printf()</strong>, estávamos manipulando a saída de informações, ou seja, o Fluxo de Saída.
Semelhantemente ao <strong>printf</strong>, para execução do comando de entrada é obrigatória a presença da diretiva: <strong>#include<stdio.h></strong>. 
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

'@[Entrada de Dados]({"stubs": ["comandoentrada.cpp"],"command": "sh /project/target/run.sh"})

# Processamento Sequencial
Cada instrução/comando em um programa é executado sequencialmente (de cima para baixo) do início ao fim. A figura abaixo representa a execução de um programa C representando o processamento sequencial.

![programa](/markdowns/ExecucaoProgramac.gif)
