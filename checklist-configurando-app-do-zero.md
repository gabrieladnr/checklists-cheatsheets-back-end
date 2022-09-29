
# Checklist confuguração básica com Node.js e Express

Configurando um app com Node.js e Express do zero passo a passo:

## 1. Criar o diretório da aplicação, um diretório raiz e entrar no diretório da aplicação
 `sh
mkdir nome-do-app nome-do-app/src && cd nome-do-app
`
## 2. Iniciar um pacote Node.js com a configuração padrão
 `sh
npm init -y
`
## 3. Iniciar o framework Express
 > Aqui utilizamos a versão 4.17

`sh
npm i express@4.17
`
## 4. Iniciar o ESLint desejado
 `sh 
npm install --save-dev eslint-config-nome-da-config-escolhida
`
Sugestões de configurações aqui: https://github.com/dustinspecker/awesome-eslint

## 5. Criar arquivos de configuração do ESLint
 >.eslintignore: usado para que o ESLint ignore arquivos e diretórios específicos
 >.eslintrc.json: usado para sobrescrever regras do ESLint
 
 `sh
touch .eslintignore .eslintrc.json
`
## 6. Ignorar o ESLint no node_modules
 Dentro do arquivo .eslintignore, digite:
 `node_modules
 `
## 7. Iniciar um repositório git na aplicação
 `sh 
git init 
`
## 8. Criar um arquivo de configuração do git
 `sh 
touch .gitignore
`
## 6. Ignorar node_modules no git
 Dentro do arquivo .gitignore, digite:
 `sh 
node_modules
`
