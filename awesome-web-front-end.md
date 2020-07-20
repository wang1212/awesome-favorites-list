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
- [HTML](#html)
  - [工具库（Library）](#html-工具库)
- [CSS](#css)
  - [工具库（Library）](#css-工具库)
  - [字体图标（Font Icon）](#字体图标)
- [JavaScript](#javascript)
  - [代码风格规范（Code Style Specifications）](#代码风格规范)
  - [工具库（Library）](#js-工具库)
- [UI 组件（UI Component）](#ui-组件)
  - [组件库（Component Library）](#组件库)
  - [独立组件（Independent Components）](#独立组件)
- [数据可视化（Data Visualization）](#数据可视化)
- [开发框架（Framework）](#开发框架)
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
- [WebAssembly](https://webassembly.org/) - WebAssembly 官方网站，可在浏览器中运行 C/C++ 代码。
- [Chrome Blink status](https://www.chromestatus.com/) - Google Chrome 的 Blink 引擎功能特性的官方实现和标准化的开发状态查询列表。
- [Firefox status](https://platform-status.mozilla.org/) - Firefox 的 Web 平台功能的官方实现和标准化路线图查询列表。
- [Webkit](https://webkit.org/) - Webkit 浏览器引擎的官方网站，可查询其功能特性的实现和标准化状态。
- [JSON Specification](http://www.json.org/) - JSON 数据格式规范。
- [JSON Schema](http://json-schema.org/) - JSON 数据校验。
- [JSON5 Specification](https://spec.json5.org/) - JSON5 数据格式规范，是对 JSON 格式的扩展，支持注释等特性。
- [NDJSON Specification](http://ndjson.org/) - Newline Delimited JSON 数据格式规范。
- [TypeScript](http://www.typescriptlang.org/) - JavaScript 的超集，强类型语言。

[`Go Top ↑`](#awesome-web-front-end-list)

## 技术参考文档

*Official and unofficial technical reference documents.*

- [MDN Developer Document](https://developer.mozilla.org/en-US/) - MDN Web Docs 网站提供开放网络（Open Web）技术有关的信息，包括用于网站和渐进式网络应用的 HTML、CSS 和 API，是提供给 Web 开发者最好的学习资料和技术文档，**可作为官方标准参阅学习**。
- [Can I use](https://caniuse.com/) - 可以查询特定 Web API（H5、CSS3）在各个浏览器平台的实现和标准化状态，**非官方网站**。
- [cssdb](https://cssdb.org/) - CSS 新特性列表。
- [CSS BEM](https://en.bem.info/) - CSS 类名的 BEM 命名风格和规则。
  - [BEM Cheat Sheet](https://9elements.com/bem-cheat-sheet/)
- [30 seconds](https://github.com/30-seconds) - 30 seconds 是一个系列，包含 JS、React.js、CSS 相关的编程技巧。
- [JS The Right Way](http://jstherightway.org/) - 一些 JavaScript 最佳实践。
- [SJSJ](https://github.com/HugoGiraudel/SJSJ) - JavaScript 术语介绍。
- [33 js concepts](https://github.com/leonardomso/33-js-concepts) - 包含了丰富的 JavaScript 相关的知识概念，学习资源。
- [印记中文](https://docschina.org/) - 包含了许多前端技术库的中文翻译文档。
- [jQuery API 中文文档](http://jquery.cuishifeng.cn/) - 一个国内开发者维护的 jQuery API 中文文档，非常实用。
- [favorite JavaScript utilities](https://1loc.dev/) - JavaScript 编程技巧，一行代码。
- [CSS Triggers](https://csstriggers.com/) - 一些改变会导致重绘、重布局的 CSS 属性。
- [JavaScript Algorithms and Data Structures](https://github.com/trekhleb/javascript-algorithms) - 算法和数据结构。

[`Go Top ↑`](#awesome-web-front-end-list)

## HTML

> [W3C HTML 官方规范标准（W3C HTML Official Specification Standard）](https://www.w3.org/html/)

### HTML 工具库

*HTML tool library, dealing with compatibility issues, etc.*

- [html5shiv](https://github.com/aFarkas/html5shiv) - 在旧浏览器（IE9 以下）上提供对 HTML5 新标签（例如 footer、nav）的支持。

[`Go Top ↑`](#awesome-web-front-end-list)

## CSS

> [W3C CSS 官方规范标准（W3C CSS Official Specification Standard）](https://www.w3.org/Style/CSS/)

### CSS 工具库

*CSS tool library, dealing with compatibility issues, etc.*

- 兼容性（Polyfill）
  - [Respond](https://github.com/scottjehl/Respond) - 在旧浏览器（IE 6-8）上提供对 CSS3 Media Queries（媒体查询）的支持。
  - [selectivizr](http://selectivizr.com/) - 在旧浏览器（IE 6-8）上提供对 CSS3 新选择器的支持，注意 `style` 标签内样式不解析，动态生成的 DOM 也不解析。

- CSS 重置（CSS Reset）
  - [Normalize.css](http://necolas.github.io/normalize.css/) - 现代化的 Reset CSS 工具库，统一浏览器默认样式。
  - [sanitize.css](https://csstools.github.io/sanitize.css/)

- 动画（Animate）
  - [Animate.css](https://daneden.github.io/animate.css/) - 丰富的 CSS 动画工具库。
  - [Hover.css](http://ianlunn.github.io/Hover/) - 添加鼠标悬停动画效果。
  - [Imagehover.css](http://imagehover.io/) - 添加鼠标悬停动画效果。
  
- CSS In JS
  - [JSS](https://cssinjs.org) - 一种 CSS-in-JS 的解决方案。
  - [styled components](https://www.styled-components.com) - 一种 CSS-in-JS 的解决方案。

- 实用工具（Utils）
  - [Tailwind CSS](https://tailwindcss.com/) - 可定制设计的低级 CSS 框架，不提供组件样式，仅提供预设的工具类，来进行组合创建样式。
    - [Tailwind CSS Cheat Sheet](https://nerdcave.com/tailwind-cheat-sheet)
    
### 字体图标

*Font icon, vector icon.*

- 字体（Font）
  
- 图标（Icon）
  - [Bootstrap Icons](https://icons.getbootstrap.com/) - SVG 图标库，**Bootstrap 官方发布**。
  - [Font Awesome](https://fontawesome.com/) - 提供了非常多的免费图标的库，使用率非常高。
  - [Material Icons](https://material.io/tools/icons/) - Material Design 风格的图标库，**Google 官方发布**。
  - [Material Design Icons](http://materialdesignicons.com/) - 遵循 Google Material Design 的图标库，**非官方**。
  - [material design palette](https://www.materialpalette.com/) - Google Material Design 设计工具，提供官方图标（Material Icons）下载，**非官方**。
  - [Fabric Icons](https://developer.microsoft.com/en-us/fabric#/styles/web/icons) - 微软官方提供的一套图标库，**Microsoft 官方发布**。
  - [IonIcons](https://ionicons.com) - ionic 框架团队制作的图标库。
  - [Octicons](https://octicons.github.com/) - GitHub 官方制作的图标库，**GitHub 官方发布**。
  - [Feather](https://feathericons.com/)
  - [Flat Icon](https://www.flaticon.com/)
  - [Icons8](https://icons8.com/) - 提供免费的图标设计工具。

[`Go Top ↑`](#awesome-web-front-end-list)

## JavaScript

> [ECMAScript 官方规范标准（ECMAScript Official Specification Standard）](https://www.ecma-international.org/publications/standards/Ecma-262.htm)

*（Recommend）推荐一个其它的收藏库，:point_right: https://github.com/sorrycc/awesome-javascript*

- [TC39 ECMAScript proposals](https://github.com/tc39/proposals) - TC39 对 ECMAScript 标准制定提案的记录。
- [OpenJS Foundation](https://openjsf.org/) - 开源 JS 基金会，由 Node 基金会和 JS 基金会合并而成。

### 代码风格规范

*Code Style Specifications.*

- [JavaScript Standard Style](https://standardjs.com/) - 支持 JSX 等语法，社区维护。
- [Airbnb JavaScript Style Guide](https://airbnb.io/javascript/) - 支持 React 技术栈，**Airbnb 公司发布**。
- [Google JavaScript Style Guide](https://google.github.io/styleguide/jsguide.html) - 仅支持原生 JavaScript，**Google 公司发布**。

### JS 工具库

*JavaScript tool libraries (browser-side), such as file manipulation, Canvas drawing, HTTP requests, etc.*

- 兼容性（Polyfill）
  - [core-js](https://github.com/zloirock/core-js) - 现代 JavaScript 标准库。
  - [Promise Polyfill](https://github.com/taylorhakes/promise-polyfill) - 为浏览器提供 Promise API 支持。
  - [webp-hero](https://github.com/chase-moskal/webp-hero) - 为浏览器提供 WebP 格式图片支持。

- 文档（Doc）
  - [JSDoc](https://jsdoc.app/) - JavaScript 的 API 文档生成工具。
  - [highlight.js](https://highlightjs.org/) - 页面代码高亮。
  
- 测试（Test）
  - [Mocha](https://mochajs.org/)
  - [JEST](https://jestjs.io/) - Facebook 出品的 JavaScript 单元测试工具。
  - [faker.js](https://github.com/marak/faker.js) - 生成大量随机测试数据，可用来开发过程中进行 API 调试。
  - [Chance](https://chancejs.com/) - 生成随机的测试数据。
  - [Perfume.js](https://zizzamia.github.io/perfume/) - 性能监控工具。
 
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
 
- 文档对象模型（DOM）
  - [jQuery](https://jquery.com/) - 前几年非常流行的 DOM 操作工具库，处理了兼容性的细节问题。
  - [Zepto.js](https://zeptojs.com/) - 兼容 jQuery API 的轻量级工具库，适合移动端使用。
  - [Lozad.js](https://github.com/ApoorvSaxena/lozad.js) - 轻量、高性能图片懒加载工具，使用了 [Intersection Observer API](https://developer.mozilla.org/en-US/docs/Web/API/Intersection_Observer_API)。
  - [clipboard.js](https://clipboardjs.com/) - 现代的粘贴板工具库。
  
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

- 数据与缓存（Data && Cache）
  - [crypto-js](https://github.com/brix/crypto-js) - JavaScript 加密库。
  - [SJCL](http://bitwiseshiftleft.github.io/sjcl/) - JavaScript 加密库。
  - [localForage](https://github.com/localForage/localForage) - 离线存储，对 IndexedDB、WebSQL、localStorage 的封装。

- 科学计算（Compute - Math && High precision && Scientific Computing）
  - [math.js](https://mathjs.org/)
  - [stdlib](https://stdlib.io/)

- 绘图（Canvas && Draw）
  - [DOM to Image](https://github.com/tsayen/dom-to-image/) - 利用 HTML5 Canvas 生成 DOM 节点的快照图片。
  - [html2canvas](https://html2canvas.hertzen.com) - 截屏，利用 HTML5 Canvas 生成 DOM 节点的快照图片。
  - [Create.js](https://createjs.com) - 工具套件，包含 Canvas、Web Audio 等工具库。
  - [Konva](https://konvajs.org) - 用于桌面和移动应用程序的 HTML5 2D canvas 库。
  - [Two.js](https://two.js.org/) - Web 二维绘图工具库，基于 Canvas、Svg、WebGL。
  - [Paper.js](http://paperjs.org/) - 矢量绘图工具。
  - [Fabric.js](http://fabricjs.com/) - 矢量绘图工具。
  - [Pencil.js](https://pencil.js.org/) - 2D 绘图库。

- 动画（Animate）
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

- 二维码（QR Code）
  - [node-qrcode](https://github.com/soldair/node-qrcode) - 二维码生成。
  - [Awesome-qr.js](https://www.bitcat.cc/webapp/awesome-qr/index.html) - 个性化二维码生成。（:warning: 不再更新）

- 文件（File）
  - utils
    - [FileSaver.js](https://github.com/eligrey/FileSaver.js/) - Web 浏览器客户端文件保存 api 实现。
    - [StreamSaver.js](https://github.com/jimmywarting/StreamSaver.js) - Web 浏览器客户端异步保存文件 api 实现，解决了 FileSaver 的大小限制问题。
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

- HTTP 请求（HTTP - Ajax / Promise / fetch）
  - [axios](https://github.com/axios/axios) - 基于 Promise 的 HTTP 客户端工具库。

- 套接字（Socket / TCP）
  - [socket.io-client](https://socket.io/) - 优秀的实时通信客户端框架。

[`Go Top ↑`](#awesome-web-front-end-list)

## UI 组件

*UI Component*

### 组件库

*UI component library, providing a set of components with consistent design style.*

#### Bootstrap

- [Bootstrap](https://getbootstrap.com/) - 最流行的 CSS UI 框架。
- [Bootswatch](https://bootswatch.com/) - 开源免费的 Bootstrap 主题集合，**非官方**。

#### Google Material Design

- [Material Design Lite](https://getmdl.io/) - 基于 Material Design 的轻量级 CSS UI 框架，**Google 官方发布**。（:warning: 不再更新）
- [Material Components Web](https://material.io/develop/) - 基于 Material Design 的 Web 组件库，**Google 官方实现**。
- [Materialize](https://materializecss.com/) - 最流行的实现了 Google Material Design 的 CSS UI 框架。

#### 其它（Others）

- [Office UI Fabric Core](https://developer.microsoft.com/en-us/fabric) - Office 风格的 UI 库，**Microsoft 官方发布**。
- [Semantic UI](https://semantic-ui.com) - 很受欢迎的组件库。（:warning: 不再更新）
- [UIkit](https://getuikit.com/) - 轻量级的现代化前端 CSS 框架。
- [Pure.CSS](https://purecss.io/) - 一组小的，响应式的 CSS 模块。
- [Skeleton](http://getskeleton.com/)
- [Framework7](https://framework7.io/) - 跨平台 UI 库，支持 Android/ios/Desktop 平台，且主题样式设计适配相应平台。
- [Metro 4](https://metroui.org.ua/)
- [Layui](https://www.layui.com/) - 适合后端开发使用。

### 独立组件

*Independent UI components, only providing component modules that implement an interactive function.*

- 时间日期选择器（DatePicker & TimePicker）
  - [flatpickr](https://flatpickr.js.org/)
  - [layDate](https://www.layui.com/laydate/)

- 轮播（Carousel）
  - [Swiper](https://swiperjs.com/)
  - [slick-carousel](https://kenwheeler.github.io/slick/)
  - [Glider.js](https://nickpiscitelli.github.io/Glider.js/)
  - [Flickity](https://flickity.metafizzy.co/)
  - [lory.js](http://loryjs.github.io/lory/)
  - [keen-slider](https://keen-slider.io/)
  
- 模态框（Modal box）
  - [SweetAlert](https://sweetalert.js.org/) - 浏览器 Alert 弹框的替代，更漂亮美观。（:warning: 不再更新）
  - [SweetAlert2](https://sweetalert2.github.io/) - SweetAlert 的继承者。
  
- 图片浏览（Image Browse）
  - [Viewer.js](https://fengyuanchen.github.io/viewerjs/) - 图片列表预览。
  - [Image Compare Viewer](https://image-compare-viewer.netlify.app/) - 图片对比预览。
  - [Cropper.js](https://fengyuanchen.github.io/cropperjs/) - 图片裁剪。

- 表格（Table）
  - [Grid.js](https://gridjs.io/) - 高级表格插件。
  - [Frappe Datatable](https://frappe.io/datatable)

- H5 媒体（Audio & Video）
  - [video.js](https://videojs.com/) - 兼容大部分视频格式的视频播放器。
  - [MediaElement.js](http://www.mediaelementjs.com/) - 非常漂亮的视、音频播放器。
  - [Plyr](https://plyr.io/) - 很棒的视、音频播放器。
  - [clappr](http://clappr.io/) - 视频播放器。
  - [APlayer](https://aplayer.js.org/) - 非常漂亮的音乐播放器。
  - [DPlayer](http://dplayer.js.org/) - 视频播放器。
  - [Vime](https://vime-js.com/) - 视频播放器。

- 文件上传（File Upload）
  - [FilePond ](https://pqina.nl/filepond/) - 文件上传。
  - [DropzoneJS](https://www.dropzonejs.com/) - 文件上传组件，支持拖放文件、图片预览功能。

- 拖拽布局（Drag Layout）
  - [Packery](https://packery.metafizzy.co/) - 拖动网格布局。
  - [gridstack.js](https://gridstackjs.com/)
  
- 其它（Others）
  - [TOAST UI Calendar](https://github.com/nhn/tui.calendar) - 强大的日历日程组件。
  - [reveal.js](https://revealjs.com/) - 创建漂亮的演示文稿（幻灯片）。
  - [Cleave.js](https://nosir.github.io/cleave.js/) - 格式化输入框内容。
  - [TOAST UI Editor](https://ui.toast.com/tui-editor/) - 所见即所得编辑器。
  - [fullPage](https://alvarotrigo.com/fullPage/) - 全屏滚动页面。

[`Go Top ↑`](#awesome-web-front-end-list)

## 数据可视化

*Data visualization libraries, such as chart libraries, 3D engines, etc.*

- [D3](https://d3js.org/) - 数据驱动的可视化库，非常著名，许多图表库基于此开发。
- [three.js](https://threejs.org/) - 强大的 JavaScript 3D 动画库。
- [PixiJS](https://www.pixijs.com/) - 高性能 2D WebGL 渲染引擎。
- [Chart.js](https://www.chartjs.org/) - 最流行的轻量级图表库。
- [Frappe Charts](https://frappe.io/charts) - 高性能 SVG 图标库。
- [Frappe Gantt](https://frappe.io/gantt) - 甘特图。
- [Echarts](http://echarts.apache.org/) - 国内百度团队开发的图表库，功能丰富。
- [C3](https://c3js.org/) - 基于 D3 的可重用图表库。
- [GSAP](https://greensock.com/) - 现代化的高性能动画工具库。
- [Shifty](https://jeremyckahn.github.io/shifty/doc/index.html) - 轻量级、高性能的低级动画工具库。
- [Textures.js](https://riccardoscalco.it/textures/) - 创建 SVG 模式。
- [carbon-charts](https://carbon-design-system.github.io/carbon-charts/) - 遵循 Carbon 风格图表库，**IBM 公司发布**。

[`Go Top ↑`](#awesome-web-front-end-list)

## 开发框架

*Web front-end development framework (library).*

- [React.js](https://reactjs.org/) -  前端响应式 UI 库，其技术生态圈非常繁荣，Facebook 公司发布。
  - [Awesome-React.js](./awesome-reactjs.md) - React.js 生态技术汇总。
  
- [Vue.js](https://vuejs.org/)

- [Angular.js](https://angularjs.org/) - 一个比较重型的功能齐全的前端开发框架，Google 公司发布。

- [Svelte](https://svelte.dev/) - 更轻量的前端 UI 库。
  - [Sapper](https://sapper.svelte.dev/) - 基于 Svelte 的 Web App 开发框架。

- [Hyperapp](https://hyperapp.dev/) - 轻量的，纯函数式，声明式开发框架。

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
    
- 图片压缩（Image Compression）
  - [Compress PNG](https://compresspng.com/)
  - [Picdiet](https://www.picdiet.com/)
  - [TinyPNG](https://tinypng.com/)
  - [Optimizilla](https://imagecompressor.com/)
  - [压缩图](https://www.yasuotu.com/)
  - [色彩笔](http://www.secaibi.com/tools/)
  
- 在线 IDE、编辑器（IDE / Editor）
  - [StackBlitz](https://stackblitz.com/)
  - [JSFiddle](https://jsfiddle.net/)
  - [CodeSandbox](https://codesandbox.io/)
  - [CodePen](https://codepen.io/)
  - [WebAssembly Studio](https://webassembly.studio/) - 在线的 WebAssembly 编辑器，**Mozilla 发布**。
  
- 其它（Others）
  - [enjoyCSS](https://enjoycss.com/) - 便捷的组件样式设计输出在线工具。
  - [bit](https://bit.dev/) - 构建可重用组件的协作平台。
  - [Prettier Playground](https://prettier.io/playground/) - Prettier 代码格式化工具的在线版本。
  - [Color Hunt](https://colorhunt.co/) - 配色方案。
  - [Open Color](https://yeun.github.io/open-color/) - 配色方案。
  - [Sorted CSS Colors](https://enes.in/sorted-colors/)  
  - [Doka](https://doka.photo/) - 图片编辑工具。
  - [easings.co](https://easings.co/) - 测试动画函数效果。
  - [Keyframes](https://keyframes.app/) - CSS 预览小工具。

### 文章

*Some technical discussion articles.*

- [What forces layout / reflow](https://gist.github.com/paulirish/5d52fb081b3570c81e3a) - 一些会导致重绘、重布局的 DOM 操作。
- [You might not need jQuery](http://youmightnotneedjquery.com/)
- [CSS Tricks](https://css-tricks.com/) - CSS 技术文章。
- [The complete guide to CSS media queries](https://polypane.app/blog/the-complete-guide-to-css-media-queries/)

### 其它

*Other unclassified resources.*

- WebAssembly(wasm)
  - [Emscripten](https://emscripten.org/) - 用于编译为使用 LLVM 构建的 asm.js 和 WebAssembly 的工具链，可在 Web 浏览器中运行 C/C++ 代码。
  - [Cheerp](https://www.leaningtech.com/cheerp/) - 与 Emscripten 类似。
  - [Perspective](https://github.com/finos/perspective) - 基于 C++ 的 wasm 数据可视化组件。

- [JavaScript Open Source Award](https://osawards.com/javascript/) - JavaScript 开源项目奖，**非官方**。

[`Go Top ↑`](#awesome-web-front-end-list)
