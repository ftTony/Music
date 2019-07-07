![image](./img/timg.jpg)
<br>

## 前言

本人平时学习及收集内容，欢迎参入一起讨论。

## 关于作者

暂时欠着

## 移动端音乐WebApp

参考资料:[慕课网](http://coding.imooc.com/class/107.html)

基于vu2(2.5)+vuex+vue-router+vue-axios+better-scroll+scss+es6等开发一款音乐WebApp，UI界面参考了移动端QQ音乐、flex布局适配常见移动端

预览效果：

<img width="322" alt="wx20190224-173558 2x" src="https://user-images.githubusercontent.com/6395813/53297641-3642b980-385c-11e9-96db-e11d80105f7d.png">

## 技术栈

**【前端】**

- `Vue`：用于构建用户界面的 MVVM 框架。它的核心是响应的数据绑定和组系统件
- `vue-router`：为单页面应用提供的路由系统，项目上线前使用了 Lazy Loading Routes 技术来实现异步加载优化性能
- `vuex`：Vue 集中状态管理，在多个组件共享某些状态时非常便捷
- `vue-lazyload`：第三方图片懒加载库，优化页面加载速度
- `better-scroll`：iscroll 的优化版，使移动端滑动体验更加流畅
- `Sass(Scss)`：css 预编译处理器
- `ES6`：ECMAScript 新一代语法，模块化、解构赋值、Promise、Class 等方法非常好用

**【后端】**

- `Node.js`：利用 Express 起一个本地测试服务器
- `jsonp`：服务端通讯。抓取 QQ音乐(移动端)数据
- `axios`：服务端通讯。结合 Node.js 代理后端请求，抓取 QQ音乐(PC端)数据

**【自动化构建及其他工具】**

- `webpack`：js、css打包处理及启用本地服务
- `eslint`：代码风格检查工具，规范代码项目代码
- `vConsole`：移动端调试工具，在移动端输出日志

## 运行项目

启用node后端服务，命令行进入server目录下，运行以下命令

```npm run start```

接着返回上一级目录，运行以下命令

```npm run dev```
## 联系作者

<div align="center">
    <p>
        在颠覆世界的同时，也要好好关照自己。
    </p>
    <img src="./img/contact.png" />
</div>
