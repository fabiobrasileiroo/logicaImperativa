# logicaImperativa | Desenvolvimento 5
Fiz um algoritmo simples com uma estrutura condicional composta, utilizando 'se' e 'senão'. Caso não seja fornecido um número válido, o usuário será solicitado a digitar um número válido. Optei por utilizar o comando 'escolha' ou 'switch' com casos, pois achei que era a melhor opção para este algoritmo
## Resposta 
```js
Algoritmo 5;
var
	num: inteiro;
inicio
	escreval("Digite 1 para fumantes ou com animais");
	escreval("2 para grupos de 5 ou mais pessoas");
	escreval("3 para qualquer outro grupo de pessoas");
	escreval("dica: 1>2>3 em ordem de preferência");
	leia(num);
	se(num >=1 E num <=3)
		escolha(num)
			caso 1:
				escreval("Va para área externa");
				pare;
			caso 2;
				escreval("Va para 1º andar, pois não da para juntar mesas no térreo");
				pare;
			caso 3;
				escreval("Permaneça no térreo");
	senao 
		escreva("Digite novamente um numero valido");
	fimse
fim.
```
