# studies-node
Estudos relacionados ao node.js sua aplicação e implementação de frameworks que apoiam no desenvolvimento.

A playlist que encontrei e achei bem completa sobre o conteúdo é do seguinte canal: https://www.youtube.com/watch?v=IPbLptXXXc0&list=PLJ_KhUnlXUPtbtLwaxxUxHqvcNQndmI4B&index=12

## Node.js
É um interpretador de Javascript, nos permiti desenvolver e visualizar sem a necessidade de navegador.

### Instalação do node.js
1. Download da versão (LTS) mais atual (https://nodejs.org/pt)
2. Abrir painél de comando (CMD) -> E a partir daí conseguimos iniciar o nosso trabalho com node. 

### Comandos básicos para navegação
1. Acessar pasta <br>
`cd <pasta/diretório>` (Mudar diretório)
2. Executar arquivo
   `node <nome do arquivo>`

#### Módulos
- Aqui conseguimos quebrar nossas funções em arquivos diferentes e com isso acessar todas essas funções através da importação, linha de código de utilização:

1. Exportação para que possa ser importado no arquivo principal
   `export deafult <nome da função>;`
2. Importar na página principal
   `import <nome da função> from 'diretório'`

#### Rotas
-> Conseguimos a partir delas carregar módulos

Para chamar o express usamos as seguintes variáveis:
1. Chamar o módulo do express
`var express = require('express')`
2. Vincular os arquivos do express ao site que iremos trabalhar.
`var app = express()`

- Parâmetros
  Para a criação de rotas dinâmicas usamos os parâmetros, exemplo:
  ./:nome/:cargo

`app.get ("/", function (req, res) {
  res.send(Bem vindo)
})`

#### Módulo NODEMON
É um módulo que ao ser modificado os arquivos identifica e salva automaticamente no servidor.

Instalar o NODEMON:
- `npm install nodemon -g` (Garante com que se aplique globalmente implementando esse módulo em todos os arquivos)


