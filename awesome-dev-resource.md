<div align="center">
  <h1>Awesome-Development-Resources</h1>

  <p>:heart: 收藏列表 - :+1: 很棒的软件开发资源，包括软件、命令行工具等资源。</p>
  <p><i>Favorites list - great software development resources, including software, command line tools and other resources.</i></p>
</div>

<br />

_[Open Source Collective](https://opencollective.com/opensource)_

## 目录

*Resource navigation list.*

- [镜像站（Mirror Site）](#镜像站)
- [技术标准规范（Technical Standard Specification）](awesome-dev-specifications.md)
- [技术实践规范（Technical Practice Specification）](#技术实践规范)
- [技术参考文档（Technical Reference Document）](#技术参考文档)
- [技术学习（Technical Learning）](#技术学习)
  - [面试（Interview）](#面试)
  - [学习（Learn）](#学习)
  - [论坛（Forum）](#论坛)
  - [期刊（Journal）](#期刊)
- [在线资源（Online Resources）](#在线资源)
  - [在线实用工具（Online utility）](#在线实用工具)
  - [公共 API（Public API）](#公共-api)
  - [GitHub](#github)
  - [设计工具（Design Tools）](#设计工具)
  - [图像工具（Image Tools）](#图像工具)
  - [编程字体（Programming Font）](#编程字体)
  - [徽章图标服务（Badge Icon Service）](#徽章图标服务)
- [软件工具（Software Tools）](#软件工具)
  - [Chrome 扩展程序（Chrome Extension）](#chrome-扩展程序) 
  - [测试（Test）](#测试)
  - [代码编辑器/IDE（Code editor/IDE）](#代码编辑器ide)
  - [源代码管理（Source Code Management）](#源代码管理)
  - [API 文档管理（API Document Management）](#api-文档管理)
  - [服务器远程管理（Server Remote Management）](#服务器远程管理)
  - [命令行工具（Command Line Tools）](#命令行工具)
  - [WSL（Windows Subsystem for Linux）](#wsl)
  - [USB Boot](#usb-boot)
  - [实用工具（Utilities）](#实用工具)
- [工具套件（Tool kit）](#工具套件)
- [文档站点生成器（Documentation Site Generator）](#文档站点生成器)
- [更多（More）](#更多)

## 镜像站

*Mirror site, unable to visit the official site due to network restrictions.*

- All
  - [中科大源](https://mirrors.ustc.edu.cn/)
  - [清华大学源](https://mirror.tuna.tsinghua.edu.cn/)
  - [哈工大源](http://mirrors.hit.edu.cn/)
  - [阿里云源](https://developer.aliyun.com/mirror/)
  - [腾讯云源](https://mirrors.cloud.tencent.com/)
  - [网易源](https://mirrors.163.com/)

- Node.js
  - [淘宝源](https://npmmirror.com/)

- GitHub
  - [Fast Git](http://fastgit.org/)
  - [https://github.com.cnpmjs.org/](https://github.com.cnpmjs.org/) - GitHub 镜像网站。
  - [GitClone](https://gitclone.com/) - GitHub 仓库缓存加速。
  - [GitHub Proxy](https://ghproxy.com/) - 文件代理加速下载。
  - [https://d.serctl.com/](https://d.serctl.com/) - 文件代下服务。

- Others
  - [思谋学术](https://ac.scmor.com/) - 谷歌学术源。

[`Go Top ↑`](#awesome-development-resources)

## 技术实践规范

*Technical practice specification, some best engineering practices recommended by the industry.*

### 代码风格

*Code styles.*

- [SQL Style Guide](https://www.sqlstyle.guide/) - SQL 语句规范指南参考。
- [Google Style Guides](https://google.github.io/styleguide/) - Google 代码风格指南。
- [Specs vs. Tests](https://sites.google.com/site/unclebobconsultingllc/specs-vs-tests) - 如何看待测试。
- [What is Better Specs](https://www.betterspecs.org/) - 编写更好的测试。

### 项目管理

*Project management, such as version control, update logs, etc.*

- [Choose an open source license](https://choosealicense.com/) - 如何选择合适的开源许可。
- [Semantic Versioning](https://semver.org/) - 语义化版本控制。
  - [Software release life cycle](https://en.wikipedia.org/wiki/Software_release_life_cycle) - 了解软件发布的生命周期。
- [Conventional Commits](https://www.conventionalcommits.org/) - 代码提交信息格式约定推荐规范。
  - [AngularJS Commit Message Format](https://github.com/angular/angular/blob/master/CONTRIBUTING.md#-commit-message-format) - AngularJS 提交信息格式约定，可作为参考。
- [keep a changelog](https://keepachangelog.com/) - 项目内应始终存在一个 *CHANGELOG.md* 文件，并遵循一定的规范。
- [ARCHITECTURE.md](https://matklad.github.io/2021/02/06/ARCHITECTURE.md.html) - 建议在开源项目中加入 *ARCHITECTURE.md* 文件。
- [How to Build a CONTRIBUTING.md](https://mozillascience.github.io/working-open-workshop/contributing/) - 如何为开源项目构建 *CONTRIBUTING.md* 文件。
- Git Workflow
  - [Git Flow](https://nvie.com/posts/a-successful-git-branching-model/)
  - [GitLab Flow](https://docs.gitlab.com/ee/topics/gitlab_flow.html)
  - [GitHub Flow](http://githubflow.github.io/)
- [Advantages of monorepos](https://danluu.com/monorepo/) - `monorepos` 模式代码仓库的优点。

### 软件与架构设计

*Software and architecture design. See also :point_right: [Awesome Software Architecture](https://mehdihadeli.github.io/awesome-software-architecture/)*

- [https://12factor.net/](https://12factor.net/) - 开发应用的十二要素。
- [c4model](https://c4model.com/) - 用于软件架构的 C4 模型。
- [The System Design Primer](https://github.com/donnemartin/system-design-primer) - 学习构建大型系统。
- [Superhero.js](http://superherojs.com/) - 构建大型 JavaScript 项目的一些技巧。
- [Command Line Interface Guidelines](https://clig.dev/) - 命令行接口指南。
- [Awesome Software and Architectural Design Patterns](https://github.com/DovAmir/awesome-design-patterns)
- [Design Patterns for Humans](https://roadmap.sh/guides/design-patterns-for-humans) - 设计模式。

### 其它

*Others.*

- [Google Engineering Practices Documentation](https://google.github.io/eng-practices/) - Google 工程实践文档。
- [HTTP Status Codes](https://httpstatuses.com/) - HTTP 协议状态码列表。
- [devops-exercises](https://github.com/bregman-arie/devops-exercises) - DevOps 实践。
- [中文文案排版指北](https://github.com/sparanoid/chinese-copywriting-guidelines) - 技术文档翻译排版。

[`Go Top ↑`](#awesome-development-resources)

## 技术参考文档

*Some official or unofficial technical reference documents.*

- [The Book Of Secret Knowledge](https://github.com/trimstray/the-book-of-secret-knowledge) - 开发资源工具清单。
- [Developer Roadmaps](https://roadmap.sh/) - 开发者路线图。
- [4Dev.tools](https://4dev.tools/) - Web 开发人员开发资源。
- [lib4dev](http://www.lib4dev.in/) - 开源库分类查询。
- [DevDocs](https://devdocs.io/) - 在线技术文档查询。
- [Code Cheatsheets](https://devhints.io/) - 备忘清单，脚本片段。
- [Database of Database](https://dbdb.io/) - 聚合全球数据库信息。
- [Bash Pitfalls](http://mywiki.wooledge.org/BashPitfalls) - 此页面汇总了 Bash 用户常犯的编程错误。
- [COMMANDLINEFU.COM](https://www.commandlinefu.com/commands/browse) - 汇集了很多优秀的、充满智慧的、简洁的命令行命令。
- [CODELF](https://unbug.github.io/codelf/) - 根据关键词查找开源项目中变量命名。
- [Naming cheatsheet](https://github.com/kettanaito/naming-cheatsheet) - 变量命名指南。
- [OWASP Cheat Sheet Series](https://cheatsheetseries.owasp.org/) - 技术安全相关备忘单，由 OWASP 基金会维护。
- [Conflict-free Replicated Data Type](https://crdt.tech/) - 一种数据结构，可简化分布式数据存储系统和多用户应用程序。

[`Go Top ↑`](#awesome-development-resources)

## 技术学习

*Developer-related journals, articles, news, etc.*

- 免费电子书（Free Books）
  - [List of Free Learning Resources](https://ebookfoundation.github.io/free-programming-books/)
  - [Programming Notes for Professionals books](https://goalkicker.com/)

- 出版商（Publisher）
  - [Cooperpress](https://cooperpress.com/) - 计算机技术相关杂志、网站。

### 面试

*Interview.*

- [LeetCode](https://leetcode-cn.com/) - 在线笔试算法题练习。
- [牛客网](https://www.nowcoder.com/) - 在线刷题。
- [Reverse interview](https://github.com/viraptor/reverse-interview) - 面试时候可以反问的一些问题。
- [Coding Interview University](https://github.com/jwasham/coding-interview-university)
- [Tech Interview Handbook](https://techinterviewhandbook.org/)

### 学习

*Resource websites such as learning tutorials and courses.*

- [Awesome CTO](https://github.com/kuchin/awesome-cto) - 为首席技术官（CTO）准备的资源清单。
- [Hackr.io](https://hackr.io/) - 在线教程。
- [RealWorld example apps](https://github.com/gothinkster/realworld) - 不同技术栈实现相同的前后端应用示例代码。
- [build-your-own-x](https://github.com/danistefanovic/build-your-own-x) - 自己构建某种技术的教程。
- [TodoMVC](http://todomvc.com/) - 构建 MV* 应用的技术选型推荐。
- [The Art of Command Line](https://github.com/jlevy/the-art-of-command-line) - 命令行的艺术，技巧。
- [WebGL Guide](https://xem.github.io/articles/webgl-guide.html) - WebGL 技术指南。
- [WebGL Fundamentals](https://webglfundamentals.org/) - WebGL 基础知识。
- [Perfection Kills](http://perfectionkills.com/)	
- [30 seconds](https://www.30secondsofcode.org/) - 30 seconds 是一个系列，包含 JS、React.js、CSS、Git 相关的编程技巧和代码片段。

#### 算法与数据结构

*Algorithm and data structure.*

- [The Algorithms](https://the-algorithms.com/) - 学习算法和数据结构及其在多个语言中的实现。
- [VisuAlgo](https://visualgo.net/zh) - 可视化算法过程。
- [Pathfinding Visualizer](https://josephprichard.github.io/Pathfinder/) - 寻路算法可视化工具。
- [Data Structure Visualizations](https://www.cs.usfca.edu/~galles/visualization/) - 数据结构可视化。

#### 编码练习

*Some coding exercises and challenges website.*

- [Codewars](https://www.codewars.com/) - 通过挑战解决代码问题提高编码水平。

### 论坛

*Some valuable developer forum websites, Q&A communities, etc.*

- [Hacker News](https://news.ycombinator.com/) - 硅谷著名的创业孵化器机构 YC 运营的全球访问量最高的技术论坛。
- [hacker noon](https://hackernoon.com/) - 高质量技术文章发布社区。
- [Stack Overflow](https://stackoverflow.com/) - 全球程序员学习、分享，技术问答社区网站，**包含在 StackExchange 中**。
- [StackShare](https://stackshare.io/) - 全球技术趋势分享讨论。
- [DEV](https://dev.to/) - 开发者社区。
- [in Depth Dev](https://indepth.dev/) - 高级 Web 开发技术新闻。
- [Front-End Front](https://frontendfront.com/) - 前端开发人员社区。
- [CNode 社区](https://cnodejs.org/) - CNode 社区由一批热爱 Node.js 技术的工程师发起，致力于 Node.js 的技术研究。
- [Ruby China](https://ruby-china.org/) - 由众多爱好者共同维护的 Ruby 中文社区。
- [V2EX](https://v2ex.com/) - 一个汇集各类奇妙好玩的话题和流行动向的网站。
- [SegmentFault](https://segmentfault.com/) - 国内一个类似 Stack Overflow 的程序员技术学习，问答社区网站。
- [w3schools](https://www.w3schools.com/) - 国外一个非常棒的 Web 技术学习资源网站。（须翻墙）
- [w3school](http://www.w3school.com.cn/) - 国内一个仿国外 w3schools 的 Web 技术学习资源网站。
- [菜鸟教程](http://www.runoob.com/) - 国内另一个仿国外 w3schools 的 Web 技术学习资源网站。
- [掘金社区](https://juejin.im/) - 国内一个帮助开发者成长的社区，有很多优质的技术文章。
- [掘金翻译计划](https://github.com/xitu/gold-miner) - 掘金翻译计划，可能是世界最大最好的英译中技术社区，最懂读者和译者的翻译平台。
- [图灵社区](http://www.ituring.com.cn/) - 国内一个出版计算机类相关书籍的社区，外文书翻译质量非常高，拥有很好的用户口碑。
- [慕课网](https://www.imooc.com/) - 国内一个提供计算机开发技术学习课程收费服务的网站，有大量免费优质学习资源。
- [Linux 公社](https://www.linuxidc.com/) - 国内一个论坛，内有大量 Linux 相关资源。
- [PaperWeekly](http://www.paperweekly.site/) - 一个推荐、解读、讨论和报道人工智能前沿论文成果的学术平台。
- [前端资源网](http://www.fly63.com/) - Web 前端开发技术资源论坛。

### 期刊

*Some developer news journals related to industry technology trends.*

- 每日（Every day）
  - [Webdesigner News](https://www.webdesignernews.com/) - 日报，针对 Web 设计师的新闻。
  - [Echo JS](https://www.echojs.com/) - 日报，Web 前端新闻。
  - [CSS-Tricks](https://css-tricks.com/) - 日报，CSS 技术文章。
  - [Sidebar](https://sidebar.io/) - 日报，设计相关新闻。
  
- 每周（Weekly）
  - [StatusCode Weekly](https://weekly.statuscode.com/) - 周刊，软件开发、Web 技术、软件架构等。（Cooperpress 出版）
  - [Web Tools Weekly](https://webtoolsweekly.com/) - 周刊，Web 开发工具资讯。
  - [Mobile Dev Weekly](https://mobiledevweekly.com/) - 周刊，移动应用（Web 和 Native）开发技术。（Cooperpress 出版）
  - [Android Weekly](https://androidweekly.net/) - 周刊，Android 技术。
  - [Frontend Focus](https://frontendfoc.us/) - 周刊，Web 前端技术资讯。（Cooperpress 出版）
  - [Frontend Weekly](https://frontendweekly.co/) - 周刊，Web 前端技术资讯。
  - [JavaScript Weekly](https://javascriptweekly.com/) - 周刊，JavaScript 技术。（Cooperpress 出版）
  - [JSK Weekly](https://javascriptkicks.com/) - 周刊，JavaScript 技术。
  - [CSS Weekly](https://css-weekly.com/) - 周刊，CSS 技术。
  - [CSS Animation Weekly](https://cssanimation.rocks/weekly/) - 周刊，CSS 动画。
  - [React Status](https://react.statuscode.com/) - 周刊，React.js 相关技术。（Cooperpress 出版）
  - [Node Weekly](https://nodeweekly.com/) - 周刊，Node.js 技术。（Cooperpress 出版）
  - [npm Weekly](https://www.npmjs.com/npm-weekly) - 周刊，npm 新闻，**npm 官方**。（:warning: 停止更新）
  - [Deno Weekly](https://denoweekly.com/) - 周刊，Deno 技术。（Cooperpress 出版）
  - [Ruby Weekly](https://rubyweekly.com/) - 周刊，Ruby 技术。（Cooperpress 出版）
  - [PyCoder’s Weekly](https://pycoders.com/) - 周刊，Python 技术。
  - [Golang Weekly](https://golangweekly.com/) - 周刊，Go 技术。（Cooperpress 出版）
  - [DB Weekly](https://dbweekly.com/) - 周刊，数据库技术。（Cooperpress 出版）
  - [Postgres Weekly](https://postgresweekly.com/) - 周刊，PostgreSQL 技术。（Cooperpress 出版）
  - [Serverless Status](https://serverless.email/) - 周刊，Serverless 和 FaaS 相关技术。（Cooperpress 出版）
  - [iOS Dev Weekly](https://iosdevweekly.com/) - 周刊，iOS 开发者相关。
  - [Smashing Magazine](https://www.smashingmagazine.com/) - 周刊，Web 前端与 UX 资讯。
  - [科技爱好者周刊](https://github.com/ruanyf/weekly)
  - [Awesome Weekly](https://github.com/jondot/awesome-weekly) - 更多周刊。

- 每月（Monthly）
  - [The Deep Dive](https://indepth.dev/newsletter) - 月刊，一月两次，高级 Web 开发技术。

- 半年（Half a year）
  - [Technology Radar](https://www.thoughtworks.com/radar) - 六个月一期，[ThoughtWorks](https://www.thoughtworks.com/) 出品的技术雷达。

- 其它（Others）
  - [MongoDB Memo](https://mongodb.email/) - MongoDB 新闻。（Cooperpress 出版）

[`Go Top ↑`](#awesome-development-resources)

## 在线资源

*Online Resources.*

_see also 👉  [Web 端软件资源](./awesome-software.md#浏览器端)_

### 在线实用工具

*Online utils tools.*

- [HTTP Archive](https://httparchive.org/) - Web 站点跟踪测试。
- [free-for.dev](https://free-for.dev/) - 软件开发人员可用的免费 SaaS、PaaS、IaaS 等服务。

- Toolset
  - [URL Encoder](https://www.urlencoder.org/) - URL 编解码，以及一系列小工具。
  - [SOCODE.PRO](https://socode.pro/) - 快速搜索开发文档，小工具等，**提供浏览器插件**。
  - [345Tool](https://www.345tool.com/) - 开发者工具集。
  - [tool.lu](https://tool.lu/) - 开发者工具集。  
  - [toolb.dev](https://www.toolb.dev/)
  - [Carbon](https://carbon.now.sh/) - 生成漂亮的源代码图片。
  - [FastIcon](https://fasticon.sawirstudio.com/) - 在线快速生成 Android 与 IOS 应用图标。
  - [Understand your dependencies](https://deps.dev/) - 在线分析开源模块，了解依赖代码的安全性、许可证等信息，**Google Cloud 提供**。
  - [What's that site running?](https://sitereport.netcraft.com/) - 探测一个网站背后的基础设施信息。

- HTTP/IP/DNS
  - [IPAddress](https://www.ipaddress.com/) - 在线查询某个站点的 IP 地址。
  - [Resolve.rs](https://resolve.rs/tools.html) - 查询本机 IP、DNS 服务器等。
  - [FreeSSL](https://freessl.org/) - 免费 SSL 证书在线申请。
  - [IKnowWhatYouDownload](https://iknowwhatyoudownload.com/) - 查看 IP 下载过的 BT 资源。

- Service
  - [Web-Scale UUID as a Service](https://uuid.rocks/) - 在线生成 uuid。  

- Checker
  - [ShellCheck](https://www.shellcheck.net/) - shell 脚本 bug 检查工具。（支持本地安装）
  - [Diffchecker](https://www.diffchecker.com/) - 在线文本、图片差异比较工具。

- Regular Expression
  - [regex101](https://regex101.com/) - 在线正则调试工具。
  - [RegEx Pal Tester](https://www.regexpal.com/)
  - [iHateRegex](https://ihateregex.io/)
  - [regexr](https://regexr.com/)

### 公共 API

*Public api.*

- [OpenWeather](https://openweathermap.org/) - 全球城市天气预报。
- [Public APIs](https://github.com/public-apis/public-apis) - 免费的公共 API 集合。
- [Administrative-divisions-of-China](https://github.com/modood/Administrative-divisions-of-China) - 中华人民共和国行政区划（五级）名称数据。

### 设计工具

*Design Tools.*

- [Code My UI](https://codemyui.com/) - Web UI 设计相关的代码片段。

### 图像工具

*Image tool.*

#### 占位图像服务

*Placeholder image service.*

- [Placeholder.com](https://placeholder.com/) - 图片、灰度图、文本。
- [Fake images please?](https://fakeimg.pl/) - 灰度图、文本，**免费开源**。
- [Dynamic Dummy Image Generator](https://dummyimage.com/) - 灰度图、文本。
- [Lorem Picsum](https://picsum.photos/) - 图片。
- [PlaceIMG](https://placeimg.com/) - 图片。
- [Ipsum Image](https://ipsumimage.appspot.com/) - 灰度图、文本。

### 编程字体

*Monospaced Font.*

- [Dev Fonts](https://devfonts.gafi.dev/) - 编程字体对比。
- [Programming Fonts](https://www.programmingfonts.org/) - 编程字体对比。
- [Nerd Fonts](https://www.nerdfonts.com/) - 开发人员使用的标志性图标和字体集合。
- [Powerline fonts](https://github.com/powerline/fonts)
- [Source Code Pro](https://github.com/adobe-fonts/source-code-pro) - 等宽字体，适合编程使用，**Adobe 出品，开源**。
- [JetBrains Mono](https://www.jetbrains.com/lp/mono/) - 等宽字体，适合编程使用，**JetBrains 出品，开源**。
- [CodingFont](https://www.codingfont.com/) - 根据测试选择适合自己的编程字体。

### 徽章图标服务

*Badge icon service.*

- [Shields.IO](https://shields.io/)
- [NodeICO](https://nodei.co/)
- [Badgen](https://badgen.net/)
- [Version Badge](https://badge.fury.io/)
- [Badges](https://formidable.com/open-source/badges/)
- [GitHub Readme Stats](https://github.com/anuraghazra/github-readme-stats) - 显示 GitHub 仓库统计信息。
- [GitHub Stats Visualization](https://github.com/jstrieb/github-stats)
- [Star Charts](https://starchart.cc/) - GitHub 星数量趋势图。
- [Git Awards](http://git-awards.com/) - Git 用户仓库统计排名信息。
- [Markdown Badges](https://github.com/Ileriayo/markdown-badges)

[`Go Top ↑`](#awesome-development-resources)

## 软件工具

*Software tools.*

### Chrome 扩展程序

*Chrome extension.*

- `Lighthouse` - 站点性能监测工具，可提供优化建议和报告，**官方扩展**。
- [Wappalyzer](https://chrome.google.com/webstore/detail/wappalyzer/gppongmhjkpfnbhagpmjfkannfbllamg) - 检测当前站点所使用到的 Web 开发技术，包括框架、库、服务器、编程语言等。
- [WhatRuns](https://chrome.google.com/webstore/detail/whatruns/cmkdbmfndkfgebldhnkbfhlneefdaaip) - 同上。
- [WhatFont](https://chrome.google.com/webstore/detail/whatfont/jabopobgcpjmedljpbcaablpmlmfcogm) - 检测网站中所使用到的字体。
- [JSON-handle](https://chrome.google.com/webstore/detail/json-handle/iahnhfdhidomcpggpaimmmahffihkfnj) - JSON 文档的浏览器和编辑器。
- [CSS Peeper](https://chrome.google.com/webstore/detail/css-peeper/mbnbehikldjhnfehhnaidhjhoofhpehk) - 页面 CSS 调试工具。
- [Headless Recorder](https://chrome.google.com/webstore/detail/headless-recorder/djeegiggegleadkkbgopoonhjimgehda) - 录制页面交互，生成 JS 无头脚本代码。
- Enhance the function of github. *(see also 👉 https://github.com/stefanbuck/awesome-browser-extensions-for-github)*
  - [Sourcegraph](https://about.sourcegraph.com/) - 代码搜索工具，提供源代码快速搜索，智能代码提示，代码审查等功能。
  - [Refined GitHub](https://github.com/sindresorhus/refined-github) - 增强 GitHub 网站界面功能，在许多细节方面做了改进。
  - [Octotree](https://www.octotree.io/) - 生成代码文件树，方便浏览仓库文件。
  - [OctoLinker](https://octolinker.now.sh/) - 源代码中引用的依赖包信息预览，例如 `import`, `require` 语句。
  - [File Icons for GitHub and GitLab](https://github.com/homerchen19/github-file-icons) - 为 GitHub、Gitlab、Bitbucket、gitea 和 gogs 网站提供不同类型文件的图标。
  - [Enhanced Github](https://github.com/softvar/enhanced-github) - 增强 GitHub 网站界面功能，显示仓库大小、每个文件的大小、下载链接和复制文件内容的按钮等。
  - [ZenHub for GitHub](https://github.com/marketplace/zenhub) - GitHub 项目管理工具。
  - [GitHub Dark](https://github.com/StylishThemes/GitHub-Dark) - GitHub 网站界面黑夜模式。
  - [GitHub Hovercard](https://justineo.github.io/github-hovercard/) - 悬浮卡片。
- [CodeCopy](https://github.com/zenorocha/codecopy) - 为网站上的代码块提供复制到粘贴板按钮。
- [daily.dev | The Homepage Developers Deserve](https://daily.dev/) - 开发者新闻汇总。

### 测试

*Various testing tools.*

- HTTP 基准测试（Benchmarks）
  - [*HTTP(S) Benchmark Tools*](https://github.com/denji/awesome-http-benchmark#https-benchmark-tools) - *HTTP 基准测试工具集。*
  - [*Web Frameworks Benchmark*](https://web-frameworks-benchmark.netlify.app/) - *Web 框架的公开基准测试，仅供参考。*

### 代码编辑器/IDE 

*Open source free IDE editor, and some commercial paid IDE.*

#### 在线编辑器（Online Editor）

- [StackBlitz](https://stackblitz.com/)
- [JSON Editor Online](http://jsoneditoronline.org/) - 在线 JSON 编辑器。
- [CodeTable](https://code.hackerearth.com/)
- [JDoodle](https://www.jdoodle.com/)
- [IdeOne](https://ideone.com/)
- [OnlineGDB](https://www.onlinegdb.com/)
- [Monaco Editor](https://microsoft.github.io/monaco-editor/)

#### 桌面端（Desktop Editor）

- [Notepad++](https://notepad-plus-plus.org/) - 一款轻量级的文本编辑器，**开源软件**。
- [VS Code](https://code.visualstudio.com/) - 一款轻量级开发工具，功能很强大，深受开发者的青睐，是 Web 前端开发者的工作利器，**开源软件**。
  - [VSCodium](https://vscodium.com/) - 社区驱动、免费许可的 VS Code 版本。
  - [Create Your Own VS Code Themes](https://themes.vscode.one/) - 创建 VS Code 主题。
- [Sublime Text](http://www.sublimetext.com/) - 一款开源的轻量级编辑器，功能很强大，是在 VS Code、Atom 出现之前最受开发者欢迎的编辑器。
- [Eclipse](https://www.eclipse.org/) - 开源的重量级编辑器，功能非常强大，是 Java 开发者中使用最多的 IDE，**开源软件**。
- [UltraEdit](https://www.ultraedit.com/) - 文本编辑器，功能强大，性能较好，**商业软件**。
- [EmEditor](https://www.emeditor.com/) - 文本编辑器，功能强大，浏览大文件性能很好，**商业软件**。

#### 代码格式化

*Code formatting.*

- [Prettier](https://prettier.io/)
- [EditorConfig](https://editorconfig.org/)

### 编码统计

_Coding Statistics._

- [WakaTime](https://wakatime.com/)
  - [wakapi](https://wakapi.dev/) - 自托管服务，**开源免费**。
  - [hakatime](https://github.com/mujx/hakatime) - 自托管服务，**开源**。

- [Code Time](https://app.software.com/)

### 源代码管理

*Source code version management system and building tools.*

- [Git](https://git-scm.com/) - 目前最受欢迎的，使用最广泛的分布式源代码版本控制工具。
  - [Resources to learn Git](http://try.github.io/) - 学习 Git 的文档。
  - [Git Explorer](https://gitexplorer.com/) - Git 命令参考。
  - [Learn Git Branching](https://learngitbranching.js.org/) - 在线 Git 命令互动式学习。
  - [A collection of .gitignore templates](https://github.com/github/gitignore) - 不同类型项目的 `.gitignore` 文件模板。
    - [gitignore.io](https://www.toptal.com/developers/gitignore) - 根据关键词生成 `.gitignore` 文件模板。
  - [Sourcetree](https://www.sourcetreeapp.com/) - 免费的 Git 客户端，支持 Windows 和 Mac。
  - [git-open](https://github.com/paulirish/git-open) - git 命令行工具，可直接在浏览器中打开仓库页面。
  - [gitmoji](https://gitmoji.dev/) - Git 提交信息中的 emoji 表情。

- [Tortoise SVN](https://tortoisesvn.net/) - SVN 是一种传统的中心化管理的源代码版本控制工具，Tortoise SVN 提供了 GUI 来使用 SVN。

- 公共代码托管平台（Public code hosting platform）
  - [GitHub](https://github.com/)
    - [github1s](https://github.com/conwnet/github1s) - 可直接在浏览器的 VS Code 中打开 GitHub 仓库代码。
  - [GitLab](https://about.gitlab.com/) - 支持本地部署。
  - [Bitbucket](https://bitbucket.org/)
  - [Gitee](https://gitee.com/) - 码云，国内[开源中国](https://www.oschina.net/)推出。
  - [Coding](https://coding.net/) - 目前由腾讯入股，体验相比刚开始变差，不建议使用。

- 自托管 Git 服务（Self-hosted Git service）
  - [Gitea](https://gitea.io/) - 本地部署，**开源项目**。
  - [Gogs](https://gogs.io/) - 本地部署，**开源项目**。

### API 文档管理

*API document management and testing.*

- [Postman](https://www.getpostman.com/) - 一个非常棒的 API 管理工具。
- [Insomnia](https://insomnia.rest/) - API 接口测试工具。
- [hoppscotch](https://hoppscotch.io/) - API 接口测试、管理，**开源软件**。

### 服务器远程管理

*Server remote management tools, such as SSH client, etc.*

- Windows
  - [WinSCP](https://winscp.net/) - 使用 SSH 的图形化 SFTP 客户端，同时支持 SCP 协议，用于远程文件传输，**开源免费**。
  - [PuTTY](https://www.putty.org/) - 一个集 Telnet、SSH、rlogin、纯 TCP 以及串行接口连接软件，配合 WinSCP 可以很好的远程管理 Linux 服务器，也支持 Unix 平台，**开源免费**。
  - [Bitvise SSH Client](https://www.bitvise.com/ssh-client) - SSH 文件传输、终端、隧道，**免费软件**。

- Linux/Unix

### 命令行工具

*Command line tools.*

#### Windows

*Used on Windows platform.*

- [Git Bash](https://gitforwindows.org/)
- [MSYS2](https://www.msys2.org/) - 基于 Cygwin 和 MinGW-w64 对 MSYS 的重写，支持 Bash、Git 等更多特性。
- [MinGW](http://www.mingw.org/) - Minimalist GNU for Windows，不支持 POSIX。
- [Cygwin](http://www.cygwin.com/) - GNU 和开源工具的集合，支持 POSIX。
- [ConEmu](https://conemu.github.io/)
- [Clink](https://mridgers.github.io/clink/)
- [hyper](https://hyper.is/)
- [Cmder](https://cmder.net/) - 基于 ConEmu 和 Clink 特性，采用 Monokai 颜色主题，支持 Git 等。
- [Far Manager](https://www.farmanager.com/) - Windows 系统纯文本的文件管理器。

#### Linux

*Used on Linux platform.*

- [Modern Unix](https://github.com/ibraheemdev/modern-unix) - 常见 Unix 命令更好的替代品。
  - [tldr](https://tldr.sh/) - 类似于 `man` 命令，简化版的命令手册文档。
  - [htop](https://htop.dev/) - 类似于 `top` 命令，交互式进程浏览器。
  - [exa](https://the.exa.website/) - 类似于 `ls` 命令。
  - [fd](https://github.com/sharkdp/fd) -  类似于 `find` 命令，更简单好用。
  - [bat](https://github.com/sharkdp/bat) - 类似于 `cat` 命令，支持语法高亮等特性。
  - [ripgrep ](https://github.com/BurntSushi/ripgrep) - 类似于 `grep` 命令。
  - [duf](https://github.com/muesli/duf) - 类似于 `df` 命令，查看硬盘使用情况的工具，支持多个平台。

- [Bash](https://www.gnu.org/software/bash/)
  - [bash-it](https://bash-it.readthedocs.io/) - bash 工具集，提供主题等功能，类似 on-my-zsh。
  - [oh-my-bash](https://github.com/ohmybash/oh-my-bash)

- [Z-Shell](https://www.zsh.org/)
  - [on-my-zsh](https://ohmyz.sh/) - 管理 Z-Shell 配置的框架。

- [The Fuck](https://github.com/nvbn/thefuck) - 命令行错误命令纠正工具（多平台支持）。
- [screenFetch](https://github.com/KittyKatt/screenFetch) - 显示系统详细信息。
- [Glances](https://nicolargo.github.io/glances/) - 系统性能指标监控工具（多平台支持）。
- [ncdu](https://dev.yorhel.nl/ncdu) - 磁盘使用情况统计。
- [fzf](https://github.com/junegunn/fzf) - 模糊查找器。
- [sslh](https://github.com/yrutschle/sslh) - 实现端口复用。
- [BusyBox](https://www.busybox.net/) - 实用的 Linux 命令集合。

#### 其它

*Others.*

- [glow](https://github.com/charmbracelet/glow) - 在命令行渲染 Markdown 文档。
- [Certbot](https://certbot.eff.org/) - 管理 [Let's Encrypt](https://letsencrypt.org/) 证书工具，为网站启用 HTTPS，**开源软件**。
- [FFmpeg](http://ffmpeg.org/) - 命令行工具，完整的、跨平台的解决方案，用于记录、转换和流传输音频和视频，**开源软件**。
- [aria2](https://aria2.github.io/) - 支持多协议、高速文件下载工具，**开源软件**。
- [PhotoRec](https://www.cgsecurity.org/wiki/PhotoRec) - 文件数据恢复软件，**开源软件**。
- [gron](https://github.com/tomnomnom/gron) - 使 JSON 数据更易读，**开源软件**。
- [fx](https://github.com/antonmedv/fx) - 命令行 JSON 处理工具，**开源软件**。
- [gping](https://github.com/orf/gping) - 图形化 `ping` 命令结果。
- [tcping](https://elifulkerson.com/projects/tcping.php) - 类似 `ping` 命令，使用 TCP 端口。
- [subfinder](https://github.com/projectdiscovery/subfinder) - 查找子域名。
- [dog](https://dns.lookup.dog/) - 命令行 DNS 客户端。
- [nativefier](https://github.com/nativefier/nativefier) - 可将 Web 网站转换成本地应用。

### WSL

*[Windows Subsystem for Linux](https://docs.microsoft.com/en-us/windows/wsl/) resources.*

- [wsl2-hacks - Updated for Ubuntu 20.04 / 20.10](https://github.com/shayne/wsl2-hacks) - 一些针对 Ubuntu 20.04 / 20.10 的技巧。
- [LxRunOffline](https://github.com/DDoSolitary/LxRunOffline) - 用于管理适用于 Linux 的 Windows 子系统 (WSL) 的全功能实用程序。
- [WSL2Proxy](https://github.com/wizcas/wsl2proxy) - 配置网络代理的脚本。
- [go-wsl2-host](https://github.com/shayne/go-wsl2-host)

### USB Boot

*Make USB boot disk, maintain PE system.*

- [Rufus](https://rufus.ie/)
- [WePE](http://www.wepe.com.cn/) - Windows PE 系统。
- Linux
  - [Universal USB Installer](https://www.pendrivelinux.com/universal-usb-installer-easy-as-1-2-3/) - 可在 U 盘中安装 Linux 操作系统。
  - [Multiboot USB Creator](https://www.pendrivelinux.com/yumi-multiboot-usb-creator/) - 可在 U 盘中**同时安装多个** Linux 发行版本。
  - [UNetbootin](http://unetbootin.github.io/) - 制作 Linux Live USB。
  - [Etcher](https://www.balena.io/etcher) - 制作 Linux Live USB。
  - [LF](https://github.com/gokcehan/lf) - 终端文件管理工具命令包。

### 实用工具

*Utils tools.*

- 幻灯片（Slideshow）
  - [Cleaver](http://jdan.github.io/cleaver/) - Markdown 文件生成幻灯片。
  - [nodeppt](https://github.com/ksky521/nodeppt) - Markdown 文件生成幻灯片。
  - [reveal.js](https://revealjs.com/)
  - [Slidev](https://sli.dev/)

[`Go Top ↑`](#awesome-development-resources)

## 工具套件

*Tool kit.*

- [free-for.dev](https://free-for.dev/) - **免费**的开发资源服务列表。
- [Cube.js](https://cube.dev/) - **开源**的 Web 应用分析解决方案。
- [Counter](https://counter.dev/) - **开源免费**的 Web 站点统计分析平台。
- [Splitbee](https://splitbee.io/) - Web 站点分析统计平台，个人项目免费。
- [Ackee](https://ackee.electerious.com/) **开源**的可自托管的站点分析工具。
- [screego](https://screego.net/#/) - 屏幕共享服务器。
- [hoppscotch](https://hoppscotch.io/) - 在线的 http 客户端工具。
- [netdata](https://www.netdata.cloud/) - 系统指标监控 Web 平台，**开源免费**。
- [Skia](https://skia.org/) - 2D 渲染引擎，在 Chrome、Chrome OS、Android、Flutter、Mozilla Firefox 等产品中使用。
- [nocodb](https://www.nocodb.com/) - NoCode 平台，将任何数据库转换为电子表格，**开源软件**。
- [Talk](https://github.com/vasanthv/talk) - 点对点的 Web 视频会议和屏幕共享应用，**开源软件**。
- [nb](https://xwmx.github.io/nb/) - 命令行和本地 Web 笔记、文档管理、检索应用程序。
- [Web File Browser](https://filebrowser.org/) - 基于 Web 的云文件浏览器。

- 抓包工具
  - [WireShark](https://www.wireshark.org/) - 协议分析，**开源免费**。
  - [Fiddler Everywhere](https://www.telerik.com/fiddler) - **提供免费版本**。
  - [mitmproxy](https://www.mitmproxy.org/) - Python 开发的 HTTPS 代理，**开源免费**。
  - [whistle](https://wproxy.org/whistle/)

[`Go Top ↑`](#awesome-development-resources)

## 文档站点生成器

*Documentation Site Generator.*

- [Docusaurus](https://v2.docusaurus.io/) - 快速构建优化、快速的网站，**Facebook 发布**。
- [docsify](https://docsify.js.org/) - 一个神奇的文档站点生成器。
- [MkDocs](https://www.mkdocs.org/)
- [GitBook](https://www.gitbook.com/)

[`Go Top ↑`](#awesome-development-resources)

## 更多

*More uncategorized resources.*

- [Openbase](https://openbase.com/) - 开源项目讨论及评奖。
- [LibHunt](https://www.libhunt.com/) - 收集了各种库的网站。
- [TIOBE Index](https://www.tiobe.com/tiobe-index/) - 编程语言全球排名。
- [DB-Engines](https://db-engines.com/) - 数据库排名信息。
- [Learn Anything](https://learn-anything.xyz/) - 知识路径图谱。

[`Go Top ↑`](#awesome-development-resources)
