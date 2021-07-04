<div align="center">
  <h1>Awesome-Node.JS-List</h1>

  <p>:heart: 收藏列表 - :+1: 很棒的 Node.js 开发工具和生态技术。</p>
  <p><i>Favorites list - great Node.js development tools and ecological technology.</i></p>
</div>

<br />

> Node.js 是一个基于 Chrome V8 引擎的 JavaScript 运行环境，使用了一个事件驱动、非阻塞式 I/O 的模型，为 JavaScript 提供了一个服务器端应用程序开发平台，:point_right: https://nodejs.org/

[OpenJS Foundation](https://openjsf.org/) - 开源 JS 基金会，由 Node 基金会和 JS 基金会合并而成。

（Recommend）推荐一个其它的很棒的收藏列表，:point_right: https://github.com/sindresorhus/awesome-nodejs

## 目录

*Resource navigation list.*

- [技术标准规范（Technical Standard Specification）](#技术标准规范)
- [技术参考文档（Technical Reference Document）](#技术参考文档)
- [Node 版本管理（Node Version Management）](#node-版本管理)
- [Node 包管理（Node Package Manage）](#node-包管理)
- [工具库（Tool Library）](#工具库)
- [命令行工具（Command Line Tools）](#命令行工具)
- [数据库（Database）](#数据库)
- [Web 框架（Web Framework）](#web-框架)
- [内容管理系统（Content Management System）](#内容管理系统)
- [桌面端开发（Desktop Development）](#桌面端开发)
- [文章（Article）](#文章)
- [更多（More）](#更多)

## 技术标准规范

*Technical standard specification.*

- [ECMAScript Official Specification Standard](https://www.ecma-international.org/publications/standards/Ecma-262.htm) - ECMAScript 官方规范标准。
  - [ECMA International](http://www.ecma-international.org/) - ECMA 国际是一家国际性会员制度的信息和电信标准组织，负责行业标准的制定，例如 ECMA Script。
  - [TC39 ECMAScript proposals](https://github.com/tc39/proposals) - TC39 对 ECMAScript 标准制定提案的记录。
- [Node.js](https://nodejs.org/) - Node.js 官方网站。
  - [V8](https://v8.dev/) - Node.js 的运行时，也是 Chrome 浏览器的 JS 运行时。:point_right: [中文翻译](https://v8.js.cn/)
  - [CommonJS](http://www.commonjs.org/) - Node.js 默认采用的模块加载方式。
  - [AMD](https://github.com/amdjs/amdjs-api/blob/master/AMD.md) - 异步模块定义，适合浏览器端。
  - [Universal Module Definition](https://github.com/umdjs/umd) - 通用模块定义，兼容 AMD、CommonJS 以及全局变量方式。
- [TypeScript](http://www.typescriptlang.org/) - JavaScript 的超集，强类型语言。
  - [tsdoc](https://github.com/microsoft/tsdoc) - TypeScript 语言注释规范，**Microsoft 官方发布**。
  
*More others 👉 [Awesome-Development-Technical-Standard-Specifications](awesome-dev-specifications.md)*
  
[`Go Top ↑`](#awesome-nodejs-list)

## 技术参考文档

*Official and unofficial technical reference documents.*

- 标准实现状态（Standard implementation status）
  - [compatibility table](https://node.green/) - 可查询 ECMAScript API 在各个版本 Node.js 实现的状态，**非官方网站**。

- [Node.js 中文网](http://nodejs.cn/) - 唯一与官方同步更新的 Node.js 中文文档。
- [JavaScript Algorithms and Data Structures](https://github.com/trekhleb/javascript-algorithms) - 算法和数据结构。

[`Go Top ↑`](#awesome-nodejs-list)

## Node 版本管理

*Node version management, can install multiple versions at the same time, and switch at any time.*

- [n](https://github.com/tj/n) - npm 包，Node 版本管理工具，**不支持 Windows 系统**。
- [nvm](https://github.com/nvm-sh/nvm) - Node 版本管理，**不支持 Windows 系统**。
- [nvm-windows](https://github.com/coreybutler/nvm-windows) - Node 版本管理工具，**仅支持 Windows 系统**。

[`Go Top ↑`](#awesome-nodejs-list)

## Node 包管理

*Node.js package (or library) manage.*

- 包管理器（Packages Manageer）
  - [npm](https://www.npmjs.com/) - Node.js 的官方包管理器。
  - [Yarn](https://www.yarnpkg.com/)
  - [pnpm](https://pnpm.js.org/)
  - [Bower](https://bower.io/)
  - [jspm](https://jspm.org/)

- 包开发（Package Development）
  - [Rollup](http://rollupjs.org/) - 打包工具，适合开发库、框架。
  - [np](https://github.com/sindresorhus/np) - `npm publish` 的替代工具库，让发布更优雅、安全。
  - [Denoify](https://github.com/garronej/denoify) - 为 npm 模块作者提供 Deno 支持。
  - [cross-env](https://github.com/kentcdodds/cross-env) - 为 npm 脚本配置和使用环境变量提供跨平台支持。

- [Monorepo](https://en.wikipedia.org/wiki/Monorepo) 工具（Monorepo Tools）
  - [Lerna](https://lerna.js.org/) - 管理 Monorepo 架构的 Node 模块代码库工具。
  - [Nx](https://nx.dev/) - 管理 Monorepo 架构的 Node 模块代码库工具。

- 工具（Tools）
  - [Verdaccio](https://verdaccio.org/) - 开源的轻量级私有 npm 代理仓库。
  - [nrm](https://github.com/Pana/nrm) - npm 换源。
  - [npm-check-updates](https://github.com/tjunnone/npm-check-updates) - 项目依赖 npm 包批量更新工具。
  - [Npm Trends](https://www.npmtrends.com/) - 可以查询对比多个 Npm 包的下载流量数据、star 数目等。
  - [Moiva](https://moiva.io/) - 比较 Github 和 npm 包下载趋势，关注度等等。
  - [Npm Charts](https://npmcharts.com/) - 可以查询对比多个 Npm 包的下载流量数据、star 数目等。
  - [BUNDLEPHOBIA](https://bundlephobia.com/) - 分析 npm 包大小和依赖关系。
  - [Package Phobia](https://packagephobia.com/) - 分析 npm 包大小。
  - [runpkg](https://www.runpkg.com/) - 在线浏览 npm 包内的文件内容。
  - [depcheck](https://github.com/depcheck/depcheck) - 项目依赖检查。
  - [npkill](https://npkill.js.org/) - 搜索系统中的 *node_modules* 文件夹并清理。
  - [njt](https://njt.now.sh/) -  npm jump to，npm 包搜索并跳转到相应 npm 站点。

[`Go Top ↑`](#awesome-nodejs-list)

## 工具库

*Tool Library, some unofficial high-quality Node.js packages (or libraries).*

- 构建工具（Build Tools）
  - 编译器（Compiler）
    - [Babel](https://babeljs.io/) - 编译工具，可将 TypeScript、ES6/7/8 代码编译为 JavaScript（ES5） 代码。
    - [TS Node](https://github.com/TypeStrong/ts-node) - Node.js 的 TypeScript 语言运行器和交互式解释器。
    - [Neon](https://neon-bindings.com/) - Rust 的 Node.js 绑定，可用来编写快速、安全的原生模块。
  - 调试（Debug）
    - [debug](https://github.com/visionmedia/debug) - 打印 debug 日志。
  - 日志（Log）
    - [log4js](https://github.com/log4js-node/log4js-node) - 日志记录。
    - [winston](https://github.com/winstonjs/winston) - 简单通用的日志库。
    - [pino](https://getpino.io/) - 简单的 JSON 日志记录器。
  - 其它（Others）
    - [dotenv](https://github.com/motdotla/dotenv) - 从 **.env** 文件为 Node.js 项目加载环境变量。
    - [Envalid](https://github.com/af/envalid) - 环境变量校验。
    - [esm](https://github.com/standard-things/esm) - 能够为 `.js` 文件提供 [ECMAScript Modules](https://tc39.es/ecma262/#sec-modules) 支持。
    - [envinfo](https://github.com/tabrindle/envinfo) - 生成开发环境信息报告。
    - [Madge](https://github.com/pahen/madge) - 生成可视化的模块依赖图。
    - [threads.js](https://threads.js.org/) - 在浏览器和 Node.js 环境中实现一致的 Web Worker API。
    - [web-worker](https://github.com/developit/web-worker) - 在浏览器和 Node.js 环境中实现一致的 Web Worker API。
    - [piscina](https://github.com/piscinajs/piscina) - 线程池工具。

- 文档（Doc）
  - [tldr](https://github.com/tldr-pages/tldr) - Unix 系统的 man pages 文档简化版本，更清晰易懂。
  - [JSDoc](https://jsdoc.app/) - JavaScript 的 API 文档生成工具。
  - [typedoc](https://typedoc.org/) - 生成 TypeScript 项目文档。

- 测试（Test）
  - [Mocha](https://mochajs.org/) - 测试框架。
  - [JEST](https://jestjs.io/) - Facebook 出品的 JavaScript 单元测试工具。
  - [JSON Server](https://github.com/typicode/json-serve) - 可快速启动一个提供 REST API 的服务器，并返回指定测试数据。  
  - [Nock](https://github.com/nock/nock) - 模拟 API 服务，响应指定测试数据。
  - [Mock.js](http://mockjs.com/) - 模拟 API 服务，响应随机测试数据。
  - [MSW](https://mswjs.io/) - 模拟 API 服务。
  - [faker.js](https://github.com/marak/faker.js) - 生成大量随机测试数据，可用来开发过程中进行 API 调试。
  - [Chance](https://chancejs.com/) - 生成随机的测试数据。
  - [Browsersync](https://www.browsersync.io/) - 浏览器同步调式工具，功能非常强大。

* 基准测试（Benchmarks）
  * [autocannon](https://github.com/mcollina/autocannon#limitations)

- 性能分析（profiling ）
  - [0x](https://github.com/davidmarkclements/0x)

- 代码静态分析（Code Lint）
  - [ESLint](https://eslint.org/) - JavaScript 语法规则检查工具。
  - [Prettier](https://prettier.io/) - 代码格式化工具，支持多种语言。
  - [stylelint](https://stylelint.io/) - CSS 语法规则检查工具，支持 CSS/Sass/CSS-in-JS 等。
  - [Flow](https://flow.org/) - Facebook 出品的 JavaScript 静态类型检查工具。

- 代码版本管理（Code version management ）
  - [husky](https://github.com/typicode/husky) - 更容易的使用 [Git Hooks](https://git-scm.com/book/it/v2/Customizing-Git-Git-Hooks)。
  - [lint-staged](https://www.npmjs.com/package/lint-staged) - 搭配 husky 使用，提交代码前进行 lint。

- 进程管理（Process Manage）
  - [nodemon](https://nodemon.io) - 提供 Node.js 开发时热重载机制。
  - [node-dev](https://github.com/fgnass/node-dev) - 热重载。
  - [Forever](https://github.com/foreversd/forever) - Node 应用生产环境进程管理工具，使用简单方便。
  - [PM2](https://pm2.keymetrics.io/) - Node 应用生产环境进程管理工具，支持集群、负载、远程部署，提供收费服务的实时监控平台。
  - [StrongLoop-PM](http://strong-pm.io/) - Node 应用生产环境进程管理工具，支持集群、负载、远程部署，提供收费服务的实时监控平台。

- 实用工具（Utils）
  - [Underscore](https://underscorejs.org/) - JavaScript 的工具函数库，提供了大量非常有用的工具函数。
  - [Lodash](https://lodash.com/) - JavaScript 的工具函数库，参考自 Underscore，功能更丰富。
  - [Ramda](https://ramdajs.com/) - JavaScript 的工具函数库，适用于函数式编程。
  - [RxJS](https://rxjs.dev/) - 响应式编程（Reactive Extensions）的 JavaScript 实现，对异步数据集合处理很方便。
  - [tslog](https://tslog.js.org/) - 日志格式化。
  - [uuid](https://github.com/uuidjs/uuid) - 生成随机 id。
  - [Nano ID](https://zelark.github.io/nano-id-cc/) - 生成唯一、URL 友好、安全的随机字符串。
  - [cuid](https://github.com/ericelliott/cuid) - 生成防碰撞的随机 id。
  - [execa](https://github.com/sindresorhus/execa) - 对官方 [`child_process`](https://nodejs.org/api/child_process.html) 模块的改进。
  
- 异步操作（Asynchronous operation）
  - [promise-fun](https://github.com/sindresorhus/promise-fun) - `Promise` 工具库集合。
  
- 时间日期（Date && Time）
  - [Day.js](https://day.js.org/) - 轻量级时间日期工具库。
  - [ms](https://github.com/vercel/ms) - 毫秒格式化工具。
  
- 数据校验（Data Validation）
  - [ajv](https://github.com/ajv-validator/ajv) - JSON Schema validator。
  - [joi](https://joi.dev/)
  - [yup](https://github.com/jquense/yup)
  
- 数据操作（Data Manipulation）
  - [Danfo.js](https://danfo.jsdata.org/) - 处理结构化数据的工具库，类似 Python 的 [Pandas](https://pandas.pydata.org/pandas-docs/stable/index.html)。
  
- 数据加密、解密（Data encryption and decryption）
  - [bcrypt](https://github.com/kelektiv/node.bcrypt.js) - 生成密码哈希值。
  - [crypto-js](https://github.com/brix/crypto-js) - JavaScript 加密库。
  - [https://github.com/digitalbazaar/forge](https://www.npmjs.com/package/node-forge) - JavaScript 加密库。
  - [md5.js](https://github.com/crypto-browserify/md5.js) - md5 哈希库。（:warning: 不再更新）
  - [md5](https://github.com/pvorb/node-md5) - md5 哈希库。
  - [object-hash](https://github.com/puleos/object-hash) - 对 JavaScript 对象进行 hash 处理。
  - [SJCL](http://bitwiseshiftleft.github.io/sjcl/) - JavaScript 加密库。（:warning: 不再更新）
  
- 数学计算（Compute - Math & High precision & Scientific Computing）
  - [math.js](https://mathjs.org/) - 数学计算。
  - [stdlib](https://stdlib.io/)
  
- 二维码（QR Code）
  - [node-qrcode](https://github.com/soldair/node-qrcode) - 二维码生成。
  - [Awesome-qr.js](https://www.bitcat.cc/webapp/awesome-qr/index.html) - 个性化二维码生成。（:warning: 不再维护）
  
- 文件（File）
  - utils tools
    - [fs-extra](https://github.com/jprichardson/node-fs-extra) - 作为官方原生 [`fs`](https://nodejs.org/api/fs.html) 模块的补充和优化。
    - [rimraf](https://github.com/isaacs/rimraf) - 为 Node 提供类似 `rm -rf` 删除文件操作。
    - [memfs](https://github.com/streamich/memfs) - 内存文件系统。
    - [rotating-file-stream](https://github.com/iccicci/rotating-file-stream) - 文件流自动轮转，可用于日志文件分割，类似 UNIX `logrotate`。
    - [file-type](https://github.com/sindresorhus/file-type) - 探测文件类型。
    - [fdir](https://thecodrr.github.io/fdir/) - 最快的目录搜索器。
  - html/xml
    - [jsdom](https://github.com/jsdom/jsdom) - Web 标准的纯 JavaScript 实现。
    - [cheerio](https://cheerio.js.org/) - 包装了[parse5](https://github.com/inikulin/parse5) 和 [htmlparser2](https://github.com/fb55/htmlparser2/) 的轻量级 HTML 文档解析库，具有类 jQuery 的 api。
    - [parse-xml](https://github.com/rgrove/parse-xml) - XML 解析器。
  - markdown
    - [Marked](https://marked.js.org/) - markdown 文件解析，转换成 HTML 文件。
    - [gray-matter](https://github.com/jonschlinkert/gray-matter) - 解析 [Front Matter](https://jekyllrb.com/docs/front-matter/)。
    - [front-matter](https://github.com/jxson/front-matter) - 解析 Front Matter。    
  - json5
    - [JSON5](https://json5.org/) - JSON5 格式数据解析、序列化。
  - yaml
    - [js-yaml](https://github.com/nodeca/js-yaml) - yaml 文件解析和生成。
  - zip
    - [JSZip](https://stuk.github.io/jszip/) - 解析、生成 zip 文件，具有简单的 API。 
    - [ADM-ZIP](https://github.com/cthackers/adm-zip)
    - [Archiver](https://www.archiverjs.com/) - 生成存档文件的流式接口。
    - [node-stream-zip](https://github.com/antelle/node-stream-zip) - 支持大的 zip 文件。    
  - csv
    - [CSV](https://csv.js.org/) - 功能全面的 csv 文件生成、解析、转换、序列化工具。
    - [Papa Parse](https://www.papaparse.com/)    
  - pdf
    - [PDF-LIB](https://pdf-lib.js.org/) - 解析和操作 PDF 文件。
    - [PDFKit](http://pdfkit.org/) - 生成 PDF 文件。
  - xlsx
    - [exceljs](https://github.com/exceljs/exceljs) - 读、写 xlsx、csv 文件。
    - [xlsx](https://sheetjs.com/) - 读、写 xlsx、csv 文件（写功能部分特性不免费）。    
  - docx
    - [officegen](https://github.com/Ziv-Barber/officegen) - 生成 Office 文档。 
    - [docx](https://github.com/dolanmiu/docx) - 生成 docx 文档。
  - image
    - [sharp](https://sharp.pixelplumbing.com/) - 图像处理，拉伸、缩放、色彩提取等等，底层使用 [libvips](https://libvips.github.io/libvips/)，无需安装其它依赖，开箱即用，效率更高。
    - [gm](http://aheckmann.github.io/gm/) - 图像处理，需先安装 [GraphicsMagick](http://www.graphicsmagick.org/) 或 [ImageMagick](https://imagemagick.org/index.php)。
  - svg
    - [SVGO](https://github.com/svg/svgo) - SVG 文件优化工具。

- HTTP 服务器（HTTP Server）
  - [http-server](https://github.com/http-party/http-server) - 可快速启动一个轻量的 http 服务器。
  - [CORS Anywhere](https://github.com/Rob--W/cors-anywhere) - 反向代理服务器。

- HTTP 请求（HTTP Request）
  - [axios](https://github.com/axios/axios) - 处理 HTTP 请求的工具库，非常方便。
  - [form-data](https://github.com/form-data/form-data) - 创建 `multipart/form-data` 数据，并提供正确的 Headers。
  - [formidable ](https://github.com/node-formidable/formidable) - 解析请求中的 `multipart/form-data` 数据。
  - [Busboy](https://github.com/mscdex/busboy) -  解析请求中的 `multipart/form-data` 数据，支持流。
  
- HTML 模板引擎（HTML Template Engines）
  - [EJS](https://ejs.co)
  - [Handlebars.js](http://handlebarsjs.com/)
  - [Jade](http://jade-lang.com/)
  
- 远程过程调用（RPC）
  - [Lounge](https://thelounge.chat/) - 现代的 Web RPC 客户端。
  
- 套接字（Socket）
  - [Socket.IO](http://socket.io/) - 基于事件的实时通信框架，提供客户端和服务器实现。
  - [ws](https://github.com/websockets/ws) - Node.js WebSocket 客户端和服务器。

- 邮件（SMTP）
  - [Nodemailer](https://nodemailer.com/) - 邮件发送。
  - [mailgen](https://github.com/eladnava/mailgen) - 生成响应式 HTML 电子邮件模版。

- 无头浏览器（Headless Browser）
  - [playwright](https://playwright.dev/) - 跨浏览器 Web 自动化工具，**Microsoft 发布**。
  - [puppeteer](https://github.com/puppeteer/puppeteer)
  - [cypress](https://www.cypress.io/)
  - [testcafe](https://devexpress.github.io/testcafe/)
  - [Nightwatch.js](https://nightwatchjs.org/)
  - [Nightmare](http://www.nightmarejs.org/)

- 系统组件（System Components）
  - [node-notifier](https://github.com/mikaelbr/node-notifier) - 跨平台原生通知功能。

- 本地化（Native）
  - [node-windows](https://github.com/coreybutler/node-windows) - Windows 平台对 Node.js 脚本（守护程序，事件日志，UAC 等）的支持。
  - [systeminformation](https://github.com/sebhildebrandt/systeminformation) - 获取系统信息。

- 其它（Others）
  - [ssh2](https://github.com/mscdex/ssh2) - SSH 客户端和服务器。

[`Go Top ↑`](#awesome-nodejs-list)

## 命令行工具

*Command line tools and tools used to develop command line applications.*

- [zx](https://github.com/google/zx) - 编写 JavaScript 脚本，而非 Bash 脚本。

* CLI Tool
  * [chalk](https://github.com/chalk/chalk) - 终端输出字符串样式工具，支持全部的颜色。
  * [concurrently](https://github.com/kimmobrunfeldt/concurrently) - 并行执行多个命令。
  * [shell.js](https://documentup.com/shelljs/shelljs) - 基于 NOde.js 的 Unix Shell 命令的可移植实现。

- 命令行应用开发（CLI App Dev）
  - [minimist](https://github.com/substack/minimist) - 命令行参数解析器。
  - [Caporal](https://github.com/mattallty/Caporal.js) - 全功能命令行应用开发框架。
  - [commander](https://github.com/tj/commander.js) - 简单的命令行接口。
  - [meow](https://github.com/sindresorhus/meow) - 命令行应用开发工具包。
  - [Gluegun](https://github.com/infinitered/gluegun) - 命令行应用开发工具包。
  - [Terminal Kit](https://github.com/cronvel/terminal-kit) - 编写命令行程序的工具包。
  - [blessed](https://github.com/chjj/blessed) - 高级终端接口库。
    - [blessed-contrib](https://github.com/yaronn/blessed-contrib) - 仪表面板工具库。
  - [inquirer](https://github.com/SBoudrias/Inquirer.js) - 交互式命令行。
  - [ora](https://github.com/sindresorhus/ora) - 终端 spinner 效果。 

* 可执行程序（Executable）
  * [pkg](https://github.com/vercel/pkg) - 将 Node.js 脚本打包成单个可执行文件。
  * [nexe](https://github.com/nexe/nexe)

[`Go Top ↑`](#awesome-nodejs-list)

## 数据库

*Database.*

- [Knex.js](http://knexjs.org/) - SQL 生成器，支持 Node.js 与浏览器环境。

- [mongodb](http://mongodb.github.io/node-mongodb-native/) - [MongoDB](https://www.mongodb.com/) 的 Node.js 驱动，**MongoDB 官方发布**。
  - [mongoose](https://mongoosejs.com/) - 对象文档映射（ODM），对 mongodb 的封装，提供模型 Schema，API 更简洁、易用。
  
- [mysql](https://github.com/mysqljs/mysql) - [MySQL](https://www.mysql.com/) 的 Node.js 驱动，**非官方发布**。

- [sqlite3](https://github.com/mapbox/node-sqlite3) - [SQLite](https://sqlite.org/) 的 Node.js 驱动，异步、非阻塞，**非官方发布**。
  - [better-sqlite3](https://github.com/JoshuaWise/better-sqlite3) - 比 node-sqlite3 更快更简单的 API。

- [GraphQL](https://graphql.org/) - 开源的数据库查询语言。
- [Prisma](https://github.com/prisma/prisma) - 数据库工具套件。
- [PostGraphile](https://www.graphile.org/postgraphile/) - 为已有的 PostgreSQL 数据库提供 GraphQL API 支持。

- 对象关系映射（ORM）
  - [Sequelize](https://sequelize.org/) - 基于 Promise 的 Node.js ORM 库，支持 Postgres, MySQL, MariaDB, SQLite 和 Microsoft SQL Server。
  - [TypeORM](https://typeorm.io/) - 可以运行在所有 JS 技术栈中的 ORM 库，支持主流数据库。
  - [Objection.js](https://vincit.github.io/objection.js/) - 基于 `Knex.js` 构建。
  - [Bookshelf](https://bookshelfjs.org/) - 基于 `Knex.js` 构建。
  - [mikro-orm](https://mikro-orm.io/) - TypeScript ORM 库，支持 MongoDB, MySQL, MariaDB, PostgreSQL 和 SQLite。

- [ioredis](https://github.com/luin/ioredis) - 高性能、全功能的 Redis 客户端。

[`Go Top ↑`](#awesome-nodejs-list)

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
  - [AdminBro](https://adminbro.com/) - 应用管理面板，**Koa 官方提供插件支持**。

- [Restify](http://restify.com/) - 可快速构建 RESTful API 的框架。
- [Fastify](https://www.fastify.io/) - 高性能、低消耗的 Web 框架。
- [NestJs](https://nestjs.com/) - 基于 Express / fastify 的渐进式 Web 框架。
- [hapi](https://hapi.dev/) - 注重安全、简洁的 Web 框架。
- [Feathers](https://feathersjs.com/) - 轻量的、面向服务的构建实时 Web 应用和 REST APIs 的框架。
- [Sails.js](https://sailsjs.com/) - 实时的 MVC 框架。
- [Adonis.js](https://adonisjs.com/) - 全栈 MVC 框架。

[`Go Top ↑`](#awesome-nodejs-list)

## 内容管理系统

*Content Management System.*

- [Strapi](https://strapi.io/) - **开源**的无头 CMS。

[`Go Top ↑`](#awesome-nodejs-list)

## 桌面端开发

*Desktop-side application development framework.*

- [Electron](https://electronjs.org/) - 基于 Node.js 与 Chromium 技术的开源跨平台桌面端应用开发解决方案。
- [NW.js](https://nwjs.io/) - 基于 Node.js 与 Chromium 技术的开源跨平台桌面端应用开发解决方案。
- [Neutralino](https://neutralino.js.org/) - 轻量级跨平台桌面端应用开发框架。
- [NodeGui](https://docs.nodegui.org/)

[`Go Top ↑`](#awesome-nodejs-list)

## 文章

*Article.*

- [Introduction to Node.js](https://nodejs.dev/) - Node.js 技术介绍。
- [Write an Open Source JavaScript Library](https://github.com/sarbbottam/write-an-open-source-js-lib) - 如何编写开源 JavaScript 库，并且发布到 npm。
- [Setting up multi-platform npm packages](https://2ality.com/2017/04/setting-up-multi-platform-packages.html) - 多平台支持的 npm 包配置。
- [Deepal's Blog Articles on NodeJS](https://blog.insiderattack.net/node/home) - Deepal 的博客文章，Node.js 相关，比较有深度。
- [Node.js CLI Apps Best Practices](https://github.com/lirantal/nodejs-cli-apps-best-practices) - 开发 Node.js 命令行应用的最佳实践。

[`Go Top ↑`](#awesome-nodejs-list)

## 更多

*More other unclassified resources.*

- [JavaScript Open Source Award](https://osawards.com/javascript/) - JavaScript 开源项目奖，**非官方**。
- [Testing Library](https://testing-library.com/) - 包含了众多测试工具项目。
- [awesome-nodejs-security](https://github.com/lirantal/awesome-nodejs-security) - Node.js 安全相关工具。
- [NodeBB](https://github.com/NodeBB/NodeBB) - 开源论坛软件。
- [AdminBro](https://adminbro.com/) - Node.js 应用管理面板系统。

- JS 引擎/运行时（Javascript Engine/Runtime）
  - [SpiderMonkey](https://developer.mozilla.org/en-US/docs/Mozilla/Projects/SpiderMonkey) - Firefox 浏览器 JS 引擎，**Mozilla 开发**。
  - [QuickJS](https://bellard.org/quickjs/)
  - [JavaScriptCore](http://trac.webkit.org/wiki/JavaScriptCore)

[`Go Top ↑`](#awesome-nodejs-list)
