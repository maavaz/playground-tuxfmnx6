
---
### Processamento com Sinalizador de Parada.
---
+ Esse tipo de processamento é representado pela estrutura ```While```
+ Sinalizador de parada é um valor, em geral externo ao programa, que torna <b>Falsa</b> a condição da estrutura ```while```. 
+ É necessário definir uma variável sinalizador, para ser usada no comando de leitura dos dados (***scanf***).
+ Colocar antes da estrutura ```While``` o comando de leitura contendo a variável sinalizador e repetir esse mesmo comando ao final da estrutura. Veja o exemplo:
![while](/markdowns/while2.png)

+ O exemplo a seguir lê uma sequência de números inteiros positivos. O programa termina quando for lido um valor negativo.

@[IDE]({"stubs": ["./www/ExemploEntrada"],"command": "sh /project/target/www/Sinal.sh"
})


