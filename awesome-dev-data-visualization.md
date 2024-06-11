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
  - [JavaScript](#javascript)
  - [Python](#python)
  - [Ruby](#ruby)
- [平台应用（Platform Application）](#平台应用)

## 参考文档

*Reference documentation.*

*see also :point_right: [计算机图形学读物](https://github.com/wang1212/awesome-favorites-list/blob/master/awesome-reading.md#%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9B%BE%E5%BD%A2%E5%AD%A6)*

_[AWESOME DATA SCIENCE](https://github.com/academic/awesome-datascience)_

- 数据可视化（Data Visualization）
  - [from Data to Viz](https://www.data-to-viz.com/) - 数据可视化决策工具。
  - [The Data Visualisation Catalogue](https://datavizcatalogue.com/) - 数据可视化目录。
  - [Google Material Design Data visualization](https://material.io/design/communication/data-visualization.html)
  - [AnyChart - Chartopedia](https://www.anychart.com/chartopedia/usage-type/) - 图表百科。
  - [Dataviz Inspiration](https://www.dataviz-inspiration.com/) - 数据可视化灵感，案例。
  - [FlowingData Tutorials](https://flowingdata.com/category/tutorials/) - 可视化向导。
  - [Visual Capitalist](https://www.visualcapitalist.com/) - 可视化经典案例。

- 文档资料（Docs）
  - [InfoVis:Wiki](https://infovis-wiki.net/wiki/Main_Page) - 信息可视化社区平台。
  - [OpenGL Wiki](https://www.khronos.org/opengl/wiki)
  - [Graphics Related Lessons](https://github.com/gfxfundamentals)
    - [WebGL Fundamentals](https://webglfundamentals.org/) - WebGL 基础知识。
    - [WebGL2 Fundamentals](https://webgl2fundamentals.org/) - WebGL2 基础知识。
    - [Three.js Fundamentals](https://threejs.org/manual/) - Three.js 基础知识。
    - [CS307: Computer Graphics](https://cs.wellesley.edu/~cs307/index.html) - 计算机图形学公开课。
  - [WebGL Guide](https://xem.github.io/articles/webgl-guide.html) - *WebGL 技术指南。*
  - [CSC8820 Advanced Graphics Algorithms](https://slideplayer.com/slide/12894894/) - 一些图形算法介绍。
  - [Discover three.js](https://discoverthreejs.com/book/) - 介绍了开始探索 3D Web 图形所需的所有重要概念和术语。
  - [High Dynamic Range Image Encodings](http://www.anyhere.com/gward/hdrenc/hdr_encodings.html)

- 公共资源（Public Resource）
  - [Shadertoy](https://www.shadertoy.com/) - 着色器代码分享。
  - [ambientCG](https://ambientcg.com/) - 公共领域基于物理渲染的资源。
  - [CGAXIS](https://cgaxis.com/) - PBR 材质、3D 模型等资源。
  - [textures.com](https://www.textures.com/) - 提供各种材质的纹理资源。
  - [Dwitter.net](https://beta.dwitter.net/) - 用简短的代码实现各种有趣的效果。

- 教程
  - [Data Science for Beginners](https://microsoft.github.io/Data-Science-For-Beginners/) - 数据科学入门，**Microsoft 发布**。

[`Go Top ↑`](#awesome-data-visualization-list)

## 工具库

*Data visualization libraries, such as chart libraries, 3D engines, etc.*

### JavaScript

#### 可视化工具

*Data visualization tool library.*

- 数据算法（Data Algorithm）
  - [Largest-Triangle-Three-Buckets(LTTB)](https://github.com/sveinn-steinarsson/flot-downsample) - 一种时间序列的数据集降采样算法。
  - [Flatbush](https://github.com/mourner/flatbush) - 2D 点空间索引算法，希尔伯特 R 树算法。
  - [The Use of Context in Pattern Recognition](https://www.bic.mni.mcgill.ca/~mallar/CS-644B/Home.html)

- 3D
  - [*A collection of WebGL and WebGPU frameworks and libraries*](https://gist.github.com/dmnsgn/76878ba6903cf15789b712464875cfdc)
  - Model Web Viewer
    - [Model Viewer](https://modelviewer.dev/)
    - [View 3D](https://naver.github.io/egjs-view3d/) - 快速且可定制的 glTF 3D 模型查看器，功能齐全。
  - Tools
    - [stackgl](http://stack.gl/) - 编写着色器代码的工具集。
    - [gl-matrix](https://glmatrix.net/) - 为 WebGL 应用提供高性能的矩阵属性运算能力。
  - [three.js](https://threejs.org/) - 3D WebGL 渲染引擎。
    - [three-stdlib](https://github.com/pmndrs/three-stdlib) - 用 TypeScript 重写的 [`threejs/examples/jsm`](https://github.com/mrdoob/three.js/tree/dev/examples/jsm) 的独立 npm 包。
    - Raycasting
      - [THREE.Interactive](https://github.com/markuslerner/THREE.Interactive) - 为 Three 对象提供基于射线检测机制的事件支持。
      - [three-mesh-bvh](https://github.com/gkjohnson/three-mesh-bvh) - BVH 实现，加速射线检测和空间查询。
    - [postprocessing](https://pmndrs.github.io/postprocessing/public/docs/) - 后处理效果工具库。
    - [meshline](https://github.com/pmndrs/meshline) - 替代 `THREE.Line` 绘制线，可设置线宽等。
    - [3D tiles](https://github.com/CesiumGS/3d-tiles/tree/main/specification)
      - [3d-tiles-renderer](https://github.com/NASA-AMMOS/3DTilesRendererJS)
      - [three-loader-3dtiles](https://github.com/nytimes/three-loader-3dtiles)
    - [three-globe](https://github.com/vasturiano/three-globe) - 3D 地球组件工具库。
    - [neat](https://neat.camberi.com/) - 3D 渐变。
  - [A-Frame](https://aframe.io/) - 构建 3D/AR/VR 应用的框架。
  - [sigma.js](http://sigmajs.org/) - 可视化大数据量的关系节点。
    - [Graphology](https://graphology.github.io/)
  - [Zdog](https://zzz.dog/) - 圆形、扁平的设计师友好的伪 3D 引擎。
  - :point_right: React.js
    - [react-three-fiber](https://docs.pmnd.rs/react-three-fiber/getting-started/introduction) - 可视化库，React.js 的 Threejs 渲染器。
    - [React Unity WebGL](https://react-unity-webgl.dev/)

- 2D (Canvas/SVG/WebGL)
  - [D3](https://d3js.org/) - 可视化库，数据驱动的，非常著名，许多图表库基于此开发。
  - [*Canvas Engines Comparison*](https://github.com/slaylines/canvas-engines-comparison)
  - [Rough.js](https://roughjs.com/) - 创建具有手绘风格的草图图形。
  - [Konva](https://konvajs.org) - 用于桌面和移动应用程序的 HTML5 2D canvas 库。
  - [Paper.js](http://paperjs.org/) - 矢量绘图工具。
  - [Pencil.js](https://pencil.js.org/) - 2D 绘图库。
  - [EaselJS](https://createjs.com) - 工具套件，包含 Canvas、Web Audio 等工具库。
  - [Fabric.js](http://fabricjs.com/) - 2D 绘图库，支持 Canvas、SVG。
  - [Two.js](https://two.js.org/) - Web 2D 绘图工具库，基于 Canvas、Svg、WebGL。
  - [PixiJS](https://www.pixijs.com/) - 2D WebGL 渲染引擎，高性能。
  - 文本处理
    - [canvas-txt](https://canvas-txt.geongeorge.com/)
    - [canvas-hypertxt](https://github.com/glideapps/canvas-hypertxt)
  - :point_right: React.js
    - [react-digraph](https://github.com/uber/react-digraph) - 有向图编辑器。
    - [uvcanvas](https://uvcanvas.com/) - 着色器动画画布。

- 动画引擎（Animation Engine）
  - Tools
    - [bezier-easing](https://github.com/gre/bezier-easing) - Cubic Bezier Curve 缓动函数的实现。
    - [Robert Penner's Easing](http://robertpenner.com/easing/) - Robert Penner's Easing Functions。
  - [tween.js](http://tweenjs.github.io/tween.js/) - 用于简单动画的 JavaScript 补间引擎。
  - [GSAP](https://greensock.com/) - 现代化的高性能动画工具库，**部分插件收费**。
  - [Anime.js](https://animejs.com/) - 动画引擎，轻量的 JavaScript 动画工具库，支持 SVG 形变动画。
  - [Velocity.js](http://velocityjs.org/) - 动画引擎，为元素提供动画效果。
  - [motion](https://motion.dev/) - 轻量的，基于 [`Web Animations API`](https://developer.mozilla.org/en-US/docs/Web/API/Web_Animations_API) 的动画引擎。
  - [KUTE.js](https://thednp.github.io/kute.js/) - 高性能动画引擎，支持 SVG 形变动画。
  - [Popmotion](https://popmotion.io/) - 实用、灵活的 JavaScript 动画工具套件。
    - [Framer Motion](https://www.framer.com/motion/) - 动画工具库，由 Popmotion 驱动。
  - [tween.js](https://createjs.com/tweenjs) - 动画工具库。（ :warning: 不再更新）
  - [Shifty](https://jeremyckahn.github.io/shifty/doc/index.html) - 轻量级、高性能的低级动画工具库。
  - [scene.js](https://daybrush.com/scenejs/release/latest/doc/index.html) - 支持 JavaScript 和 CSS 的动画库。
  - SVG
    - [vivus.js](https://github.com/maxwellito/vivus) - 为 SVG 提供动画效果。
    - [SVG.js](https://svgjs.dev/) - 轻量级 SVG 动画库。
    - [Snap.svg](http://snapsvg.io/)
    - [bonsai.js](https://bonsaijs.org/) - SVG 渲染器。
    - [lazy line painter](https://github.com/camoconnell/lazy-line-painter) - SVG 路径动画。
  - [mo.js](https://mojs.github.io/) - 丰富，强大的运动图形动画工具库。

- 游戏引擎（Game Engine）
  - [Babylon.js](https://www.babylonjs.com/) - 3D 游戏渲染引擎。
  - [Little.JS](https://killedbyapixel.github.io/LittleJS/docs/)  - 轻量级 2D 游戏渲染引擎。

- Others
  - Text 2 Diagram
    - [mermaid](https://github.com/mermaid-js/mermaid) - txt 文本生成流程图。
    - [PlantUML](https://plantuml.com/) - 快速使用简洁的文本描述生成 UML 图。
    - [Pintora](https://pintorajs.vercel.app/) - 利用可扩展的文本绘制成图表。
    - [MathJax](https://www.mathjax.org/) - 浏览器中的数学公式可视化引擎。
    - [flowchart.js](http://flowchart.js.org/) - 流程图。
    - [markmap.js](https://markmap.js.org/) - Markdown 转思维导图。
    - [Penrose](https://penrose.cs.cmu.edu/)
  - [Textures.js](https://riccardoscalco.it/textures/) - 创建 SVG 模式。
  - [ztext.js](https://bennettfeely.com/ztext/) - 实现文字 3D 效果。
  - [P5.js](https://p5js.org/) - 可视化工具。
  - [Pts](https://ptsjs.org/) - 可视化工具。
  - [vis.js](https://visjs.org/) - 动态的，基于浏览器的可视化库。
  - [Motion Canvas](https://motioncanvas.io/) - Canvas 动画视频编辑器。

#### 图表

*Chart library, such as line chart, column chart, etc.*

- 常规图表（Regular Chart）
  - Based on D3.js
    - [Plot](https://observablehq.com/plot/) - 可探索性图表库，**D3.js 官方发布**。
    - [C3](https://c3js.org/) - 基于 D3.js 的可重用图表库。
    - [billboard.js](https://naver.github.io/billboard.js/) - 基于 D3.js 的图表库。
  - [Chart.js](https://www.chartjs.org/) - 最流行的轻量级库。
  - [Echarts](http://echarts.apache.org/) - 国内百度团队开发，功能丰富。
  - [Apexcharts](https://apexcharts.com/) - 图表库。
  - [carbon-charts](https://carbon-design-system.github.io/carbon-charts/) - 遵循 Carbon 风格，**IBM 公司发布**。
  - [roughViz](https://github.com/jwilber/roughViz) - 手绘风格图表。
  - [vizzu](https://github.com/vizzuhq/vizzu-lib) - 交互式动画图表。
  - [Frappe Charts](https://frappe.io/charts) - 基于 SVG 的高性能图表库。
  - [Charts.css](https://chartscss.org/) - CSS 图表库。
  - [MetricsGraphics.js](https://github.com/metricsgraphics/metrics-graphics) - 为简洁的时间序列数据集可视化优化的图表库。
  - [Vega-Lite](https://vega.github.io/vega-lite/) - 数据分析领域的交互式图形语法。
  - :point_right: React.js
    - Based on D3.js
      - [visx](https://airbnb.io/visx) - 图表库，基于 React.js 和 D3.js，**Airbnb 团队开发**。
      - [nivo](https://nivo.rocks/) - 图表库，基于 React.js 和 D3.js。
    - [React-Vis](https://uber.github.io/react-vis/) - 图表库，**Uber 团队开发**。（ :warning: 已被弃用）
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
  - [cal-heatmap](https://cal-heatmap.com/) - 日历热图。
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
  - [Transition.css](https://transition.style/) - CSS 过渡动画。

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

### Python

#### 可视化工具

*Data visualization tool library.*

- [Matplotlib](https://matplotlib.org/stable/index.html) - 创建静态、动画、交互式可视化的综合库。
- [plot-cli](https://plot-cli.readthedocs.io/en/stable/index.html) - 命令行数据可视化工具。（ :warning: 不再更新）
- [plotext](https://pypi.org/project/plotext/) - 终端绘图可视化。
- [graph-cli](https://github.com/mcastorina/graph-cli) - 命令行工具，从 CSV 文件创建图表。
- [termgraph](https://github.com/mkaz/termgraph) - 终端绘图可视化。（ :warning: 不再更新）
- [Diagrams](https://diagrams.mingrammer.com/) - 用 Python 代码绘制架构图。
- [manim](https://github.com/ManimCommunity/manim/) - 数学动画引擎。

### Ruby

#### 可视化工具

*Data visualization tool library.*

- [YouPlot](https://github.com/red-data-tools/YouPlot) - 命令行工具，终端绘制可视化图表。

[`Go Top ↑`](#awesome-data-visualization-list)

## 平台应用

*Platform application.*

- [Tableau](https://www.tableau.com/) - 可视化分析平台，**商业软件**。
  - [Rath](https://github.com/Kanaries/Rath) - 自动化的数据探索和可视化分析平台，**开源软件**。
  - [Graphic Walker](https://docs.kanaries.net/graphic-walker) - Tableau 的开源替代品。

- [Grafana](https://grafana.com/oss/grafana/) - 数据可视化和监控解决方案，**开源软件**。

[`Go Top ↑`](#awesome-data-visualization-list)
