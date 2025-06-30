# 🔐 Gerador de Senhas Seguras

Um gerador de senhas aleatórias e seguras via linha de comando (CLI), feito em Node.js + TypeScript.

## Funcionalidades

- Definir o tamanho da senha
- Incluir letras maiúsculas, minúsculas, números e símbolos
- Botão para copiar a senha gerada para a área de transferência
- Interface simples e interativa no terminal

## Como usar

1. **Clone o repositório:**
   ```sh
   git clone https://github.com/seu-usuario/gerador-de-senhas-seguras.git
   cd gerador-de-senhas-seguras
   ```

2. **Instale as dependências:**
   ```sh
   npm install
   ```

3. **Execute o gerador:**
   ```sh
   npx ts-node src/cli.ts
   ```

4. **Siga as instruções no terminal para gerar sua senha.**

## Exemplo de uso

```
🔐 Gerador de Senhas Seguras
Tamanho da senha: 12
Incluir letras maiúsculas? (s/n): s
Incluir letras minúsculas? (s/n): s
Incluir números? (s/n): s
Incluir símbolos? (s/n): n
Senha gerada: XyT8kLmPqRzS
Copiar senha para a área de transferência? (s/n): s
Senha copiada!
```

## Tecnologias

- Node.js
- TypeScript
- [clipboardy](https://www.npmjs.com/package/clipboardy)

## Licença

Este projeto está sob a licença MIT.
