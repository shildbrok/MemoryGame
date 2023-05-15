# MemoryGame
## Artigo abordando o desenvolvimento de jogo da memória em Python.
#### Written by: Estevan Generoso

Este artigo irá abordar somente, as partes principais do desenvovimento. Com dicas de aulas e vídeos para melhor entendimento e aprendizado.</br>
Vamos começar a pontuar os objetivos da atividade.</br>
Para uma melhor compreensão de códigos, deveremos usar um Função para poder separar melhor os códigos. Facilitando a manutenção do código e possiveis erros.</br>

`````
def iniciartProjeto:
  ### Link para estudos
  ### https://www.youtube.com/watch?v=ezfr9d7wd_k
`````
https://www.youtube.com/watch?v=ezfr9d7wd_k </br>
Este vídeo nos ajudará a compreender melhor oque é função e como usar.


1º Gerar 50 imagens aleatórias que não podem se repetir.
---
Temos que gerar 50 imagens aleatórioas, que pode ser utilizado a Tabela ASCII, para gerar os sinais.</br>
https://www.techtudo.com.br/noticias/2022/10/o-que-e-o-codigo-ascii-confira-a-tabela-completa-e-para-que-serve.ghtml </br>
E quando mechemos com valores Randomicos sempre utilizaremos a lib Random.
`````
 import random
 ### importamos uma biblioteca nativa do python
 ### para usar é só chamar ela.
 
`````
Para ver  mais conteudo desta LIB acesse o link: https://docs.python.org/3/library/random.html </br>
Conteúdo em vídeo: https://www.youtube.com/watch?v=OPh0nngbBSY </br>

2º A matriz deve ser preenchida com 50 pares distintos de imagens.
---
Bom... Depois de Randomizarmos 50 imagens, deveremos posicionar randomicamente em uma matriz com 100 espaços.</br>
https://www.youtube.com/watch?v=EGmlFdwD4C4 </br>

3º A posição das imagens é definida aleatoriamente (randomicamente) no início do jogo.
---
Bom esta estapa é meio que auto-explicativa. Basta posicionar os sinais gerados.</br>

4º O jogador inicia com 5 vidas.
---
Recomendo que coloque essa parte em uma função onde deve ser verificada a cada jogada realizada. Que ENQUANTO a VIDA > 0 então o jogo continua.</br>
https://www.youtube.com/watch?v=LH6OIn2lBaI </br>
Usando essa estrutura.

5º A cada erro (escolha de 2 imagens distintas) perde uma vida. 
---
A jogada só acaba, QUANDO 2 imagens forem selecionadas e COMPARADAS.

6º A cada 3 acertos consecutivos, ganha uma vida. 
---
Mais uma comparação, só que dessa vez de adição de vida, deve receber o numero de acertos concecutivos.

7º Inicialmente, todas as posições estão fechadas (invisíveis para o jogador). 
---
O jogador não pode ver nenhuma infomação, use uma mascara para esconder as informações sem alterar o valor posicional da Matriz.

8º A cada rodada, o jogador escolhe as coordenadas da 1ª imagem e as coordenadas da 2ª imagem.
---
Devemos utilizar cordenadas em X e Y, já que estamos trabalhando com matriz...</br>

9º O jogo mostra as imagens nas posições escolhidas pelo jogador.</br>
10º Caso as imagens das posições escolhidas formarem um par, permanecerão expostas.</br>
11º Caso as imagens das posições escolhidas não formarem um par, voltarão a ser fechadas.</br>
12º O jogador vence, quando conseguir montar todos os pares de imagens.</br>
13º O jogador perde o jogo quando esgotar suas vidas. </br>

Esses passos são auto-explicativos, é uma dificuldade de implementação e não de conhecimento. A parte lógica é a mais complexas porem divida o desafio em pequenas etapas, assim será fácil a compreeensão.</br>


Caso haja alguma dúvida, o grupo da monitoria estará disponivel a partir das 17:30.</br>
### Bonne Etudie mon's Amie.
