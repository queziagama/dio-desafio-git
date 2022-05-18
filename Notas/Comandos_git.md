# Comandos git

## Comandos de navegação

 - `cd + /caminho/ ` redireciona o terminal para o diretório/pasta local desejado

## Clonando e commitando

Comandos utilizados no terminal:

 - `git clone <+ link>` clona o repositório e envia para a máquina local
 - `git status`  informa o status do repositório
 - `git add .` prepara o git para o commit na máquina local
 - `git commit -m  "comentário entre aspas duplas"` faz o commit e inclui comentário, porém apenas no diretório local
 - `git push` envia os commits locais para a nuvem no github ou `git push origin master`
 - `git pull origin master` atualiza os arquivos no diretório local 
 - `git checkout -b master` cria a branch master
 
 ## Force
 
 Atenção: quando utilizar o comando `--force` os arquivos serão sobrescritos (apagados e substituídos pelos do novo commit).
 Caso realmente queira fazer isso, utilize o comando:
 
 `git push origin master --force`
 
## Unir comandos

Podemos unir os comandos ao invés de utilizar o terminal várias vezes. Para produzir o mesmo efeito de:

`git clone git@github.com:repositorio/teste.git` 
`cd teste`
`atom . `

é possível utilizar`&&` para unir comandos, por exemplo mudar de diretório `cd` ou executar programas `<nome + .>`:

`git clone git@github.com:repositorio/teste.git && cd teste && atom . `

## Forks & Pull Requests

- clonar
- alterar
- pull request
- merge - quando há alterações (e no local tb? - ver dps e botar imagensss)
Fazer um fork de um diretório online em seu perfil, e depois cloná-lo para o diretório local.
