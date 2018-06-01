## Identificadores <a id="identificadores"></a>
São utilizados para dar nomes a constantes, variáveis, funções e vários objetos definidos pelo usuário. As regras para formação desses nomes são:

 
<ol>
  <li>Todo identificador deve iniciar por uma letra (a..z ou A..Z) ou um sublinhado</li>
  <li>Não pode conter símbolos especiais. Após o primeiro caracter pode ser utilizado: letras, sublinhados e/ou dígitos.</li>
  <li>Utiliza-se identificadores de, no máximo, 32 caracteres por estes serem significativos.</li>
  <li>Não pode ser palavra reservada e nem nome de funções de bibliotecas.</li>
 </ol>
 
<strong>Obs: letras maiúsculas e minúsculas são tratadas de forma diferente. </strong>

# Tipo de dados básicos
A tabela abaixo mostra os principais tipos de dados básico da linguagem C. Nesse momento, e para o objetivo do curso, apresentaremos apenas esses tipos.
<table>
  <tr>
    <th>Tipo</th>
    <th>Número de bytes</th>
    <th>Escala</th>
 <tr><td><strong>char</strong></td> <td align="center"> 1 </td> <td> -128 a 127</td> </tr>
 <tr><td><strong>int</strong></td> <td align="center"> 2</td> <td> -32768 a 32767</td> </tr>
 <tr><td><strong> float </strong></td> <td align="center"> 4 </td> <td> 3.4E-38 a 3.4E+38 (+-)</td> </tr>
<tr align="center"><td><strong> double </strong></td> <td align="center"> 8 </td> <td> 1.7E-308 a 1.7E+308 (+-)</td> </tr>
<tr><td><strong> void</strong></td> <td align="center"> 0 </td> <td> sem valor</td> </tr>
</table>

# Variáveis
Para que um programa possa manipular os dados, estes precisam estar armazenados em locais da memória do computador, denominado de <strong>variáveis</strong>. As variáveis podem ser definidas como locais de memória que servem para armazenar temporariamente (durante a execução do programa) dados (valores) que devem ser utilizados pelo programa. Esses dados podem ser informações vindas do meio exterior; ou resultados intermediários de alguma operação interna; ou valores que precisam ser exibidos na tela do computador como resultado da execução do programa. 
Imagine a memória do seu computador, como se fosse um escaninho (figura abaixo) onde cada local é utilizado para armazenar dados e podem ser identificados por um nome. 
![gavetas](/markdowns/gavetas.png)

Para se utilizada pelo programa, a variável precisa ser declarada. Para se declarar uma variável é necessário dar  um nome (as regras de formação do nome encontra-se descrito no item <a href="identificadores">Identificadores</a>) e associá-la a um tipo de dado, conforme exemplo abaixo:
```
Exemplo:

int total, x;                   // as variáveis total e x irão armazenar valores do tipo Inteiro
char flag;                     // a varável flag irá armazenar valores do tipo caracteres, pex. 'a', 'z' ...
single salario, desconto;     // as variáveis salario e desconto irão armazenar valores do tipo single

# Declaração de variáveis
 A forma geral para declaração de uma variável é:

Sintaxe:

<strong> tipo_da_variável     variavel1, variavel2, ..., variavelN; </strong>

 
onde tipo_da_variável  é um tipo válido em C (pex. int, char etc) e variavel1, variavel2 .... pode ser um ou mais nomes de identificadores separados por virgula.

Exemplos:

      int f, i, k;      /* todas variáveis do tipo int */

      float a, A, b;    /* todas variáveis do tipo float */


# Vamos Praticar
?[Assinalar com um X os nomes válidos (identificadores) para as variáveis abaixo:](multiple)
- [ ] ‘matricula’
- [X] total_2
- [ ] lal-55-ab
- [X] notafinaldoaluno
- [ ] 2345_resposta
- [X] numero_final
- [X] inter_sal
- [ ] teste*2
