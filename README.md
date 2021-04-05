<h1 align="center">
    <img alt="Happy" title="Happy" src=".github/logo.svg" />
</h1>

<p align="center">
  <img alt="Plataforma" src="https://img.shields.io/static/v1?label=Plataforma&message=Mobile/PC&color=64dfdf&labelColor=000000">
	
  <a aria-label="Completado" href="https://nextlevelweek.com/episodios/omnistack/edicao/3">
    <img alt="Happy" src="https://img.shields.io/badge/Happy-NLW 2-64dfdf?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAMAAAAoLQ9TAAAALVBMVEVHcExxWsF0XMJzXMJxWcFsUsD///9jRrzY0u6Xh9Gsn9n39fyMecy0qd2bjNJWBT0WAAAABHRSTlMA2Do606wF2QAAAGlJREFUGJVdj1cWwCAIBLEsRU3uf9xobDH8+GZwUYi8i6ucJwrxKE+7D0G9Q4vlYqtmCSjndr4CgCgzlyFgfKfKCVO0LrPKjmiqMxGXkJwNnXskqWG+1oSM+BSwD8f29YLNjvx/OQrn+g99oQSoNmt3PgAAAABJRU5ErkJggg==&labelColor=000000"></img>
  </a>
</p>

<br>

<p align="center">
  <img alt="Happy" src=".github/happy.png" width="100%">
</p>

## 🚀 Tecnologias

Tecnologias que usadas para desenvolver este aplicativo

- [Node.js](https://nodejs.org/en/)
- [ReactJS](https://reactjs.org/)
- [React Native](https://reactnative.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [Expo](https://expo.io/)
- [Express](https://expressjs.com/pt-br/)
- [TypeORM](https://typeorm.io/#/)
- [Yup](https://github.com/jquense/yup)
- [Axios](https://github.com/axios/axios)
- [React Router DOM](https://reacttraining.com/react-router/)
- [React Navigation](https://reactnavigation.org/)

## 💻 Projeto

O Happy é uma aplicação que conecta pessoas à casas de acolhimento institucional para fazer o dia de muitas crianças mais feliz 💜

## ⚙️ Getting started

Import the `Insomnia.json` on Insomnia App or click on [Run in Insomnia](#insomniaButton) button

### Requirements

- [Node.js](https://nodejs.org/en/)
- [Yarn](https://classic.yarnpkg.com/)
- [Expo](https://expo.io/)

```bash
$ git clone https://github.com/EliasGcf/nlw-3.git && cd nlw-3
```

**Follow the steps below**

### Backend

```bash
# Starting from the project root folder, go to backend folder
$ cd backend

# Install the dependencies
$ yarn

# Use the script to run the migrations
$ yarn typeorm migration:run

# To finish, run the api service
$ yarn dev

# Well done, project is started!
```

### Web

_Obs.: Before to continue, be sure to have the API running_

```bash
# Starting from the project root folder, go to web folder
$ cd web

# Install the dependencies
$ yarn

# Be sure the file 'src/services/api.ts' have the IP to your API

# Start the client
$ yarn start
```

### Mobile

_Obs.: Before to continue, be sure to have the API running_

```bash
# Starting from the project root folder, go to mobile folder
$ cd mobile

# Be sure the file 'src/services/api.ts' have the IP to your API

# Start the expo service and scan the QR code with Expo Client
$ yarn start
```

Feito com ♥ by heylud(Ana) 👋
