## AUTOMATIZACAO DE API REST / CYPRESS

* Instalando o Cypress
 * - npm install cypress - Aqui instala a ultima versão.
 * - npm install cypress@13.0.6 - Aqui voce set uma versão.

* inicializando o Cypress.
 * - npx cypress open

  * Criando um novo projeto no Cypress.
  * - npm init -y

## SUBINDO O SERVIDOR SERVEREST

* Subindo o Serverest
 * - npx serverest
 * - http://localhost:3000

## CONFIGURANDO UM DOCUMENTO DO CYPRESS.

* Incluir a linha de Referencia no arquivo do Cypress.
 * - /// <reference types = "cypress"/>


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