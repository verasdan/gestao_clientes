<h1 align="center"> Gestão Clientes </h1>

<p align="center">
   <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square"/>
   <img src="https://img.shields.io/github/repo-size/verasdan/gestao_clientes?color=brightgreen"/>
  <a href="https://github.com/verasdan/gestao_clientes/commits/master">
  <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/verasdan/gestao_clientes">
  </a>
  <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">
  <img src="https://img.shields.io/github/contributors/verasdan/gestao_clientes?color=brightgreen"/>
  </a>
  <a href="https://github.com/verasdan/gestao_clientes/stargazers">
  <img alt="Stargazers" src="https://img.shields.io/github/stars/verasdan/gestao_clientes?style=social">
  </a>
</p>

---


<p align="center">
 <a href="#-sobre-o-projeto">Sobre</a> •
 <a href="#-funcionalidades">Funcionalidades</a> •
 <a href="#-layout">Layout</a> • 
 <a href="#-como-executar-o-projeto">Como executar</a> • 
 <a href="#-tecnologias">Tecnologias</a> • 
 <a href="#-contribuidores">Contribuidores</a> • 
 <a href="#-autor">Autor</a> • 
 <a href="#user-content--licença">Licença</a>
</p>

## Índice 

* [Sobre](#-sobre-o-projeto)
* [Descrição do Projeto](#descrição-do-projeto)
* [Status do Projeto](#status-do-Projeto)
* [Funcionalidades](#-funcionalidades)
* [Acesso ao Projeto](#acesso-ao-projeto)
* [Tecnologias utilizadas](#tecnologias-utilizadas)
* [Pessoas Contribuidoras](#pessoas-contribuidoras)
* [Pessoas Desenvolvedoras do Projeto](#pessoas-desenvolvedoras)
* [Licença](#licença)
* [Conclusão](#conclusão)


## 💻 Sobre o projeto

♻️ Ecoleta - é uma forma de conectar empresas e entidades de coleta de resíduos orgânicos e inorgânicos as pessoas que precisam descartar seus resíduos de maneira ecológica.


Projeto desenvolvido durante a **NLW - Next Level Week** oferecida pela [Rocketseat](https://blog.rocketseat.com.br/primeira-next-level-week/).
O NLW é uma experiência online com muito conteúdo prático, desafios e hacks onde o conteúdo fica disponível durante uma semana.

---
## STATUS
<br>

> Status do Projeto: Concluido :heavy_check_mark:


## Deploy da Aplicação com Heroku: :dash:

> https://client-management-project.herokuapp.com/

<br>

---

## ⚙️ Funcionalidades

<br>

- [x] Empresas ou entidades podem se cadastrar na plataforma web enviando:
  - [x] uma imagem do ponto de coleta
  - [x] nome da entidade, email e whatsapp
  - [x] e o endereço para que ele possa aparecer no mapa
  - [x] além de selecionar um ou mais ítens de coleta: 
    - lâmpadas
    - pilhas e baterias
    - papéis e papelão
    - resíduos eletrônicos
    - resíduos orgânicos
    - óleo de cozinha

- [x] Os usuários tem acesso ao aplicativo móvel, onde podem:
  - [x] navegar pelo mapa para ver as instituições cadastradas
  - [x] entrar em contato com a entidade através do E-mail ou do WhatsApp

---

## 🎨 Layout

O layout da aplicação está disponível no Figma:

<a href="https://www.figma.com/file/1SxgOMojOB2zYT0Mdk28lB/Ecoleta?node-id=136%3A546">
  <img alt="Made by tgmarinho" src="https://img.shields.io/badge/Acessar%20Layout%20-Figma-%2304D361">
</a>


### Mobile

<p align="center">
  <img alt="NextLevelWeek" title="#NextLevelWeek" src="./assets/home-mobile.png" width="200px">

  <img alt="NextLevelWeek" title="#NextLevelWeek" src="./assets/detalhes-mobile.svg" width="200px">
</p>

### Web

<p align="center" style="display: flex; align-items: flex-start; justify-content: center;">
  <img alt="NextLevelWeek" title="#NextLevelWeek" src="./assets/web.svg" width="400px">

  <img alt="NextLevelWeek" title="#NextLevelWeek" src="./assets/sucesso-web.svg" width="400px">
</p>

---

## 🚀 Como executar o projeto

Este projeto é divido em três partes:
1. Backend (pasta server) 
2. Frontend (pasta web)
3. Mobile (pasta mobile)

💡Tanto o Frontend quanto o Mobile precisam que o Backend esteja sendo executado para funcionar.

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/). 
Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)

#### 🎲 Rodando a aplicação web (Frontend)

```bash

# Clone este repositório
$ git clone git@github.com:verasdan/gestao_clientes.git

# Acesse a pasta do projeto no terminal/cmd
$ cd gestao_clientes

# Vá para a pasta server
$ cd server

# Instale as dependências
$ python manage.py migrate

# Execute a aplicação em modo de desenvolvimento
$ python manage.py runserver

# O servidor inciará na porta:8000 - acesse http://localhost:8000 

```

---

## 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

Bootstrap 3 ou 4
AngularJS 1.6 / Angular 2+/4/5/6
PHP 5 ou 7
Python 2.7 ou 3,6
Rails 4 ou 5

#### **Website**  ([React](https://reactjs.org/)  +  [TypeScript](https://www.typescriptlang.org/))

-   **[React Router Dom](https://github.com/ReactTraining/react-router/tree/master/packages/react-router-dom)**
-   **[React Icons](https://react-icons.github.io/react-icons/)**
-   **[Axios](https://github.com/axios/axios)**
-   **[Leaflet](https://react-leaflet.js.org/en/)**
-   **[React Leaflet](https://react-leaflet.js.org/)**
-   **[React Dropzone](https://github.com/react-dropzone/react-dropzone)**

> Veja o arquivo  [package.json](https://github.com/tgmarinho/README-ecoleta/blob/master/web/package.json)

#### [](https://github.com/tgmarinho/Ecoleta#server-nodejs--typescript)**Server**  ([NodeJS](https://nodejs.org/en/)  +  [TypeScript](https://www.typescriptlang.org/))

-   **[Express](https://expressjs.com/)**
-   **[CORS](https://expressjs.com/en/resources/middleware/cors.html)**
-   **[KnexJS](http://knexjs.org/)**
-   **[SQLite](https://github.com/mapbox/node-sqlite3)**
-   **[ts-node](https://github.com/TypeStrong/ts-node)**
-   **[dotENV](https://github.com/motdotla/dotenv)**
-   **[Multer](https://github.com/expressjs/multer)**
-   **[Celebrate](https://github.com/arb/celebrate)**
-   **[Joi](https://github.com/hapijs/joi)**

> Veja o arquivo  [package.json](https://github.com/tgmarinho/README-ecoleta/blob/master/server/package.json)

#### [](https://github.com/tgmarinho/Ecoleta#mobile-react-native--typescript)**Mobile**  ([React Native](http://www.reactnative.com/)  +  [TypeScript](https://www.typescriptlang.org/))

-   **[Expo](https://expo.io/)**
-   **[Expo Google Fonts](https://github.com/expo/google-fonts)**
-   **[React Navigation](https://reactnavigation.org/)**
-   **[React Native Maps](https://github.com/react-native-community/react-native-maps)**
-   **[Expo Constants](https://docs.expo.io/versions/latest/sdk/constants/)**
-   **[React Native SVG](https://github.com/react-native-community/react-native-svg)**
-   **[Axios](https://github.com/axios/axios)**
-   **[Expo Location](https://docs.expo.io/versions/latest/sdk/location/)**
-   **[Expo Mail Composer](https://docs.expo.io/versions/latest/sdk/mail-composer/)**

> Veja o arquivo  [package.json](https://github.com/tgmarinho/README-ecoleta/blob/master/mobile/package.json)

#### [](https://github.com/tgmarinho/Ecoleta#utilit%C3%A1rios)**Utilitários**

-   Protótipo:  **[Figma](https://www.figma.com/)**  →  **[Protótipo (Ecoleta)](https://www.figma.com/file/1SxgOMojOB2zYT0Mdk28lB/Ecoleta)**
-   API:  **[IBGE API](https://servicodados.ibge.gov.br/api/docs/localidades?versao=1)**  →  **[API de UFs](https://servicodados.ibge.gov.br/api/docs/localidades?versao=1#api-UFs-estadosGet)**,  **[API de Municípios](https://servicodados.ibge.gov.br/api/docs/localidades?versao=1#api-Municipios-estadosUFMunicipiosGet)**
-   Maps:  **[Leaflet](https://react-leaflet.js.org/en/)**
-   Editor:  **[Visual Studio Code](https://code.visualstudio.com/)**  → Extensions:  **[SQLite](https://marketplace.visualstudio.com/items?itemName=alexcvzz.vscode-sqlite)**
-   Markdown:  **[StackEdit](https://stackedit.io/)**,  **[Markdown Emoji](https://gist.github.com/rxaviers/7360908)**
-   Commit Conventional:  **[Commitlint](https://github.com/conventional-changelog/commitlint)**
-   Teste de API:  **[Insomnia](https://insomnia.rest/)**
-   Ícones:  **[Feather Icons](https://feathericons.com/)**,  **[Font Awesome](https://fontawesome.com/)**
-   Fontes:  **[Ubuntu](https://fonts.google.com/specimen/Ubuntu)**,  **[Roboto](https://fonts.google.com/specimen/Roboto)**


---

## 💪 Como contribuir para o projeto

1. Faça um **fork** do projeto.
2. Crie uma nova branch com as suas alterações: `git checkout -b my-feature`
3. Salve as alterações e crie uma mensagem de commit contando o que você fez: `git commit -m "feature: My new feature"`
4. Envie as suas alterações: `git push origin my-feature`
> Caso tenha alguma dúvida confira este [guia de como contribuir no GitHub](./CONTRIBUTING.md)

---

## 🦸 Autor

<a href="https://github.com/verasdan">
 <img style="border-radius: 50%;" src="https://media.discordapp.net/attachments/891798888594436199/980284436954357780/perfil_dan.jpg?width=406&height=406" width="100px;" alt="foto"/>
 <br />
 <sub><b>Dan Veras</b></sub></a> <a href="https://github.com/verasdan" title="">🚀</a>
 <br />

[![Twitter Badge](https://img.shields.io/badge/-@veras_dan-1ca0f1?style=flat-square&labelColor=1ca0f1&logo=twitter&logoColor=white&link=https://twitter.com/veras_dan)](https://twitter.com/veras_dan) [![Linkedin Badge](https://img.shields.io/badge/-Danilo_Veras-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/verasdanilo/)](https://www.linkedin.com/in/verasdanilo/) 
[![Hotmail Badge](https://img.shields.io/badge/-veras_dan@hotmail.com-0078D4?style=flat-square&logo=microsoft-outlook&logoColor=white&link=mailto:veras_dan@hotmail.com)](mailto:veras_dan@hotmail.com)

---

## 📝 Licença

Este projeto esta sobe a licença [MIT](./LICENSE).

Feito com ❤️ por Dan Veras 👋🏽 [Entre em contato!](https://www.linkedin.com/in/verasdanilo/)

---








<p align="center">
  
</p>

<h4 align="center">
  Status: 🚀 Finished
</h4>

<p align="center">
  <a href="#tech-stack">Tech Stack</a> •
  <a href="#contact">Contact</a> 
</p>

## Tech Stack
<img src="https://img.shields.io/badge/Canva-05122A?style=flat&logo=canva" alt="canva Badge" height="25">&nbsp;
<img src="https://img.shields.io/badge/Css3-05122A?style=flat&logo=css3" alt="css3 Badge" height="25">&nbsp;
<img src="https://img.shields.io/badge/Django-05122A?style=flat&logo=django" alt="django Badge" height="25">&nbsp;
<img src="https://img.shields.io/badge/Figma-05122A?style=flat&logo=figma" alt="figma Badge" height="25">&nbsp;
<img src="https://img.shields.io/badge/Git-05122A?style=flat&logo=git" alt="git Badge" height="25">&nbsp;
<img src="https://img.shields.io/badge/Html5-05122A?style=flat&logo=html5" alt="html5 Badge" height="25">&nbsp;
<img src="https://img.shields.io/badge/Illustrator-05122A?style=flat&logo=adobeillustrator" alt="illustrator Badge" height="25">&nbsp;
<img src="https://img.shields.io/badge/Javascript-05122A?style=flat&logo=javascript" alt="javascript Badge" height="25">&nbsp;
<img src="https://img.shields.io/badge/Laravel-05122A?style=flat&logo=laravel" alt="laravel Badge" height="25">&nbsp;
<img src="https://img.shields.io/badge/Mysql-05122A?style=flat&logo=mysql" alt="mysql Badge" height="25">&nbsp;
<img src="https://img.shields.io/badge/Php-05122A?style=flat&logo=php" alt="php Badge" height="25">&nbsp;
<img src="https://img.shields.io/badge/Vuejs-05122A?style=flat&logo=vuedotjs" alt="vuejs Badge" height="25">&nbsp;

