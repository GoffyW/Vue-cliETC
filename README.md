# my-project

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

### 文件目录结构：

> 主要分析开发(dev)和构建(build)两个过程涉及到的文件

```markdown
|-- build                            		// 项目构建(webpack)相关代码
|   |-- build.js                     		// 生产环境构建代码
|   |-- check-version.js             // 检查node、npm等版本
|   |-- utils.js                     		// 构建工具相关
|   |-- vue-loader.conf.js           // webpack loader配置
|   |-- webpack.base.conf.js         // webpack基础配置
|   |-- webpack.dev.conf.js          // webpack开发环境配置,构建开发本地服务器
|   |-- webpack.prod.conf.js         // webpack生产环境配置
|-- config                           		// 项目开发环境配置
|   |-- dev.env.js                  		 // 开发环境变量
|   |-- index.js                     		// 项目一些配置变量
|   |-- prod.env.js                 		 // 生产环境变量
|   |-- test.env.js                  		// 测试脚本的配置
|-- src                              			// 源码目录
|   |-- components                    // vue所有组件
|   |-- router                               // vue的路由管理
|   |-- App.vue                           // 页面入口文件
|   |-- main.js                             // 程序入口文件，加载各种公共组件
|-- static                                   // 静态文件，比如一些图片，json数据等
|-- test                                      // 测试文件
|   |-- e2e                                   // e2e 测试
|   |-- unit                                  // 单元测试
|-- .babelrc                              // ES6语法编译配置
|-- .editorconfig                      // 定义代码格式
|-- .eslintignore                      // eslint检测代码忽略的文件（夹）
|-- .eslintrc.js                           // 定义eslint的plugins,extends,rules
|-- .gitignore                            // git上传需要忽略的文件格式
|-- .postcsssrc                          // postcss配置文件
|-- README.md                        // 项目说明，markdown文档
|-- index.html                           // 访问的页面
|-- package.json                     // 项目基本信息,包依赖信息等
```



### 两种搭建方式

#### 1、利用淘宝镜像搭建：（npm run dev）

全局安装 vue-cli `npm install --global vue-cli`

```npm
创建一个基于 webpack 模板的新项目vue init webpack my-project(这一步名称可以大写)
? Project name my-project ：设置项目名称（这一步名称必须小写）
? Project description A Vue.js project：填写项目描述
? Author runoob test@runoob.com：填写作者
? Vue build ：选择默认的Runtime + Compiler: recommended for most users
？Install vue-router? (Y/n)：是否需要路由，选择Y
? Use ESLint to lint your code? (Y/n)：是否使用EsLint编码，我不会，选择N
? Pick an ESLint preset Standard
? Setup unit tests with Karma + Mocha? Yes
? Setup e2e tests with Nightwatch? Yes->NPM
```

#### 2、使用官网办法：(npm run serve)

安装vue/cli：npm install -g @vue/cli
安装之前cd到自己想要安装的路径上
安装vue：vue create projectName(这里名称需要小写)
Please pick a preset? 选择创建方式，这里选择Manually select features自己选择配置。

A全选，I全部反选，空格选择，上下键切换，回车确认

```
? Check the features needed for your project: 
 ◯ Babel
 ◯ TypeScript
 ◯ Progressive Web App (PWA) Support
❯◉ Router
 ◉ Vuex
 ◯ CSS Pre-processors
 ◉ Linter / Formatter
 ◯ Unit Testing
 ◯ E2E Testing	
```













































































