
### Pré-requis :

- javascript / D.O.M
- git / github
- node / npm
- es6
- html / css / pré-processeurs css / framework css
- anglais

---

# Jour 1

## Le fonctionnement des navigateurs :

### HTML markup
     https://developer.mozilla.org/fr/docs/Web/HTML [FR]
### Browser D.O.M (accès par javascript)
     https://developer.mozilla.org/fr/docs/Web/API/Document_Object_Model
### Browser Rendering
    https://developers.google.com/web/fundamentals/performance/rendering/

### Javascript engines
    https://github.com/a0viedo/demystifying-js-engines
    http://developer.telerik.com/featured/a-guide-to-javascript-engines-for-idiots/


Browser, Headless Browser, or Runtime JavaScript | Engine
---|---:
Mozilla | Spidermonkey
Chrome | V8
IE and Edge | Chakra
Safari | JavaScriptCore (Nitro)
Node.js | V8


### javascript versions (es5, es6, ...)
     https://developer.mozilla.org/fr/docs/Web/JavaScript
     https://kangax.github.io/compat-table/es6/
     https://johnpapa.net/es5-es2015-typescript/

  * es2015, es2016, es2017
    * babel tranpiler :

    https://babeljs.io/docs/plugins/preset-latest/
    https://github.com/babel/babel-loader

## Les navigateurs et les servers :

### server / browser request

  * browser page request
  * browser image request
  * browser API request
  * ...

### domains et security

  * Request headers
  * Response headers
  * cors
  * ...

### templating

  * browser responsability
  * server responsability
  * Futur : more and more browser responsability
  * la mode : serverless
  * la mode : chatbot => templating == 0

### API vs Server rendering

## Les web applications :

  * single page application : WTF ?

### Les frameworks & libraires JS sur le marché actuellement :
- ReactJS, AngularJS, VueJS ... (emberjs...)
- Les points essentiels :
  - virtual dom (shallow rendering) VS dirty checking
  - strict unidirectional data flow (one way binding) VS two way binding

## Development workflow :

### editor : (atom / sublimetext, webstorm)

  - jsx
  - emmet,
  - babel
  - language syntax colorization, ternjs

### Best practices / conventions

  - linter (eslint)
  - editorconfig
  - TRAVAILLER EN EQUIPE

### debugging / logging

  - chrome dev tools
  - react dev tools
  - redux dev tools

### React development stack :

- webpack / webpack-dev-server : Mega-power bundler
- babel : es2015 / 2017 (future of web browser) => babel-preset-env
- react : the view part (virtualdom  / one way binding)
- redux / react-redux : the model part (functional reactive programming)

### React community :
- facebook, rbnb, ...
- Dan Abramov (@gaeron)
- https://react.rocks/
- https://github.com/enaqx/awesome-react
- https://github.com/brillout/awesome-react-components
- https://github.com/xgrommx/awesome-redux

# Let's step into :

## Check list

- nvm ?
- node version : node -v
- npm i -g eslint

## First react application

- npm install create-react-app -g
- cd your-projects-folder
- create-react-app my-first-project
- Your first web app / Your first component

## Check list atom :

- cf. Packages list

Romain Valin
Basile ![Basile Photo](https://avatars2.githubusercontent.com/u/15260538?v=3&u=e98797e3016b0afe6141e51a8af3c967e016824b&s=400)

Paul Reinhardt https://scontent-frt3-1.xx.fbcdn.net/v/t31.0-8/10494889_10203418881611834_148925699178724527_o.jpg?oh=15fac3ca2158add9029d31dace57049e&oe=592B4698
