# Git e Github

Curso Digital Innovation One - Instrutor : Otávio Reis<br>
Link para o curso: https://web.digitalinnovation.one/course/introducao-ao-git-e-ao-github/learning/75b9fe49-6ed4-4480-83a7-7e37fc356aa9/

## Utilizando terminais

* Windows 
```
> Entrar/Sair de diretórios: cd <foldername>/cd ..
> Listar diretório: dir
> Criar arquivo/pasta: echo > <filename.txt>/mkdir <foldername>
> Deletar arquivo/pasta: del <filename.txt>/rmdir <foldername> /S /Q
> Limpar terminal: cls
```
* Linux
```
> Entrar/Sair de diretórios: cd <foldername>/cd ..
> Listar diretório: ls
> Criar arquivo/pasta: echo > <filename.txt>/mkdir <foldername>
> Deletar arquivo/pasta: rm <filename.txt>/rm -rf <foldername>
> Limpar terminal: clear
```

## Configurando seu git
```
> git config --global user.email "<email>"
> git config --global user.name <name>
```

## Iniciando um repositório
```
> git init
> git add <filename>
> git commit -m "first commit"
> git remote add origin git@github.com:username/repository.git
> git remote set-url origin https://github.com/username/repository.git
> git branch -M main
> git push -u origin main
```

## Clonando repositório

```
> git clone https://github.com/AlanDeveloper/GIT-Course git-clone
```

## Controle de versão

```
> git log
> git log --decorate
> git log --author="Alan"
> git shortlog
> git log --graph
> git log --oneline
```

## Visualizando diferenças antes do commit

```
> git diff
> git diff --name-only
```

## Voltando para versão

```
> git reset --soft(staged) <numbercommit>
> git reset --mixed(untracked) <numbercommit>
> git reset --hard(commit) <numbercommit>
> git revert <numbercommit>
```

## Branchs

```
> git branch
> git checkout -b <namebranch> (Criar um branch)
> git checkout <namebranch> (Mudar de branch)
> git branch -D <namebranch> (Deletar um branch)
```

## Stash

```
> git stash save "first stash"
> git stash list
> git stash pop 1
```
