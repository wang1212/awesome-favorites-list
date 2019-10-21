<div align="center">
  <h1>Awesome-Node.JS-List</h1>

  <p>:heart: 我自己的收藏列表 - :+1: 很棒的 Node.js 开发工具和生态技术。</p>
</div>

<br />

> Node.js 是一个基于 Chrome V8 引擎的 JavaScript 运行环境，使用了一个事件驱动、非阻塞式 I/O 的模型，为 JavaScript 提供了一个服务器端应用程序开发平台，:point_right: https://nodejs.org/

## Contents

- [技术标准](#技术标准)
  - [规范标准](#规范标准)
  - [技术文档](#技术文档)
  - [包管理器](#包管理器)
- [Node 模块](#node-模块)
- [开发框架](#开发框架)
- [其它](#其它)
  - [HTML 模板引擎](#html-模板引擎)
  - [辅助工具](#辅助工具)
  - [社区论坛](#社区论坛)
  - [期刊](#期刊)

## 技术标准

- [Node.js](https://nodejs.org/) - Node.js 官方网站。

### 规范标准

- [OpenAPI](https://www.openapis.org/) - 定义了一种 REST APIs 标准。

### 技术文档

- [Node.js 中文网](http://nodejs.cn/) - 唯一与官方同步更新的 Node.js 中文文档。

### 包管理器

- [npm](https://www.npmjs.com/) - Node.js 的官方包管理器。
- [Yarn](https://www.yarnpkg.com/)
- [Bower](https://bower.io/)

[Go Top ↑](#awesome-nodejs-list)

## Node 模块

- Utils
  - [chalk](https://github.com/chalk/chalk) - 终端输出字符串样式工具，支持全部的颜色。

- Node Version Manage
  - [n](https://github.com/tj/n) - npm 包，Node 版本管理工具。
  - [nvm](https://github.com/nvm-sh/nvm) - Node 版本管理。

- Process Manage
  - [Forever](https://github.com/foreversd/forever) - Node 应用生产环境进程管理工具，使用简单方便。
  - [PM2](https://pm2.keymetrics.io/) - Node 应用生产环境进程管理工具，支持集群、负载、远程部署，提供收费服务的实时监控平台。
  - [StrongLoop-PM](http://strong-pm.io/) - Node 应用生产环境进程管理工具，支持集群、负载、远程部署，提供收费服务的实时监控平台。

- HTTP Server
  - [Connect](https://github.com/senchalabs/connect) - 可扩展的 HTTP 服务器框架，使用中间件机制，早期的 [Express](http://expressjs.com/) 基于此开发。
  - [log4js](https://github.com/log4js-node/log4js-node) - 日志记录。

- Dev
  - [npm-check-updates](https://github.com/tjunnone/npm-check-updates) - 项目依赖 npm 包批量更新工具。
  - [nodemon](https://nodemon.io) - 提供 Node.js 开发时热重载机制。
  
- DataBase
  - [mongodb](http://mongodb.github.io/node-mongodb-native/) - 高性能、分布式文档数据库，No SQL 数据库。
    - [mongoose](https://mongoosejs.com/) - Node.js 对 mongodb 模型的封装。
  
- File
  - [fs-extra](https://github.com/jprichardson/node-fs-extra) - 作为官方原生 fs 模块的补充和优化。
  - [rotating-file-stream](https://github.com/iccicci/rotating-file-stream) - 文件流自动轮转，可用于日志文件分割，类似 UNIX `logrotate`。

[Go Top ↑](#awesome-nodejs-list)

## 开发框架

- [Express](http://expressjs.com/) - 非常成熟的 Node.js Web 开发框架。
  - [express-session](https://github.com/expressjs/session) - Express 中间件，提供 Session-Cookie 机制的支持，**官方发布**。
  - [body-parser](https://github.com/expressjs/body-parser) - Express 中间件，对 request 的 body 进行预处理，**官方发布**。
  - [Multer](https://github.com/expressjs/multer) - Express 中间件，处理 `multipart/form-data` 表单数据，**官方发布**。
  - [morgan](https://github.com/expressjs/morgan) - Express 中间件，请求日志记录，**官方发布**。
- [Koa](https://koajs.com/) - 轻量级、高性能的 Web 框架，Express 团队开发。
  
- [Electron](https://electronjs.org/) - 基于 Node.js 与 Chromium 技术的开源跨平台桌面端应用开发解决方案，对 Web 前端开发人员友好。

[Go Top ↑](#awesome-nodejs-list)

## 其它

### HTML 模板引擎

- [EJS](https://ejs.co)
- [Handlebars.js](http://handlebarsjs.com/)
- [Jade](http://jade-lang.com/)

### 辅助工具

- [Npm Trends](https://www.npmtrends.com/) - 非官方网站，可以查询对比多个 Npm 包的下载流量数据、star 数目等。
- [Npm Charts](https://npmcharts.com/) - 非官方网站，可以查询对比多个 Npm 包的下载流量数据、star 数目等。

### 社区论坛

- [CNode 社区](https://cnodejs.org/) - CNode 社区由一批热爱 Node.js 技术的工程师发起，致力于 Node.js 的技术研究。

### 期刊

- [Node-weekly](https://nodeweekly.com/) - Node.js 周刊。

[Go Top ↑](#awesome-nodejs-list)
