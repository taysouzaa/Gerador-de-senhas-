## Gerador de Senhas Seguras

Este projeto é uma aplicação de linha de comando que gera senhas aleatórias com base nas preferências do usuário.
Ideal para criar senhas fortes e seguras com letras, números e símbolos.

Desenvolvido com **TypeScript**, o projeto é organizado em módulos reutilizáveis e de fácil manutenção.

---

## Funcionalidades

* Definir o tamanho da senha
* Incluir letras maiúsculas e minúsculas
* Incluir números e símbolos
* Geração instantânea de senha aleatória
* Copiar a senha gerada
* Interface via CLI simples e objetiva

---

## Estrutura do Projeto

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

## Como Executar

> Requisitos: Node.js e TypeScript instalados

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/gerador-de-senhas-seguras.git

# Acesse a pasta do projeto
cd gerador-de-senhas-seguras

# Instale as dependências
npm install

# Compile o TypeScript
npx tsc

# Execute a aplicação
node dist/cli.js
```

A aplicação exibirá instruções no terminal para que você defina as opções e gere sua senha segura.

## Demonstração (Simulada)

```
📂 Projeto iniciado...

? Qual o comprimento da senha? 16  
? Incluir letras maiúsculas? (Y/N) y  
? Incluir letras minúsculas? (Y/N) y  
? Incluir números? (Y/N) y  
? Incluir símbolos? (Y/N) y  

🔐 Senha gerada: Gx#9Kw@dR2eT6$Vm
```

---

## Tecnologias Utilizadas

* Node.js
* TypeScript
* CLI (Command Line Interface)
* Módulos ES + boas práticas de projeto

---

## Contribuição

Contribuições são bem-vindas!
Você pode:

1. Fazer um fork do repositório
2. Criar uma branch com suas alterações
3. Abrir um Pull Request com sua sugestão ou melhoria

---
