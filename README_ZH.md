![bigLogo](http://otsu.fun/big_logo.png)
# 🔥vue-cli-electron-template
⭐使用`vue-cli3`和`Electron6`构建的一个模块化的桌面应用程序模板。可以方便进行的打包、切换程序语言，使用自定义无边框窗口，并且添加了`vue-router`、`vue-i18n`、`axios`等等常用插件，还提供了一些演示功能。

- 🌺[English](https://github.com/Pure-Peace/vue-cli-electron-template/blob/master/README.md) / 💖中文

<h2 align="center">⚡-介绍！-</h2>

🚀构建于`vue-cli` & `electron-builder`，模块化设计。添加了常用插件及演示功能。你可以在本项目中愉快的使用`svg`图片，舒适的享受`i18n`多国语言支持， 切换程序语言（整个程序！包括electron原生菜单及浏览器页面)，快速进行多窗口管理、菜单管理，并且具有一个方便快捷的网络请求方式。


![screenshot](http://otsu.fun/shoot_eg.png)

---

## 📘这些:
- 🍊基础: `vue-cli` &` electron-builder`
- 🌕路由: `vue-router`
- 🍁多语言: `vue-i18n`
- 🌝网络请求器: `axios`
- 🚅快速打包: `electron-builder`
- 💚css预处理器: `less`

## 🔍以及:
- ⛅自定义的原生无边框窗口
- 🎨使用面向对象的模块化写法（主进程文件）
- 🍰整个程序都可以进行方便的语言切换
- 🐳一个方便你使用`svg`图片的组件（基于`svg-sprite-loader`插件）
- 🏀`Electron6`：添加了一些api演示
- 🍉`vue-i18n`：添加了语言切换演示，包括`electron`原生菜单
- 🍩`axios`：添加了网络请求演示
- 🌼使用`ESlint`进行代码风格规范
- 🌠还有`vuex`、`vue-router`
- 🍖我没有在项目中添加第三方ui库，您可以随心所欲选择自己喜欢的添加


<h2 align="center">🏆-开始吧！-</h2>


 1. **🍬克隆这个仓库**
 
```bash
git clone https://github.com/Pure-Peace/vue-cli-electron-template
```

 2. **🍮进入目录**
 
```bash
cd vue-cli-electron-template
```

 3. **🍙安装依赖（推荐使用yarn）**
 
```bash
yarn & npm install
```` 


 4. **🌽启动应用**
 
```bash
yarn go & npm run go
```

 5. **🍭打包应用**
 
```bash
yarn packapp & npm run packapp
```


<h2 align="center">🍌-结构！-</h2>

**⚽文件的：**

- 🎰`./vue.config.js`: 包括 **vue路径别名**、` electron-builder`、`i18n` 等其它配配置项
- ☔`src/background.js`: 主进程入口文件
- 🐐`src/mainProcess.js`: 负责管理主进程
- 🚧`src/main.js`: Vue入口文件
- 🏨`src/backend.js`: 网络请求接口及`axios`配置项

**🍀目录的：**

- 🌲`src/locales`：`i18n`多语言翻译文件目录
- 🐓`src/mainProcess`：主进程模块化文件
- 🙀`src/mainProcess/events`：ipc及app事件
- 🌴`src/mainProcess/menus`：菜单管理
- 🐏`src/mainProcess/plugins`：目前只有翻译器在里面
- 🙉`src/mainProcess/windows`：多窗口及窗口管理器

---
**🔞后记：**

🌹初学electron，欢迎提建议……

