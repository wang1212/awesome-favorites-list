<div align="center">
  <h1>Awesome-Web-Front-End-List</h1>

  <p>:heart: 收藏列表 - :+1: 很棒的 Web 前端基本技术 JavaScript、CSS、HTML 相关框架、库、工具等。</p>
</div>

<br />

（Recommend）推荐看看 W3C（World Wide Web Consortium，万维网联盟） 官方网站，:point_right: https://www.w3.org/

## 目录

*Resource navigation list.*

- [技术规范标准（Technical Specifications）](#技术规范标准)
- [技术参考文档（Technical Reference Document）](#技术参考文档)
- [构建工具（Build Tools）](#构建工具)
- [HTML](#html)
  - [代码风格规范（Code Style Specifications）](#html-代码风格规范)
  - [工具库（Library）](#html-工具库)
- [CSS](#css)
  - [代码风格规范（Code Style Specifications）](#css-代码风格规范)
  - [在线资源（Online Resources）](#css-在线资源)
  - [工具库（Library）](#css-工具库)
- [JavaScript](#javascript)
  - [代码风格规范（Code Style Specifications）](#js-代码风格规范)
  - [在线资源（Online Resources）](#js-在线资源)
  - [工具库（Library）](#js-工具库)
- [TypeScript](#typescript)
- [字体图标（Font Icon）](#字体图标)
- [UI 设计系统（UI Design System）](#ui-设计系统)
- [UI 组件（UI Component）](#ui-组件)
  - [组件库（Component Library）](#组件库)
  - [独立组件（Independent Components）](#独立组件)
- [UI 模板（UI Template）](#ui-模板)
- [数据可视化（Data Visualization）](#数据可视化)
  - [可视化工具（Visualization Tools）](#可视化工具)
  - [图表（Chart）](#图表)
  - [动画（Animation）](#动画)
- [开发框架（Framework）](#开发框架)
- [应用状态管理（Application State Management）](#应用状态管理)
- [WebAssembly](#webAssembly)
- [更多（More）](#更多)
  - [CDN](#cdn)
  - [在线工具（Online Tools）](#在线工具) 
  - [文章（Article）](#文章)
  - [其它（Others）](#其它)

## 技术规范标准

*Official technical specifications.*

- [W3C](https://www.w3.org/) - 万维网联盟创建于 1994 年，是 Web 技术领域最具权威和影响力的国际中立性技术标准机构。
- [ECMA International](http://www.ecma-international.org/) - ECMA 国际是一家国际性会员制度的信息和电信标准组织，负责行业标准的制定，例如 ECMA Script。
- [ECMAScript Official Specification Standard](https://www.ecma-international.org/publications/standards/Ecma-262.htm) - ECMAScript 官方规范标准。
- [TC39 ECMAScript proposals](https://github.com/tc39/proposals) - TC39 对 ECMAScript 标准制定提案的记录。
- [JSON Specification](http://www.json.org/) - JSON 数据格式规范。
- [JSON Schema](http://json-schema.org/) - JSON 数据校验。
- [JSON5 Specification](https://spec.json5.org/) - JSON5 数据格式规范，是对 JSON 格式的扩展，支持注释等特性。
- [NDJSON Specification](http://ndjson.org/) - Newline Delimited JSON 数据格式规范。

[`Go Top ↑`](#awesome-web-front-end-list)

## 技术参考文档

*Official and unofficial technical reference documents.*

- 标准实现状态（Standard implementation status）
  - [Chrome Blink status](https://www.chromestatus.com/) - Google Chrome 的 Blink 引擎功能特性的官方实现和标准化的开发状态查询列表，**官方网站**。
  - [Firefox status](https://platform-status.mozilla.org/) - Firefox 的 Web 平台功能的官方实现和标准化路线图查询列表，**官方网站**。
  - [Webkit](https://webkit.org/) - Webkit 浏览器引擎的官方网站，可查询其功能特性的实现和标准化状态，**官方网站**。
  - [Can I use](https://caniuse.com/) - 可以查询特定 Web API（H5、CSS3）在各个浏览器平台的实现和标准化状态，**非官方网站**。
  - [compatibility table](https://kangax.github.io/compat-table/) - 可以查询 ECMAScript API 在各平台实现的状态，**非官方网站**。

- [MDN Developer Document](https://developer.mozilla.org/en-US/) - MDN Web Docs 网站提供开放网络（Open Web）技术有关的信息，包括用于网站和渐进式网络应用的 HTML、CSS 和 API，是提供给 Web 开发者最好的学习资料和技术文档，**可作为官方标准参阅学习**。
- [Frontend Developer Roadmap](https://roadmap.sh/frontend) - 前端开发技术路线图。
- [The Front-End Checklist](https://frontendchecklist.io/) - 前端清单，前端知识点及其最佳实践。
- [印记中文](https://docschina.org/) - 包含了许多前端技术库的中文翻译文档。
- [cssdb](https://cssdb.org/) - CSS 新特性列表。
- [CSS Triggers](https://csstriggers.com/) - 一些改变会导致重绘、重布局的 CSS 属性。
  - [What forces layout / reflow](https://gist.github.com/paulirish/5d52fb081b3570c81e3a) - 一些会导致重绘、重布局的 DOM 操作。
- [CSS Reference](https://cssreference.io/) - CSS 视觉指南。

- CSS 类命名规则（CSS class naming rules）
  - [CSS BEM](https://en.bem.info/)
    - [BEM Cheat Sheet](https://9elements.com/bem-cheat-sheet/)
  - [OOCSS](https://github.com/stubbornella/oocss/wiki)
  - [SMACSS](http://smacss.com/)

- 备忘单（Cheatsheet）
  - [SJSJ](http://jargon.js.org/) - JavaScript 术语介绍。
  - [Modern JS Cheatsheet](https://mbeaudru.github.io/modern-js-cheatsheet/) - 现代 JavaScript 概念要点。
  - [ECMAScript 6 — New Features: Overview & Comparison](http://es6-features.org/) - ES6 新特性与旧代码差异对比。
  - [What the f\*ck JavaScript?](https://github.com/denysdovhan/wtfjs) - JavaScript 中有趣且易错的要点。
  - [The Modern JavaScript Tutorial](https://javascript.info/) - 现代 JavaScript 教程。

- [JavaScript Algorithms and Data Structures](https://github.com/trekhleb/javascript-algorithms) - 算法和数据结构。
- [30 seconds](https://github.com/30-seconds) - 30 seconds 是一个系列，包含 JS、React.js、CSS 相关的编程技巧。
- [favorite JavaScript utilities](https://1loc.dev/) - JavaScript 编程技巧，一行代码。
- [JS The Right Way](http://jstherightway.org/) - 一些 JavaScript 最佳实践。
- [33 js concepts](https://github.com/leonardomso/33-js-concepts) - 包含了丰富的 JavaScript 相关的知识概念，学习资源。

[`Go Top ↑`](#awesome-web-front-end-list)

## 构建工具

*Build tool, packaging tool used to develop web app, realize web engineering.*

- [Create App](https://createapp.dev/) - 前端项目构建工具启动配置。

### API 兼容性支持

*API Polyfill.*

- HTML
  - [html5shiv](https://github.com/aFarkas/html5shiv) - 在旧浏览器（IE9 以下）上提供对 HTML5 新标签（例如 footer、nav）的支持。
  
- CSS
  - [Respond](https://github.com/scottjehl/Respond) - 在旧浏览器（IE 6-8）上提供对 CSS3 Media Queries（媒体查询）的支持。
  - [selectivizr](http://selectivizr.com/) - 在旧浏览器（IE 6-8）上提供对 CSS3 新选择器的支持，注意 `style` 标签内样式不解析，动态生成的 DOM 也不解析。

- JavaScript
  - [core-js](https://github.com/zloirock/core-js) - 现代 JavaScript 标准库。
  - [Promise Polyfill](https://github.com/taylorhakes/promise-polyfill) - 为浏览器提供 Promise API 支持。
  - [webp-hero](https://github.com/chase-moskal/webp-hero) - 为浏览器提供 WebP 格式图片支持。
  - [fetch](https://github.github.io/fetch/) - 提供 `window.fetch` API 的兼容性支持。
  - [unfetch](https://github.com/developit/unfetch) - 提供简单的 Fetch API 支持。

### 打包工具

*Packaging tools && Task management.*

- [webpack](https://webpack.js.org/) - 打包工具，适合开发 Web 应用。
  - [awesome-webpack](https://github.com/webpack-contrib/awesome-webpack) - Webpack 相关资源，**官方认证**。
  
- [Gulp](https://gulpjs.com/)
- [Grunt](https://gruntjs.com/)  
  
### 编译器

*Code compilation conversion.*

- [Babel](https://babeljs.io/) - 编译工具，可将 TypeScript、ES6/7/8 代码编译为 JavaScript（ES5） 代码。
- [Sass](https://sass-lang.com/) - CSS 预处理器，可提供类似编程语言的能力（变量、方法、作用域、嵌套）来编写 CSS。
  - [Sass Guidelines](https://sass-guidelin.es/) - Sass 语法风格指南，**非官方**。

- [PostCSS](https://postcss.org/) - CSS 后处理器，提供众多插件来实现还未被广泛实现和标准化的 CSS 功能特性，最终将其编译为目标平台支持的 CSS 代码。
  - [postcss-normalize](https://github.com/csstools/postcss-normalize)    
  
- CSS In JS
  - [JSS](https://cssinjs.org) - 一种 CSS-in-JS 的解决方案。
  - [styled components](https://www.styled-components.com) - 一种 CSS-in-JS 的解决方案。

### PWA

*[Progressive web apps](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps).*

- [WorkBox](https://developers.google.com/web/tools/workbox/) - Google 专门为构建 PWA （Progressive Web App，渐进式 Web 应用）提供的一套开发工具，支持多个平台，并提供了方便的 webpack 插件。
- [What PWA Can Do Today](https://whatpwacando.today/) - 在线测试 PWA 应用可以调用的 Web API。

### 代码静态分析

*Code lint.*

- [ESLint](https://eslint.org/) - JavaScript 语法规则检查工具。
- [Prettier](https://prettier.io/) - 代码格式化工具，支持多种语言。
- [stylelint](https://stylelint.io/) - CSS 语法规则检查工具，支持 CSS/Sass/CSS-in-JS 等。
- [Flow](https://flow.org/) - Facebook 出品的 JavaScript 静态类型检查工具。

### 响应式设计

*Responsive Design.*

- [Responsively](https://responsively.app/) - **开源免费**。
- [Polypane](https://polypane.app/) - 提供免费版本。

### 其它工具

*Others tools.*

- [SystemJS](https://github.com/systemjs/systemjs) - 动态 ES Module 加载器。

[`Go Top ↑`](#awesome-web-front-end-list)

## HTML

> [W3C HTML 官方规范标准（W3C HTML Official Specification Standard）](https://www.w3.org/html/)

### HTML 代码风格规范

*Code Style Specifications.*

- [Google HTML Style Guide](https://google.github.io/styleguide/htmlcssguide.html#HTML)
- [@mdo's Code Guide HTML](https://codeguide.co/#html)

### HTML 工具库

*HTML tool library, dealing with compatibility issues, etc.*

- [HTML Boilerplates](https://htmlboilerplates.com/) - HTML 文件模板。

[`Go Top ↑`](#awesome-web-front-end-list)

## CSS

> [W3C CSS 官方规范标准（W3C CSS Official Specification Standard）](https://www.w3.org/Style/CSS/)

### CSS 代码风格规范

*Code Style Specifications.*

- [Google CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html#CSS)
- [Airbnb CSS / Sass Styleguide](https://github.com/airbnb/css)
- [@mdo's Code Guide CSS](https://codeguide.co/#css)

### CSS 在线资源

*CSS related online tools.*

- [Keyframes](https://keyframes.app/) - CSS 效果预览小工具集合。
- [Animista](https://animista.net/) - 在线生成 CSS 动画样式代码。
- [easings.co](https://easings.co/) - 测试 CSS 动画函数效果。
- [enjoyCSS](https://enjoycss.com/) - 便捷的组件样式设计输出在线工具。
- [Gradient Magic](https://www.gradientmagic.com/) - 渐变设计，CSS 渐变画廊。
- [Glassmorphism CSS Generator](https://glassmorphism.com/) - 毛玻璃效果。

### CSS 工具库

*CSS tool library, dealing with compatibility issues, etc.*

- CSS 重置（CSS Reset）
  - [Normalize.css](http://necolas.github.io/normalize.css/) - 现代化的 Reset CSS 工具库，统一浏览器默认样式。（:warning: 不再更新）
  - [sanitize.css](https://csstools.github.io/sanitize.css/)
  - [ress](https://ress-css.surge.sh/)

- 实用工具（Utils）
  - [Tailwind CSS](https://tailwindcss.com/) - 可定制设计的低级 CSS 框架，不提供组件样式，仅提供预设的工具类，来进行组合创建样式。
    - [Tailwind CSS Cheat Sheet](https://nerdcave.com/tailwind-cheat-sheet)
    - [Tailwind Components](https://tailwindcomponents.com/) - 使用 TailwindCSS 构建的组件，社区支持。
    - [Hypercolor](https://hypercolor.dev/) - 渐变色集合。
  - [Masonry](https://masonry.desandro.com/) - `grid` 布局工具。

- 动画（Animate）
  - [Animate.css](https://daneden.github.io/animate.css/) - 丰富的 CSS 动画工具库。
  - [magic.css](https://www.minimamente.com/project/magic/)  - CSS3 动画。
  - [Hover.css](http://ianlunn.github.io/Hover/) - 添加鼠标悬停动画效果。（:warning: 不再更新）
  - [CSShake](https://elrumordelaluz.github.io/csshake/) - 抖动效果。
  - [Imagehover.css](http://imagehover.io/) - 添加鼠标悬停，图片动画效果。（:warning: 不再更新）
  - [Whirl](https://whirl.netlify.app/) - CSS Loading 动画。
  - [Transition.css](https://transition.style/) - CSS 过渡动画。

[`Go Top ↑`](#awesome-web-front-end-list)

## JavaScript

> [ECMAScript 官方规范标准（ECMAScript Official Specification Standard）](https://www.ecma-international.org/publications/standards/Ecma-262.htm)

*（Recommend）推荐一个其它的收藏库，:point_right: https://github.com/sorrycc/awesome-javascript*

- [TC39 ECMAScript proposals](https://github.com/tc39/proposals) - TC39 对 ECMAScript 标准制定提案的记录。
- [OpenJS Foundation](https://openjsf.org/) - 开源 JS 基金会，由 Node 基金会和 JS 基金会合并而成。

### JS 代码风格规范

*Code Style Specifications.*

- [JavaScript Standard Style](https://standardjs.com/) - 支持 JSX 等语法，社区维护。
- [Airbnb JavaScript Style Guide](https://airbnb.io/javascript/) - 支持 React 技术栈，**Airbnb 公司发布**。
- [Google JavaScript Style Guide](https://google.github.io/styleguide/jsguide.html) - 仅支持原生 JavaScript，**Google 公司发布**。

### JS 在线资源

*JavaScript related online tools.*

- [JSchallenger](https://www.jschallenger.com/) - 在线 JavaScript 编程训练。
- [Javascript.FUN](https://www.javascript.fun/) - 在线网站，JavaScript 开发资源集合。
- [JavaScripting](https://www.javascripting.com/) - JavaScript 库、插件、框架资源。

### JS 工具库

*JavaScript tool libraries (browser-side), such as file manipulation, Canvas drawing, HTTP requests, etc.*

- 文档（Doc）
  - [JSDoc](https://jsdoc.app/) - JavaScript 的 API 文档生成工具。
  - [highlight.js](https://highlightjs.org/) - 页面代码高亮。
  
- 测试（Test）
  - [Mocha](https://mochajs.org/)
  - [JEST](https://jestjs.io/) - Facebook 出品的 JavaScript 单元测试工具。
  - [faker.js](https://github.com/marak/faker.js) - 生成大量随机测试数据，可用来开发过程中进行 API 调试。
  - [Chance](https://chancejs.com/) - 生成随机的测试数据。
  - [Perfume.js](https://zizzamia.github.io/perfume/) - 性能监控工具。
  - [Mirage JS](https://miragejs.com/) - Mock API。
 
- 移动端调试（Mobile debugging）
  - [Eruda](https://eruda.liriliri.io/) - 移动端 Web 调试工具。
  - [vConsole](https://github.com/Tencent/vConsole) - 移动端 Web 调试工具，腾讯（Tencent）出品。
 
- 实用工具（Utils）
  - [Underscore](https://underscorejs.org/) - JavaScript 的工具函数库，提供了大量非常有用的工具函数。
  - [Lodash](https://lodash.com/) - JavaScript 的工具函数库，参考自 Underscore，功能更丰富。
  - [Ramda](https://ramdajs.com/) - JavaScript 的工具函数库，适用于函数式编程。
  - [RxJS](https://rxjs.dev/) - 响应式编程（Reactive Extensions）的 JavaScript 实现，对异步数据集合处理很方便。
  - [clsx](https://github.com/lukeed/clsx) - 非常轻量的 CSS 类名拼接工具。
  - [polished](https://polished.js.org/) - CSS 样式辅助工具。
  - [chroma.js](https://vis4.net/chromajs/) - 颜色字符串解析、计算工具，功能很强大。
  - [color](https://github.com/Qix-/color) - 颜色字符串解析、计算工具，更轻量。
  - [TinyColor](https://github.com/bgrins/TinyColor) - 颜色字符串解析、计算工具，更轻量一些。（:warning: 不再更新）
  - [one.color](https://github.com/One-com/one-color) - 颜色字符串解析、计算工具，支持 RGB, HSV, HSL, CMYK 等。
  - [Fuse.js](https://fusejs.io/) - 模糊搜索工具。
  - [uuid](https://github.com/uuidjs/uuid) - 生成随机唯一 id。
  - [Nano ID](https://zelark.github.io/nano-id-cc/) - 生成唯一、URL 友好、安全的随机字符串。
  - [cuid](https://github.com/ericelliott/cuid) - 生成防碰撞的随机 id。  
  - [normalizr](https://github.com/paularmstrong/normalizr) - 根据 Schema 将嵌套的 JSON 数据归一化。
  - [Quicklink](https://getquick.link/) - 预请求视区内的资源，加快页面加载速度。
 
- 文档对象模型（DOM）
  - [jQuery](https://jquery.com/) - 前几年非常流行的 DOM 操作工具库，处理了兼容性的细节问题。
  - [Zepto.js](https://zeptojs.com/) - 兼容 jQuery API 的轻量级工具库，适合移动端使用。
  - [Lozad.js](https://github.com/ApoorvSaxena/lozad.js) - 轻量、高性能图片懒加载工具，使用了 [Intersection Observer API](https://developer.mozilla.org/en-US/docs/Web/API/Intersection_Observer_API)。
  - [clipboard.js](https://clipboardjs.com/) - 现代的粘贴板工具库。
  - [Tether](http://tether.io/) - 元素跟踪定位工具。
  - [popper.js](https://popper.js.org/) - 元素定位工具。
  - [screenfull.js](https://sindresorhus.com/screenfull.js/) - 跨浏览器的 `Fullscreen API`。
  - [print.js](https://printjs.crabbly.com/) - 网页打印工具。
  - [Smooth Scrollbar](https://idiotwu.github.io/smooth-scrollbar/) - 为元素添加平滑的惯性滚动效果。  
  
- 事件（Event）
  - [Hammer.js](http://hammerjs.github.io/) - 支持移动端触摸事件，以及手势操作、多点触控。
  - [interact.js](https://interactjs.io/) - 同上。
  - [Dragula](https://bevacqua.github.io/dragula/) - 拖放事件处理，可用于列表项的拖放、顺序调整等。
  - [SortableJS](https://sortablejs.github.io/Sortable/) - 列表项拖放调整辅助库，支持 React.js、Vue.js 等。
  - [Mousetrap](https://github.com/ccampbell/mousetrap) - 处理键盘事件。
  - [Hotkeys](https://wangchujiang.com/hotkeys/) - 处理键盘事件。
  - [Hotkey](https://github.com/github/hotkey) - 处理键盘事件。
  - [Selecto.js](https://github.com/daybrush/selecto) - 拖动选择元素，支持鼠标和触摸事件。

- 日期时间（Date && Time）
  - [Moment.js](https://momentjs.com/) - 功能强大的日期、时间处理库。
  - [Luxon](https://moment.github.io/luxon/) - 现代化、api 友好的日期、时间处理库，Moment.js 团队开发。
  - [date-fns](https://date-fns.org/)
  - [Day.js](https://github.com/iamkun/dayjs) - 现代化、轻量级日期、时间处理库。
  - [ms](https://github.com/vercel/ms) - 毫秒格式化工具。

- 绘图（Canvas && Draw）
  - [DOM to Image](https://github.com/tsayen/dom-to-image/) - 利用 HTML5 Canvas 生成 DOM 节点的快照图片。
  - [html2canvas](https://html2canvas.hertzen.com) - 截屏，利用 HTML5 Canvas 生成 DOM 节点的快照图片。
  - [Create.js](https://createjs.com) - 工具套件，包含 Canvas、Web Audio 等工具库。
  - [Konva](https://konvajs.org) - 用于桌面和移动应用程序的 HTML5 2D canvas 库。
  - [Two.js](https://two.js.org/) - Web 二维绘图工具库，基于 Canvas、Svg、WebGL。
  - [Paper.js](http://paperjs.org/) - 矢量绘图工具。
  - [Fabric.js](http://fabricjs.com/) - 矢量绘图工具。
  - [Pencil.js](https://pencil.js.org/) - 2D 绘图库。

- 二维码（QR Code）
  - [node-qrcode](https://github.com/soldair/node-qrcode) - 二维码生成。
  - [Awesome-qr.js](https://www.bitcat.cc/webapp/awesome-qr/index.html) - 个性化二维码生成。（:warning: 不再更新）

- 文件（File）
  - utils
    - [FileSaver.js](https://github.com/eligrey/FileSaver.js/) - Web 浏览器客户端文件保存 api 实现。
    - [StreamSaver.js](https://github.com/jimmywarting/StreamSaver.js) - Web 浏览器客户端异步保存文件 api 实现，解决了 FileSaver 的大小限制问题。
  - html/xml
    - [parse-xml](https://github.com/rgrove/parse-xml) - XML 解析器。
  - json5
    - [JSON5](https://json5.org/) - JSON5 格式数据解析、序列化。
  - zip
    - [JSZip](https://github.com/Stuk/jszip) - 创建/读写 zip 文件。
  - xlsx
    - [exceljs](https://github.com/exceljs/exceljs) - 读、写 xlsx、csv 文件。  
    - [xlsx](https://sheetjs.com/) - 读、写 xlsx、csv 文件（写功能部分特性不免费）。
  - csv
    - [Papa Parse](https://www.papaparse.com/)
  - docx
    - [docx](https://github.com/dolanmiu/docx) - 生成 docx 文档。
  - pdf
    - [PDF-LIB](https://pdf-lib.js.org/) - 解析和操作 PDF 文件。
    - [jsPDF](https://github.com/MrRio/jsPDF) - Web 客户端生成 PDF 文件。
    - [PDFKit](http://pdfkit.org/) - 生成 PDF 文件。
  - image
    - [Pica](http://nodeca.github.io/pica/demo/) - 图片质量调整。
    - [merge-images](https://github.com/lukechilds/merge-images) - 图片拼接合并。
    - [blurify](https://github.com/JustClear/blurify) - 图片模糊化。
    - [Compressor.js](https://fengyuanchen.github.io/compressorjs/) - 图片压缩。
    - [Lena.js](https://fellipe.com/demos/lena-js/) - 图片滤镜。
  - audio
    - [howler.js](https://howlerjs.com/) - 强大的音频处理工具库，支持所有的编解码器，跨浏览器支持。
  - markdown
    - [Marked](https://marked.js.org/) - markdown 文件解析，转换成 HTML 文件。
  - svg
    - [Trianglify](https://github.com/qrohlf/trianglify) - 通过算法生成三角网 SCG 背景图。(:point_right: https://trianglify.io/)

- HTTP 请求（HTTP - Ajax / Promise / fetch）
  - [axios](https://github.com/axios/axios) - 基于 Promise 的 HTTP 客户端工具库。
    - [axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter) - Mock API。

- 套接字（Socket / TCP）
  - [socket.io-client](https://socket.io/) - 优秀的实时通信客户端框架。

- 科学计算（Compute - Math && High precision && Scientific Computing）
  - [math.js](https://mathjs.org/)
  - [stdlib](https://stdlib.io/)
  - [glMatrix](http://glmatrix.net/) - 矩阵和矢量运算。

- 数据与缓存（Data && Cache）
  - [crypto-js](https://github.com/brix/crypto-js) - JavaScript 加密库。
  - [https://github.com/digitalbazaar/forge](https://www.npmjs.com/package/node-forge) - JavaScript 加密库。
  - [md5.js](https://github.com/crypto-browserify/md5.js) - md5 哈希库。（:warning: 不再更新）
  - [md5](https://github.com/pvorb/node-md5) - md5 哈希库。
  - [object-hash](https://github.com/puleos/object-hash) - 对 JavaScript 对象进行 hash 处理。
  - [crypto-browserify](https://github.com/crypto-browserify/crypto-browserify) - Node 中 `crypto` 模块在浏览器中的实现。（:warning: 不再更新）
  - [SJCL](http://bitwiseshiftleft.github.io/sjcl/) - JavaScript 加密库。（:warning: 不再更新）

- 多线程（Web Worker）
  - [Comlink](https://github.com/GoogleChromeLabs/comlink) - 使 `Web Worker` 的使用更加简单、方便，**Chrome 实验室发布**。

- 客户端数据库（Client Database）
  - [localForage](https://github.com/localForage/localForage) - 离线存储，对 IndexedDB、WebSQL、localStorage 的封装。
  - [SQL.js](https://sql.js.org/)
  - [LokiJS](https://github.com/techfort/LokiJS) - 文档型内存数据库。

- OCR
  - ['tesseract.js](https://github.com/naptha/tesseract.js) - 支持 100 种语言的图像文本识别。

- 自然语言处理（NLP）
  - [compromise](http://compromise.cool/)

[`Go Top ↑`](#awesome-web-front-end-list)

## TypeScript

> [TypeScript 官网](https://www.typescriptlang.org/) - JavaScript 超集，强类型语言。

- [TypeScript Performance Tips](https://github.com/microsoft/TypeScript/wiki/Performance) - TypeScript 性能优化，**官方**。
- [typescript-cheatsheet](https://rmolinamir.github.io/typescript-cheatsheet/) - TypeScript 备忘单。
- [TypeScriptToLua](https://typescripttolua.github.io/) - 用 TypeScript 编写 Lua。

[`Go Top ↑`](#awesome-web-front-end-list)

## 字体图标

*Font icon, vector icon.*

### 字体

*Font.*
  
### 图标

*Icon.*

- [Glyphs](https://glyphs.fyi/) - **开源**图标库。
- [Bootstrap Icons](https://icons.getbootstrap.com/) - **开源**图标库，仅支持 SVG，**Twitter 公司发布**。
- [Feather](https://feathericons.com/) - 简单漂亮的**开源**图标库，仅支持 SVG。
- [Remix Icon](https://remixicon.com/) - 中性风格的**开源**图标库，支持 SVG 与 Web font。
- [IonIcons](https://ionicons.com) - 精美的**开源**图标库，支持 SVG 与 Web font，**ionic 团队制作**。
- [Material Icons](https://material.io/tools/icons/) - Material Design 风格的**开源**图标库，支持 SVG 与 Web font，**Google 官方发布**。
- [Material Design Icons](http://materialdesignicons.com/) - Material Design 风格的**开源**图标库，支持 SVG 与 Web font**非官方，社区支持**。
- [Octicons](https://octicons.github.com/) - GitHub **开源**图标库，**GitHub 官方发布**。
- [Teenyicons](https://teenyicons.com/) - **开源**图标库，仅支持 SVG。
- [Forge Icons](https://icons.theforgesmith.com/) - **免费**图标库，仅支持 SVG。
- [Simple Icons](https://simpleicons.org/) - **免费**的品牌 logo 图标，仅支持 SVG。
- [Fabric Icons](https://developer.microsoft.com/en-us/fabric#/styles/web/icons) - 图标库，仅支持 Web font，**Microsoft 官方发布**。
- [Spectrum Icons](https://spectrum.adobe.com/page/icons/) - Adobe Spectrum 设计系统图标，**Adobe 官方发布**。
- [Font Awesome](https://fontawesome.com/) - 丰富的图标库，提供**免费版**。
- [IconPark](https://iconpark.bytedance.com/official) - **开源免费**的图标库，**字节跳动公司发布**。

[`Go Top ↑`](#awesome-web-front-end-list)

## UI 设计系统

*Some open source, shared UI design kits.*

- [Primer](https://primer.style/) - GitHub 设计，包含组件库、图标等资源，**GitHub 官方发布**。
- [Material Design](https://material.io/) - Material 设计，包含组件库、图标等资源，**Google 公司发布**。
- [Fluent UI](https://developer.microsoft.com/en-us/fluentui) - Fluent UI，包含组件库、图标等资源，**Microsoft 公司发布**。
- [Carbon](https://www.carbondesignsystem.com/) - Carbon 设计，包含组件库、图标、数据可视化工具等资源，**IBM 公司发布**。
- [Spectrum](https://spectrum.adobe.com/) - Spectrum 设计，包含组件库、图标、字体等资源，**Adobe 公司发布**。
- [Ant Design](https://ant.design/) - Ant 设计，包含组件库、图标、数据可视化工具等资源，**阿里巴巴公司发布**。
- [TOAST UI](https://ui.toast.com/) - 包含日历、编辑器、网格组件，以及图表库，**NHN 公司发布**。

[`Go Top ↑`](#awesome-web-front-end-list)

## UI 组件

*UI Component*

[Bit](https://bit.dev/)，共享组件发布平台。

### 组件库

*UI component library, providing a set of components with consistent design style.*

#### Bootstrap

- [Bootstrap](https://getbootstrap.com/) - 最流行的 CSS UI 框架，**Twitter 公司发布**。
- [Bootswatch](https://bootswatch.com/) - 开源免费的 Bootstrap 主题集合，**非官方**。

#### Material Design

- [Material Design Lite](https://getmdl.io/) - 基于 Material Design 的轻量级 CSS UI 框架，**Google 官方发布**。（:warning: 不再更新）
- [Material Components Web](https://material.io/develop/) - 基于 Material Design 的 Web 组件库，**Google 官方实现**。
- [Materialize](https://materializecss.com/) - 最流行的实现了 Google Material Design 的 CSS UI 框架。

#### 其它（Others）

- [UIkit](https://getuikit.com/) - 轻量级的现代化前端模块化 CSS 框架。
- [Framework7](https://framework7.io/) - 跨平台 UI 库，支持 Android/ios/Desktop 平台，且主题样式设计适配相应平台。
- [Metro 4](https://metroui.org.ua/)
- [Bulma](https://bulma.io/)
- [Office UI Fabric Core](https://developer.microsoft.com/en-us/fabric) - Office 风格的 UI 库，**Microsoft 公司发布**。
- [carbon-components](https://www.carbondesignsystem.com/get-started/develop/vanilla) - Carbon 设计风格，**IBM 公司发布**。
- [Spectrum CSS](https://opensource.adobe.com/spectrum-css/) - Spectrum 设计，**Adobe 公司发布**。
- [Pure.CSS](https://purecss.io/) - 一组小的，响应式的 CSS 模块。
- [Layui](https://www.layui.com/) - 适合后端开发使用。
- [Semantic UI](https://semantic-ui.com) - 很受欢迎的组件库。（:warning: 不再更新）
- [Skeleton](http://getskeleton.com/) - 简单的响应式 CSS 框架。（:warning: 不再更新）

### 独立组件

*Independent UI components, only providing component modules that implement an interactive function.*

- 表单组件（Form）
  - [Cleave.js](https://nosir.github.io/cleave.js/) - 格式化输入框。
  - [flatpickr](https://flatpickr.js.org/) - 时间日期选择器。
  - [layDate](https://www.layui.com/laydate/) - 时间日期选择器。

- 轮播（Carousel）
  - [Swiper](https://swiperjs.com/)
  - [slick-carousel](https://kenwheeler.github.io/slick/)
  - [Glider.js](https://nickpiscitelli.github.io/Glider.js/)
  - [Flickity](https://flickity.metafizzy.co/)
  - [lory.js](http://loryjs.github.io/lory/)
  - [keen-slider](https://keen-slider.io/)
  - [Siema](https://pawelgrzybek.github.io/siema/) - 无任何依赖的轻量轮播组件。
 
- Lightbox
  - [GLightbox](https://github.com/biati-digital/glightbox)
 
- 模态框（Modal box）
  - [SweetAlert](https://sweetalert.js.org/) - 浏览器 Alert 弹框的替代，更漂亮美观。（:warning: 不再更新）
  - [SweetAlert2](https://sweetalert2.github.io/) - SweetAlert 的继承者。
  - [Noty](https://ned.im/noty/) - 浏览器 Alert 弹框的替代，提供动画效果。（:warning: 不再更新）
  
- 图片浏览（Image Browse）
  - [Viewer.js](https://fengyuanchen.github.io/viewerjs/) - 图片列表预览。
  - [Image Compare Viewer](https://image-compare-viewer.netlify.app/) - 图片对比预览。
  - [Cropper.js](https://fengyuanchen.github.io/cropperjs/) - 图片裁剪。
  - [Medium Zoom](https://medium-zoom.francoischalifour.com/) - 图片缩放预览。

- 表格（Table）
  - [Grid.js](https://gridjs.io/) - 高级表格插件。
  - [Frappe Datatable](https://frappe.io/datatable)
  - [RevoGrid](https://revolist.github.io/revogrid/)

- H5 媒体（Audio & Video）
  - [hls.js](https://github.com/video-dev/hls.js) - `HLS` 协议支持。
  - [video.js](https://videojs.com/) - 兼容大部分视频格式的视频播放器。
  - [MediaElement.js](http://www.mediaelementjs.com/) - 非常漂亮的视、音频播放器。
  - [Plyr](https://plyr.io/) - 很棒的视、音频播放器。
  - [clappr](http://clappr.io/) - 视频播放器。
  - [APlayer](https://aplayer.js.org/) - 非常漂亮的音乐播放器。
  - [DPlayer](http://dplayer.js.org/) - 视频播放器。
  - [Vime](https://vimejs.com/) - 视频播放器。
  - [Artplayer](https://artplayer.org/) - 全功能 H5 播放器。

- 文件上传（File Upload）
  - [FilePond ](https://pqina.nl/filepond/) - 文件上传。
  - [DropzoneJS](https://www.dropzonejs.com/) - 文件上传组件，支持拖放文件、图片预览功能。

- 拖拽布局（Drag Layout）
  - [Muuri](https://muuri.dev/)
  - [Packery](https://packery.metafizzy.co/) 
  - [gridstack.js](https://gridstackjs.com/)
  - [DragSelect](https://dragselect.com/) - 拖拽选择。
  
- 用户引导（User guided tours）
  - [intro.js](https://introjs.com/)
  - [Driver.js](https://kamranahmed.info/driver.js/)
  - [Shepherd](https://shepherdjs.dev/)
   
- 其它（Others）
  - [PACE](https://codebyzach.github.io/pace/) - 页面加载指示器。
  - [TOAST UI Calendar](https://github.com/nhn/tui.calendar) - 强大的日历日程组件。
  - [FullCalendar](https://fullcalendar.io/) - 日历日程组件。
  - [reveal.js](https://revealjs.com/) - 创建漂亮的演示文稿（幻灯片）。
  - [TOAST UI Editor](https://ui.toast.com/tui-editor/) - 所见即所得编辑器。
  - [fullPage](https://alvarotrigo.com/fullPage/) - 全屏滚动页面。
  - [mailgo](https://mailgo.dev/) - 邮件和电话系统行为。
  - [PulltoRefresh](https://www.boxfactura.com/pulltorefresh.js/) - 下拉刷新。
  - [Tweakpane](https://cocopon.github.io/tweakpane/) - 可快速创建跟踪值变化和调节的控制面板。
  - [Holder.js](http://holderjs.com/) - 图像占位符。
  - [List.js](https://listjs.com/) - 为列表提供过滤、排序等功能。
  - [simple-drawing-board.js](https://github.com/leader22/simple-drawing-board.js) - 简单画板。
  - [simple-keyboard](https://virtual-keyboard.js.org/) - 虚拟键盘。
  - [Tippy.js](https://atomiks.github.io/tippyjs/) - 工具提示组件。

[`Go Top ↑`](#awesome-web-front-end-list)

## UI 模板

*UI template.*

- [tabler](https://tabler.io/) - **开源免费**的可视化管理页面模板。

[`Go Top ↑`](#awesome-web-front-end-list)

## 数据可视化

*Data visualization libraries, such as chart libraries, 3D engines, etc.*

### 可视化工具

*Data visualization tool library.*

- [D3](https://d3js.org/) - 可视化库，数据驱动的，非常著名，许多图表库基于此开发。
- [three.js](https://threejs.org/) - 3D 动画库，强大的 JavaScript 3D 动画库。
- [stackgl](http://stack.gl/) - WebGL 引擎。
- [PixiJS](https://www.pixijs.com/) - 2D WebGL 渲染引擎，高性能。
- [Textures.js](https://riccardoscalco.it/textures/) - 创建 SVG 模式。
- [ztext.js](https://bennettfeely.com/ztext/) - 实现文字 3D 效果。
- [FilterizR](https://yiotis.net/filterizr/) - 过滤搜索动画。
- [mermaid](https://github.com/mermaid-js/mermaid) - txt 文本生成流程图。

### 图表

*Chart library, such as line chart, column chart, etc.*

- [Chart.js](https://www.chartjs.org/) - 最流行的轻量级库。
- [Frappe Charts](https://frappe.io/charts) - 基于 SVG 的高性能库。
- [Frappe Gantt](https://frappe.io/gantt) - 甘特图。
- [Echarts](http://echarts.apache.org/) - 国内百度团队开发，功能丰富。
- [C3](https://c3js.org/) - 基于 D3.js 的可重用图表库。
- [carbon-charts](https://carbon-design-system.github.io/carbon-charts/) - 遵循 Carbon 风格，**IBM 公司发布**。
- [Plotly](https://plotly.com/javascript/) - 丰富的图表，支持金融、科学相关图表。
- [Apexcharts](https://apexcharts.com/) - 图表库。
- [sigma.js](http://sigmajs.org/) - 图形网络库。
- [Cytoscape.js](https://js.cytoscape.org/) - 用于可视化和分析的图论（网络）库。
- [uPlot](https://github.com/leeoniya/uPlot) - 快速、轻量级的图标库。
- [Charts.css](https://chartscss.org/) - CSS 图表库。

### 动画

*Animation library, such as linear animation, inertial animation, etc.*

- [Anime.js](https://animejs.com/) - 动画引擎，轻量的 JavaScript 动画工具库。
- [Velocity.js](http://velocityjs.org/) - 动画引擎，为元素提供动画效果。
- [mo.js](https://mojs.github.io/) - 丰富，强大的运动图形动画工具库。
- [KUTE.js](https://thednp.github.io/kute.js/) - 高性能动画引擎。
- [Popmotion](https://popmotion.io/) - 实用、灵活的 JavaScript 动画工具套件。
- [tween.js](https://createjs.com/tweenjs) - 动画工具库。
- [ScrollReveal](https://scrollrevealjs.org/) - 为滚动进入视区的元素提供动画效果。
- [lax.js](https://github.com/alexfoxy/laxxx) - 简单、轻量的工具库，创建平滑的滚动动画。
- [vivus.js](https://github.com/maxwellito/vivus) - 为 SVG 提供动画效果。
- [SVG.js](https://svgjs.com/) - 轻量级 SVG 动画库。
- [Typed.js](https://github.com/mattboldt/typed.js) - 为输入框输入提供动画效果。
- [Rough Notation](https://roughnotation.com/) - 为元素提供注释效果和动画。
- [Rellax](https://dixonandmoe.com/rellax/) - 元素滚动视差效果工具库。
- [Framer Motion](https://www.framer.com/motion/) - 动画工具库。
- [GSAP](https://greensock.com/) - 现代化的高性能动画工具库。
- [Shifty](https://jeremyckahn.github.io/shifty/doc/index.html) - 轻量级、高性能的低级动画工具库。
- [ts Particles](https://particles.matteobruni.it/) - 简单的粒子动画。
- [particles.js](https://vincentgarreau.com/particles.js/) - 轻量的粒子动画库。
- [CountUp.js](https://inorganik.github.io/countUp.js/) - 数字文本动画。
- [granim.js](https://sarcadass.github.io/granim.js/index.html) - 创建交互式渐变动画。
- [dom-confetti](https://github.com/daniel-lundin/dom-confetti) - 五彩纸屑动画。
- [Canvas Confetti](https://www.kirilv.com/canvas-confetti/) - 五彩纸屑动画。
- [Vanta.js](https://www.vantajs.com/) - 数款页面 WebGL 背景动画。

[`Go Top ↑`](#awesome-web-front-end-list)

## 开发框架

*Web front-end development framework (library).*

- [React.js](https://reactjs.org/) -  前端响应式 UI 库，其技术生态圈非常繁荣，Facebook 公司发布。
  - [Awesome-React.js](./awesome-reactjs.md) - React.js 生态技术汇总。
  
- [Vue.js](https://vuejs.org/)

- [Angular.js](https://angularjs.org/) - 一个比较重型的功能齐全的前端开发框架，Google 公司发布。

- [Svelte](https://svelte.dev/) - 更轻量的前端 UI 库。
  - [Sapper](https://sapper.svelte.dev/) - 基于 Svelte 的 Web App 开发框架。

- [Inferno](https://infernojs.org/) - 类 React API 的 UI 库。
- [Hyperapp](https://hyperapp.dev/) - 轻量的，纯函数式，声明式开发框架。
- [Marko](https://markojs.com/) - 声明式、响应式开发框架。
- [Snabbdom](https://github.com/snabbdom/snabbdom) - 基于虚拟 DOM 机制，模块化、高性能开发框架。
- [mithril.js](https://mithril.js.org/)
- [Ember.js](https://emberjs.com/)

- [Riot.js](https://riot.js.org/) - 基于组件的 UI 库。
- [LitElement](https://lit-element.polymer-project.org/) - 用于创建 [Web 组件](https://developer.mozilla.org/en-US/docs/Web/Web_Components) 的基类工具库。
- [Hybrids](https://hybrids.js.org/) - 用于创建 Web 组件的 UI 库。

[`Go Top ↑`](#awesome-web-front-end-list)

## 应用状态管理

*Application state management tool for modern web application development.*

（Recommend）Redux 生态技术，:point_right: https://github.com/markerikson/redux-ecosystem-links

- [Redux](https://redux.js.org/)
  - [Redux Thunk](https://github.com/reduxjs/redux-thunk) - 中间件，提供异步支持，**官方发布**。
  - [Redux-Saga](https://redux-saga.js.org/) - 提供异步支持，比 Redux Thunk 功能更丰富，易于测试。
  - [Reselect](https://github.com/reduxjs/reselect) - 状态缓存，提高性能，**官方发布**。
  - [Redux-Persist](https://github.com/rt2zz/redux-persist) - 状态持久化。
  - [Redux Logger](https://github.com/LogRocket/redux-logger) - 中间件，调试工具，追踪状态变更日志。
  - [Redux DevTools](https://github.com/reduxjs/redux-devtools) - Chrome 插件，调试工具，追踪状态变更日志，重放、快照等功能。
  - [Redux Toolkit](https://redux-toolkit.js.org/) - 集成大部分第三方库、预配置的工具套件，使 Redux 更易于使用，**官方发布**。
  - [Rematch](https://rematch.github.io/rematch/) - 对 Redux 进行了封装，提供更简单、更易理解、更容易使用的 API。

- [MobX](https://mobx.js.org/)

- [Flux](https://facebook.github.io/flux/) - 应用状态管理，**Facebook 公司发布**。

- [Immutable.js](https://immutable-js.github.io/immutable-js/) - 不可变数据。（:warning: 不再更新）
- [Immer](https://immerjs.github.io/immer/) - 不可变数据。

[`Go Top ↑`](#awesome-web-front-end-list)

## WebAssembly

- [WebAssembly](https://webassembly.org/) - 新型字节码格式，可将其它语言编译后在 Web 浏览器中运行，**官方网站**。
- [WASI](https://wasi.dev/) - WebAssembly 系统接口标准，致力于在浏览器之外的环境中运行 WebAssembly。

- 工具链（Tools）
  - [Emscripten](https://emscripten.org/) - 用于编译为使用 LLVM 构建的 asm.js 和 WebAssembly 的工具链，可在 Web 浏览器中运行 C/C++ 代码。
  - [Cheerp](https://www.leaningtech.com/cheerp/) - 与 Emscripten 类似。
  - [AssemblyScript](https://www.assemblyscript.org/) - 类似 TypeScript 的可编译为 WASM 的语言。
  - [Perspective](https://github.com/finos/perspective) - 基于 C++ 的 wasm 数据可视化组件。

- 运行时（Runtime）
  - [Wasmer](https://wasmer.io/) - 轻量的 WebAssembly 运行时，支持 WASI 和 Emscripten。
  - [Wasmtime](https://wasmtime.dev/) - WebAssembly 与 WASI 运行时。
  - [Lucet](https://github.com/bytecodealliance/lucet) - 本机 WebAssembly 编译器和运行时。
  - [Lunatic](https://lunatic.solutions/) - WebAssembly 运行时。

[`Go Top ↑`](#awesome-web-front-end-list)

## 更多

*More useful related resources.*

### CDN

*Content distribution network, static resource hosting.*

- Global
  - [jsDelivr](https://www.jsdelivr.com/)
  - [UNPKG](https://unpkg.com/)
  - [cdnjs](https://cdnjs.com/)
  - [Google Hosted Libraries](https://developers.google.com/speed/libraries/)
  
- China
  - [BootCDN](https://www.bootcdn.cn/) - Bootstrap 中文网维护。
  - [75CDN](https://cdn.baomitu.com) - 奇虎 360 前端团队奇舞团维护。
  - [Staticfile CDN](https://staticfile.org/) - 七牛云与掘金维护。
  - [loli.net](https://css.loli.net/)

### 在线工具

*Some online resources, such as CDN, image compression tools, online IDE, etc.*

- Web 安全（Web Security）
  - [SRI Hash Generator](https://www.srihash.org/) - [SRI](https://www.w3.org/TR/SRI/) 的 hash 生成。

- Web 优化（Web Optimization）
  - [web.dev](https://web.dev/)
  - [Varvy SEO tool](https://varvy.com/) - 一个在线网站 SEO、性能检测工具，提供优化建议和技巧。
  - [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/) - Google 提供的在线网站性能检测工具，提供优化建议和技巧，**Google 官方提供**。
  - [Lighthouse](https://developers.google.com/web/tools/lighthouse/) - Google 提供的一个网站优化检测分析工具，已被集成在 Chrome 开发工具中，也可以作为 Chrome 扩展或者命令行工具使用，**Google 官方提供**。
  - [What Web Can Do](https://whatwebcando.today/) - 可以检测当前设备所支持的 Web API，主要检测硬件设备传感器等，**非官方网站**。
  
- 在线 IDE、编辑器（IDE / Editor）
  - [StackBlitz](https://stackblitz.com/)
  - [JSFiddle](https://jsfiddle.net/)
  - [CodeSandbox](https://codesandbox.io/)
  - [CodePen](https://codepen.io/)
  - [JSitor](https://jsitor.com/)
  - [WebAssembly Studio](https://webassembly.studio/) - 在线的 WebAssembly 编辑器，**Mozilla 发布**。
  
- 其它（Others）
  - [bit](https://bit.dev/) - 构建可重用组件的协作平台。
  - [Prettier Playground](https://prettier.io/playground/) - Prettier 代码格式化工具的在线版本。
  - [PWA Inside](https://pwainside.com/) - PWA 应用资源和商店。

### 文章

*Some technical discussion articles.*

- [You might not need jQuery](http://youmightnotneedjquery.com/)
- [The complete guide to CSS media queries](https://polypane.app/blog/the-complete-guide-to-css-media-queries/)
- [What does 100% mean in CSS](https://wattenberger.com/blog/css-percents) - CSS 中 `100%` 的含义。
- [JavaScript for Data Science](https://js4ds.org/)
- [Add a web app manifest](https://web.dev/add-manifest/) - PWA 应用 `manifest.webmanifest` 文件中建议的字段。

### 其它

*Other unclassified resources.*

- [JavaScript Open Source Award](https://osawards.com/javascript/) - JavaScript 开源项目奖，**非官方**。

[`Go Top ↑`](#awesome-web-front-end-list)
