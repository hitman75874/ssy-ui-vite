<p align="center">
<div style="width:150px;margin:auto;">
<img src="assets/R.jpg">
</div>
</p>
<h1 align="center">SSY-UI-VITE</h1>
<p align="center">
  基于 Vite 栈的前端工程化实践

<p align="center">
  <img src="https://img.shields.io/github/license/hitman75874/hitman47?color=red">

</p>

## Features

- 基于 Vue 框架
- 支持 JSX与 Vue 单文件组件
- Jest + Vue3 plugins实现单元测试
- Eslint + Prettier + Husky 语法检查
- 采用 Rollup 构建
- Vitepress + Vercel 文档网站搭建
- 基于Action CI 实现持续集成与交付

## Install
``` bash
 npm i ssy-ui-vite
```

## Quick Start
```bash
  import Vue from 'vue'
  import SSYUI from 'ssy-ui'

  const App = {
  template: `
 <SButton color="blue">主要按钮</SButton>
   `,
  };
createApp(App)
.use(SSYUI)
.mount("#app");
```
