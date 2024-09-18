# aai_manha_22721
Gustavo Oliveira da Silva - 22721 (ADS - Manhã)


#Como criar um projeto React Native do zero e subir no GitHub
//Cria uma pasta para os arquivos
md Projeto

//Entra na pasta criada anteriormente
cd C:\Users\Aluno\projeto

//Linha de código responsável por criar um novo projeto EXPO (No caso o projeto ficará com o nome padrão de my-app)
npx create-expo-app@latest

//Entra na pasta criada pelo código anterior, referente ao projeto em sí
cd my-app

//Prepara as alterações que serão armazenadas no GitHub
git add .

//Envia as mudanças criadas para o GitHub
git commit -m "projetinho"

//Vincula o código a um repositório do GitHub
git remote add origin URL_DO_REPOSITORIO_GITHUB

//Faz o upload dos arquivos para o repositório escolhido na branch master
git push -u origin master

//Responsável por iniciar o projeto
npx expo start





#Como clonar o projeto da nossa aula e rodá-lo
//Clona o código do respectivo repositório na branch main
git clone --branch <master> <https://github.com/xSundowner/MobileProject.git>

//Entra na pasta do projeto
cd MobileProject

//Instala as dependências NPM
npm install

//Inicia o projeto
npm run start

