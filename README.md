# Poc-Buger-Eats-Cypress

 Projeto feito com os seguintes componentes:

 -Cypress
 
 -NodeJs
 
 -VsCode


# Casos de teste

 CENARIOS 

1-Usuario deve se tornar um entregador

2-Cpf incorreto

3-Email incorreto

4-Campo fazio

#PageObect

Estao na pasta cypress/pages/SignupPage

onde todas as funções para realizar os passos dos cenarios estao feitos 

# Fixtures e Factorie

nesse programa tem duas formas de funcionamento com massa de dados Estatica e Dinamica 

as branch 03 e anteriores estao usando massa de dados estaticas
a massa de dados Estatica está na pasta cypress/fixtures/deliver.json

da branch 04 e sucessoras a massa de dados é dinamica 
usando a bibilioteca faker e gerador de cpf do node

para adquirir essas bibiliotecas basta usar esses comandos

- npm install @faker-js/faker --save-dev
- gerador-validador-cpf --save-dev

toda massa de dados Dinamica esta na pasta cypress/factories/SignupFactory.js

# Execução 

Tem duas maneiras de fazer a execução 

Pela interface grafica basta usar o comando:(npm run test) no terminal. 

se este comando nao funcionar, é só usar o comando:(npx cypress open)

Pelo Background basta usar o comando:(npx cypress run) no terminal.

# Relatorios 

Quando o comando (npx cypress run) é utilizado o proprio cypress cria uma pasta chamada Videos dentro do projeto e dentro dessa pasta fica toda a execução gravada, se der algum erro em algum dos cenarios de teste o cypress tira screenshot e armazena na pasta screenshots dentro do projeto(se esta pasta nao existir o cypress cria)



Este repositorio é toda a pratica que fiz do curso da QA Academy, que ensinou como faz o uso do cypress
