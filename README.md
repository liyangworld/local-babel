# local-babel
本项目的目的是在本地使用 Babel 对 js 文件进行转译，项目搭建过程参考了 Babel 官网指引，CLI 选项。[地址](https://babeljs.io/docs/setup/)

### 依赖
本项目使用 babel-preset-env 作为转译规则，默认包含了 es2015、es2016、es2017。[官网详情](https://babeljs.io/docs/plugins/preset-env/)

### 使用
1. 在 es6 文件夹中使用新特性编辑 js 文件
2. 在命令行执行以下命令，将在 es5 文件夹中生成对应转译后的 js 文件
```shell
npm run build
```
