# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

- Para poder desplegar la aplicacion a Githubpages fueron necesarios los siguientes pasos:
git init
git remote add origin https://github.com/ErikaHernandez-bot/aluraChallenge

Agregar a vite.config.js
base:'https://ErikaHernandez-bot.github.io/aluraChallenge' después de plugins

En terminal:
 npm i --save-dev gh-pages Se instala libreria oficial de github pages

Agregar a package.json: 
Antes de versión:
 "homepage": "https://github.com/ErikaHernandez-bot/aluraChallenge",
En scripts:
"preview": "vite preview",
"predeploy": "npm run build",
"deploy": "gh-pages -d dist" 

En la terminal 
nvm use 20.11.0 version usada 
npm install agregar dependencias
npm install @mui/material @emotion/react @emotion/styled agregar el boton de material UI
npm run deploy


