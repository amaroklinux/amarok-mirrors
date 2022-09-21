![Logo](data/logo.png "Project Logo")
# Amarok Mirrors

[Português]

## Espelhos

Aqui neste arquivo contém todos os nossos espelhos do Repositório Oficial do Amarok Linux.

## Como instalar

Para instalar um dos espelhos contidos no arquivo, você precisará entrar no Terminal, e em seguida criar um arquivo...

#### Passo 1 - Criando o Arquivo

Para criar o referido arquivo, vá ao terminal e digite:

<code> sudo nano /etc/apt/sources.list.d/amarok-mirrors.list </code>

#### Passo 2 - Inserindo o Espelho Desejado do Repositório

Dentro do arquivo já criado anteriormente, iremos adicionar o espelho.
Como exemplo, iremos adicionar o espelho brasileiro da C3SL (UFPR)

<code> deb https://openbsd.c3sl.ufpr.br/osdn/storage/g/a/am/amaroklinux/rolling/ rolling main contrib non-free </code>

Feito isso, tecle CTRL+O, em seguida tecle ENTER para salvar e por fim tecle CTRL+X para sair.

Para o espelho ter efeito em nosso sistema, devemos atualizar a lista de repositórios com o seguinte comando:

<code> sudo apt update </code>

[English]

## Mirrors

Here in this file contains all our mirrors from the Official Amarok Linux Repository.

## How to install

To install one of the mirrors contained in the file, you will need to enter Terminal, and then create a file...

#### Step 1 - Creating the File

To create said file, go to the terminal and type:

<code> sudo nano /etc/apt/sources.list.d/amarok-mirrors.list </code>

#### Step 2 - Inserting the Desired Mirror from the Repository

Inside the previously created file, we will add the mirror.
As an example, we will add the Brazilian mirror of C3SL (UFPR)

<code> deb https://openbsd.c3sl.ufpr.br/osdn/storage/g/a/am/amaroklinux/rolling/ rolling main contrib non-free </code>

After that, press CTRL+O, then press ENTER to save and finally press CTRL+X to exit.

For the mirror to take effect on our system, we must update the list of repositories with the following command:

<code> sudo apt update </code>