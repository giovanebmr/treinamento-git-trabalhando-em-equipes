# Introdução ao Git e Controle de Versões

 ### git init
 inicia um repositório git local
 ### git clone <<repositorio>>
 clona um repositório
 ### git add . ou git add <<nome_arquivo>>
 adiciona todos os arquivos no repositório para o stage
 ### git commit -m "mensagem commit"
 comita os arquivos adicionados e define uma mensagem de commit
 ### git push
 envia os arquivos commitados para o repositório remoto
 ### git pull
 atualiza o repositório local com base no repositório remoto
 ### git merge
 faz a junção de branchs
 ### git status
 lista informações sobre o repositório local
 ### git log
 lista informações sobre os comits realizados
 ### git branch <<nome_da_branch>>
 cria um novo branch
 ### git remote add origin https://github.com/giovanebmr/treinamento-git-trabalhando-em-equipes.git
 define o repositório remoto
 ### git remote rm origin
 remove o repositório remoto anteriormente definido
 ### git push -u origin master
 envia os arquivos commitados para o repositório remoto definido em sua branch principal
 ### git branch
 lista os branch existentes
 ### git checkout -b <<nome_branch_para_criar_e_alterar>>
 cria uma nova branch e a define como branch corrente
 ### git checkout <<nome_da_branch_para_alterar>>
 altera de uma branch para outra
 ### git branch -D <<nome_da_branch_para_deletar>>
 remove uma branch
 ### git push origin <<nome_branch>>
 envia os arquivos commitados para uma branch remota especificada
 ### git log --stat
 consultar os commits, e suas estatísticas abreviadas, criados no Github 
 ### git commit -a -m "adiciona e comita"
 ### git remote
 ### git tag 'TEXTO'
 Marcar compromissos no git
 ### git rebase <<nome_da_branch>>
 refaz a base do branch onde o comando é executado
 ### git remote -v
 faz com que repositórios remotos sejam listados, até a URL do repositório
 ### git merge <<nome_branch>>
 faz o merge da branch atual com a branch especificada
 ### git commit --amend
 editar a mensagem do último commit
 ### git checkout -- NOME_DO_ARQUIVO
 'resetar' as alterações de um arquivo
 ### git config --global user.name "SEU NOME" - git config --global user.email "SEU ENDEREÇO DE E-MAIL"
 configurar usuario e e-mail na máquina
 ### git reset HEAD NOME_DO_ARQUIVO
 retirar um arquivo adicionado para commitar (após utilizar git add)
 ### git diff NOME_DO_ARQUIVO
 para ver as modificações feitas no arquivo






