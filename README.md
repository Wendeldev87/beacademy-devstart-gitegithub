# beacademy-devstart-gitegithub
Projeto criado para instruir os alunos do programa devstart, quanto a utilização do git e github. Utilizaremos este repositório para salvar dicas e comandos úteis do git e também da plataforma github.

Funcionalidades básicas
Configuração do usuário

git config --global user.name "nome"

Configurar e-mail do usuário

git config --global user.email "email"

Inicia um direito vazio

git init

Clona um repositorio existente

git clone "endereço do repositorio"

mostra os arquivos que podem ser comitados no repositorio local

git status

Prepara o arquivo a ser comitado

git add "nomedoarquivo.formato"

Prepara todos os arquivos para serem comitados

git add .

Remover o arquivo a ser comitado

git rm --cached "nomearquivo.formato"

Adiciona um compromisso

git commit -m "mensagem do commit"

Mostra o histórico de compromissos

git log

Envia o commit para o servidor

git push

Ramificação e mesclagem
Listar todas as filiais

git branch

Cria uma filial

git branch "nome da branch"

Cria e acessa uma filial

git checkout -b "nome da branch"

Deletar uma filial

git branch -d "nome da branch"

Guarda as edições atuais

git stash

Lista as edições guardadas

git stash list

Salva mudanças sem compromisso

git stash –include-untracked

outros
Mostra o remoto selecionado

git remote

Mostra de origem

git remote -v

inverter as mudanças de um commit e gera um novo commit

git revert "4 primeiros dígitos do hash do commit"

Autor Wendel

