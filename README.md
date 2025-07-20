# 🔐 GERADOR DE SENHAS SEGURAS

Gere senhas fortes e personalizadas diretamente do terminal

[![last commit](https://img.shields.io/github/last-commit/seu-usuario/gerador-de-senhas-seguras)](https://github.com/seu-usuario/gerador-de-senhas-seguras)
[![TypeScript](https://img.shields.io/badge/built_with-TypeScript-3178c6?logo=typescript)]()
[![CLI](https://img.shields.io/badge/interface-CLI-blue)]()

Construído com foco em segurança, performance e simplicidade.

---

## 📌 Visão Geral

O *Gerador de Senhas Seguras* é uma aplicação de linha de comando que gera senhas aleatórias com base nas preferências do usuário.

Ideal para criar senhas fortes e seguras com letras, números e símbolos — tudo de forma rápida e prática via terminal.

Desenvolvido com *TypeScript*, o projeto é organizado em módulos reutilizáveis e de fácil manutenção.

---

## ✨ Funcionalidades

- 🔢 Definir o tamanho da senha  
- 🔠 Incluir letras maiúsculas e minúsculas  
- 🔣 Incluir números e símbolos  
- ⚡ Geração instantânea da senha  
- 📋 Copiar a senha gerada (opcional)  
- 💻 Interface via CLI simples e objetiva  

---

## 🧩 Estrutura do Projeto

```
gerador-de-senhas-seguras/
├── src/
│   ├── app.ts                   # Arquivo principal
│   ├── cli.ts                   # Interface de linha de comando
│   ├── utils/
│   │   └── passwordGenerator.ts # Lógica de geração de senhas
│   └── types/
│       └── index.ts             # Tipagens do projeto
├── package.json                 # Dependências e scripts
├── tsconfig.json                # Configuração do TypeScript
└── README.md                    # Documentação do projeto
```

---

## ⚙ Como Executar

> *Pré-requisitos:* [Node.js](https://nodejs.org/) e [TypeScript](https://www.typescriptlang.org/) instalados

# Clone o repositório
```bash
git clone https://github.com/seu-usuario/gerador-de-senhas-seguras.git
```
# Acesse o diretório
```bash
cd gerador-de-senhas-seguras
```
# Instale as dependências
```bash
npm install
```
# Compile o código TypeScript
```bash
npx tsc
```
# Execute a aplicação
```bash
node dist/cli.js
```

---

💡 Demonstração (Simulada)

📂 Projeto iniciado...

? Qual o comprimento da senha? 16  
? Incluir letras maiúsculas? (Y/N) y  
? Incluir letras minúsculas? (Y/N) y  
? Incluir números? (Y/N) y  
? Incluir símbolos? (Y/N) y  

🔐 Senha gerada: Gx#9Kw@dR2eT6$Vm


---

🛠 Tecnologias Utilizadas

Node.js

TypeScript

CLI (Command Line Interface)

Módulos ES

Boas práticas de projeto



---

🤝 Contribuição

Contribuições são bem-vindas!
Para colaborar:

1. Faça um fork do repositório


2. Crie uma branch com suas alterações


3. Abra um Pull Request com sua sugestão ou melhoria




---

📄 Licença

Este projeto está licenciado sob a MIT License.

---
