# electron-calculadora-media

## Descrição
Este é um projeto de uma calculadora de média desenvolvida utilizando Electron.

## Funcionalidades
- Calcula a média de quatro valores inseridos pelo usuário.
- Permite abrir uma janela de informações sobre o projeto.

## Tecnologias Utilizadas
- Electron
- HTML/CSS/JavaScript

## Configuração do Ambiente de Desenvolvimento
Para configurar o ambiente de desenvolvimento local, siga as instruções abaixo:

1. Clone o repositório.
2. Instale as dependências com `npm install`.
3. Execute o aplicativo com `npm start`.

## Estrutura de Pastas e Arquivos
```bash
calculadora-media/
├── app/
│   ├── index.html          # Página principal da aplicação
│   ├── sobre.html          # Página 'Sobre' da aplicação
│   ├── assets/
│   │   └── styles.css      # Arquivo de estilos CSS
│   ├── js/
│   │   └── calculadora.js  # Lógica da calculadora
├── main.js                 # Arquivo principal da aplicação Electron
├── preload.js              # Script de pré-carregamento para Electron
└── package.json            # Configurações do projeto
