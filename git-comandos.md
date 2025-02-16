# **Comandos**   

📌 Configuração Inicial
```bash
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@example.com"
git config --list  # Ver configurações do Git
```

📁 Inicializar e Clonar Repositório
```bash
git init  # Inicializa um novo repositório Git
git clone <URL-do-repositório>  # Clona um repositório remoto para sua máquina
```

📄 Verificar Status e Logs
```bash
git status  # Mostra o status do repositório (arquivos modificados, não rastreados, etc.)
git log  # Exibe o histórico de commits
git log --oneline --graph --all  # Exibe o histórico de forma compacta
```

📂 Adicionar e Confirmar Arquivos
```bash
git add <arquivo>  # Adiciona um arquivo específico para staging
git add .  # Adiciona todos os arquivos modificados para staging
git commit -m "Mensagem do commit"  # Salva as mudanças no histórico
git commit --amend -m "Nova mensagem"  # Edita o último commit
```

🔄 Sincronização com Repositório Remoto
```bash
git remote add origin <URL-do-repositório>  # Adiciona um repositório remoto
git remote -v  # Lista os repositórios remotos configurados
git push origin <branch>  # Envia mudanças para o repositório remoto
git pull origin <branch>  # Baixa atualizações do repositório remoto
git fetch  # Obtém as mudanças remotas sem aplicar
```

🌿 Trabalhando com Branches
```bash
git branch  # Lista todas as branches do repositório
git branch <nome-da-branch>  # Cria uma nova branch
git checkout <nome-da-branch>  # Alterna para outra branch
git checkout -b <nome-da-branch>  # Cria e troca para uma nova branch
git merge <nome-da-branch>  # Mescla uma branch na atual
git branch -d <nome-da-branch>  # Deleta uma branch local
```

🔄 Desfazendo Mudanças
```bash
git reset --hard HEAD  # Desfaz todas as mudanças desde o último commit
git reset --soft HEAD~1  # Remove o último commit, mantendo os arquivos no staging
git checkout -- <arquivo>  # Restaura um arquivo modificado para o último commit
git revert <commit-hash>  # Cria um novo commit que desfaz um commit anterior
```

🎭 Trabalhando com Stash
```bash
git stash  # Guarda mudanças sem commit temporariamente
git stash list  # Lista os stashes salvos
git stash apply  # Aplica o último stash sem removê-lo
git stash drop  # Remove um stash da lista
```

🔍 Verificando Diferenças
```bash
git diff  # Mostra diferenças entre arquivos modificados e o último commit
git diff --staged  # Mostra diferenças entre staging e o último commit
```









```
