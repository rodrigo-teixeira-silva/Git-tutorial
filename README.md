# Curso de Git: Comandos Principais

## 📚 Introdução

O Git é um sistema de controle de versão distribuído, amplamente utilizado para o desenvolvimento de software. Este curso irá abordar os principais comandos do Git, ajudando você a gerenciar e versionar seu código de forma eficiente.

# ⚙️ Configuração Inicial

## Configurar Nome e Email

```
git config --global user.name "Seu Nome"

git config --global user.email "seu.email@example.com"
```
Verificar Configurações
```
git config --list
```
# 📁 Criação e Clonagem de Repositórios
## Inicializar um Repositório

```
git init
```
Clonar um Repositório

```
git clone https://github.com/usuario/repositorio.git
```
# 📂 Trabalhando com Arquivos
## Verificar o Status do Repositório

```
git status
```
## Adicionar Arquivos para o Staging

```
git add nome_do_arquivo
```
 adicionar todos os arquivos modificados
```
git add .
```
## Remover Arquivos do Staging
```
git reset nome_do_arquivo
```
## Desfazer Modificações em um Arquivo
```
git checkout -- nome_do_arquivo
```

# 📜 Commit e Histórico

## Fazer um Commit

``` 
git commit -m "Mensagem do commit"
```
## Visualizar Histórico de Commits

```
git log
 ```
## Visualizar Histórico de forma Resumida

```
git log --oneline
 ```
# 🌿 Trabalhando com Branches

## Listar Branches

``` 
git branch
```
## Criar uma Nova Branch
```
git branch nome_da_branch
 ```
## Mudar para uma Branch

``` 
git checkout nome_da_branch
```

## Criar e Mudar para uma Nova Branch
``` 
git checkout -b nome_da_branch
```
## Unir uma Branch à Branch Atual
```
git merge nome_da_branch
 ```
 ## Deletar uma Branch
``` 
git branch -d nome_da_branch
```
# 🔄 Trabalhando com Remotos
## Adicionar um Repositório Remoto

```
git remote add origin https://github.com/usuario/repositorio.git
 ```
 ## Listar Repositórios Remotos
```
 git remote -v
```
## Fazer Push para um Repositório Remoto
```
git push origin nome_da_branch
 ```

 # Fazer Pull de um Repositório Remoto
``` 
git pull origin nome_da_branch
```
# 🔙 Revertendo e Rebasing
## Reverter um Commit

```
git revert hash_do_commit
 ```
 ## Rebase (Reaplicar commits em uma nova base)
``` 
git rebase nome_da_branch
```
# 🛠️ Extras
## Stash (Guardar mudanças temporariamente)

```
git stash
 ```
## Aplicar Stash
```
git stash apply
 ```
 ## Listar Stashes
``` 
git stash list
```
## Excluir um Stash
```
git stash drop
 ```
 <br>
# 🎓 Conclusão
 Este curso abordou os comandos principais do Git. Com esses comandos, você estará apto a gerenciar seus projetos de forma eficiente e colaborativa. Pratique bastante e consulte a documentação oficial do Git:
[Site Oficial do Git](https://git-scm.com) para aprofundar seus conhecimentos.