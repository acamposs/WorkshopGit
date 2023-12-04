# Git

## O que é git e github? São as mesmas coisas?

- Git é um sistema de versionamento de arquivos que nos permite ter controle sobre tudo o que já foi escrito e todas as alterações feitas em nosso projeto.
- GitHub é uma plataforma que hospeda o controle de arquivos e versionamento do Git.

## Repositórios

- Diretórios do Git usados para armazenar os arquivos de projetos e portfólios.

## Conceitos

**Branch** 
- Ramificação do projeto, que permite trabalhar em diferentes versões do código simultaneamente.

**commit**
- "salvar"/"postar" as alterações do seu projeto

**merge**
- Junção das branchs de desenvolvimento com a branch principal do projeto
- Adiciona as alterações de diversas branchs sem conflitos e tem a capacidade de juntar a main apenas a alteração que foi feita em uma parte especifica do projeto

**remote**
- cria uma conexão do meu repositorio local com o repositorio do github

**push**
- subir os commits e as alterações para o repositorio no github

**pull**
- puxa o que esta no repositorio do github para a sua maquina

## passo a passo git
1. instalar o git
    - pesquisar no google: git download e instalar o git de acordo com o SO da sua maquina
    - criar uma nova pasta na area de trabalho
    - criar um novo arquivo README.md na pasta: arquivo em markdown. documentação e instruções que precisam para o projeto
    - git bash é o terminal do git
2. git bash
     
    - git --version: para conferir se esta instalado corretamente 
    - git init: foi inicializado um repositorio git vazio
    - git add: seleciona os arquivos que serao salvos/postados no commit. caso seja ., adiciona tudo que esta no repositorio no commit, ou pode adicionar arquivos especificos
    - git commit -m "mensagem do commit"
    - git status: mostra como esta os arquivos no momento, as alterações e os commits atualizados no momento.
    - git branch -M "main": renomeando a branch
    - git branch nome_da_branch: criar branch nova
    - git checkout nome_da_branch: mudar de branch
    - git checkout -b nome_da_branch: criar e mudar para a branch criada
    - git remote add origin link-git: conexao do repositorio local com o repositorio do github
    - git push -u origin main: empurrando os commits do me repositorio local para o repositorio do github











