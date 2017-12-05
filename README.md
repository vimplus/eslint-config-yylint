# Muggle Team eslint规则

## 准备


```shell
npm i -g eslint
```


## 使用方式

1、在项目根目录新建`.eslintrc.js`，内容为：

```javascript
module.exports = {
    "extends": "yylint"
};
```

2、在项目里安装`yylint`配置：

```javascript
yarn add eslint eslint-config-yylint --dev
```

## React项目

```javascript
module.exports = {
    "extends": "yylint",
    "plugins": [
        "react"
    ]
};
```

## Vue项目

```javascript
module.exports = {
    "extends": "yylint",
    "plugins": [
        "vue"
    ]
};
```





