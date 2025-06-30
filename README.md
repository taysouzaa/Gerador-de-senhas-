# Gerador de Senhas Seguras

Este projeto é um gerador de senhas aleatórias e seguras, permitindo que os usuários criem senhas personalizadas de acordo com suas necessidades.

## Funcionalidades

- **Definir tamanho da senha**: O usuário pode especificar o comprimento da senha desejada.
- **Incluir letras maiúsculas, minúsculas, números e símbolos**: O gerador pode criar senhas que atendem a diferentes requisitos de segurança.
- **Copiar a senha gerada**: O usuário pode facilmente copiar a senha gerada para a área de transferência.
- **Interface simples**: O projeto oferece uma interface de linha de comando (CLI) para interação fácil.

## Estrutura do Projeto

```
gerador-de-senhas-seguras
├── src
│   ├── app.ts          # Ponto de entrada da aplicação
│   ├── cli.ts          # Implementação da interface de linha de comando
│   ├── utils
│   │   └── passwordGenerator.ts  # Função para gerar senhas aleatórias
│   └── types
│       └── index.ts    # Definições de tipos utilizados no projeto
├── package.json         # Configuração do npm
├── tsconfig.json        # Configuração do TypeScript
└── README.md            # Documentação do projeto
```

## Instalação

1. Clone o repositório:
   ```
   git clone <URL_DO_REPOSITORIO>
   ```
2. Navegue até o diretório do projeto:
   ```
   cd gerador-de-senhas-seguras
   ```
3. Instale as dependências:
   ```
   npm install
   ```

## Uso

Para executar o gerador de senhas, utilize o seguinte comando na linha de comando:

```
node dist/cli.js
```

Siga as instruções na tela para definir o tamanho da senha e gerar uma nova senha segura.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir um problema ou enviar um pull request.