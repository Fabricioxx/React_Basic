### CLI - React

_CLI (Command-Line Interface) comandos importantes que são usados para desenvolver no React._




1 - Criar um novo projeto do React:

  ```Terminal
  
  npx create-react-app nomeProjeto

  
  ```
  
  2 - Execute o comando npm install para instalar as dependências do projeto que foi clonado do github
  
  ```Terminal
  
  npm install

  ```
  
  3 - Executar o projeto:
  >
  Este comando executa o projeto do React em um servidor local e abre a aplicação no navegador.
  ```Terminal
  
  npm start

  ```
  
  4 - Criar um novo componente:
  
  ```Terminal
  
  touch MyComponent.js

  ```
  
  5 - Instalar uma dependência do npm: 
  >
  Este comando instala uma nova dependência do npm no projeto do React e adiciona-a ao arquivo **package.json** como uma dependência.
  
  ```Terminal
  
  npm install <package-name> --save

  ```
  
  6 - Compilar o projeto para produção:
 >
 Este comando compila o projeto do React para produção, criando um conjunto otimizado de arquivos que podem ser implantados em um servidor web.
  
   ```Terminal
  
  npm run build

  ```
  
  7 - Executar testes:
  >
  Este comando executa os testes automatizados definidos no projeto do React.
  ```Terminal
  
  npm test

  ```
  
  8 - Para Atualizar todas as dependências do aplicativo para as versões mais recentes compatíveis.
  
  ```Terminal
  
  npm update

  ```
  9 - Executa o linter do aplicativo para verificar se há problemas de formatação e estilo de código.
  
  ```Terminal
  
  npm run lint

  ```
  
  10 - Executa o formatador de código para garantir que o código esteja formatado corretamente.
  
  ```Terminal
  
  npm run prettier

  ```
  
  11 - para verificar todas as dependências do projeto e procura por vulnerabilidades conhecidas de segurança. exibe uma lista delas e recomenda as ações a serem    tomadas para corrigi-las.
  
  ```Terminal
  
  npm audit

  ```
  
  12 - Para tentar atualizar as dependências para versões que corrigem as vulnerabilidades.
  
  ```Terminal
  
  npm audit fix

  ```
  13 - Para forçar a instalação das atualizações mais recentes das dependências, mesmo que isso possa quebrar o seu código ou resultar em comportamentos inesperados. dependendo da situação pode quebrar o codigo se as atualização não forem compativeis com o projeto atual.
       
  ```Terminal
  
  npm audit fix --force

  ```
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
