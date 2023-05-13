# O básico para usar o less

## Antes vamos diferenciar opções de comandos
Opções são usadas na invocação. Aqui o ```-S``` é uma opção:

	$ less -S bahh.txt
	
Comandos são usados quando você já está dentro do less. Nada mais são do que atalhos de teclado que executam alguma coisa. Abra um arquivo com o less (exemplo acima) e tecle ```h```. Esse comando abre a ajuda.
Caso você se esqueca de uma opção na hora de invocar, você pode usar opções como se fossem comandos, ou seja, quando já estiver dentro do less.

	$ less bahh.txt

E tecle ```-S```.

***Importante***: Vim-users talvez pensem que é necessário teclar ":" para digitar comandos/opções e não, não é.

## Opções

	-S alterna o word-wrap
	-i ignora o case quando o pattern não contém uppercase
	-I ignora o case para todos os patterns

## Comandos

Comandos com um "*" podem ser precedidos por algum número N, e quando tal os parenteses vão explicam o comportamento.

### Mover

	d desce meia tela
	U sobe meia tela
	g vai até a primeira linha
	G até a última linha
	RightArrow* move uma coluna para a direita (ou N colunas)
	LeftArrow* move uma coluna para a esquerda (ou N colunas)

### Pesquisar

	/patterns procura por patterns
	n* mostra a próxima ocorrência (ou a N° ocorrência)
	N mostra a ocorrência anterior
	ESC-u alterna o highlight das ocorrências


