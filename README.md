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
