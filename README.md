![Logo](data/logo.png "Project Logo")
# Amarok Mirrors

[Português]

## Espelhos

Aqui neste arquivo contém todos os nossos espelhos do Repositório Oficial do Amarok Linux.

## Como instalar

Para instalar um dos espelhos contidos no arquivo, você precisará entrar no Terminal, e em seguida criar um arquivo...

#### Passo 1 - Criando o Arquivo

Para criar o referido arquivo, vá ao terminal e digite:

<code>sudo nano /etc/apt/sources.list.d/amarok.mirrors</code>

#### Passo 2 - Inserindo o Espelho Desejado do Repositório

Dentro do arquivo já criando anteriormente, iremos adicionar o espelho.
Como exemplo, iremos adicionar o espelho brasileiro da C3SL (UFPR)

<code> deb https://openbsd.c3sl.ufpr.br/osdn/storage/g/a/am/amaroklinux/rolling/ rolling main contrib non-free </code>

Feito isso, tecle CTRL+O, em seguida tecle ENTER para salvar e por fim tecle CTRL+X para sair.

Para o espelho ter efeito em nosso sistema, devemos atualizar a lista de repositórios com o seguinte comando:

<code> sudo apt update </code>