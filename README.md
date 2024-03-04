# Lista Tarefas

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white) ![JSON](https://img.shields.io/badge/JSON-black?style=for-the-badge&logo=JSON%20web%20tokens) ![NodeJS](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white) ![ANGULAR](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white) ![RxJs](https://img.shields.io/badge/RxJs-404D59?style=for-the-badge)

## Aplicativo para gerenciamento de tarefas baseado em JSON-SERVER no Back End e Angular no Front End

### O Lista Tarefas é uma aplicativo que faz o gerenciamento e inclusão de tarefas diárias.

### É um MVP que tá só começando e ainda tem muitas funcionalidades novas para serem desenvolvidas.

### Baseado em curso de formação para atualização profissional chamado “Angular: torne sua aplicação interativa e personalizada com animações”, disponibilizado pela Alura e ministrado pela instrutora Nayanne Batista. Nesta oportunidade pude atualizar meus conhecimentos em:

* Aprender a utilizar o módulo de animações do Angular
* Entender como adicionar gatilhos nos elementos do template com o método trigger
* Saber como animar diferentes estados do elemento com os métodos state e style
* Aplicar diferentes formas de adicionar animações às transições de estado do elemento com os métodos transition e animate
* Conhecer os estados reservados void e coringa
* Animar elementos que não estão anexados ao DOM com :enter e :leave

## 🛠️ Instalação

### Back End

```bash
$ npm install
$ npm run start
```

### Front End

```bash
$ npm install
$ npm run start
```

## 🛠️ Como utlizar

### Servidor de desenvolvimento (BackEnd)

* Execute `npm run start` para um servidor de desenvolvimento.
* Navegue até `http://localhost:3000/`.
* O aplicativo será recarregado automaticamente se você alterar algum dos arquivos de origem.

### Como rodar a API

* No terminal, acesse a pasta raiz do projeto e insira o comando `npm run start` para rodar o projeto em modo de desenvolvimento. Você deverá ver no terminal a seguinte mensagem:

  ```
  > api-js-local@1.0.0 dev
  > nodemon server.js

  [nodemon] 2.0.16
  [nodemon] to restart at any time, enter `rs`
  [nodemon] watching path(s): *.*
  [nodemon] watching extensions: js,mjs,json
  [nodemon] starting `node server.js`
  Servidor escutando em http://localhost:3000
  ```

* Esta API está programada para ser acessada a partir de `http://localhost:3000`. 
* Certifique-se de que não existem outros recursos ocupando a porta `3000` antes de subir o projeto.

### Endpoints

A API expõe os seguintes *endpoints* a partir da *base URL* `localhost:3000`:

`/tarefas`

* `GET /tarefas`
* `GET /tarefas/:id`
* `POST /tarefas`
* `PUT /tarefas/:id`
* `DELETE /tarefas/:id`

### Servidor de aplicação (FrontEnd)

* Execute `npm run start` para um servidor de desenvolvimento. Navegue até `http://localhost:4200/`.
* O aplicativo será recarregado automaticamente se você alterar algum dos arquivos de origem.

## ⚙️ Andaime de código

* Execute `ng generate component nome-do-componente` para gerar um novo componente.
* Você também pode usar `ng generate directiva|pipe|service|class|guard|interface|enum|module`.

## 🏗️ Build

* Execute `ng build` para construir o projeto.
* Os artefatos de construção serão armazenados no diretório `dist/`.

## 🧪 Executando testes unitários

* Execute `ng test` para executar os testes de unidade via [Karma](https://karma-runner.github.io).

## 🧪 Executando testes ponta a ponta

* Execute `ng e2e` para executar os testes end-to-end através de uma plataforma de sua escolha.
* Para usar este comando, você precisa primeiro adicionar um pacote que implemente recursos de teste ponta a ponta.
