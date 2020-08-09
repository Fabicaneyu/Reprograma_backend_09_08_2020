## Conteúdo: 

## Status http


[https://http.cat/](https://http.cat/)

[https://httpstatusdogs.com/](https://httpstatusdogs.com/)

## Comandos GIT


pwd: para entender onde se esta 

ls: lista tudo que tem dentro

mkdir: cria pasta

cd: entra em uma pasta

echo: cria o conteúdo que vc quiser no arquivo que vc quiser 
    ex: echo "oi" > index.html 

touch: cria arquivos 

rm: exclui arquivos

cd.. : eu volto uma pasta 

rm -r : exclui pasta  

## Identificação na máquina


git config - -global [user.name](http://user.name) "Seu nome"

git config - -global [user.](http://user.name)email "Seu@email.com"

para confirmar: git config - -list

## Para dar push (empurar) em uma pasta


1ºAbra o git bash na pasta que será empurrada

2º git init (comando feito uma única vez, sinaliza que esta pasta será "empurrada" para a nuvem)

3º ls -a mostrará os arquivos ocultos (ex: .git)

4º git status (aparecerão os arquivos em vermelho)

5º git add nome_arquivo ou git add . (para adicionar um arquivo ou todos para a staging area e passarão a ser rastreados)

6º git status (arquivo adicionado aparecerá em verde)

7º git commit -m "" (para comitar, ideal descrever o que foi feito)

8º git log (mostra o rastreamento e commits feitos)

MASTER é a árvore.

## Conectar ao github 

1º Criar um repo no github (sem o README aparecerá a lista de comandos que deverão ser realizados)

2º No git bash usado anteriormente, rodar o comando: git remote add origin https...

3º git remote -v 

aparecerá fetch (buscar) e push (empurar)