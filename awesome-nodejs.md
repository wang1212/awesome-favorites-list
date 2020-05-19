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
- [包管理器（Package Manager）](#包管理器)
- [工具库（Tool Library）](#工具库)
- [数据库（Database）](#数据库)
- [Web 框架（Web Framework）](#web-框架)
- [其它（Others）](#其它)

## 技术规范标准

*Official technical specifications.*

- [Node.js](https://nodejs.org/) - Node.js 官方网站。
- [Universal Module Definition](https://github.com/umdjs/umd) - 通用模块定义。

[Go Top ↑](#awesome-nodejs-list)

## 技术参考文档

*Official and unofficial technical reference documents.*

- [Node.js 中文网](http://nodejs.cn/) - 唯一与官方同步更新的 Node.js 中文文档。
- [Introduction to Node.js](https://nodejs.dev/) - Node.js 技术介绍。
- [JavaScript Algorithms and Data Structures](https://github.com/trekhleb/javascript-algorithms) - 算法和数据结构。
- [Setting up multi-platform npm packages](https://2ality.com/2017/04/setting-up-multi-platform-packages.html) - 多平台支持的 npm 包配置。

[Go Top ↑](#awesome-nodejs-list)

## 包管理器

*Node.js package (or library) manager.*

- Packages Manageer
  - [npm](https://www.npmjs.com/) - Node.js 的官方包管理器。
  - [Yarn](https://www.yarnpkg.com/)
  - [Bower](https://bower.io/)
  - [jspm](https://jspm.org/)

- Tool
  - [nrm](https://github.com/Pana/nrm) - npm 换源，**非官方**。
  - [Lerna](https://lerna.js.org/) - 管理 Monorepo 架构的 Node 模块代码库工具，**非官方**。
  - [Nx](https://nx.dev/) - 管理 Monorepo 架构的 Node 模块代码库工具，**非官方**。
  - [npm-check-updates](https://github.com/tjunnone/npm-check-updates) - 项目依赖 npm 包批量更新工具，**非官方**。
  - [Npm Trends](https://www.npmtrends.com/) - 可以查询对比多个 Npm 包的下载流量数据、star 数目等，**非官方网站**。
  - [Npm Charts](https://npmcharts.com/) - 可以查询对比多个 Npm 包的下载流量数据、star 数目等，**非官方网站**。

[Go Top ↑](#awesome-nodejs-list)

## 工具库

*Tool Library, some unofficial high-quality Node.js packages (or libraries).*

- Node Version Manage
  - [n](https://github.com/tj/n) - npm 包，Node 版本管理工具，**不支持 Windows 系统**。
  - [nvm](https://github.com/nvm-sh/nvm) - Node 版本管理，**不支持 Windows 系统**。
  - [nvm-windows](https://github.com/coreybutler/nvm-windows) - Windows 系统下的 Node 版本管理工具。

- Build
  - [webpack](https://webpack.js.org/) - 打包工具，适合开发 Web 应用。
  - [Rollup](http://rollupjs.org/) - 打包工具，适合开发库、框架。
  - [SystemJS](https://github.com/systemjs/systemjs) - 动态 ES Module 加载器。
  - [esm](https://github.com/standard-things/esm) - 能够为 `.js` 文件提供 [ECMAScript Modules](https://tc39.es/ecma262/#sec-modules) 支持。
  - [nodemon](https://nodemon.io) - 提供 Node.js 开发时热重载机制。
  - [TS Node](https://github.com/TypeStrong/ts-node) - Node.js 的 TypeScript 语言运行器和交互式解释器。

- Doc
  - [JSDoc](https://jsdoc.app/) - JavaScript 的 API 文档生成工具。

- Test
  - [Mocha](https://mochajs.org/) - 测试框架。
  - [JEST](https://jestjs.io/) - Facebook 出品的 JavaScript 单元测试工具。
  - [JSON Server](https://github.com/typicode/json-serve) - 可快速启动一个提供 REST API 的服务器，并返回指定测试数据。  
  - [Nock](https://github.com/nock/nock) - 模拟 API 服务，响应指定测试数据。
  - [Mock.js](http://mockjs.com/) - 模拟 API 服务，响应随机测试数据。
  - [faker.js](https://github.com/marak/faker.js) - 生成大量随机测试数据，可用来开发过程中进行 API 调试。
  - [Chance](https://chancejs.com/) - 生成随机的测试数据。  

- Code version management 
  - [husky](https://github.com/typicode/husky) - 更容易的使用 [Git Hooks](https://git-scm.com/book/it/v2/Customizing-Git-Git-Hooks)。
  - [lint-staged](https://www.npmjs.com/package/lint-staged) - 搭配 husky 使用，提交代码前进行 lint。

- Process Manage
  - [Forever](https://github.com/foreversd/forever) - Node 应用生产环境进程管理工具，使用简单方便。
  - [PM2](https://pm2.keymetrics.io/) - Node 应用生产环境进程管理工具，支持集群、负载、远程部署，提供收费服务的实时监控平台。
  - [StrongLoop-PM](http://strong-pm.io/) - Node 应用生产环境进程管理工具，支持集群、负载、远程部署，提供收费服务的实时监控平台。

- Utils
  - [chalk](https://github.com/chalk/chalk) - 终端输出字符串样式工具，支持全部的颜色。
  - [commander](https://github.com/tj/commander.js) - 简单的命令行接口。
  - [inquirer](https://github.com/SBoudrias/Inquirer.js) - 交互式命令行。
  - [envinfo](https://github.com/tabrindle/envinfo) - 生成开发环境信息报告。
  - [web-worker](https://github.com/developit/web-worker) - 在浏览器和 Node.js 环境中实现一致的 Web Worker API。

- HTTP Server
  - [http-server](https://github.com/http-party/http-server) - 可快速启动一个轻量的 http 服务器。
  - [log4js](https://github.com/log4js-node/log4js-node) - 日志记录。

- HTTP Request
  - [axios](https://github.com/axios/axios) - 处理 HTTP 请求的工具库，非常方便。
  - [form-data](https://github.com/form-data/form-data) - 创建 `multipart/form-data` 数据，并提供正确的 Headers。
  
- HTML Template Engines
  - [EJS](https://ejs.co)
  - [Handlebars.js](http://handlebarsjs.com/)
  - [Jade](http://jade-lang.com/)
  
- QR Code
  - [node-qrcode](https://github.com/soldair/node-qrcode) - 二维码生成。
  - [Awesome-qr.js](https://www.bitcat.cc/webapp/awesome-qr/index.html) - 个性化二维码生成。（:warning: 不再维护）
  
- File
  - utils tool
    - [fs-extra](https://github.com/jprichardson/node-fs-extra) - 作为官方原生 [fs](https://nodejs.org/api/fs.html) 模块的补充和优化。
    - [rimraf](https://github.com/isaacs/rimraf) - 为 Node 提供类似 `rm -rf` 删除文件操作。
    - [memfs](https://github.com/streamich/memfs) - 内存文件系统。
    - [rotating-file-stream](https://github.com/iccicci/rotating-file-stream) - 文件流自动轮转，可用于日志文件分割，类似 UNIX `logrotate`。
  - json5
    - [JSON5](https://json5.org/) - JSON5 格式数据解析、序列化。
  - zip
    - [JSZip](https://stuk.github.io/jszip/) - 解析、生成 zip 文件，具有简单的 API。 
    - [ADM-ZIP](https://github.com/cthackers/adm-zip)
    - [Archiver](https://www.archiverjs.com/) - 生成存档文件的流式接口。
    - [node-stream-zip](https://github.com/antelle/node-stream-zip) - 支持大的 zip 文件。    
  - xlsx
    - [exceljs](https://github.com/exceljs/exceljs) - 读、写 xlsx、csv 文件。
    - [xlsx](https://sheetjs.com/) - 读、写 xlsx、csv 文件（写功能部分特性不免费）。
  - csv
    - [CSV](https://csv.js.org/) - 功能全面的 csv 文件生成、解析、转换、序列化工具。
    - [Papa Parse](https://www.papaparse.com/)    
  - pdf
    - [PDF-LIB](https://pdf-lib.js.org/) - 解析和操作 PDF 文件。
  - html/xml
    - [cheerio](https://cheerio.js.org/) - 包装了[parse5](https://github.com/inikulin/parse5) 和 [htmlparser2](https://github.com/fb55/htmlparser2/) 的轻量级 HTML 文档解析库，具有类 jQuery 的 api。
    - [puppeteer](https://github.com/puppeteer/puppeteer)    
  - markdown
    - [Marked](https://marked.js.org/) - markdown 文件解析，转换成 HTML 文件。
    - [gray-matter](https://github.com/jonschlinkert/gray-matter) - 解析 [Front Matter](https://jekyllrb.com/docs/front-matter/)。
    - [front-matter](https://github.com/jxson/front-matter) - 解析 Front Matter。
  - image
    - [sharp](https://sharp.pixelplumbing.com/) - 图像处理，拉伸、缩放、色彩提取等等，底层使用 [libvips](https://libvips.github.io/libvips/)，无需安装其它依赖，开箱即用，效率更高。
    - [gm](http://aheckmann.github.io/gm/) - 图像处理，需先安装 [GraphicsMagick](http://www.graphicsmagick.org/) 或 [ImageMagick](https://imagemagick.org/index.php)。

[Go Top ↑](#awesome-nodejs-list)

## 数据库

*Database.*

- [Sequelize](https://sequelize.org/) - 基于 Promise 的 Node.js ORM 库，支持 Postgres, MySQL, MariaDB, SQLite 和 Microsoft SQL Server。

- [mongodb](http://mongodb.github.io/node-mongodb-native/) - [MongoDB](https://www.mongodb.com/) 的 Node.js 驱动，**MongoDB 官方发布**。
  - [mongoose](https://mongoosejs.com/) - 对 mongodb 的封装，提供模型 Schema，API 更简洁、易用。
  
- [mysql](https://github.com/mysqljs/mysql) - [MySQL](https://www.mysql.com/) 的 Node.js 驱动，**非官方发布**。

- [sqlite3](https://github.com/mapbox/node-sqlite3) - [SQLite](https://sqlite.org/) 的 Node.js 驱动，异步、非阻塞，**非官方发布**。

[Go Top ↑](#awesome-nodejs-list)

## Web 框架

*Node.js-based server development framework.*

- [Connect](https://github.com/senchalabs/connect) - 可扩展的 HTTP 服务器开发框架，使用中间件机制，早期的 [Express](http://expressjs.com/) 基于此开发。

- [Express](http://expressjs.com/) - 非常成熟的 Web 开发框架。
  - [express-session](https://github.com/expressjs/session) - Express 中间件，提供 Session-Cookie 机制的支持，**官方发布**。
  - [body-parser](https://github.com/expressjs/body-parser) - Express 中间件，对 request 的 body 进行预处理，**官方发布**。
  - [Multer](https://github.com/expressjs/multer) - Express 中间件，处理 `multipart/form-data` 表单数据，**官方发布**。
  - [morgan](https://github.com/expressjs/morgan) - Express 中间件，请求日志记录，**官方发布**。
  - [Passport.js](http://www.passportjs.org/) - 身份验证中间件，可在基于 Express 的 Node.js 框架中使用。
  
- [Koa](https://koajs.com/) - 轻量级、高性能的 Web 框架，Express 团队开发。

- [Gatsby](https://www.gatsbyjs.org/) - 基于 React.js 的开源框架，可快速开发 Web 网站和应用，多用于制作静态资源站点。

[Go Top ↑](#awesome-nodejs-list)

## 其它

*Other unclassified resources.*

### 桌面端开发

*Desktop-side application development framework.*

- [Electron](https://electronjs.org/) - 基于 Node.js 与 Chromium 技术的开源跨平台桌面端应用开发解决方案。
- [NW.js](https://nwjs.io/) - 基于 Node.js 与 Chromium 技术的开源跨平台桌面端应用开发解决方案。
- [Neutralino](https://neutralino.js.org/) - 轻量级跨平台桌面端应用开发框架。

[Go Top ↑](#awesome-nodejs-list)
