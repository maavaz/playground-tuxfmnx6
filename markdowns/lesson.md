# Exercícios Seleção

Observe o trecho do programa C abaixo.
``` 
 if (X >= Y){
   W=0;
 }  
else { 
  W=1;
}
```
Considere três execuções diferentes onde os valores armazenados por X e Y, no momento de execução do ```if``` são apresentados abaixo:
<table width="120" border="1px" bgcolor="#CCC">
  <tr>
    <td width="60">X</td>
    <td width="60">Y</td>
  </tr>
  <tr>
    <td height="40">Ricardo</td>
    <td>(21) 9999-9999</td>
    <td>Rua Dois, casa 3.</td>
    <td>99999-999</td>
  </tr>
</table>


| X | Y |
|---|---|
| 1 | 2 |
| 1 | 1 |
| 2 | 3 |

?[Para a variável W ter o valor igual a 0, quais os valores de X e Y, na execução do trecho de código acima:]
-[ ] X = 2 e Y= 3.
-[ ] X = 1 e Y= 2.
-[x] X = 1 e Y= 1.
-[ ] Em nenhuma das três execuções a variável W conterá o valor 0.
----

Escreva um programa C que peça a idade de uma pessoa e se tiver 21 ou mais anos, imprima a idade juntamente com a mensagem "Você já é maior de 21 anos".
@[IDE]({"stubs": ["./www/condicional"],"command": "sh /project/target/www/condicional.sh"
})
---
As maçãs custam R$ 0,30 cada se forem compradas menos do que uma dúzia, e R$0,25 cada, se forem compradas pelo menos uma dúzia. Escreva um programa que leia o número de maçãs compradas, calcule e escreva o valor total da compra.

@[IDE]({"stubs": ["./www/condicional"],"command": "sh /project/target/www/condicional1.sh"
})
---
