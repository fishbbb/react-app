# react-app
BJTU-轻量化平台作业：实现权限控制，对用户进行菜单分配等

# 项目运行启动运行方法：
npm install
npm run dev

# 项目描述
## 项目内容
本项目旨在实现一个后台管理系统，本次作业中的目标是实现权限管理的部分，包括用户权限管理和用户权限分配。
## 项目目录结构
```
react
├─ .eslintrc.cjs
├─ .git
├─ .gitignore
├─ index.html
├─ package-lock.json
├─ package.json
├─ public
│  └─ vite.svg
├─ README.md
├─ src
│  ├─ App.css
│  ├─ App.jsx
│  ├─ assets
│  │  └─ react.svg
│  ├─ components
│  │  └─ MyLayout.jsx
│  ├─ data
│  ├─ index.css
│  ├─ main.jsx
│  ├─ pages
│  │  ├─ logOut.jsx
│  │  ├─ MenuManagePage.jsx
│  │  ├─ RegisterPage.jsx
│  │  ├─ ResourceListPage.jsx
│  │  ├─ RoleListPage.jsx
│  │  └─ UserListPage.jsx
│  └─ service
│     ├─ MenuService.js
│     └─ UserService.js
└─ vite.config.js
```
## 插件
使用了antd组件库，项目目录结构由VScode 扩展 Project Tree生成

## 组件使用说明
使用了entd组件库中的表单，按钮，树，表格，菜单等组件。
## 项目功能
```
### 用户管理
可以对用户进行新增，删除，更改和搜索。
### 角色管理
可以新增角色并对角色进行菜单分配，规定用户可以看到哪些菜单，默认由三种角色：“超级管理员”，“商品管理员”，“销售管理员”。
### 菜单管理
可以查看已有菜单，新增菜单内容，删除菜单内容等。
```
# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
