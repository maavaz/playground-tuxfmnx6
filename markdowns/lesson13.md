+ Uma animação exibindo a execução do comando ```for```

![For](/markdowns/estruturafor.gif)

----
Vamos Treinar
----
Considere os trechos de código abaixo:
+ Código 1                        
``` C                       
int x;                                           
for (x=0; x < 5; x++)    
 {
   printf("\n%d", x);
 }
 ```                           
+ Código 2
 ```runnable C                              
int x;                                           
for (x=4; x > 0; x--)    
 {
   printf("\n%d",  4 - x);
 }
 ```     

?[Assinale a alternativa correte com relação a execuções dos códigos acima (Código 1 e 2):]
-[ ] o código 1 exibe os números de 1 até 5 e o código 2 de 1 até 4.
-[ ] o código 1 exibe os números de 0 até 5 e o código 2 de 0 até 4.
-[x] o código 1 e o codigo 2 exibem os números de 0 até 4.
-[ ] o código 1 exibe os números de 0 até 4 e o código 2 de 4 até 0.
----

@[IDE]({"stubs": ["./www/condicional"],"command": "sh /project/target/www/condicional1.sh"
})
::: Solução
:::
