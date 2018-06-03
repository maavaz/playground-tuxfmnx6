# Entrada de Dados
A entrada de dados permite que um programa possa receber dados vindo de fora (pex. teclado, disco). A partir do teclado, é comum a utilização da comando (função) <strong>scanf()</strong> que tem por objetivo, enviar para o programa todos os caracteres digitados no teclado  para dentro de uma variável associada ao <strong>scanf()</strong>. Assim, temos a entrada de dados mais primitiva do C, porém, bastante funcional. 
Semelhantemente ao comando de saída (<strong>printf</strong>), para execução do comando de entrada é obrigatória a presença da diretiva: <strong>#include<stdio.h></strong>. 
Além disso, o comando também utiliza os caracteres de formatação para a(s) variável(eis) associada(s). A seguir, exibimos um exemplo do comando <strong>scanf()</strong>:

```C runnable
 #include<stdio.h> //Obrigatório para executar os comandos scanf e printf
 int main(){
    int x;
    printf("Digite um valor inteiro");
    scanf("%d", &x);
 }
``` 
O comando scanf move o valor digitado pelo usuário (teclado) para dentro da variável associada. É obrigatório o uso do caracte <strong>&(E comercial)</strong> na frente da variável que irá receber o valor digitado.


# Processamento Sequencial
Cada instrução/comando em um programa é executado sequencialmente (de cima para baixo) do início ao fim. A figura abaixo representa a execução de um programa C representando o processamento sequencial.

![programa](/markdowns/ExecucaoProgramac.gif)
