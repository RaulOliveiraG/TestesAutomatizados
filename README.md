##📌 Introdução a Testes Automatizados com Cypress

Este repositório foi criado com o objetivo de aprender e praticar testes automatizados utilizando o Cypress
, uma das ferramentas mais populares para testes end-to-end (E2E) em aplicações web.

##🚀 O que é o Cypress?
O Cypress é um framework moderno para testes automatizados em aplicações web. Ele permite escrever, executar e depurar testes de forma simples, com suporte nativo para:
✅ Testes End-to-End (E2E)
✅ Testes de Integração
✅ Testes de Componentes
✅ Simulação de eventos do usuário (cliques, digitação, navegação etc.)
✅ Execução rápida e com recarregamento automático

##📂 Estrutura básica do projeto

Após a instalação do Cypress, a estrutura do projeto se parecerá com:

cypress/
  e2e/               # Onde ficam os testes E2E
  fixtures/          # Arquivos de dados estáticos (JSON, mocks, etc.)
  support/           # Configurações globais e comandos customizados
cypress.config.js    # Arquivo de configuração do Cypress

🛠️ Pré-requisitos
Antes de começar, certifique-se de ter instalado:
Node.js
 (versão LTS recomendada)
npm ou yarn

Verifique as versões instaladas:
node -v
npm -v

##📦 Instalação

Clone o repositório e instale as dependências:
git clone https://github.com/seu-usuario/seu-repo.git
cd seu-repo
npm install cypress --save-dev

##▶️ Como rodar os testes
Abrir o Cypress Test Runner:
npx cypress open

Rodar os testes diretamente no terminal (modo headless):
npx cypress run
