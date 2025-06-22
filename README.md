21 /06 / 25 => Dia 06;

## 📘 Comandos Git Essenciais

### 📄 Visualizar histórico e mudanças
- `git status`  
  Mostra os arquivos modificados, adicionados ou removidos

- `git diff`  
  Mostra as alterações nos arquivos ainda não commitadas

- `git log`  
  Lista o histórico completo de commits

- `git log --oneline`  
  Mostra o histórico de commits em uma linha por commit (resumido)

- `git log --oneline --graph --all --decorate`  
  Exibe o histórico com gráfico de branches e tags (visual)

---

### ✅ Adicionar e confirmar mudanças
- `git add .`  
  Adiciona todas as alterações para o próximo commit

- `git commit -m "Mensagem do commit"`  
  Cria um commit com a mensagem especificada

- `git commit --amend`  
  Edita o último commit (útil para corrigir mensagem ou incluir arquivos esquecidos)

---

### 🌐 Trabalhar com repositório remoto
- `git clone <url>`  
  Clona um repositório remoto

- `git push origin main`  
  Envia os commits locais para a branch `main` no repositório remoto

- `git pull origin main`  
  Puxa alterações do repositório remoto para a sua branch atual

---

### 🌿 Branches
- `git branch`  
  Lista as branches locais

- `git checkout -b nome-da-branch`  
  Cria e muda para uma nova branch

- `git checkout nome-da-branch`  
  Muda para uma branch existente

---

### 🔥 Outros úteis
- `git rm --cached nome-do-arquivo`  
  Remove o arquivo do Git mas mantém localmente (para ignorar com `.gitignore`)

- `git reset HEAD nome-do-arquivo`  
  Desfaz o `git add` (unstage)

---
