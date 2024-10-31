# 🎯 Minicurso Introdução a Git & GitHub

Repositório oficial do Curso de Introdução a Git e GitHub! Este repositório foi criado para ensinar e demonstrar conceitos básicos de Git e GitHub. Durante o curso, os alunos praticaram fazendo commits, criando branches e colaborando em equipe.

## 🏅 Objetivo do Curso
O curso foi desenvolvido para introduzir os principais comandos e fluxos de trabalho em Git e GitHub, permitindo que os alunos aprendam a:

- Iniciar um repositório e fazer commits.
- Criar e navegar entre branches.
- Colaborar com outras pessoas usando o GitHub.
- Resolver conflitos e integrar contribuições.

## 🧩 Guia Simplificado

### 1. Configurações iniciais do Git


**Baixando e instalando o Git**
```bash
https://git-scm.com/downloads
```

**Configura nome de usuário**
```bash
git config --global user.name nome-sobrenome
```

**Configura email de usuário**
```bash
git config --global user.email email@email.com.br
```

### 2. Inicializando um repositório


**Inicializa o versionamento no respectivo diretório**
```bash
git init
```

### 3. Comandos básicos para sobreviver


**Verifica o status do repositório**
```bash
git status
```

**Adiciona todos os arquivos para serem commitados**
```bash
git add .
```

**Commitando arquivos**
```bash
git commit -m "inserir um comentário significativo"
```

**Visualizando relatório de commits**
```bash
git log // todos os commits
git log --oneline // exibe log com hash e título do commit
```

**Adicionando um repositório remoto**
```bash
git remote add origin https://github.com/User/Repository.git
```

**Enviando as modificações para o repositório remoto**
```bash
git push origin <branch>
```

**Puxando alterações do repositório remoto**
```bash
git pull origin <branch>
```

### 4. Trabalhando com branchs


**Criando e locomovendo-se para uma nova branch**
```bash
git checkout -b nome-branch 
```

**Aplicando merge em branchs**
```bash
git merge nome-branch // precisa estar na branch de destino
```

**Visualizando todas as branches existentes no repositório**
```bash
git branch
```

**Deletando uma branch local**
```bash
git branch -D nome-branch
```

[Slides Apresentação](https://www.canva.com/design/DAGUorGe3as/76oy6nR9BOFpF4g1KU_W3g/edit?utm_content=DAGUorGe3as&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

