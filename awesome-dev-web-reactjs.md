<div align="center">
  <h1>Awesome-React.JS-List</h1>

  <p>:heart: 收藏列表 - :+1: 很棒的 React.js 开发工具和生态技术。</p>
  <p><i>Favorites list - great React.js development tools and ecological technology.</i></p>
</div>

<br />

> React.js 是 Facebook 出品的开源 Web 前端 UI 框架，其结合了组件化思想、数据驱动视图、Virtual DOM 技术等，提供了快速、轻量、高性能的 Web App 开发体验，官网为 https://reactjs.org/

（Recommend）推荐一个其它的很棒的收藏列表，:point_right: https://github.com/enaqx/awesome-react

## 目录

*Resource navigation list.*

- [技术参考文档（Technical Reference Document）](#技术参考文档)
- [构建工具（Build Tools）](#构建工具)
- [Hook](#hook)
- [状态管理（Application State Management）](#状态管理)
- [路由管理（Route Management）](#路由管理)
- [UI 设计系统（UI Design System）](#ui-设计系统)
- [UI 组件（UI Component）](#ui-组件)
  - [组件库（Component Library）](#组件库)
  - [独立组件（Independent Components）](#独立组件)
- [数据可视化（Data Visualization）](#数据可视化)
- [优化方案（Application Optimization）](#优化方案)
- [文章（Article）](#文章)
- [深入探索（Explore In Depth）](#深入探索)
- [更多（More）](#更多)

## 技术参考文档

*Official and unofficial technical reference documents.*

- [React Developer Roadmap](https://roadmap.sh/react) - React 开发者路线图参考。
- [React Developer Roadmap](https://github.com/adam-golab/react-developer-roadmap) - React 开发者路线图参考。（:warning: 自 2019 年不再更新）

[`Go Top ↑`](#awesome-reactjs-list)

## 构建工具

*Application building tools, including JSX code compilation, code file merging and packaging, syntax rule checking, etc.*

- 集成开发环境（IDE）
  - [React IDE](http://reactide.io/)

- 调试（Debug）
  - [React DevTools](https://github.com/facebook/react/blob/master/packages/react-devtools) - React 应用的调试工具，可以作为 Chrome 扩展使用，**React 官方发布**。
  - [Reactime](https://reactime.io/) - 调试工具，组件快照记录，Chrome 扩展。
  - [React Sight](https://www.reactsight.com/) - 调试工具，可视化组件树，Chrome 扩展。
  - [why-did-you-render](https://github.com/welldone-software/why-did-you-render) - 探测应用重新渲染的部分的原因。

- 构建（Build）
  - [Create React App](https://create-react-app.dev/) - 零配置的 React App 构建工具，**React 官方发布**。
  - [webpack](https://webpack.js.org/) - 打包工具。
  - [Babel](https://babeljs.io/) - TypeScript/ES Next 编译工具。
    - [babel-preset-react](https://github.com/babel/babel/tree/master/packages/babel-preset-react) - Babel 的 React.js 预设插件，**Babel 官方发布**。
    - [babel-preset-flow](https://github.com/babel/babel/tree/master/packages/babel-preset-flow) - Babel 的 Flow 预设插件，**Babel 官方发布**。
    - [babel-preset-typescript](https://github.com/babel/babel/tree/master/packages/babel-preset-typescript) - Babel 的 TypeScript 预设插件，**Babel 官方发布**。[👉 react-typescript-cheatsheets](https://react-typescript-cheatsheet.netlify.app/)
    - [babel-jest](https://github.com/facebook/jest/tree/master/packages/babel-jest) - Babel 的 Jest 插件，**FaceBook 发布**。

- 代码质量分析（Lint）
  - [ESLint](https://eslint.org/) - 语法规则检查工具。
    - [eslint-plugin-react](https://github.com/yannickcr/eslint-plugin-react) - ESLint 的 React.js 语法规则插件。
    - [eslint-plugin-react-hooks](https://github.com/facebook/react/tree/master/packages/eslint-plugin-react-hooks) - ESLint 的 React Hooks 语法规则检查插件，**React 官方发布**。
  - [Prettier](https://prettier.io/) - 代码格式化工具。
  - [Flow](https://flow.org/) - JavaScript 静态类型检查工具，**FaceBook 官方发布**。

- 测试（Test）
  - [Jest](https://jestjs.io/) - 单元测试工具，**FaceBook 发布**。
  
- 组件原型开发（UI Components Dev）
  - [React Cosmos](https://reactcosmos.org/)

- 文档（Document）
  - [React Styleguidist](https://react-styleguidist.js.org/) 

[`Go Top ↑`](#awesome-reactjs-list)

## Hook

*Useful [React Hook](https://reactjs.org/docs/hooks-intro.html) tool.*

_（Recommend）推荐一个其它的很棒的收藏列表，:point_right: [rehooks/awesome-react-hooks](https://github.com/rehooks/awesome-react-hooks)_

- 资源请求（Resource Request）
  - [React Query](https://github.com/tannerlinsley/react-query) - 服务器端数据获取、缓存、异步更新。
  - [SWR](https://swr.now.sh/) - 用于远程数据获取，更轻量。
  - [axios-hooks](https://github.com/simoneb/axios-hooks) - 数据请求、缓存管理，**非 axios 官方发布**。
  - [React Async](https://docs.react-async.com/)

- 表单（Form）
  - [React Hook Form](https://react-hook-form.com/) - 表单处理。
  - [Unform](https://unform.dev/) - 注重性能的表单处理工具。  

- 其它（Others）
  - [react-use](https://github.com/streamich/react-use) - 一套 hook 工具包。
  - [React Adaptive Loading Hooks & Utilities](https://github.com/GoogleChromeLabs/react-adaptive-hooks) - 检测客户端的状态，例如网络状态、媒体支持等。
  - [useWorker](https://useworker.js.org/) - 使用 Web Worker 运行复杂任务，创建非阻塞 UI。
  - [use-deep-compare-effect](https://github.com/kentcdodds/use-deep-compare-effect) - `useEffect` 的深比较模式。
  - [react-laag](https://www.react-laag.com/) - 创建工具提示或者弹出框。

[`Go Top ↑`](#awesome-reactjs-list)

## 状态管理

*React application global state management and optimization.*

_（Recommend）其它收藏列表 :point_right: [olegrjumin/awesome-react-state-management](https://github.com/olegrjumin/awesome-react-state-management)_

- [React-Redux](https://react-redux.js.org/) - 为 React 应用提供 Redux 支持，**Redux 官方实现**。
  - [Redux 工具链](./awesome-dev-web-front-end.md#应用状态管理)
- [Mobx-React](https://mobx-react.js.org/) - 为 React 应用提供 Mobx 支持，**Mbox 官方实现**。
- [Recoil](https://recoiljs.org/) - 状态管理工具，**Facebook 官方发布**。
- [@xstate/react](https://github.com/statelyai/xstate/tree/main/packages/xstate-react) - 基于状态机模型。
- [zustand](https://github.com/pmndrs/zustand) - 轻量级状态管理库,类似于 Redux。
- [jotai](https://jotai.pmnd.rs/) - 轻量级状态管理库,类似于 Recoil。

- Tools
  - [Immutable.js](https://immutable-js.github.io/immutable-js/) - 不可变数据。
  - [Immer](https://immerjs.github.io/immer/) - 不可变数据。

[`Go Top ↑`](#awesome-reactjs-list)

## 路由管理

*Route management for SPA applications built with React.js.*

- [React-Router](https://reacttraining.com/react-router/)
- [Reach Router](https://reach.tech/router)
- [react-location](https://github.com/tannerlinsley/react-location)

[`Go Top ↑`](#awesome-reactjs-list)

## UI 设计系统

_UI Design System, provides a base system for building a design system._

- [Rebass](https://rebassjs.org/)
- [radix](https://www.radix-ui.com/)
- [Reakit](https://reakit.io/)
- [Geist](https://geist-ui.dev/)

[`Go Top ↑`](#awesome-reactjs-list)

## UI 组件

*Feature-rich component library built on React.js.*

*（Recommend）推荐一个其它的收藏列表，:point_right: https://github.com/brillout/awesome-react-components*

### 组件库

*UI component library, providing a set of components with consistent design style.*

#### Material Design

*Component library that implements [Google Material Design](https://www.material.io/).*

- [MDC React](https://github.com/material-components/material-components-web-react) - 实现了 Google Material Design，**Google 官方实现**。
- [Material UI](https://material-ui.com/) - 实现了 Google Material Design，组件非常丰富。
- [Framework7-React](https://framework7.io/react/) - 跨平台 UI 组件库，支持 Android/ios/Desktop，且自适应相应平台设计风格。  
- [React Toolbox](http://react-toolbox.io/) - 实现了 Google Material Design。（:warning: 不再更新）
  
#### Bootstrap
  
*Based on [Bootstrap](https://getbootstrap.com/)*.

- [reactstrap](https://reactstrap.github.io/) - 基于 Bootstrap 4，**非 Bootstrap 官方实现**。
- [react-bootstrap](https://github.com/react-bootstrap/react-bootstrap) - 基于 Bootstrap 4，**非 Bootstrap 官方实现**。
- [React Bootstrap Typeahead](http://ericgio.github.io/react-bootstrap-typeahead/) - 输入框自动完成组件，**非 Bootstrap 官方实现**。

#### 其它

- [Base Web React UI framework](https://baseweb.design/) - **Uber 公司发布**。
- [Office UI Fabric React](https://developer.microsoft.com/en-us/fabric) - Office UI 风格，**Microsoft 公司发布**。
- [Carbon Design System React](https://www.carbondesignsystem.com/tutorial/react/overview) - 遵循 Carbon 设计风格，**IBM 公司发布**。
- [React Spectrum](https://react-spectrum.adobe.com/react-spectrum/) - Spectrum 设计，**Adobe 公司发布**。
- [Grommet](https://v2.grommet.io/)
- [Blueprint](https://blueprintjs.com/) - 提供复杂的数据分析展示、表格等组件。
- [React Rainbow](https://react-rainbow.io/)
- [Chakra UI](https://chakra-ui.com/)
- [Evergreen](https://evergreen.segment.com/)
- [Ant Design of React](https://ant.design/docs/spec/introduce-cn)
- [Semantic UI](https://react.semantic-ui.com/) - 非常受欢迎的组件库。（:warning: 不再更新）
- [Mantine](https://mantine.dev/) - 全功能的组件库和 Hook 库。
- [Next UI](https://nextui.org/)
- [Prime React](https://www.primefaces.org/primereact/)
- [react-desktop](http://reactdesktop.js.org/) - 桌面端 UI 组件库，基于 macOS Sierra 和 Windows 10 主题设计。

### 独立组件

*Independent UI components, only providing component modules that implement an interactive function.*

- 表单（Form）
  - [Formik](https://jaredpalmer.com/formik/) - 表单自动验证，异步提交，提供 Hook API。
  - [React Select](https://react-select.com/) - 支持多选、自动完成、异步搜索选项等。
  - [React Autosuggest](http://react-autosuggest.js.org/) - 输入建议，自动完成功能。
  - [react-number-format](https://github.com/s-yadav/react-number-format) - 数字输入格式化。

- 表格（Table）
  - [React Table](https://github.com/tannerlinsley/react-table)
  - [RevoGrid](https://revolist.github.io/revogrid/)
  
- 时间日期选择器（DatePicker & TimePicker）
  - [react-dates](https://github.com/airbnb/react-dates) - 国际化、移动端友好，**Airbnb 公司发布**。
  - [react-day-picker](http://react-day-picker.js.org/)
  - [React Datepicker](https://reactdatepicker.com/)

- 文件上传（File Upload）
  - [react-dropzone](https://react-dropzone.js.org/) - 文件上传组件，支持 Hook API。

- 轮播（Carousel）
  - [react-slick](https://react-slick.neostack.com/)

- 图片（Image）
  - [React Carousel Image Gallery](https://github.com/xiaolin/react-image-gallery) - 图片轮播组件。
  - [React Images](https://jossmac.github.io/react-images) - 图片点击原图查看、列表。
  - [React Image Lightbox](https://frontend-collective.github.io/react-image-lightbox/) - 图片点击原图查看、列表、缩放。
  - [React lightbox component](https://github.com/jfcaiceo/react-lightbox-component) - 图片点击原图查看、列表、缩放、旋转。（:warning: 不再更新）
  - [react-zmage](https://zmage.caldis.me/) - 图片点击原图查看、列表、旋转。

- 颜色选择器（Color Picker）
  - [React Color](http://casesandberg.github.io/react-color/) - 颜色拾取器，支持十多种样式。

- 拖拽（Draggable）
  - [react-beautiful-dnd](https://react-beautiful-dnd.netlify.app/)
  - [react-grid-layout](https://github.com/react-grid-layout/react-grid-layout) - 拖放布局，调整大小。
    - [React-Draggable](https://github.com/STRML/react-draggable) - 让组件位置可以被拖动调整布局。 
  - [React DnD](https://react-dnd.github.io/react-dnd/)
  - [dnd kit](https://dndkit.com/) - 轻量、高性能的拖放组件。
  - [react-rnd](https://github.com/bokuweb/react-rnd)- 拖放，调整大小。

- 大量数据渲染（Large amount of data rendering）
  - [react-virtualized](https://bvaughn.github.io/react-virtualized/)
  - [react-window](https://github.com/bvaughn/react-window)

- 动画（Animation）
  - [React Transition Group](https://reactcommunity.org/react-transition-group/) - 过渡动画。
  - [React-Motion](https://github.com/chenglou/react-motion) - 提供更简单的动画 API。
  - [Framer-Motion](https://framer.com/api/motion) - 手势动画。
  - [React Awesome Reveal](https://react-awesome-reveal.morello.dev/) - 基于 [Intersection Observer API](https://developer.mozilla.org/en-US/docs/Web/API/Intersection_Observer_API) 和 [Animate.css](https://animate.style/) 的动画库。
  - [React Spinners](https://www.davidhu.io/react-spinners/) - 丰富的 Loading 动画。
  - [React Move](https://react-move-docs.netlify.app/)
  - [Renature](https://formidable.com/open-source/renature/) - 物理动画库。
  - [react-confetti](https://github.com/alampros/react-confetti) - 五彩纸屑动画。
  - [React DOM Confetti](https://daniel-lundin.github.io/react-dom-confetti/) - 五彩纸屑动画。
  - [react-number-easing](https://javier.xyz/react-number-easing/) - 数字滚动动画。

- 二维码（QR Code）
  - [qrcode.react](https://github.com/zpao/qrcode.react)
  - [react-qr-code](https://github.com/rosskhanas/react-qr-code)

- 用户引导（User guided tours）
  - [React Joyride](https://react-joyride.com/)
  - [Reactour](https://reactour.js.org/)

- 消息通知（Notification）
  - [React-Toastify](https://fkhadra.github.io/react-toastify/) - 消息弹窗组件。
  - [React Toast Notifications](https://jossmac.github.io/react-toast-notifications/) - 消息通知弹窗组件。
  - [react-hot-toast](https://react-hot-toast.com/)
  - [notistack](https://iamhosseindhv.com/notistack)

- 其它（Others）
  - [React PDF](https://projects.wojtekmaj.pl/react-pdf/) - pdf 文件预览组件。
  - [react-big-calendar](http://jquense.github.io/react-big-calendar/) - 事件日历，日程表组件。
  - [React Diagrams](https://projectstorm.gitbook.io/react-diagrams/) - 流程图组件。
  - [React Sortable Tree](https://github.com/frontend-collective/react-sortable-tree) - 树形列表，支持拖拽。
  - [React Measure](https://github.com/souporserious/react-measure) - 组件尺寸测量。
  - [React-Menu](https://szhsin.github.io/react-menu/) - 菜单组件，支持多级菜单、滚动菜单等。
  - [Emoji Mart](https://missive.github.io/emoji-mart/) - emoji 表情选择组件。
  - [react-responsive](https://github.com/contra/react-responsive) - 响应式 UI 工具组件。
  - [use-count-up](https://github.com/vydimitrov/use-count-up) - 计数器。
  - [react-markdown](https://remarkjs.github.io/react-markdown/) - markdown 渲染组件。

[`Go Top ↑`](#awesome-reactjs-list)

## 数据可视化

*Data visualization chart library, framework.*

- [React-Vis](https://uber.github.io/react-vis/) - 图表库，**Uber 团队开发**。
- [visx](https://airbnb.io/visx) - 图表库，基于 React 和 D3.js,**Airbnb 团队开发**。
- [Recharts](http://recharts.org/) - 图表库。
- [React Charts](https://react-charts.js.org/) - 图表库。
- [Victory](https://formidable.com/open-source/victory/) - 图表库。
- [react-three-fiber](https://docs.pmnd.rs/react-three-fiber/getting-started/introduction) - 可视化库，React.js 的 Threejs 渲染器。
- [React Financial Charts](https://github.com/reactivemarkets/react-financial-charts) - 图表库，股票蜡烛图。
- [react-flow](https://reactflow.dev/) - 可视化工具库，构建流程图等。
- [react-chartjs-2](https://github.com/reactchartjs/react-chartjs-2)
- [react-spring](https://react-spring.io/) - 动画工具库。

[`Go Top ↑`](#awesome-reactjs-list)

## 优化方案

*React web application optimization solution.*

- 懒加载、代码分割（Lazy Load && Code Split）
  - [loadable-components](https://www.smooth-code.com/open-source/loadable-components/) - 实现组件懒加载功能，支持服务器端渲染（SSR）。
  - [React-Loadable](https://github.com/jamiebuilds/react-loadable) - 基于 React 高阶组件，实现组件懒加载功能。（:warning: 不再更新）

- CSS In JS
  - [React-JSS](https://cssinjs.org/react-jss) - JSS 是 CSS-in-JS 的一种解决方案，这个是与 React 的集成方案。  

- 服务器端渲染（SSR，server side rendering）
  - [Next.js](https://nextjs.org) - React.js 服务器端渲染框架。
  
- 国际化（i18n）
  - [react-i18next](https://react.i18next.com/)
  - [react-intl](https://formatjs.io/docs/react-intl)

- 加载占位符（Loading Placeholder）
  - [React Content Loader](https://github.com/danilowoz/react-content-loader) - 提供了组件加载占位效果（Skeleton Screen），优化交互体验。
  - [react-placeholder](https://github.com/buildo/react-placeholder)

- 其它（Others）
  - [react-fast-compare](https://formidable.com/open-source/react-fast-compare/) - React 组件的高性能深度比较，可替代 `lodash.isEqual`。
  - [Gatsby](https://www.gatsbyjs.org/) - 静态站点生成器，基于 React.js 的开源框架，可快速开发 Web 网站和应用。
  - [react-error-boundary](https://github.com/bvaughn/react-error-boundary) - 简单的可重用 React 错误边界组件。
  - [react-refetch](https://github.com/heroku/react-refetch) - 组件数据加载。

## 文章

*Some articles explaining the core technology of React.*

- React 团队核心成员 [Dan Abramov 的博客](https://overreacted.io/)文章
  - [React as a UI Runtime](https://overreacted.io/react-as-a-ui-runtime/)
  - [Why Do React Elements Have a $$typeof Property?](https://overreacted.io/why-do-react-elements-have-typeof-property/) - React 中 `$$typeof` 属性的意义。
- [React in Depth Dev](https://indepth.dev/react) - 一些讲解 React 高级概念的文章。
  - [Inside Fiber: in-depth overview of the new reconciliation algorithm in React](https://indepth.dev/posts/1008/inside-fiber-in-depth-overview-of-the-new-reconciliation-algorithm-in-react)
  - [The how and why on React’s usage of linked list in Fiber to walk the component’s tree](https://indepth.dev/posts/1007/the-how-and-why-on-reacts-usage-of-linked-list-in-fiber-to-walk-the-components-tree)
  - [In-depth explanation of state and props update in React](https://indepth.dev/posts/1009/in-depth-explanation-of-state-and-props-update-in-react)
- [React Fiber Architecture](https://github.com/acdlite/react-fiber-architecture) - React Fiber 架构简介。
- [Good advice on JSX conditionals](https://thoughtspile.github.io/2022/01/17/jsx-conditionals/) - 更好的使用 JSX 语法。

[`Go Top ↑`](#awesome-reactjs-list)

## 深入探索

*Explore the principles behind the technology, the underlying architecture, etc.*

[`Go Top ↑`](#awesome-reactjs-list)

## 更多

*More other unclassified resources.*

- [React Open Source Awards](https://osawards.com/react/) - React 开源项目奖，**非官方**。
- [Proton Native](https://proton-native.js.org/#/) - 跨平台桌面端应用的 React.js 环境。
- [Spectacle](https://formidable.com/open-source/spectacle/) - 基于 React.js 的演示文稿工具库。
- [React Interview Questions & Answers](https://github.com/sudheerj/reactjs-interview-questions) - React.js 面试 Q/A。

[`Go Top ↑`](#awesome-reactjs-list)
