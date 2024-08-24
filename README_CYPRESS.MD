## AUTOMATIZACAO DE API REST / CYPRESS
### USANDO O CYPRESS COMO O FRAMEWORK.

### INTALANDO PROGRAMAS PARA USO DO CYPRESS.

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

### INTALANDO AMBIENTE DO CYPRESS.

  * Criando um novo projeto no Cypress.
  * - npm init -y

* Instalando o Cypress
 * - Criar um arquivo com `.gitignore` - node js.
 * - npm install cypress
 ou
 * - npm install cypress@13.0.6

* inicializando o Cypress.
 * - npx cypress open
 * - Template E2E Testing
 * - Navegador Eletron
 * - Scaffold example specs



### CONFIGURANDO UM DOCUMENTO DO CYPRESS.

* Incluir a linha de Referencia no arquivo do Cypress.
 * /// <reference types = "cypress"/>





### SUBINDO O SERVIDOR SERVEREST

* Subindo o Serverest
 * - npx serverest
 * - http://localhost:3000




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