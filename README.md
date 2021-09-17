# Estudando um pouco mais sobre GIT/GITHUB #

## Usando a ferramenta TYPORA para editar arquivos do tipo markdown ##

### Para criar uma nova BRANCH utilize o seguinte comando:

### Sintaxe

#### git checkout  -b NOMEDABRANCH

### Para trocar pra uma branch

### Sintaxe

#### git checkout NOMEDABRANCH

### Para juntar as branch's

### Sintaxe

#### git merge NOMEDABRANCH

### Renomear o nome da branch ###

Obs: Existem 2 maneiras, a primeira você troca o nome da branch em que está o HEAD e a segunda você pode trocar o nome de determina branch sem que você esteja nela.

### 1º estando na branch

### Sintaxe

#### git branch -m NOVONOME

### 2º Outra branch

### Sintaxe

#### git branch -m nomeatual nomenovo



### Deletar uma Branch

### Sintaxe

#### git branch -d nomedabranch



# Para não carregar "lixo" de uma branch pra outra, use o comando git stash, seria uma especia de caixa menor para guardar o seu trabalho de forma temporaria. Dessa forma, você pode trocar de branch sem se preocupar com as alterações que estavam sendo feita em outra branch. Abaixo alguns comandos basicos do git stash.



### - Para salvar alterações sem ter que fazer commit, armazene no stash.

### Sintaxe

#### git stash save "contexto"

### - Para listar alterações salvas 

### Sintaxe

#### git stash list

### Para abrir a caixa, retornando com as tarefas que estava trabalhando, basta usar o comando POP, para "estourar" a caixa e dropar os "commits" feito pro stash

### Sintaxe

#### git stash pop





