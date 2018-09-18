# nuxt-temp

> Nuxt.js project

## nuxt 搭建 vue 服务器端渲染

### 搭建环境

- 新建项目文件夹 vue-nuxt (项目名根据自身需求可更改)
- 进入到文件夹下，执行 npm init -y 初始化项目为 npm 项目
- 执行 `npm i nuxt` 命令，安装 nuxt 包。(nuxt 包内集成了 vue 的开发环境，所以不需要安装 vue 的基础包)
- 在根目录下新建 pages/index.vue 文件(这个 pages 文件夹代表的是项目的路由文件)，index.vue 代表的就是首页组件
- index.vue 内填写一个 hello world
- 在 package.json 的 script 字段下，填写一个命令 `dev:"nuxt"`
- 打开项目终端，执行 `npm run dev`,启动 nuxt 的开发环境，就会在 localhost:3000 看到 hello world
