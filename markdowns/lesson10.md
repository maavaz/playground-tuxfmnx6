# Processamento Condicional

### Estrutura Condicional Composta

+ Existem situações onde é necessário agrupar um conjunto de comandos onde a Condição é avaliada **Verdadeira** e um conjunto de comandos onde a Condição é avaliada **Falsa**
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
 + O **else** simboliza a negação da condição do ```if```, logo está ligado ao conjunto de comandos que será executado quando a condição for **Falsa**.
 + A Estrutura Condicional Composta representa uma bifurcação,i.e., ou executo os comandos associados a condição Verdadeira ou executo os comandos associados a condição Falsa, mas nunca os dois.
![bifurcacao](/markdowns/bifurcação.png)
---
+ A imagem abaixo representa o exemplo de funcionamento da estrutura ```IF Composto```, para as 2 situações (Verdadeira e Falsa).

![programa](/markdowns/gif_IF_Composto.gif)

---
