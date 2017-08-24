## React技术栈
- react react-router4 redux react-redux
## 初始化
    yarn init -y

##webpack
    $ yarn add webpack webpack-dev-server --dev
##babel
    $ yarn add babel-core babel-loader babel-preset-es2015 babel-preset-stage-0 babel-preset-react css-loader style-loader less less-loader html-webpack-plugin --dev[开发依赖]
##react
    $ yarn add react redux react-redux react-router-dom react-dom
##  fetch
    $ yarn add es6-promise whatwg-fetch --dev
##  express
    $ yarn add express
## scripts
    "start" ,"webpack-dev-server --port 5000 --open --progress --colors",
    "build","webpack -p"

## 目录结构

    -components 组件  木偶组件
    -containers 页面组件，或者自己的subpage目录下
        -home
            -subpage  智能组件
            -index.jss


    -routes 路由
        -index.js RouterMap
        -containers -index.js RouterMap

头部：呆瓜组件