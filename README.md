# Rollup开发空框架

框架目前集成了rollup开发、打包的基础功能。

- es和cjs的代码规范输出
- eslint、ts校验
- 自动生成types定义文件
- npm publish快速发布
- babel转码兼容

使用该框架能够使你开箱即可开发基于rollup构建的工具库、npm插件、脚手架等功能。

>如果需要进行cli开发，在`package.json`加入:
>
>```javascript
>"bin": {
>    "my-cli": "lib/index.js"
>}
>```
