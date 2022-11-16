<div align="center">
  <h1>Awesome-Data-Visualization-List</h1>

  <p>:heart: 收藏列表 - :+1: 很棒的数据可视化领域开发的相关资源。</p>
  <p><i>Favorites list - Great resources for developing in the field of data visualization.</i></p>
</div>

<br />

## 目录

*Resource navigation list.*

- [参考文档（Reference documentation）](#参考文档)
- [工具库（Tool Library）](#工具库)

## 参考文档

_Reference documentation._

_see also :point_right: [计算机图形学读物](https://github.com/wang1212/awesome-favorites-list/blob/master/awesome-reading.md#%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9B%BE%E5%BD%A2%E5%AD%A6)_

- 数据可视化
  - [from Data to Viz](https://www.data-to-viz.com/) - 数据可视化决策工具。
  - [The Data Visualisation Catalogue](https://datavizcatalogue.com/) - 数据可视化目录。
  - [Google Material Design Data visualization](https://material.io/design/communication/data-visualization.html)

- 学习资料（Docs）
  - [OpenGL Wiki](https://www.khronos.org/opengl/wiki)   
  - [Graphics Related Lessons](https://github.com/gfxfundamentals)
    - [_WebGL Fundamentals_](https://webglfundamentals.org/) - _WebGL 基础知识。_
    - [_WebGL2 Fundamentals_](https://webgl2fundamentals.org/) - _WebGL2 基础知识。_
    - [_Three.js Fundamentals_](https://threejs.org/manual/) - _Three.js 基础知识。_
  - [_WebGL Guide_](https://xem.github.io/articles/webgl-guide.html) - _WebGL 技术指南。_
  - [Advanced Graphics Algorithms](https://sites.google.com/site/csc8820/educational/course-overview) - 一些图形算法介绍。
  - [Discover three.js](https://discoverthreejs.com/book/) - 介绍了开始探索 3D Web 图形所需的所有重要概念和术语。
  - [Shadertoy](https://www.shadertoy.com/) - 着色器代码分享。

[`Go Top ↑`](#awesome-data-visualization-list)

## 工具库

*Data visualization libraries, such as chart libraries, 3D engines, etc.*

### JavaScript

#### 可视化工具

*Data visualization tool library.*

- [D3](https://d3js.org/) - 可视化库，数据驱动的，非常著名，许多图表库基于此开发。

- 3D
  - [_A collection of WebGL and WebGPU frameworks and libraries_](https://gist.github.com/dmnsgn/76878ba6903cf15789b712464875cfdc) 
  - Tools
    - [stackgl](http://stack.gl/) - 编写着色器代码的工具集。
    - [Draco](https://google.github.io/draco/) - 3D 数据压缩工具。
    - [meshoptimizer](https://github.com/zeux/meshoptimizer) - 优化 glTF 文件的工具。
    - [glTF-Transform](https://gltf-transform.donmccurdy.com/index.html) - 处理 glTF 模型文件的 SDK。
    - [gl-matrix](https://glmatrix.net/) - 为 WebGL 应用提供高性能的矩阵属性运算能力。
  - [three.js](https://threejs.org/) - 3D WebGL 渲染引擎。
    - [three-globe](https://github.com/vasturiano/three-globe) - 3D 地球组件工具库。
    - [View 3D](https://naver.github.io/egjs-view3d/) - 快速且可定制的 glTF 3D 模型查看器，功能齐全。
    - [3D tiles](https://github.com/CesiumGS/3d-tiles/tree/main/specification)
      - [3d-tiles-renderer](https://github.com/NASA-AMMOS/3DTilesRendererJS)
      - [three-loader-3dtiles](https://github.com/nytimes/three-loader-3dtiles)
  - [A-Frame](https://aframe.io/) - 构建 3D/AR/VR 应用的框架。
  - [sigma.js](http://sigmajs.org/) - 可视化大数据量的关系节点。
    - [Graphology](https://graphology.github.io/)
  - [Zdog](https://zzz.dog/) - 圆形、扁平的设计师友好的伪 3D 引擎。
  - :point_right: React.js
    - [react-three-fiber](https://docs.pmnd.rs/react-three-fiber/getting-started/introduction) - 可视化库，React.js 的 Threejs 渲染器。
    - [React Unity WebGL](https://react-unity-webgl.dev/)

- [Babylon.js](https://www.babylonjs.com/) - 游戏渲染引擎。

- 2D (Canvas/SVG/WebGL)
  - [_Canvas Engines Comparison_](https://github.com/slaylines/canvas-engines-comparison) 
  - [Rough.js](https://roughjs.com/) - 创建具有手绘风格的草图图形。
  - [Konva](https://konvajs.org) - 用于桌面和移动应用程序的 HTML5 2D canvas 库。
  - [Paper.js](http://paperjs.org/) - 矢量绘图工具。
  - [Pencil.js](https://pencil.js.org/) - 2D 绘图库。
  - [EaselJS](https://createjs.com) - 工具套件，包含 Canvas、Web Audio 等工具库。
  - [Fabric.js](http://fabricjs.com/) - 2D 绘图库，支持 Canvas、SVG。
  - [Two.js](https://two.js.org/) - Web 2D 绘图工具库，基于 Canvas、Svg、WebGL。
  - :point_right: React.js
    - [react-digraph](https://github.com/uber/react-digraph) - 有向图编辑器。
  - [PixiJS](https://www.pixijs.com/) - 2D WebGL 渲染引擎，高性能。

- 动画引擎（Animation Engine） 
  - Tools
    - [bezier-easing](https://github.com/gre/bezier-easing) - Cubic Bezier Curve 缓动函数的实现。
    - [Robert Penner's Easing](http://robertpenner.com/easing/) - Robert Penner's Easing Functions。
  - [tween.js](http://tweenjs.github.io/tween.js/) - 用于简单动画的 JavaScript 补间引擎。
  - [GSAP](https://greensock.com/) - 现代化的高性能动画工具库。
  - [Anime.js](https://animejs.com/) - 动画引擎，轻量的 JavaScript 动画工具库。
  - [Velocity.js](http://velocityjs.org/) - 动画引擎，为元素提供动画效果。
  - [motion](https://motion.dev/) - 轻量的，基于 [`Web Animations API`](https://developer.mozilla.org/en-US/docs/Web/API/Web_Animations_API) 的动画引擎。
  - [mo.js](https://mojs.github.io/) - 丰富，强大的运动图形动画工具库。
  - [KUTE.js](https://thednp.github.io/kute.js/) - 高性能动画引擎。
  - [Popmotion](https://popmotion.io/) - 实用、灵活的 JavaScript 动画工具套件。
    - [Framer Motion](https://www.framer.com/motion/) - 动画工具库，由 Popmotion 驱动。
  - [tween.js](https://createjs.com/tweenjs) - 动画工具库。
  - [Shifty](https://jeremyckahn.github.io/shifty/doc/index.html) - 轻量级、高性能的低级动画工具库。
  - [scene.js](https://daybrush.com/scenejs/release/latest/doc/index.html) - 支持 JavaScript 和 CSS 的动画库。

- Others
  - Text 2 Diagram
    - [mermaid](https://github.com/mermaid-js/mermaid) - txt 文本生成流程图。
    - [PlantUML](https://plantuml.com/) - 快速使用简洁的文本描述生成 UML 图。
    - [Pintora](https://pintorajs.vercel.app/) - 利用可扩展的文本绘制成图表。
    - [MathJax](https://www.mathjax.org/) - 浏览器中的数学公式可视化引擎。
  - [Textures.js](https://riccardoscalco.it/textures/) - 创建 SVG 模式。
  - [ztext.js](https://bennettfeely.com/ztext/) - 实现文字 3D 效果。
  - [P5.js](https://p5js.org/) - 可视化工具。
  - [Pts](https://ptsjs.org/) - 可视化工具。
  - [vis.js](https://visjs.org/) - 动态的，基于浏览器的可视化库。

#### 图表

*Chart library, such as line chart, column chart, etc.*

- 常规图表（Regular Chart）
  - [Chart.js](https://www.chartjs.org/) - 最流行的轻量级库。
  - [Echarts](http://echarts.apache.org/) - 国内百度团队开发，功能丰富。
  - [C3](https://c3js.org/) - 基于 D3.js 的可重用图表库。
  - [billboard.js](https://naver.github.io/billboard.js/) - 基于 D3.js 的图表库。
  - [Apexcharts](https://apexcharts.com/) - 图表库。
  - [carbon-charts](https://carbon-design-system.github.io/carbon-charts/) - 遵循 Carbon 风格，**IBM 公司发布**。
  - [roughViz](https://github.com/jwilber/roughViz) - 手绘风格图表。
  - [vizzu](https://github.com/vizzuhq/vizzu-lib) - 交互式动画图表。
  - [Frappe Charts](https://frappe.io/charts) - 基于 SVG 的高性能图表库。
  - [Charts.css](https://chartscss.org/) - CSS 图表库。
  - :point_right: React.js
    - [React-Vis](https://uber.github.io/react-vis/) - 图表库，**Uber 团队开发**。
    - [visx](https://airbnb.io/visx) - 图表库，基于 React.js 和 D3.js，**Airbnb 团队开发**。
    - [nivo](https://nivo.rocks/) - 图表库，基于 React.js 和 D3.js。
    - [Recharts](http://recharts.org/) - 图表库。
    - [React Charts](https://react-charts.js.org/) - 图表库。
    - [Victory](https://formidable.com/open-source/victory/) - 图表库。
    - [react-chartjs-2](https://github.com/reactchartjs/react-chartjs-2) - 图表库，基于 Chart.js 的图表组件。

- 关系图（Relation Chart）
  - [Cytoscape.js](https://js.cytoscape.org/) - 用于可视化和分析的图论（网络）库。

- 其它（Others）
  - [Frappe Gantt](https://frappe.io/gantt) - 甘特图。
  - [Perspective](https://perspective.finos.org/) - 基于 C++ 的 wasm 高性能数据可视化组件。
  - [Plotly](https://plotly.com/javascript/) - 丰富的图表，支持金融、科学相关图表。
  - [uPlot](https://github.com/leeoniya/uPlot) - 快速、轻量级的图表库。
  - [webdatarocks](https://www.webdatarocks.com/) - 创建透视表，**免费**。
  - [wordcloud2.js](https://github.com/timdream/wordcloud2.js) - 词云。
  - :point_right: React.js
    - [reaviz](https://github.com/reaviz) - 一系列 React 数据可视化组件。
    - [react-flow](https://reactflow.dev/) - 可视化工具库，构建流程图等。
    - [React Financial Charts](https://github.com/reactivemarkets/react-financial-charts) - 图表库，股票蜡烛图。
    - [react-calendar-heatmap](https://www.kevinqi.com/react-calendar-heatmap/) - 基于 SVG 的日历热图。

#### 动画

*Animation library, such as linear animation, inertial animation, etc.*

- CSS
  - [Animate.css](https://daneden.github.io/animate.css/) - 丰富的 CSS 动画工具库。
  - [magic.css](https://www.minimamente.com/project/magic/)  - CSS3 动画。
  - [Hover.css](http://ianlunn.github.io/Hover/) - 添加鼠标悬停动画效果。（:warning: 不再更新）
  - [CSShake](https://elrumordelaluz.github.io/csshake/) - 抖动效果。
  - [Imagehover.css](http://imagehover.io/) - 添加鼠标悬停，图片动画效果。（:warning: 不再更新）
  - [Whirl](https://whirl.netlify.app/) - CSS Loading 动画。
  - [Transition.css](https://transition.style/) - CSS 过渡动画。

- SVG
  - [vivus.js](https://github.com/maxwellito/vivus) - 为 SVG 提供动画效果。
  - [SVG.js](https://svgjs.dev/) - 轻量级 SVG 动画库。
  - [Snap.svg](http://snapsvg.io/)
  - [bonsai.js](https://bonsaijs.org/) - SVG 渲染器。
  - [lazy line painter](http://lazylinepainter.info/) - SVG 路径动画。

- JavaScript
  - [ScrollReveal](https://scrollrevealjs.org/) - 为滚动进入视区的元素提供动画效果。
  - [lax.js](https://github.com/alexfoxy/laxxx) - 简单、轻量的工具库，创建平滑的滚动动画。
  - [Typed.js](https://github.com/mattboldt/typed.js) - 打字动画效果。
  - [Typeit](https://www.typeitjs.com/) - 打字动画效果。
  - [Rough Notation](https://roughnotation.com/) - 为元素提供注释效果和动画。
  - [Rellax](https://dixonandmoe.com/rellax/) - 元素滚动视差效果工具库。
  - [simplePARALLAX.js](https://simpleparallax.com/)
  - [ts Particles](https://particles.matteobruni.it/) - 简单的粒子动画。
  - [particles.js](https://vincentgarreau.com/particles.js/) - 轻量的粒子动画库。
  - [CountUp.js](https://inorganik.github.io/countUp.js/) - 数字文本动画。
  - [granim.js](https://sarcadass.github.io/granim.js/index.html) - 创建交互式渐变动画。
  - [dom-confetti](https://github.com/daniel-lundin/dom-confetti) - 五彩纸屑动画。
  - [Canvas Confetti](https://www.kirilv.com/canvas-confetti/) - 五彩纸屑动画。
  - [Vanta.js](https://www.vantajs.com/) - 数款页面 WebGL 背景动画。

- :point_right: React.js

[`Go Top ↑`](#awesome-data-visualization-list)

