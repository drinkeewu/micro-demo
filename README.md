# Micro-FE

基于`single-spa`（JavaScript微前端框架）,`single-spa-vue`(vue子项目使用的`npm`包)，搭建的微前端项目示例。

## 目录结构

```
├── child //子项目
└── parent //父项目
```



## 子项目

```
cd child
npm install
npm run serve
```

> 项目运行地址：http://localhost:3000

## 父项目

启动

```
cd parent
npm install
npm run serve
```

> 项目运行地址：http://localhost:8000



运行界面：

![image](https://github.com/drinkeewu/micro-demo/raw/master/screenshot.png)