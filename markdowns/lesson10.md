# Processamento Condicional

### Estrutura Condicional Composta

+ Existem situações onde é necessário agrupar um conjunto de comandos onde a(s) Condição(ões) é(são) avaliada(s) **Verdadeira** e um conjunto de comandos onde a(s) Condição(ões) é(são) avaliadas **Falsa**
+ Em linguagem C o código equivalente para essa estrutura de decisão é:
```
 if (condição)
 {
    Comando(s) para condição Verdadeira;
 }
 else
 {
    Comando(s) para condição Falsa;
 }
 ```
 + O **else** simboliza a negação da condição do ```if```, logo está ligado à instrução que será executada quando a condição for falsa.
 + Esse tipo de Estrutura representa uma bifurcação, onde ou executo os comandos associados a condição Verdadeira ou executo os comandos associados a condição Falsa, mas nunca os dois.
![bifurcacao](/markdowns/bifurcacao.png)
