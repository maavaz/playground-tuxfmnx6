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
Considere três execuções do trecho de código acima, onde os valores armazenados por X e Y são apresentados abaixo:

| X | Y |
|---|---|
| 1 | 2 |
| 1 | 1 |
| 2 | 3 |

?[Qual das execuções acima (valores de X e Y), faz com que a variável W armazene o valor 0 (zero):]
-[ ] X = 2 e Y= 3.
-[ ] X = 1 e Y= 2.
-[x] X = 1 e Y= 1.
-[ ] Em nenhuma das três execuções a variável W conterá o valor 0.
----
Dado o trecho de código abaixo:
```
printf ("A");
if (q1) {
 printf ("B");
}
else {
  printf ("C");
}
printf ("D");
if (q2) {
 printf("E");
}
else {
  printf ("F");
}
printf ("G");
printf ("H");

}
```
?[Que sequência será impressa pelo programa, caso as condições q1 e q2 sejam verdadeiras:]
-[x] A B D E G H.
-[ ] A C D F G H.
-[ ] A B D F G H.
-[ ] A C D E G H.
----

Escreva um programa C que peça a idade de uma pessoa e se tiver 21 ou mais anos, imprima a idade juntamente com a mensagem "Você já é maior de 21 anos".
@[IDE]({"stubs": ["./www/condicional"],"command": "sh /project/target/www/condicional1.sh"
})
---
As maçãs custam R$ 0,30 cada se forem compradas menos do que uma dúzia, e R$0,25 cada, se forem compradas pelo menos uma dúzia. Escreva um programa que leia o número de maçãs compradas, calcule e escreva o valor total da compra.

@[IDE]({"stubs": ["./www/condicional"],"command": "sh /project/target/www/condicional1.sh"
})
---
