### React - Passo a Passo

- Docs  https://reactjs.org/docs/create-a-new-react-app.html
>    

 **Material Desing** 
- https://mui.com
- https://react.dev/
- https://getbootstrap.com/docs/5.3/examples/
- https://react-bootstrap.github.io

**Prompts** [**terminal npm e npx :**](https://github.com/Fabricioxx/React_Basic/blob/main/CLI%20-%20React.md)

#### Estrutura projeto [ **npx create-react-app my-app** ]

```
my-app
├── README.md
├── node_modules
├── package.json
├── .gitignore
├── public
│   ├── favicon.ico
│   ├── index.html
│   └── manifest.json
└── src
    ├── App.css
    ├── App.js
    ├── App.test.js
    ├── index.css
    ├── index.js
    ├── logo.svg
    └── serviceWorker.js
    └── setupTests.js

```

#### codigo basico de um componente

```javascript

import "./nomeComponente.css";

export default function nomeComponente() {


    return (
    
    // codigo HTML - jsx ( retorna o codigo HTML )
        )
        
}

ou utilizando ( Arrow function )

const nomeComponente = () => {
  
  return (
    
  );
};

export default nomeComponente;





```


1 - Instalar o Node.Js - cmd

2 - Instalar o React - cmd

3 - Abra o seu terminal e crie um novo projeto usando o comando **npx create-react-app NomeProjeto**. Certifique-se de ter o Node.js instalado na sua máquina. (nome do projeto tudo letra minuscula)

4 - Crie uma pasta chamada **Components** dentro da pasta src usando o comando **mkdir src/Components**.

5 - Crie uma pasta com o nome do componente **componenteExemplo** dentro da pasta **src/Components** usando o comando **mkdir src/Components/componenteExemplo**
    ( _faça isso para todos os componentes que precisar criar no projeto_ )
    
6 - Pronto! Agora você tem uma estrutura básica de pastas para começar a trabalhar no seu projeto em React.   

--------------------------------------------------------------------------------------------------------------------
    

