
### **Adicionar arquivos ao Staging (track file):**
`git add (nome do arquivo)`
`git add .`
### **Remover arquivos do Staging:**
`git rm --cached (nome do arquivo)`
`git rm --cached .`
### **Cria uma nova versão para o repositório:**
`git commit -m 'mensagem do commit'`
### **Ver o histórico de commits (versões):**
`git log` 
`git log --oneline`
`git log -(numero de commits que você quer ver)`
### **Edita commit atual:**
`git commit --amend`
### **Navegar entre Commits:**
1. `git log --oneline`
2. `git checkout (id do commit)`
### **Reverter um arquivo para o ultimo Commit:**
`git checkout (nome do arquivo)`
### **Remover arquivos fora do git add (fora do staging):**
`git clean -f`
### **Criar um .gitignore:**
`touch .gitignore`
### **Enviar atualizações para o Repositório:**
`git push`
### Atualizar repositório local:
`git pull`
## **Abrir um Repositório pela linha de comando**
`cd (nome da pasta)`
**linux:**
`start` 
**windows:**
`explorer .`
## **Gerar uma chave SSH:**
`ssh-keygen`
A chave ficará numa pasta chamada .ssh
## **Criar uma Branch e entrar nela:**
`git checkout -b (nome da branch)`
## **Listar todas as Branchs:**
`git branch --list`
## **Mandar a Branch para o repositório:**
`git --u origin develop`
## **Remover Branch locais:**
`git branch -d (nome da branch)`
## **Remover Branch remota:**
`git push --delete origin (nome da branch)`
## **Renomear uma Branch:**
`git branch -m (nome antigo) (nome novo)`
## **Puxar alterações de uma Branch para outra:**
*Trazer as alterações de developer para a branch main.*
`git merge main developer`
## **Voltar no commit Head (ultimo commit):**
*(volta a branch  um commit anterior)*
`git reset --hard HEAD~1`
*(volta a branch 2 commits)*
`git reset --hard HEAD~2`
*(forçar o repositório remoto a ficar igual ao local)*
`git push --force`
## **Voltar o repositório para um commit específico:**
`git reset --hard (id do commit)`
`git push -force`
