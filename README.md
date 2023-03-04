# tutorial_git
Tutorial Git

# CLONAR REPOSITÓRIO DO GITHUB PARA A MÁQUINA
git clone link_copiado_do_github

# APRESENTAR O STATUS/SITUAÇÃO DO REPOSITÓRIO
git status

Esse comando mostrará se a branch sofreu alguma alteração, 
se existe algum arquivo que ainda não foi comitado.

# ESTRUTURA GIT-(DIRETÓRIO DE TRABALHO >> git add >> PREPARAÇÃO >> git commit >> REPOSITÓRIO)
Diretório de trabalho:
    - Arquivos:
        - Modificados.
        - Excluídos.
        - Adicionados.

Preparação:
    - Arquivos adicionados e preparados para serem versionados

Repositório:
    - Arquivos salvos.

# ADICIONAR UM ARQUIVO PARA ÁREA DE PREPARAÇÃO
git add nome_do_arquivo.extensão

# ADICIONAR TODOS OS ARQUIVOS PARA ÁREA DE PREPARAÇÃO
git add . 

# COMITAR UM ARQUIVO PARA REPOSITÓRIO
git commit -m "mensagem"

# VER O LOG DOS COMMITS REALIZADOS
git log

# COLOCAR OS DADOS COMITADOS PARA O GITHUB
git push origin nome_da_branch

# TRAZER OS DADOS NA BRANCH DO GIHUB PARA A MINHA BRANCH
git pull origin nome_da_branch

# LISTAR BRANCHS
git branch

# CRIAR BRANCH
git branch nome_da_branch

# ALTERAR BRANCH
git checkout nome_da_branch

# APAGAR BRANCH
git branch -d nome_da_branch

# MERGEAR BRANCH
git merge nome_da_branch