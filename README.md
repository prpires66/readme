# Zodíaco
[![License: MIT](https://img.shields.io/github/license/prpires66/nlw-esports?style=for-the-badge)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

## 1. Objetivo
 Registrar as atividades de estudo desenvolvidas durante o evento **\<NLW/> eSportes - 2022.**

## 2. Descrição
O NLW (*Next Level Week*) é uma ação de marketing da [Rocketseat](https://www.rocketseat.com.br/) focada em programação. A abordagem é de apresentar conteúdos práticos e desenvolver uma aplicação completa em uma semana. O evento e composto de duas trilhas de aprendizagem: **explorer**, para usuários iniciantes e **ignite** para usuários mais experientes. Este projeto acompanha o desenvolvimento da trilha ignite.

## 3. Projetos

* ### 3.1 Aplicação back-end
Desenvolvimento de uma API utilizando [Node.js](https://nodejs.org/) e [SQLite](https://www.sqlite.org/) que retorna um JSON com as informações dos games para uso pelas aplicações front-end.

* ###  3.2 Aplicação front-end mobile
Desenvolvimento de aplicação para celular utilizando [React Native](https://reactnative.dev/) acessando a API do back-end e apresentando os dados no celular.

* ### 3.3 Aplicação front-end web
Desenvolvimento de aplicação para web utilizando [React](https://reactjs.org/) acessando a API do back-end e apresentando os dados no browser.

## 4. Leiaute
O leiaute do projeto pode ser visualizado no link [design do projeto](https://www.figma.com/file/MHLGpGZ8Dq4KTU4o1GIV5M/NLW-eSports-(Community)?node-id=0%3A1). É necessário ter conta no [Figma](https://figma.com) para acessá-lo.

* ### 4.1 Interface mobile
![exemplo-aplicacao](https://user-images.githubusercontent.com/4954302/191538789-bfd785ba-3350-4487-8f46-8b570a6aca8f.png)

## 5. Pré-requisitos

### 5.1 Node.js
> Faça o download e instalação do [Node.js](https://nodejs.org/)
### 5.2 npm
> npm (Node Package Manager)
   ```sh
   npm install npm@latest -g
   ```   
   
## 6. Instalação
### 6.1 Clonar o repositório
   ```sh
   git clone git@github.com:prpires66/nlw-eSports.git
   ```
### 6.2 Acessar o diretório do projeto   
   ```sh
   cd nlw-eSports.git
   ```
### 6.3 Instalar as dependências  
   > Dependências da aplicação server
   ```sh
   cd server && npm install
   ```
   > Dependências da aplicação web
   ```sh
   cd web && npm install
   ```
   > Dependências da aplicação mobile
   ```sh
   cd mobile && npm install
   ```
## 7. Execução
>Serão necessários 02 terminais simultâneos para execucão. Um para o back-end (server) e outrao para o front-end (mobile/web) 
   > Aplicação server
   ```sh
   npm run dev
   ```
   > Aplicação mobile
   ```sh
   npx expo start
   ```
   > Aplicação web
   ```sh
   npm run dev
   ```

## 8. Licença
[![License: MIT](https://img.shields.io/github/license/prpires66/nlw-esports?style=for-the-badge)

> Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](./LICENSE.md) para mais detalhes.
