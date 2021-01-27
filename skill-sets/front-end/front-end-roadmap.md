# Front-end Roadmap (2021)

First things first: front-end vs. back-end vs. full-stack
- front-end dev: front facing website or app UI
  - html, css, sass, javascript, typescript, js frameworks, dom, http, etc.
- back-end dev: server apis, data, tasks, etc
  - programming languages (js, python, c#, php, java, and more), databases (rdbms, nosql), knowledge of servers and config, etc
- full-stack dev: combined front-end / back-end
  - both front-end and back-end knowledge

What's your goals?
- Professional dev at a big company / lead a teamwork on my own
- Build my own apps, saas; consultant
- Content creation
- Hobby

design software: adobe xd, photoshop, sketch (mac only), figma (web-based)

## Internet

[The internet](internet/the-internet.md)

- [Browsers and how they work?](internet/browsers-and-how-they-work.md)
- [How the web works?](internet/how-the-web-works?)

- How does the internet work?
- What is HTTP?
  - http requests: fetch api (get, post, put, delete)
- Browsers and how they work?
- DNS and how it works?
- What is Domain Name?
- What is hosting?

## HTML, CSS, JavaScript

HTML
- [HTML Syntax](html-css-javascript/html-syntax.md)
- [HTML Multimedia and Embedding](html-css-javascript/html-multimedia-and-embedding.md)
- [HTML tables](html-css-javascript/html-tables.md)

CSS
- [CSS Syntax](html-css-javascript/css-syntax.md)
- [Styling Text](html-css-javascript/styling-text.md)
- [CSS Layout](html-css-javascript/css-layout.md)
  - alignment: flexbox, css grid

- [ ] responsive design / media queries

JavaScript
- [JavaScript Syntax](html-css-javascript/javascript-syntax.md)
  - basics: variables, arrays, functions, loops, etc
  - array methods: foreach, map, filter, reduce, etc
- [DOM and styling](#)
  - selecting and manipulating elements
- [Web APIs](#)

Applied
- [Web Forms - Working with User Data](html-css-javascript/web-forms.md)

Accessibility - make the web usable by everyone
- [Accessibility](#)
- [Responsive Design](#)
- [Convention and best practices](#)
- [SEO](#)

res
- html/css playlist (traversy channel)
- modern html & css from the beginning (udemy courses)
- 50 projects in 50 days (udemy courses)

res
- traversy channel
  - vanilla js playlist
- udemy courses
  - modern js from the beginning
  - 20 web projects with vanilla js
  - 50 projects in 50 days

## Version Control Systems

- basic usage of git, subversion
- repo hosting services: github, gitlab, bitbucket

res (travesy channel)
- git crash course
- getting started with open-source

## Web Security Knowledge

get a basic knowledge
- HTTPS
- CORS
- Content Security Policy
- OWASP Security Risks

## Package Managers

- npm
- yarn

res (traversy channel)
- npm crash course
- yarn crash course

## CSS Architecture

With modern frameworks and CSS-in-JS you don't have to worry about these anymore, but still it would be a good idea to get familiarized with BEM at least.

- BEM
- (optional) OOCSS
- (optional) SMACSS

## CSS Preprocessors

With modern frameworks there has been more push towards CSS-in-JS, so you may not need these but still good idea to familiarize yourself.

CSS preprocessor that gives you more functionality in your styling. Sass offers things like variables, mixins, functions, nesting, etc.

- Sass
  - Although Sass is optional, it is something I suggest learning. It is easy to pickup and you will most likely run into it at some point.
- (optional) PostCSS
- (optional) Less

res
- Sass crash course (traversy channel)
- responsive portfolio website (traversy channel)
- fancy form ui from scratch (traversy channel)


## Build Tools

linters and formatters
- prettier
- eslint
- (optional) standardjs

task runners
- npm scripts
- (optional) gulp

module bundlers
- webpack
- rollup
- parcel

browser developer tools
- console
- network
- storage

editor extensions & helpers
- snippets, live server, etc

res (traversy channel)
- chrome devtools crash course
- emmet crash course
- eslint & prettier setup

## Frameworks

React.js
- Redux
- MobX

Angular
- RxJS
- NgRx

Vue.js
- VueX

Svelte

Statement management
- react: context, redux, mobx
- vue: vuex
- angular: shared service, ngrx
- svelte: context api

res
- traversy channel
  - react crash course
  - react project playlist
  - vue crash course
  - angular crash course
  - redux crash course
  - vuex crash course
  - react context api
- udemy course
  - react front to back
  - mern stack front to back
  - mern ecommence from scratch
  - angular front to back

## Modern CSS

- Styled Components
- CSS Modules
- Styled JSX
- Emotion
- (optional) Radium
- (optional) Glamorous

## Web Components

- HTML Templates
- Custom Elements
- Shadow DOM

## CSS F.rameworks

CSS frameworks can be a great tool to create websites and uis quickly. however, it is important to learn the fundamentals of CSS first.

JS-based and better to use with your framework JS-based APPs
- Reactstrap
- Material UI
- Tailwind CSS: utility-first framework
- Chakra UI

CSS first framworks which don't come with JavaScript components by default
- Bootstrap: popular framework (bootstrap 5 released)
- Materialize CSS: based-on material design
- Bulma: modular & lightweight

res
- traversy channel
  - bootstrap creash course
  - materialize crash course
  - build your fist tailwind css site
  - bulma crash course
- udemy courses
  - bootstrap 4 from scratch
  - materialize css from scratch

## UI design

- color & contrast: make sure text is readable
- white space: spacing between elements
- scale: sizing relative to other elements
- visual hierarchy: arrange in order of importance
- typography: text typefaces, sizing, etc

res
- traversy channel
  - UI design for devleoper

## Testing APPs

Learn the difference between Unit, Integration and Functional tests, and learn how write them with the tools listed on the below
- Jest
- react-testing-library
- Cypress
- Enzyme

Optional
- Mocha
- Chai
- Ava
- Jasmine

Testing helps prevent problems before they happen
- unit tests: individual units like functions or classes
- integration tests: modules tested as a group
- end-to-end tests: test workflow from start to finish

testing frameworks
- js: jest, mocha
- python: pytest, robot

res (traversy channel)
- intro to js unit testing & bdd
- jest crash course
- intro to testing with mocha & chai

## Type Checkers

- TypeScript: great for larger projects
- (optional) Flow

TypeScript is a superset of js and is popular on its own as well as being paired with a front-end framework
- bing a 'strict' type system to js
- makes your code more robust and less prone to errors
- object-oriented programming: classes, interfaces, generics, modules

res (traversy channel)
- typescript crash course

## Progressive Web APPs

Learn different Web APIs used in PWAs
- Storage
- Web Sockets
- Service Workers
- Location
- Notification
- Device Orientation
- Payments
- Credentials

Calculating, measuring and improving performance
- PRPL Pattern
- RAIL Model
- Performance Metrics
- Using Lighthouse
- Using DevTools

## Server Side Rendering (SSR)

You can also run frameworks like React and Vue on the server. There are advantages to this such as better SEO, easy routing, etc.

React.js
- Next.js
- (optional) After.js

Angular
- Universal

Vue.js
- Nuxt.js

Svelte
- Snapper

res (traversy channel)
- nuxt crash course
- nuxt crash course
- build a blog with next.js & ghost

## GraphQL

- Apollo
- Relay Modern

## Static Site Generators

SSGs generate your website pages at build-time as opposed to real-time, making them super fast & secure.
- Next.js
- GatsbyJS: react-based
- Nuxt.js
- Vuepress
- JekyII: ruby-based
- Hugo: go-based
- 11ty: js alternative to jekyll
- gridsome: vue-based

res (traversy channel)
- gatsby crash course
- build an event app with vue.js, gridsome & strapi
- build a website with 11ty

## Headless CMS

CMS is commonly used with static site generators
- strapi
- sanity.io
- contentful
- prismic
- wordpress

res (traversy channel)
- strapi crash course
- build an event app with vue.js, gridsome & strapi
- sanity.io crash course
- build a portfolio with react & sanity.io
- explore the wordpress rest api

## The Jamstack - javascript, apis & markup

Web architecture with high performance, security and scalability at a low cost with a great dev experience.
- static sites / assets
- markdown
- serverless
- headless cms for content
- hosting with services like netlify

res (traversy channel)
- what is the jamstack
- what is serverless
- markdown crash course
- serverless lambda functions

## Mobile APPs

- React Native
- NativeScript
- Flutter
- Ionic

## Desktop APPs

- Electron
- (optional) Carlo
- (optional) Proton Native

## Basic front-end deployment

You should be able to do a basic website or front-end app deployment
- static hosting: netlify, github pages, heroku
- cpanel hosting: inmotion, hostgator, bluehost

Methods of deploying
- git: continuous deployment by pushing to a repo
- ftp / sftp: file transfer protocol (slow)
- ssh: secure shell

Some other things you will run into during a basic deployment
- domain names: namecheap, google domains, enom
- email hosting: namecheap, zoho mail, cpanel
- ssl certificates: let's encrypt, cloudflare, namecheap

res (traversy channel)
- deploying sites with netlify
- build & deploy a portfolio website
- build a responsive website (netlify deploy)
- github pages deploy & domain
- web hosting & cpanel guide

## Web Assembly
Web Assembly or WASM is the binary instructions generated from higher level languages such as Go, C, C++ or Rust. It is faster than JavaScript.

WASM 1.0 has already shipped in the major browsers. W3C accepted it as an official standard at the end of 2019. It will still take quite some time to go mainstream though.

----
itheima courses

established time: 2021-07-31 end  
基础 - Vue - mini-program - react - cross-platform - 前段工程化 - 前端服务化

```
0. 14 html,css baiscs (PC web page)
- flaoting, positioning, flex
- 背景, 圆角, 阴影, 渐变 / 转换, 过渡, 动画

1. 13 responsive design (mobile web page 适配方案)
- 媒体查询, 分辨率, 视口, 媒体查询, rem, 屏幕适配, 2 倍图, 响应式图片, 刘海屏适配, 添加主屏, 禁止复制, bootstrap, 栅格化

2. 30 javascript / web apis / jquery
- 视觉交互, 数据处理, 安全, 性能
- Echarts: 数据可视化

3. 25 server-side programming
- 防抖节流, JWT 权鉴, 资讯CMS系统
  - ajax, axios, 跨域, 防抖节流, Express, db, node.js, 身份认证, jwt, token

4. 59 vue.js
- 人资中台, 电商
- webpack, vue-cli, element, vuex, vue-router, mvvm

5. 14 mini program
- 优品购
  - wechat pay, mobx, uni-app, wxs

6. 20 react.js
- 好租房
  - jsx, 虚拟dom, 组件通信, 数据管理流程, antd

7. 17 react.js advanced
- 电商后台 (typescript)
  - typescript + hooks / 函数式编程

8. 35 cross-platform

9. 8 工程化: webpack, 脚手架, git flow

10. 30 服务化: nosql, ssr, 性能监控, 埋点方案, PV/UV 统计, 性能监控
```

Foundational front-end developer
- setup a productive dev env
- write html, css & js
- use sass & css frameworks
- crate responsive layouts
- build websites with some dynamic functionalities and work with the dom
- connect to 3rd party apis with fetch & understand basic http
- use git with github
- deploy & manage a website or small web app

-> next step
- sharpen the js skills
- learn front-end frameworks: react, vue, angular
- learn a server-side language / tech (node, python, php, c#)

-> intermediate front-end developer
- build apps and interfaces with a front-end frameworks
- work with component and global state
- connect to back-end json data integrate into your apps
- write and test clean and efficient code
- use typescript write more robust code
- server side rendering
- static site generators / jamstack
