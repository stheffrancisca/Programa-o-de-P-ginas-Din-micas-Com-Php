# Programa-o-de-P-ginas-Din-micas-Com-Php
# O que acontece em nosso programa caso a condição em questão não seja verdadeira? Qual retorno é exibido nesse caso?
# Digite o código no emulador seguinte, execute-o e veja você mesmo:

# Como $var1 é menor que $var2, nada é exibido no navegador, já que a condição é falsa. Nessa situação, para imprimirmos uma mensagem informando que a condição é falsa, ou seja, que $var1 é menor que $var2, faremos uso do else. Veja como ficaria nosso código nesse ponto:


<?php

 $var1 = 10;
 $var2 = 20;

 if($var1 > $var2){
	echo "$var1 é maior que $var2";
 }else{
	echo "$var1 é menor que $var2";
 }

