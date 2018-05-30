# Identificadores
 

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
 <tr align="center"><td><strong>char</strong></td> <td> 1 </td> <td> -128 a 127</td> </tr>
 <tr align="center"><td><strong>int</strong></td> <td> 2</td> <td> -32768 a 32767</td> </tr>
 <tr align="center"><td><strong> float </strong></td> <td> 4 </td> <td> 3.4E-38 a 3.4E+38 (+-)</td> </tr>
<tr align="center"><td><strong> double </strong></td> <td> 4 </td> <td> 1.7E-308 a 1.7E+308 (+-)</td> </tr>
<tr align="center"><td><strong> void</strong></td> <td> 0 </td> <td> sem valor</td> </tr>
</table>

# Declaração de variáveis
 A forma geral para declaração de uma variável é:

Sintaxe:

<strong> tipo_da_variável variavel1, variavel2, ..., variavelN; </strong>

 
onde tipo_da_variável  é um tipo válido em C (pex. int, char etc) e variavel1, variavel2 .... pode ser um ou mais nomes de identificadores separados por virgula.

Exemplos:

      int f, i, k;      /* todas variáveis do tipo int */[2]

      float a, A, b;    /* todas variáveis do tipo float */

 # Caracteres de controle (Escape) da linguagem C
 A linguagem C possui vários caracteres que desempenham tarefas bastante importantes na formação e exibição dos textos, mas não possuem representação em C. Todo Caractere de controle (Escape) é formado por uma barra invertida e outro caractere que definirá a ação. Para o propósito do curso apresentaremos apenas o caracter utilizado para pular uma linha na impressão ou escrita:
```
\n - Nova página (line feed)
```
Existe um conjunto de caracteres que podem ser utilizados. Pesquisem na Internet (Sequência de Escape).

# Vamos praticar
?[Assinalar com um X os nomes válidos (identificadores) para as variáveis abaixo:] (multiple)
-[] ‘matricula’
-[X] total_2
-[] lal-55-ab
-[X] notafinaldoaluno
-[] 2345_resposta
-[X] numero_final
-[X] inter_sal
-[] teste*2
    
