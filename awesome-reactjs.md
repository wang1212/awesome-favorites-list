<div align="center">
  <h1>Awesome-React.JS-List</h1>

  <p>:heart: 收藏列表 - :+1: 很棒的 React.js 开发工具和生态技术。</p>
</div>

<br />

> React.js 是 Facebook 出品的开源 Web 前端 UI 框架，其结合了组件化思想、数据驱动视图、Virtual DOM 技术等，提供了快速、轻量、高性能的 Web App 开发体验，官网为 https://reactjs.org/

（Recommend）推荐一个其它的很棒的收藏列表，:point_right: https://github.com/enaqx/awesome-react

## 目录

*Resource navigation list.*

- [构建工具（Build Tools）](#构建工具)
- [Hook](#hook)
- [状态管理（Application State Management）](#状态管理)
- [路由管理（Route Management）](#路由管理)
- [UI 组件（UI Component）](#ui-组件)
  - [组件库（Component Library）](#组件库)
  - [独立组件（Independent Components）](#独立组件)
- [数据可视化（Data Visualization）](#数据可视化)
- [优化方案（Application Optimization）](#优化方案)
- [更多（More）](#更多)

## 构建工具

*Application building tools, including JSX code compilation, code file merging and packaging, syntax rule checking, etc.*

- 调试（Debug）
  - [React DevTools](https://github.com/facebook/react/blob/master/packages/react-devtools) - React 应用的调试工具，可以作为 Chrome 扩展使用，**React 官方发布**。
  - [React Sight](https://www.reactsight.com/) - 调试工具，可视化组件树，Chrome 扩展。

- 构建（Build）
  - [Create React App](https://create-react-app.dev/) - 零配置的 React App 构建工具，**React 官方发布**。
  - [webpack](https://webpack.js.org/) - 打包工具。
  - [Babel](https://babeljs.io/) - TypeScript/ES Next 编译工具。
    - [babel-preset-react](https://github.com/babel/babel/tree/master/packages/babel-preset-react) - Babel 的 React.js 预设插件，**Babel 官方发布**。
    - [babel-preset-flow](https://github.com/babel/babel/tree/master/packages/babel-preset-flow) - Babel 的 Flow 预设插件，**Babel 官方发布**。
    - [babel-preset-typescript](https://github.com/babel/babel/tree/master/packages/babel-preset-typescript) - Babel 的 TypeScript 预设插件，**Babel 官方发布**。[（react-typescript-cheatsheets）](https://github.com/typescript-cheatsheets/react-typescript-cheatsheet)
    - [babel-jest](https://github.com/facebook/jest/tree/master/packages/babel-jest) - Babel 的 Jest 插件，**FaceBook 发布**。

- 代码质量分析（Lint）
  - [ESLint](https://eslint.org/) - 语法规则检查工具。
    - [eslint-plugin-react](https://github.com/yannickcr/eslint-plugin-react) - ESLint 的 React.js 语法规则插件。
    - [eslint-plugin-react-hooks](https://github.com/facebook/react/tree/master/packages/eslint-plugin-react-hooks) - ESLint 的 React Hooks 语法规则检查插件，**React 官方发布**。
  - [Prettier](https://prettier.io/) - 代码格式化工具。
  - [Flow](https://flow.org/) - JavaScript 静态类型检查工具，**FaceBook 官方发布**。

- 测试（Test）
  - [Jest](https://jestjs.io/) - 单元测试工具，**FaceBook 发布**。

[`Go Top ↑`](#awesome-reactjs-list)

## Hook

*Useful [React Hook](https://reactjs.org/docs/hooks-intro.html) tool.*

（Recommend）推荐一个其它的很棒的收藏列表，:point_right: https://github.com/rehooks/awesome-react-hooks

- [useWorker](https://useworker.js.org/) - 使用 Web Worker 运行复杂任务，创建非阻塞 UI。
- [SWR](https://swr.now.sh/) - 用于远程数据获取的 Hook。
- [React Query](https://github.com/tannerlinsley/react-query) - 服务器端数据获取、缓存、异步更新。

[`Go Top ↑`](#awesome-reactjs-list)

## 状态管理

*React application global state management and optimization.*

（Recommend）Redux 生态技术，:point_right: https://github.com/markerikson/redux-ecosystem-links

- [Redux](https://redux.js.org/) - Redux 是一个独立的应用状态管理库，它本身是可以和任何库结合使用的，但通常提到它均是认为和 React.js 一块使用，需要配合 react-redux 使用。
  - [React-Redux](https://react-redux.js.org/) - 将 Redux 与 React.js 搭配使用，**Redux 官方实现**。
  - [Redux-Thunk](https://github.com/reduxjs/redux-thunk) - 作为一个 Redux 的中间件存在，提供了异步支持，**Redux 官方实现**。
  - [redux-saga](https://redux-saga.js.org/) - 提供异步支持，功能比 Redux-Thunk 更丰富，利于测试。
  - [Reselect](https://github.com/reduxjs/reselect) - Redux 状态缓存。
  - [Redux-Logger](https://github.com/LogRocket/redux-logger) - 调试工具，作为一个 Redux 的中间件存在，提供了打印 Redux 日志功能。
  - [redux-devtools](https://github.com/reduxjs/redux-devtools) - Redux 调试工具，Chrome 插件。

- [Rematch](https://rematch.github.io/rematch/) - 对 Redux 进行了封装，提供更简单方便的 API。
- [Mirror](https://github.com/mirrorjs/mirror) - 简单的状态管理库。
- [MobX](https://mobx.js.org/)

- [Immutable.js](https://immutable-js.github.io/immutable-js/) - 不可变数据。（:warning: 不再更新）
- [Immer](https://immerjs.github.io/immer/) - 不可变数据。

[`Go Top ↑`](#awesome-reactjs-list)

## 路由管理

*Route management for SPA applications built with React.js.*

- [React-Router](https://reacttraining.com/react-router/)
- [Reach Router](https://reach.tech/router)

[`Go Top ↑`](#awesome-reactjs-list)

## UI 组件

*Feature-rich component library built on React.js.*

*（Recommend）推荐一个其它的收藏列表，:point_right: https://github.com/brillout/awesome-react-components*

### 组件库

*UI component library, providing a set of components with consistent design style.*

#### Google Material Design

*Component library that implements [Google Material Design](https://www.material.io/).*

- [MDC React](https://github.com/material-components/material-components-web-react) - 实现了 Google Material Design，**Google 官方实现**。
- [Material UI](https://material-ui.com/) - 实现了 Google Material Design，组件非常丰富。
- [Framework7-React](https://framework7.io/react/) - 跨平台 UI 组件库，支持 Android/ios/Desktop，且自适应相应平台设计风格。  
- [React Toolbox](http://react-toolbox.io/) - 实现了 Google Material Design。（:warning: 不再更新）
  
#### Bootstrap
  
*Based on [Bootstrap](https://getbootstrap.com/)*.

- [reactstrap](https://reactstrap.github.io/) - 基于 Bootstrap 4，**非 Bootstrap 官方实现**。
- [react-bootstrap](https://github.com/react-bootstrap/react-bootstrap) - 基于 Bootstrap 4，**非 Bootstrap 官方实现**。

#### 其它

- [Carbon Design System React](https://www.carbondesignsystem.com/tutorial/react/overview) - 遵循 Carbon 设计风格，**IBM 公司发布**。
- [Office UI Fabric React](https://developer.microsoft.com/en-us/fabric) - Office UI 风格，**Microsoft 公司发布**。
- [Semantic UI](https://react.semantic-ui.com/) - 非常受欢迎的组件库。（:warning: 不再更新）
- [Grommet](https://v2.grommet.io/)
- [Rebass](https://rebassjs.org/) - 构建 React UI 组件的工具库。
- [Blueprint](https://blueprintjs.com/) - 提供复杂的数据分析展示、表格等组件。
- [React Rainbow](https://react-rainbow.io/)

### 独立组件

*Independent UI components, only providing component modules that implement an interactive function.*

- 表单（Form）
  - [Formik](https://jaredpalmer.com/formik/)
  - [React Hook Form](https://react-hook-form.com/)

- 表格（Table）
  - [React Table](https://github.com/tannerlinsley/react-table)

- 动画（Animation）
  - [React Transition Group](https://reactcommunity.org/react-transition-group/) - 过渡动画。
  - [React-Motion](https://github.com/chenglou/react-motion) - 提供更简单的动画 API。
  - [Framer-Motion](https://framer.com/api/motion) - 手势动画。
  - [React Awesome Reveal](https://react-awesome-reveal.morello.dev/) - 基于 [Intersection Observer API](https://developer.mozilla.org/en-US/docs/Web/API/Intersection_Observer_API) 和 [Animate.css](https://animate.style/) 的动画库。
  - [React Spinners](https://www.davidhu.io/react-spinners/) - 丰富的 Loading 动画。

- 时间日期选择器（DatePicker & TimePicker）
  - [react-dates](https://github.com/airbnb/react-dates) - 国际化、移动端友好，**Airbnb 公司发布**。
  - [react-day-picker](http://react-day-picker.js.org/)
  - [React Datepicker](https://reactdatepicker.com/)

- 文件上传（File Upload）
  - [react-dropzone](https://react-dropzone.js.org/) - 文件上传组件，支持 Hook API。

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
  - [React DnD](https://react-dnd.github.io/react-dnd/)
  - [React-Draggable](https://github.com/STRML/react-draggable) - 让组件位置可以被拖动调整。

- 大量数据渲染（Large amount of data rendering）
  - [react-virtualized](https://bvaughn.github.io/react-virtualized/)
  - [react-window](https://github.com/bvaughn/react-window)

- 其它（Others）
  - [React-Toastify](https://fkhadra.github.io/react-toastify/) - 消息弹窗组件。
  - [qrcode.react](https://github.com/zpao/qrcode.react) - 二维码组件。
  - [react-big-calendar](http://jquense.github.io/react-big-calendar/) - 事件日历，日程表组件。

[`Go Top ↑`](#awesome-reactjs-list)

## 数据可视化

*Data visualization chart library, framework.*

- [React-Vis](https://uber.github.io/react-vis/) - 图表可视化库，**Uber 团队开发**。
- [vx](https://vx-demo.now.sh/) - 基于 React 和 D3.js 的可视化库。
- [React Charts](https://react-charts.js.org/)

[`Go Top ↑`](#awesome-reactjs-list)

## 优化方案

*React web application optimization solution.*

- 懒加载、代码分割（Lazy Load && Code Split）
  - [loadable-components](https://www.smooth-code.com/open-source/loadable-components/) - 实现组件懒加载功能，支持服务器端渲染（SSR）。
  - [React-Loadable](https://github.com/jamiebuilds/react-loadable) - 基于 React 高阶组件，实现组件懒加载功能。（:warning: 不再更新）

- 服务器端渲染（SSR，server side rendering）
  - [Next.js](https://nextjs.org) - React.js 服务器端渲染框架。
  
- 其它（Others）
  - [React Content Loader](https://github.com/danilowoz/react-content-loader) - 提供了组件加载占位效果（Skeleton Screen），优化交互体验。

## 更多

*More other unclassified resources.*

- [React-JSS](https://cssinjs.org/react-jss) - JSS 是 CSS-in-JS 的一种解决方案，这个是与 React 的集成方案。
- [React Open Source Awards](https://osawards.com/react/) - React 开源项目奖，**非官方**。

[`Go Top ↑`](#awesome-reactjs-list)
