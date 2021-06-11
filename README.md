<!--
 * @Descripttion:
 * @version: 0.0.1
 * @Author: lilingfeng <lingfeng.li@going-link.com>
 * @Date: 2021-06-11 10:05:33
 * @LastEditors: lilingfeng
 * @LastEditTime: 2021-06-11 10:49:36
-->

##

1.使用绝对路径代替相对路径 引入 baseUrl:'/src' 2.引入格式化插件 yarn add --dev --exact prettier
3.echo {}> .prettierrc.json 忽略格式化的文件 build coverage
4.npx mrm lint-staged 格式化前预校验 再安装 eslint-config-prettier 配合 react 中 eslit 使用  
5. ** "eslintConfig": {
"extends": [
"react-app",
"react-app/jest",
"prettier"
]
} **

6.规范代码提交规范 --save-dev @commitlint/{config-conventional,cli}
