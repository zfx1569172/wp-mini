多页面应用的脚手架，支持使用ES6，less，模块化，等功能

webpack.config.build.js/webpack.config.dev.js里增加新页面



var pageConfig = [{
    name: 'index',
    html: 'home/index.html',
    jsEntry: 'home/index.js'
},{
    name: 'about',
    html: 'about/about.html',
    jsEntry: 'about/about.js'
}];