# Git
Aulas de Git e Github<br>
[Ir para vídeos aulas](https://www.youtube.com/watch?v=iQn5vZt0iWI&list=PLpaKFn4Q4GMOhOuffvi7VagNib0P325AV)


## Configurando o git Local

git config --global user.name "Nome"<br>
git config --global user.email "Email do github"<br>

## Configurando o chave SSH
ssh-keygen -t rsa -b 4096 -C "seu_email@example.com"<br>
cat ~/.ssh/id_rsa.pub <br>
cat ~/.ssh/id_rsa.pub 

## Comandos

#### git init
Iniciando o GIT que será gerado a pasta .git

#### git branch 
Diretorios em quem os arquivos commitados ficam.

#### git status 
Verifica como está os status dos arquivos antes do commit.

#### git add .
Adicionando os arquivos para poder ser feito um commit.

#### git add 
Nome do arquivo expecifico depois do add "git add arquivo.md".

#### git commit -m "" 
Commitando o arquivos adicionados.

#### git remote add origin ur_do_github
Git local esta se comunicando com o git remoto

#### git remote get-url origin
Aparece a url que foi configurada

#### git push -u origin Nome_da_Branch
Subindo todos os commits para o git remoto na Branch origin

#### git log
Verificar o commits que foram realizados assim como o reponsavel, data e hora.

#### git log --pretty=oneline
Mostrar um resumo dos commits.

#### git diff 
Mostra o que foi feito nos arquivos commitados

#### git restore --staged arquivo
Eles exclui o arquivo do commit

#### git branch -M master
Renomear uma branch