## SITE DE PARÂMETROS DO GIT
https://devhints.io/git-branch

## git init
Inicia um repositório.

## git status
Quais alterações ja aconteceu no código, se existe algum arquivo para commitar, se existe algum arquivo que ainda não é monitorado pelo git.

## git add
adiciona no git o arquivo a ser monitorado.

## git add.
monitora todos os arquivos da pasta atual.

## git commit -m
Commit são pontos de alteração, salvar alterações que foi realizada. Nunca comitar um código que não funciona.

## git log
Navega e visualiza o histórico de alteração, mostrando o range (identificação unica) de cada commit, autor e data do commit.

## git log --oneline
Navega e visualiza o histórico de alterações mas mostrando somente o ID e commit.

## git config --local user.name "nome" / git config --local user.email "email"
modifica ou visualiza as configurações usando os parametros (user.name "seu nome"; user.email"seu email") mas somente no projeto da maquina local.

##git config --global user.name "nome" / git config --local user.email "email"
modifica ou visualiza as configurações usando os parametros (user.name "seu nome"; user.email"seu email") em todos os projetos da maquina local.

## git remote
Lista todos os repositórios remotos que o repositório local conhece

## git remote add (nome do repositório) (caminho que será alocado)
Adiciona um repositório remoto

## git remote
retorno o repositório adicinado.

## git remote -v
visualiza o endereço dos repositórios remotos

## git clone (endereço URl ou caminho do repositório)
Clona o repositório remoto para o repositório local

## git push
Empurra as modificações para o git remote

## git push local master
envia todos os dados por todos os códigos e alterações feitas até então para o repositório chamado de **"local"**, dentro de "servidor". Após pressionarmos "Enter", é gerado uma mensagem de que uma nova branch (ramo) foi criada em "servidor", chamada **master**.

## git pull local master
Traz os dados da master para local

## git push -u origin master
envia os dados do repositório com **git push -u origin master**, cujo **-u** define que, sempre que usado **git push** e estiver na **master**, o envio seja feito para **origin**. Ou seja, a partir de então poderá ser executar simplesmente **git push**.

## git checkout master
retorna à branch correspondente.
