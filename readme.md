# single-spa-container

## Install development environment dependencies
*install create-single-spa*
`npm install —global create-single-spa`
*install vue-cli3*
`npm install -g @vue/cli`

## Create project
Front-end microservices are divided into two steps：
一, Create a microservice container, the single-spa framework.
二, Create a microservice module, and the sub-applications are the various service modules in the microservice.
### Create a microservice container
`npm i sinle-spa-container -s`
### Create a microservice module
1. Create a sub-application
`vue create sub-app1`
2. Add single-spa plugin
`vue add single-spa`
4. Modified as a front-end microservice application
`vue add 4singlespa`

## Configure microservice container
```
// todo
single-spa html
```
## Configure microservice module
Extract dependencies and optimize file size after packaging：
```
// todo
vue.config.js
```
## other
* [System.js](https://github.com/systemjs/systemjs) is used in the microservice container，This is a module loader that provides a backward compatible workflow for ES modules in the browser.
* Source code：single-spa-contianer，[vue-cli-plugin-4singlespa](https://github.com/hjdtl/vue-cli-plugin-4singlespa)，反馈请issue。

