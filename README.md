# TBC Pokedex - Challenge

## Layout

- Acesse https://www.figma.com/file/jecQlczA93OOOOiKHmolRi/Tbc-pokemon?type=design&node-id=0%3A1&mode=design&t=oaMwzepmnRxNM93J-1

## Api para obter as informações dos pokemons

- https://pokeapi.co/

### Endpoint para listar

https://pokeapi.co/api/v2/pokemon

#### Parametros de url
- limit: numero que representa a quantidade limite de registros na requisição. O padrão para este projeto é 30.
- offset: numero que representa a pagina atual, para trazer a primeira pagina é 0

Exemplo de url para obter os 30 primeiros pokemons da primeira pagina:
https://pokeapi.co/api/v2/pokemon?limit=30&offset=0

## Requisitos de ambiente

- Acesse https://nodejs.org/pt-br/download para baixar e instalar a versão mais recente do Nodejs.

- Acesse https://code.visualstudio.com/download para baixar o Visual studio code

## Instalando as dependencias do projeto

Após ter instalado o NodeJs e o VS Code em seu computador, iremos criar um projeto React usando o vite

Abra o cmd ou o seu terminal e execute os comandos abaixo dentro da pasta que gostaria de ter o projeto.

Este comando ira criar os primeiros arquivos do projeto

```bash
$ npm create vite@latest tbc-pokedex -- --template react-swc-ts
```

Com o projeto criado iremos navegar para dentro da pasta dele

```bash
$ cd tbc-pokedex
```

Uma vez na pasta, iremos instalar todos os modulos que usaremos para a demonstração

```bash
$ npm install react-icons
```

## Instalando a fonte roboto
Copie o codigo abaixo para dentro da tag "head" do seu arquivo index.html

```html
<link rel="preconnect" href="https://fonts.googleapis.com" />
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
<link
  rel="stylesheet"
  href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500;600;700&display=swap"
/>
```

Exemplo de onde colar o codigo acima:
```html
  <head>
    <meta charset="UTF-8" />
    <link rel="icon" type="image/svg+xml" href="/vite.svg" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Vite + React + TS</title>

   <!-- Cole aqui o codigo acima -->
  </head>
```

## Executando o projeto

Abra uma janela do terminal dentro da pasta do projeto e execute o comando abaixo:

```bash
$ npm run dev
```

Com isso rodando, abra o seu navegador e digite a seguinte url: http://localhost:5173/
