# Estudo-Cypress
Estudo sobre automação com Cypress

Automação Web todoMVC com Cypress
Este projeto realiza a automação do site todoMVC utilizando o framework Cypress.

Tecnologias Utilizadas
Node.js (v18.16.1)
Cypress
Documentações

Estrutura de PageObjects para Automação
O projeto utiliza uma estrutura de PageObjects para organizar a automação.

Configuração do Projeto
Instale o Node.js: Baixe aqui

Instale o Yarn:

npm install -g yarn
Crie a pasta do projeto

Abra o Visual Studio Code para instalar o Cypress:

npm install -g cypress
Inicialize o projeto:

npm init
Adicione o Cypress ao seu projeto:

yarn add cypress --dev
Como Rodar os Testes
Abra o Cypress:

yarn run cypress open
Escolha uma spec para executar.

Testes Criados
Adicionar Texto
Concluir Item
Filtrar Item
Deletar Item
Specs de Testes
Cada ação no site possui specs de testes separados.
Existe também a spec regressiva regressivoToDoApp, que engloba todas as ações em uma única spec.
