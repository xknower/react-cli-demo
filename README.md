# react-cli-demo

> REACT  命令, 安装配置 及页面框架案例

## 开发环境

### 1. 安装编辑器

- [VS Code](https://code.visualstudio.com/) - 编辑器

### 2. 配置编辑器

```jsonc
{
  "editor.rulers": [100],
  "editor.formatOnSave": true,
}
```

将以上配置放到 vscode 的用户配置中。

### 3. 安装配置

```bash

# node & fw
> npm install create-react-app -g
> create-react-app react-cli-demo
> cd react-cli-demo
> npm run start

// fw
react-cli-demo
  │
  ├─public
  │      favicon.ico
  │      index.html
  │      logo192.png
  │      logo512.png
  │      manifest.json
  │      robots.txt
  │      
  └─src
        App.css
        App.js
        App.test.js
        index.css
        index.js
        logo.svg
        serviceWorker.js
        setupTests.js

//
  │  .gitignore
  │  package.json
  │  yarn.lock
  └─ README.md

```