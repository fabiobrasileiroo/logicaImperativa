### Desenvolvimento 6
Usei o 'para' e pré-defini o índice (i) para 1.
Assim, fiz com que fosse de 1 até 5, com passos 
de 1 em 1 ou seja pulando de um em um, e usei 'escreval' com 'l' para pular 
de linha em linha. Também poderia usar '\n'e prefirir usar o para para essa
questã, porque ao meu ver se encaixar melhor na resolucão.
## 

#### Portugol

```javascript
Algoritmo 6;
var
	i : inteiro;
	nomeDaEquipe : caractere;
	
inicio
	escreval("Digite o nome da equipe");
	leia(nome);
	para i de 1 ate 5 passo 1 faca
		escreval(nome," - ", i,"º");
	fimpara
fim.
