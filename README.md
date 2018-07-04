<p align="center">
  <h1>quick-vue-admin</h1>
</p>

English | [简体中文](./README.zh-CN.md)

# Introduction

Least coding ,support config CRUD admin integration solution based on Element UI 2.x with MongoDB.


# Live Demo:
 https://linzhixian.github.io/element-vue-admin
 
## Dependencies
- nodejs &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(need stand alone install)
- koa 2.0.0  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(include)
- Element UI 2.x &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(include)
- MongoDB 3.x &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(need stand alone install)

## Features
```
- Login / Logout

- Permission Authentication
  - Menu permission
  - User Role permission

- CRUD CONFIG
  - through create one meta config file to auto generate CRUD page
  - auto create collection in MongoDB
  - auto create index in MongoDB
 

- Error Page
  - 401
  - 404
```

## Getting started

```bash
# clone the project
git clone https://github.com/linzhixian/quick-vue-admin.git

# install dependency
npm install

# develop
npm run dev
```

Open browser on： http://localhost:9001.

## Build
```bash
# build for production environment
npm run build
```
## Run
```bash
# Run for development environment
npm run dev
# Run for production environment
npm run pm2
```

## License

[MIT](https://github.com/linzhixian/quick-vue-admin/blob/master/LICENSE)

Copyright (c) 2018-present ZhiXianLin
