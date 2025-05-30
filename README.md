# 📘 Git Básico RocketSeat

Bem-vindo ao repositório **Git Básico**, ideal para quem está começando no mundo do versionamento de código. Aqui você encontrará:

- ✅ Conceitos fundamentais
- 💻 Instalação passo a passo em diferentes sistemas operacionais
- 🧩 Comandos essenciais com explicações claras
- 🧠 Dicas práticas para o dia a dia com Git
- 🔁 Fluxo básico de trabalho com Git e GitHub
- 📚 Recursos extras e links úteis

---

## 🧠 O que é Git?

**Git** é um sistema de controle de versão distribuído, gratuito e de código aberto, criado por Linus Torvalds. Ele é amplamente utilizado para registrar mudanças em arquivos, colaborar em projetos e garantir a integridade do histórico de desenvolvimento.

Com o Git, você pode:
- 📂 Controlar versões de arquivos e código-fonte
- 🤝 Colaborar com outros desenvolvedores
- 🔙 Reverter alterações problemáticas
- 🚀 Trabalhar com branches para desenvolver funcionalidades paralelas
- ☁️ Subir seu projeto para repositórios como o GitHub ou GitLab

---

## 🖥️ Instalação

### 🪟 Windows
1. Acesse: [https://git-scm.com/downloads](https://git-scm.com/downloads)
2. Baixe o instalador para Windows
3. Execute e siga as instruções (pode manter as configurações padrão)

### 🐧 Linux (Debian/Ubuntu)
```bash
sudo apt update
sudo apt install git
```

### 🍎 macOS (via Homebrew)
```bash
brew install git
```

Caso não tenha o Homebrew instalado, instale com:
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

---

## ⚙️ Configurações iniciais

Após instalar o Git, é importante configurar seu nome e e-mail (serão usados nos commits):

```bash
git config --global user.name "Seu Nome"
git config --global user.email "seu@email.com"
```

Você pode verificar as configurações com:
```bash
git config --list
```

---

## 🧩 Comandos básicos do Git

### 📂 Criar um novo repositório
```bash
git init
```
Cria um novo repositório Git na pasta atual.

### 🔄 Clonar um repositório existente
```bash
git clone https://github.com/usuario/repositorio.git
```
Baixa um repositório remoto para sua máquina.

### 📥 Verificar status do repositório
```bash
git status
```
Mostra alterações feitas, arquivos não rastreados e prontos para commit.

### ➕ Adicionar alterações ao stage
```bash
git add .
```
Adiciona todas as mudanças ao stage (preparação para commit).

### 💾 Salvar mudanças
```bash
git commit -m "Mensagem do commit"
```
Cria um ponto de salvamento com uma mensagem descritiva.

### 📤 Enviar alterações para o repositório remoto
```bash
git push origin main
```
Envia os commits locais para a branch `main` no GitHub (ou outro remoto).

### 📥 Baixar alterações do remoto
```bash
git pull origin main
```
Atualiza seu repositório local com as mudanças do remoto.

### 🌿 Criar uma nova branch
```bash
git checkout -b nome-da-branch
```
Cria e muda para uma nova branch.

### 🔁 Mudar de branch
```bash
git checkout main
```
Volta para a branch `main`.

---
