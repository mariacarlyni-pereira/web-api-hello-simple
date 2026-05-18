## Web API de Hello World

Um projeto simples em Node.js usando Express e Morgan.

## Visão geral

Este projeto cria um servidor HTTP básico que responde a requisições `GET /` com a mensagem `Hello, World!`.


<img width="1913" height="1027" alt="image" src="https://github.com/user-attachments/assets/32c7d477-8b3e-49a2-b8f4-5a08a5be25dd" />



## Tecnologias

- Node.js
- Express
- Morgan

## Pré-requisitos

- Node.js 18+ instalado
- npm instalado

## Instalação

1. Abra um terminal na pasta do projeto.
2. Execute:

```bash
npm install
```

## Uso

Inicie o servidor com:

```bash
node index.js
```

Em seguida, abra no navegador ou use uma ferramenta como `curl`:

```bash
http://localhost:3000/
```

## Endpoint

- `GET /` - Retorna `Hello, World!`

## Logs

O projeto usa `morgan` para gerar logs de requisição no console.

## Arquivos principais

- `index.js` - ponto de entrada do servidor
- `package.json` - dependências e scripts do projeto
- `requests.http` - exemplo de requisição HTTP para teste local

## Observação

O servidor escuta na porta `3000` e exibe uma mensagem no console quando iniciado.
