<div align="center">
  <h1>Awesome-Node.JS-List</h1>

  <p>:heart: 收藏列表 - :+1: 很棒的 Node.js 开发工具和生态技术。</p>
</div>

<br />

> Node.js 是一个基于 Chrome V8 引擎的 JavaScript 运行环境，使用了一个事件驱动、非阻塞式 I/O 的模型，为 JavaScript 提供了一个服务器端应用程序开发平台，:point_right: https://nodejs.org/

[OpenJS Foundation](https://openjsf.org/) - 开源 JS 基金会，由 Node 基金会和 JS 基金会合并而成。

## 目录

*Resource navigation list.*

- [技术规范标准（Technical Specifications）](#技术规范标准)
- [技术参考文档（Technical Reference Document）](#技术参考文档)
- [Node 模块（Node Module）](#node-模块)
  - [包管理器（Package Manager）](#包管理器)
  - [第三方模块（Unofficial Module）](#第三方模块)
- [Web 开发框架（Web Development Framework）](#web-开发框架)
- [其它（Others）](#其它)

## 技术规范标准

*Official technical specifications.*

- [Node.js](https://nodejs.org/) - Node.js 官方网站。

[Go Top ↑](#awesome-nodejs-list)

## 技术参考文档

*Official and unofficial technical reference documents.*

- [Node.js 中文网](http://nodejs.cn/) - 唯一与官方同步更新的 Node.js 中文文档。
- [Introduction to Node.js](https://nodejs.dev/) - Node.js 技术介绍。

[Go Top ↑](#awesome-nodejs-list)

## Node 模块

*Node modules (packages or libraries).*

### 包管理器

*Node.js package (or library) manager.*

- Packages Manageer
  - [npm](https://www.npmjs.com/) - Node.js 的官方指定包管理器。
  - [Yarn](https://www.yarnpkg.com/)
  - [Bower](https://bower.io/)

- Tool
  - [nrm](https://github.com/Pana/nrm) - npm 换源，**非官方**。
  - [Lerna](https://lerna.js.org/) - 管理 Monorepo 架构的 Node 模块代码库工具，**非官方**。
  - [Npm Trends](https://www.npmtrends.com/) - 可以查询对比多个 Npm 包的下载流量数据、star 数目等，**非官方网站**。
  - [Npm Charts](https://npmcharts.com/) - 可以查询对比多个 Npm 包的下载流量数据、star 数目等，**非官方网站**。
  
### 第三方模块

*Some unofficial high-quality Node.js packages (or libraries).*

- Node Version Manage
  - [n](https://github.com/tj/n) - npm 包，Node 版本管理工具，**不支持 Windows 系统**。
  - [nvm](https://github.com/nvm-sh/nvm) - Node 版本管理，**不支持 Windows 系统**。
  - [nvm-windows](https://github.com/coreybutler/nvm-windows) - Windows 系统下的 Node 版本管理工具。

- Process Manage
  - [Forever](https://github.com/foreversd/forever) - Node 应用生产环境进程管理工具，使用简单方便。
  - [PM2](https://pm2.keymetrics.io/) - Node 应用生产环境进程管理工具，支持集群、负载、远程部署，提供收费服务的实时监控平台。
  - [StrongLoop-PM](http://strong-pm.io/) - Node 应用生产环境进程管理工具，支持集群、负载、远程部署，提供收费服务的实时监控平台。

- Doc
  - [JSDoc](https://jsdoc.app/) - JavaScript 的 API 文档生成工具。

- Test
  - [Mocha](https://mochajs.org/)
  - [JEST](https://jestjs.io/) - Facebook 出品的 JavaScript 单元测试工具。

- Dev
  - [esm](https://github.com/standard-things/esm) - 能够为 `.js` 文件提供 [ECMAScript Modules](https://tc39.es/ecma262/#sec-modules) 支持。
  - [npm-check-updates](https://github.com/tjunnone/npm-check-updates) - 项目依赖 npm 包批量更新工具。
  - [nodemon](https://nodemon.io) - 提供 Node.js 开发时热重载机制。

- Code version management 
  - [husky](https://github.com/typicode/husky) - 更容易的使用 [Git Hooks](https://git-scm.com/book/it/v2/Customizing-Git-Git-Hooks)。
  - [lint-staged](https://www.npmjs.com/package/lint-staged) - 搭配 husky 使用，提交代码前进行 lint。

- Utils
  - [chalk](https://github.com/chalk/chalk) - 终端输出字符串样式工具，支持全部的颜色。
  - [commander](https://github.com/tj/commander.js) - 简单的命令行接口。
  - [inquirer](https://github.com/SBoudrias/Inquirer.js) - 交互式命令行。
  - [envinfo](https://github.com/tabrindle/envinfo) - 生成开发环境信息报告。

- HTTP Server
  - [http-server](https://github.com/http-party/http-server) - 可快速启动一个 http 服务器。
  - [Connect](https://github.com/senchalabs/connect) - 可扩展的 HTTP 服务器框架，使用中间件机制，早期的 [Express](http://expressjs.com/) 基于此开发。
  - [log4js](https://github.com/log4js-node/log4js-node) - 日志记录。

- HTTP Request
  - [axios](https://github.com/axios/axios) - 处理 HTTP 请求的工具库，非常方便。
  - [form-data](https://github.com/form-data/form-data) - 创建 `multipart/form-data` 数据，并提供正确的 Headers。
  
- DataBase
  - [mongodb](http://mongodb.github.io/node-mongodb-native/) - 高性能、分布式文档数据库，No SQL 数据库。
    - [mongoose](https://mongoosejs.com/) - 对 mongodb 的封装，提供模型 Schema，API 更简洁、易用。
  - [mysql](https://github.com/mysqljs/mysql)
    - [Sequelize](https://sequelize.org/) - 基于 Promise 的 Node.js ORM 库，支持 Postgres, MySQL, MariaDB, SQLite 和 Microsoft SQL Server。
  
- File
  - utils tool
    - [fs-extra](https://github.com/jprichardson/node-fs-extra) - 作为官方原生 [fs](https://nodejs.org/api/fs.html) 模块的补充和优化。
    - [rimraf](https://github.com/isaacs/rimraf) - 为 Node 提供类似 `rm -rf` 删除文件操作。
    - [memfs](https://github.com/streamich/memfs) - 内存文件系统。
    - [rotating-file-stream](https://github.com/iccicci/rotating-file-stream) - 文件流自动轮转，可用于日志文件分割，类似 UNIX `logrotate`。
  - xlsx
    - [exceljs](https://github.com/exceljs/exceljs) - 读、写 xlsx、csv 文件。
    - [xlsx](https://sheetjs.com/) - 读、写 xlsx、csv 文件（写功能部分特性不免费）。
  - pdf
    - [PDF-LIB](https://pdf-lib.js.org/) - 解析和操作 PDF 文件。
  - html/xml
    - [cheerio](https://cheerio.js.org/) - 包装了[parse5](https://github.com/inikulin/parse5) 和 [htmlparser2](https://github.com/fb55/htmlparser2/) 的轻量级 HTML 文档解析库，具有类 jQuery 的 api。
    - [puppeteer](https://github.com/puppeteer/puppeteer)    
  - markdown
    - [Marked](https://marked.js.org/) - markdown 文件解析，转换成 HTML 文件。

- HTML Template Engines
  - [EJS](https://ejs.co)
  - [Handlebars.js](http://handlebarsjs.com/)
  - [Jade](http://jade-lang.com/)
  
- Image Process
  - [sharp](https://sharp.pixelplumbing.com/) - 图像处理，拉伸、缩放、色彩提取等等，底层使用 [libvips](https://libvips.github.io/libvips/)，无需安装其它依赖，开箱即用，效率更高。
  - [gm](http://aheckmann.github.io/gm/) - 图像处理，需先安装 [GraphicsMagick](http://www.graphicsmagick.org/) 或 [ImageMagick](https://imagemagick.org/index.php)。

[Go Top ↑](#awesome-nodejs-list)

## Web 开发框架

*Node.js-based server development framework.*

- [Express](http://expressjs.com/) - 非常成熟的 Node.js Web 开发框架。
  - [express-session](https://github.com/expressjs/session) - Express 中间件，提供 Session-Cookie 机制的支持，**官方发布**。
  - [body-parser](https://github.com/expressjs/body-parser) - Express 中间件，对 request 的 body 进行预处理，**官方发布**。
  - [Multer](https://github.com/expressjs/multer) - Express 中间件，处理 `multipart/form-data` 表单数据，**官方发布**。
  - [morgan](https://github.com/expressjs/morgan) - Express 中间件，请求日志记录，**官方发布**。
  - [Passport.js](http://www.passportjs.org/) - 身份验证中间件，可在基于 Express 的 Node.js 框架中使用。
  
- [Koa](https://koajs.com/) - 轻量级、高性能的 Web 框架，Express 团队开发。

[Go Top ↑](#awesome-nodejs-list)

## 其它

*Other unclassified resources.*

### 桌面端开发

*Desktop-side application development framework.*

- [Electron](https://electronjs.org/) - 基于 Node.js 与 Chromium 技术的开源跨平台桌面端应用开发解决方案，对 Web 前端开发人员友好。

[Go Top ↑](#awesome-nodejs-list)
