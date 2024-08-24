## AUTOMATIZACAO DE API REST / CYPRESS
### USANDO O CYPRESS COMO O FRAMEWORK.

## INTALANDO PROGRAMAS PARA USO DO CYPRESS.

* Instalando o Node JS
  * - link para instalação do Node JS.
  https://nodejs.org/en/download/prebuilt-installer

  * - Verificar o versão do node js. = `node -v`

* Instalando o Visual Studio
  * - link para instalação do VS Code.
  https://code.visualstudio.com/download

  * - verificar a versao do virtual studio = `code -v`

* Instalando o Extensao no Visual Studio.
  * - Cypress Snippets,
  * - ES6 Mocha Snippets,

* Instalando o Cypress
 * - npm install cypress - Aqui instala a ultima versão.
 * - npm install cypress@13.0.6 - Aqui voce set uma versão.

* inicializando o Cypress.
 * - npsx cypress open

  * Criando um novo projeto no Cypress.
  * - npm init -y

## SUBINDO O SERVIDOR SERVEREST

* Subindo o Serverest
 * - npx serverest
 * - http://localhost:3000

## CONFIGURANDO UM DOCUMENTO DO CYPRESS.

* Incluir a linha de Referencia no arquivo do Cypress.
 * /// <reference types = "cypress"/>


const { defineConfig } = require("cypress");

module.exports = defineConfig({
  e2e: {
    setupNodeEvents(on, config) {
      // implement node event listeners here
    },
    baseUrl: "http://localhost:3000"
    
  },
});

* Configurar uma url base.
 * `cypress.config.js`