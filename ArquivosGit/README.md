Augusto  
João Vitor  
Guilhermy Ferreira da Silva.

## Primeira e Segunda aula

# PARA CONECTAR A CONTA GIT
git config --global user.name "x"
git config --global user.email "x@gmail.com"

# Comandos para acessar pastas
ls-> para ver quais pastas tem
cd-> para navegar nas pastas

# comando para inicializar o git
git init -> inicializa um repositório git

# comando gerais do git

git clone URL -> para clonar arquivo

git branch -m master main -> mudar caso o seu esteja master

git status -> para ver o status dos arquivos, para ver se tem que dar algum commit ou se o commit foi

git add NomeArquivo -> para marcar o arquivo que você quer incluir no próximo commit

git commit -m "descrição commit" -> salva no repositório local git

git push -> para subir para o github

git pull origin main -> para puxar o repositório caso já tenha ele clonado

git branch nomeBranch -> para criar versões/ramificações

git fetch ->busca as atualizações do repositório remoto sem alterar o código local

# remover um arquivo
git rm nomeDoArquivo.md (exemplo)
git commit "Nome do commit"
git push

# Criar e trocar de branch

git checkout -b "nome da branch" -> para criar o nome da branch

git checkout nomeBranch -> para trocar de branch

# Merge da branch

git merge nomeDaBranchQueVaiJuntar
git push origin main

## Terceira aula 30/08/2025.

Comandos de WSL

# exibe o satus - distribuição padrão e versão WSL
wsl --status
# atualizar o kernel linux para a ultima versão
wsl --update

# lista de distribuição linux
wsl --list --online
wsl -l -o
wsl -l
wsl -l -v

# instalação de subsistemas linux para windows
wsl --install
wsl --install -d NOME-DISTRIBUIÇÃO

# executa uma distribuição linux
wsl -d NOME-DISTRIBUIÇÃO

# parar uma distribuição 
wsl --terminate NOME-DISTRIBUIÇÃO

# remove uma distribuição
 wsl --unregister NOME-DISTRIBUIÇÃO

# reiniciar o WSL pode ajudar a resolver problemas de integração com o Docker.
wsl --shutdown

# set uma determinada distribuição para ser a padrão
wsl -s NOME-DISTRIBUIÇÃO

# Comandos de Docker.

Objetos docker = conteiner, imagens(imagens são deplantes, um modelo que especifica como criar uma imagem)
Brincar com Hostinger vps
n8n IA para criar chatbox, etc...
Criar volumes e vincular esses volumes em um conteiner.
Estudar o docker compose...

docker run -it --nameDoConteiner -d NomeDaImagem:tag -> Cria e inicializa um conteiner 
docker ps -> lista os conteiners em execução
docker ps -a -> lista todos conteiners.
docker start -> inicia o conteiner.
docker stop -> Para o conteiner.
docker rm -> remove um conteiner.
docker rmi -> remove uma imagem.
docker exec -it NomeDoConteiner seguidoDaAplicação-> executa o conteiner.



