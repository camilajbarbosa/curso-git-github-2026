# Curso Teo Me Why Git \& GitHub

Curso para iniciantes aprenderem a trabalhar com versionamento de código e repositórios remotos com GitHub

Além disso, vamos trabalhar com GitFlow ao final do curso e Visual Studio Code.


## Fluxo de trabalho Git local

01. git checkout -b <nova-branch>
02. cria ou atualiza arquivos conforme necessário
03. git status
04. git add .
05. git status
06. git commit -m "mensagem sobre alteração"
07. git checkout main
08. git merge <nova-branch>

## Fluxo de trabalho GitHub <> Local (projeto próprio ou da sua empresa)

01. git clone <endereço do projeto>
02. git checkout -b <nova_branch>
03. cria ou atualiza arquivos conforme necessário
04. git status
05. git add "arquivos"
06. git status
07. git commit -m "mensagem sobre alteração"
08. git push origin <nova_branch>
09. abrir pull request no GitHub para main
10. excluir <nova_branch> origin
11. git checkout main
12. git branch -D <nova_branch>

## Fluxo de trabalho GitHub <> Local (projetos open-source)

01. fork do projeto para seu próprio github
02. git clone <endereço do projeto fork>
03. git checkout -b <nova_branch>
04. cria ou atualiza arquivos conforme necessário
05. git status
06. git add "arquivos"
07. git status
08. git commit -m "mensagem sobre alteração"
09. git push origin <nova_branch>
10. abrir pull request no GitHub da branch fork para a main do projeto original
11. excluir <nova_branch> origin
12. git checkout main
13. git branch -D <nova_branch>

