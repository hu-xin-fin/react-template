说在最前面，我打算做一个 `typescript + styleLint + eslint` 的项目

# 配置 eslint

## eslint [官网](http://eslint.cn/) 
* [原理](http://eslint.cn/docs/about/)
* [规则](http://eslint.cn/docs/rules/)
* [Getting Started with ESLint](http://eslint.cn/docs/user-guide/getting-started)

## 配置
1. 安装 eslint `npm install eslint --save-dev`，安装 eslint/create-config `npm i @eslint/create-config@0.4.2`
2. 生成配置文件 `npm init @eslint/config`
    * How would you like to use ESLint? · `style`，
    * What type of modules does your project use? · `esm`
    * Which framework does your project use? · `react`
    * Does your project use TypeScript? · No / `Yes`
    * Where does your code run? · `browser`
    * How would you like to define a style for your project? · `guide`
    * Which style guide do you want to follow? · `standard-with-typescript`
    * What format do you want your config file to be in? · `JSON`
        * ps: node 版本`12.16.1`过低，导致 `npm init @eslint/config` 命令执行不了，升级成了 `16.18.0` 解决

# 配置 typescript
# 配置 stylelint