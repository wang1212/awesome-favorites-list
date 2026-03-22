<div align="center">
  <h1>Awesome-Development-Resources</h1>

  <p>:heart: 收藏列表 - :+1: 很棒的软件开发资源，包括软件、命令行工具等资源。</p>
  <p><i>Favorites list - great software development resources, including software, command line tools and other resources.</i></p>
</div>

<br />

[_opensource.com_](https://opensource.com/)

[_The Book Of Secret Knowledge_](https://github.com/trimstray/the-book-of-secret-knowledge)

## 目录

*Resource navigation list.*

- [镜像站（Mirror Site）](#镜像站)
- [技术标准规范（Technical Standard Specification）](awesome-dev-specifications.md)
- [技术实践规范（Technical Practice Specification）](#技术实践规范)
  - [代码风格（Code Style）](#代码风格)
  - [项目管理（Project Management）](#项目管理)
  - [软件与架构设计（Software and Architecture Design）](#软件与架构设计)
- [技术参考资源（Technical Reference Resources）](#技术参考资源)
  - [统计信息（Statistics）](#统计信息)
  - [技术文档（Technical Documentation）](#技术文档)
  - [算法与数据结构（Algorithms and Data Structures）](#算法与数据结构)
  - [编码技巧（Coding Skills）](#编码技巧)
- [社区论坛（Community Forum）](#社区论坛)
- [技术期刊（Technical Journal）](#技术期刊)
  - [技术博客（Technical Blog）](#技术博客)
- [在线资源（Online Resources）](#在线资源)
  - [在线实用工具（Online utility）](#在线实用工具)
  - [公共 API（Public API）](#公共-api)
  - [编程字体（Programming Font）](#编程字体)
  - [徽章图标服务（Badge Icon Service）](#徽章图标服务)
- [AI 编程工具（AI Native Programming Tools）](#ai-编程工具)
- [软件工具（Software Tools）](#软件工具)
  - [Emoji :smile:](#emoji)
  - [Chrome 扩展程序（Chrome Extension）](#chrome-扩展程序)
  - [测试（Test）](#测试)
  - [代码编辑器/IDE（Code editor/IDE）](#代码编辑器ide)
  - [源代码管理（Source Code Management）](#源代码管理)
  - [API 文档管理（API Document Management）](#api-文档管理)
  - [服务器远程管理（Server Remote Management）](#服务器远程管理)
  - [命令行工具（Command Line Tools）](#命令行工具)
  - [WSL（Windows Subsystem for Linux）](#wsl)
  - [实用工具（Utilities）](#实用工具)
- [工具套件（Tool kit）](#工具套件)
- [面试指南（Interview Guidelines）](#面试指南)
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
  - [http://hub.fgit.ml/](http://hub.fgit.ml/)
  - [https://github.com.cnpmjs.org/](https://github.com.cnpmjs.org/) - GitHub 镜像网站。
  - [GitClone](https://gitclone.com/) - GitHub 仓库缓存加速。
  - [GitHub Proxy](https://ghproxy.com/) - 文件代理加速下载。
  - [https://d.serctl.com/](https://d.serctl.com/) - 文件代下服务。
  - [GitHub & BitBucket HTML Preview](https://github.com/htmlpreview/htmlpreview.github.com) - 静态资源预览代理。
  - [FastGithub](https://github.com/dotnetcore/FastGithub) - 加速工具。

- Others
  - [思谋学术](https://ac.scmor.com/) - 谷歌学术源。
  - [Watt Toolkit](https://steampp.net/) - Steam 游戏加速，可加速 Github。

- Tools
  - [chsrc](https://github.com/RubyMetric/chsrc) - 换源工具。
  - [Xget](https://github.com/xixu-me/Xget) - 资源加速。

[`Go Top ↑`](#awesome-development-resources)

## 技术实践规范

*Technical practice specification, some best engineering practices recommended by the industry.*

### 代码风格

*Code styles.*

- [SQL Style Guide](https://www.sqlstyle.guide/) - SQL 语句规范指南参考。
- [Google Style Guides](https://google.github.io/styleguide/) - Google 代码风格指南。
- [Specs vs. Tests](https://sites.google.com/site/unclebobconsultingllc/specs-vs-tests) - 如何看待测试。
- [What is Better Specs](https://www.betterspecs.org/) - 编写更好的测试。
- 命名（Naming）
  - [_CODELF_](https://unbug.github.io/codelf/) - 根据关键词查找开源项目中变量命名。
  - [Naming cheatsheet](https://github.com/kettanaito/naming-cheatsheet) - 变量命名指南。
  - [classnames](https://classnames.paulrobertlloyd.com/)

### 项目管理

*Project management, such as version control, update logs, etc.*

- [Choose an open source license](https://choosealicense.com/) - 选择合适的开源许可。
  - [Creative Commons](https://creativecommons.org/choose/) - 知识共享协议许可。
- [About READMEs](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes) - 项目自述文档。
  - [Make a README](https://www.makeareadme.com/)
- [Diátaxis](https://diataxis.fr/) - 技术文档编写指南。
- [ARCHITECTURE.md](https://matklad.github.io/2021/02/06/ARCHITECTURE.md.html) - 建议在开源项目中加入 _ARCHITECTURE.md_ 文件。
- [Contributor Covenant](https://www.contributor-covenant.org/) - 贡献者契约，开源社区的行为准则声明。
- [How to Build a CONTRIBUTING.md](https://mozillascience.github.io/working-open-workshop/contributing/) - 如何为开源项目构建 _CONTRIBUTING.md_ 文件。
- Git Workflow
  - [Git Flow](https://nvie.com/posts/a-successful-git-branching-model/)
  - [GitLab Flow](https://docs.gitlab.com/ee/topics/gitlab_flow.html)
  - [GitHub Flow](http://githubflow.github.io/)
- [Conventional Commits](https://www.conventionalcommits.org/) - 代码提交信息格式约定推荐规范。
  - [AngularJS Commit Message Format](https://github.com/angular/angular/blob/master/CONTRIBUTING.md#-commit-message-format) - AngularJS 提交信息格式约定，可作为参考。
- [Software release life cycle](https://en.wikipedia.org/wiki/Software_release_life_cycle) - 软件发布的生命周期。
  - [Semantic Versioning](https://semver.org/) - 语义化版本控制。
  - [keep a changelog](https://keepachangelog.com/) - 项目内应始终存在一个 _CHANGELOG.md_ 文件，并遵循一定的规范。
- [Advantages of monorepos](https://danluu.com/monorepo/) - `monorepos` 模式代码仓库的优点。
  - [monorepo.tools](https://monorepo.tools/)

### 软件与架构设计

*Software and architecture design. See also :point_right: [软件架构设计书籍](https://github.com/wang1212/awesome-favorites-list/blob/master/awesome-reading.md#%E8%BD%AF%E4%BB%B6%E6%9E%B6%E6%9E%84%E8%AE%BE%E8%AE%A1)*

- 设计模式（Design Patterns）
  - [Awesome Software and Architectural Design Patterns](https://github.com/DovAmir/awesome-design-patterns)
  - [Design Patterns for Humans](https://roadmap.sh/guides/design-patterns-for-humans) - 设计模式。
  - [Refactoring.Guru](https://refactoring.guru/) - 图文结合讲解软件工程、设计模式的知识。
  - [Software Design and Architectural Patterns](http://software-pattern.org/)

- 系统架构（System Architecture Design）
  - [Developer to Architect](https://developertoarchitect.com/)
  - [Awesome Software Architecture](https://mehdihadeli.github.io/awesome-software-architecture/)
  - [awesome-scalability](https://github.com/binhnguyennus/awesome-scalability) - 可伸缩、可扩展系统设计实践。
  - [The System Design Primer](https://github.com/donnemartin/system-design-primer) - 学习构建大型系统。
  - [System Design 101](https://github.com/ByteByteGoHq/system-design-101) - 用图表展示系统架构设计，**ByteByteGo 出品**。
  - [System Design Cheatsheet](https://gist.github.com/vasanthk/485d1c25737e8e72759f) - 系统设计备忘单。
  - [system-design](https://github.com/systemdesign42/system-design)

- 其它（Others）
  - [https://12factor.net/](https://12factor.net/) - 开发应用的十二要素。
  - [c4model](https://c4model.com/) - 用于软件架构的 C4 模型。
  - [Superhero.js](http://superherojs.com/) - 构建大型 JavaScript 项目的一些技巧。
  - [Command Line Interface Guidelines](https://clig.dev/) - 命令行接口指南。
  - [Awesome Diagramming](https://github.com/shubhamgrg04/awesome-diagramming) - 可用来画架构图的一些图表工具。
  - [Guidelines](https://vercel.com/design/guidelines) - UI 设计指南，**Vercel 发布**。

### 其它

*Others.*

- [The Turing Way](https://the-turing-way.netlify.app/) - 一本描述开源社区如何协作的开源书籍。
  - [Open Source Guides](https://opensource.guide/) - 开源指南。
  - [The open source way](https://opensource.com/open-source-way)
- [Google Engineering Practices Documentation](https://google.github.io/eng-practices/) - Google 工程实践文档。
- [devops-resources](https://github.com/bregman-arie/devops-resources) - DevOps 资源。
  - [devops-exercises](https://github.com/bregman-arie/devops-exercises)
- [中文文案排版指北](https://github.com/sparanoid/chinese-copywriting-guidelines) - 技术文档翻译排版。

[`Go Top ↑`](#awesome-development-resources)

## 技术参考资源

_Some technical reference resources._

- [Awesome CTO](https://github.com/kuchin/awesome-cto) - 为首席技术官（CTO）准备的资源清单。
- [Developer Roadmaps](https://roadmap.sh/) - 开发者路线图。
- [build-your-own-x](https://github.com/danistefanovic/build-your-own-x) - 构建某种技术的技术资料。
- [RealWorld example apps](https://github.com/gothinkster/realworld) - 不同技术栈实现相同的前后端应用示例代码。
- [TodoMVC](http://todomvc.com/) - 构建 MV* 应用的技术选型推荐。
- [Interactive tutorial](https://www.learnshell.org/about) - 交互式教程。

### 统计信息

_Statistics._

- [TIOBE Index](https://www.tiobe.com/tiobe-index/) - 编程语言全球排名。
- [DB-Engines](https://db-engines.com/) - 数据库排名信息。
- [Database of Database](https://dbdb.io/) - 聚合全球数据库信息。
- Open Source Project Discovery
  - [Openbase](https://openbase.com/) - 开源项目讨论及评奖。
  - [LibHunt](https://www.libhunt.com/) - 收集了各种库的网站。
  - [Open Hub](https://www.openhub.net/)
- [GitHub Innovation Graph](https://innovationgraph.github.com/) - GitHub 全球统计数据趋势。

### 技术文档

_Technical documentation._

- [HTTP Status Codes](https://httpstatuses.com/) - HTTP 协议状态码列表。
- [DevDocs](https://devdocs.io/) - 在线技术文档查询，freeCodeCamp 组织维护，**开源免费**。
- [Zeal](https://zealdocs.org/) - 支持离线浏览的技术文档浏览器，**开源免费**。
- [OWASP Cheat Sheet Series](https://cheatsheetseries.owasp.org/) - 技术安全相关备忘单，由 OWASP 基金会维护。

### 算法与数据结构

*Algorithm and data structure.*

- [Big-O Cheat Sheet](https://www.bigocheatsheet.com/)
  - [big-o](https://samwho.dev/big-o/) - 以可视化方式解释 Big-O 概念。
- [The Algorithms](https://the-algorithms.com/) - 学习算法和数据结构及其在多个语言中的实现。

- 算法可视化（Algorithm Visualization）
  - [VisuAlgo](https://visualgo.net/zh) - 可视化算法过程。
  - [Pathfinding Visualizer](https://josephprichard.github.io/Pathfinder/) - 寻路算法可视化工具。
  - [Data Structure Visualizations](https://www.cs.usfca.edu/~galles/visualization/) - 数据结构可视化。
  - [Hello 算法](https://www.hello-algo.com/) - 图解算法。
  - [algoviz](https://www.algoviz.app/)

- JavaScript
  - [JavaScript Algorithms and Data Structures](https://github.com/trekhleb/javascript-algorithms) - 算法和数据结构。

### 编码技巧

_Coding skills._

- [The Art of Command Line](https://github.com/jlevy/the-art-of-command-line) - 命令行的艺术，技巧。
- [COMMANDLINEFU.COM](https://www.commandlinefu.com/commands/browse) - 汇集了很多优秀的、充满智慧的、简洁的命令行命令。
- [Bash Pitfalls](http://mywiki.wooledge.org/BashPitfalls) - 此页面汇总了 Bash 用户常犯的编程错误。
- [Code Cheatsheets](https://devhints.io/) - 备忘清单，脚本片段。
- [30 seconds](https://www.30secondsofcode.org/) - 30 seconds 是一个系列，包含 JS、React.js、CSS、Git 相关的编程技巧和代码片段。

[`Go Top ↑`](#awesome-development-resources)

## 社区论坛

*Some valuable developer forum websites, Q&A communities, etc.*

- [Hacker News](https://news.ycombinator.com/) - 硅谷著名的创业孵化器机构 YC 运营的全球访问量最高的技术论坛。
- [hacker noon](https://hackernoon.com/) - 高质量技术文章发布社区。
- [Stack Overflow](https://stackoverflow.com/) - 全球程序员学习、分享，技术问答社区网站，**包含在 StackExchange 中**。
- [StackShare](https://stackshare.io/) - 全球技术趋势分享讨论。
- [DEV](https://dev.to/) - 开发者社区。
- [in Depth Dev](https://indepth.dev/) - 高级 Web 开发技术新闻。
- [Front-End Front](https://frontendfront.com/) - 前端开发人员社区。
- [图灵社区](http://www.ituring.com.cn/) - 国内一个出版计算机类相关书籍的社区，外文书翻译质量非常高，拥有很好的用户口碑。
- [CNode 社区](https://cnodejs.org/) - CNode 社区由一批热爱 Node.js 技术的工程师发起，致力于 Node.js 的技术研究。
- [Ruby China](https://ruby-china.org/) - 由众多爱好者共同维护的 Ruby 中文社区。
- [V2EX](https://v2ex.com/) - 一个汇集各类奇妙好玩的话题和流行动向的网站。
- [SegmentFault](https://segmentfault.com/) - 国内一个类似 Stack Overflow 的程序员技术学习，问答社区网站。
- [w3schools](https://www.w3schools.com/) - 国外一个非常棒的 Web 技术学习资源网站。（须翻墙）
  - [w3school](http://www.w3school.com.cn/) - 国内一个仿国外 w3schools 的 Web 技术学习资源网站。
  - [菜鸟教程](http://www.runoob.com/) - 国内另一个仿国外 w3schools 的 Web 技术学习资源网站。
- [掘金社区](https://juejin.im/) - 国内一个帮助开发者成长的社区，有很多优质的技术文章。
  - [掘金翻译计划](https://github.com/xitu/gold-miner) - 掘金翻译计划，可能是世界最大最好的英译中技术社区，最懂读者和译者的翻译平台。
- [Linux 公社](https://www.linuxidc.com/) - 国内一个论坛，内有大量 Linux 相关资源。
- [PaperWeekly](http://www.paperweekly.site/) - 一个推荐、解读、讨论和报道人工智能前沿论文成果的学术平台。
- [freeCodeCamp Learning](https://www.freecodecamp.org/learn/)
- [Hackr.io](https://hackr.io/) - 课程分享与学习。
- [ui.dev](https://ui.dev/) - 交互式 JavaScript 教程。
- [Hello GitHub](https://hellogithub.com/) - 一个发现和分享有趣、入门级开源项目的平台。
- [linux.do](https://linux.do/)

[`Go Top ↑`](#awesome-development-resources)

## 技术期刊

*Some developer news journals related to industry technology trends.*

- 出版商（Publisher）
  - [Cooperpress](https://cooperpress.com/) - 计算机技术相关杂志、网站。

- 每日（Every day）
  - [freeCodeCamp News](https://www.freecodecamp.org/news)
  - [Webdesigner News](https://www.webdesignernews.com/) - 日报，针对 Web 设计师的新闻。
  - [Echo JS](https://www.echojs.com/) - 日报，Web 前端新闻。
  - [CSS-Tricks](https://css-tricks.com/) - 日报，CSS 技术文章。
  - [Sidebar](https://sidebar.io/) - 日报，设计相关新闻。
  - [AINews](https://news.smol.ai/) - 日报，汇总全网的 AI 新闻资讯。

- 每周（Weekly）
  - System Design
    - [StatusCode Weekly](https://weekly.statuscode.com/) - 周刊，软件开发、Web 技术、软件架构等。（Cooperpress 出版）（ :warning: 停止更新）
    - [ByteByteGo Newsletter](https://blog.bytebytego.com/) - 周刊，系统设计相关内容。
    - [System Design Newsletter](https://newsletter.systemdesign.one/) - 周刊，系统设计相关内容。
  - Database
    - [DB Weekly](https://dbweekly.com/) - 周刊，数据库技术。（Cooperpress 出版）（ :warning: 停止更新）
    - [Postgres Weekly](https://postgresweekly.com/) - 周刊，PostgreSQL 技术。（Cooperpress 出版）
  - AI (Machine Learning)
    - [Latent.Space](https://www.latent.space/) - 周刊，AI 工程师播客。
    - [NLP Newsletter](https://nlp.elvissaravia.com/) - 周刊，机器学习论文。
    - [Interconnects](https://www.interconnects.ai/) - 周刊，人工智能资讯。
    - [Deep (Learning) Focus](https://cameronrwolfe.substack.com/) - 周刊，人工智能领域主题。
  - CSS
    - [CSS Weekly](https://css-weekly.com/) - 周刊，CSS 技术。
    - [CSS Animation Weekly](https://cssanimation.rocks/weekly/) - 周刊，CSS 动画。
  - JavaScript & Web Frontend
    - [JavaScript Weekly](https://javascriptweekly.com/) - 周刊，JavaScript 技术。（Cooperpress 出版）
    - [JSK Weekly](https://javascriptkicks.com/) - 周刊，JavaScript 技术。
    - [ECMAScript News](http://esnextnews.com/) 周刊，最新的 JavaScript 技术资讯。
    - [bytes.dev](https://bytes.dev/) - 周刊，JavaScript 技术。（ui.dev 出版）
    - [Frontend Focus](https://frontendfoc.us/) - 周刊，Web 前端技术资讯。（Cooperpress 出版）
    - [Frontend Weekly](https://frontendweekly.co/) - 周刊，Web 前端技术资讯。
    - [Smashing Magazine](https://www.smashingmagazine.com/) - 周刊，Web 前端与 UX 资讯。
    - [GameDev.js Weekly](https://gamedevjsweekly.com/) - 周刊，HTML5 游戏开发资讯。
  - React.js
    - [React Status](https://react.statuscode.com/) - 周刊，React.js 相关技术。（Cooperpress 出版）
    - [React Newsletter](https://reactnewsletter.com/) - 周刊，React.js 相关技术。（ui.dev 出版）
    - [ReactWeekly](https://react.thisweekin.io/)
    - [React Digest](https://reactdigest.net/)
    - [This Week in React](https://thisweekinreact.com/)
  - Mobile Native Client
    - [Mobile Dev Weekly](https://mobiledevweekly.com/) - 周刊，移动应用（Web 和 Native）开发技术。（Cooperpress 出版）
    - [Android Weekly](https://androidweekly.net/) - 周刊，Android 技术。
    - [iOS Dev Weekly](https://iosdevweekly.com/) - 周刊，iOS 开发者相关。
  - Node.js & Deno
    - [Node Weekly](https://nodeweekly.com/) - 周刊，Node.js 技术。（Cooperpress 出版）
    - [npm Weekly](https://www.npmjs.com/npm-weekly) - 周刊，npm 新闻，**npm 官方**。（ :warning: 停止更新）
    - [Deno Weekly](https://denoweekly.com/) - 周刊，Deno 技术。（Cooperpress 出版）
  - Other
    - [Web Tools Weekly](https://webtoolsweekly.com/) - 周刊，Web 开发工具资讯。
    - [Ruby Weekly](https://rubyweekly.com/) - 周刊，Ruby 技术。（Cooperpress 出版）
    - [PyCoder’s Weekly](https://pycoders.com/) - 周刊，Python 技术。
    - [Golang Weekly](https://golangweekly.com/) - 周刊，Go 技术。（Cooperpress 出版）
    - [Serverless Status](https://serverless.email/) - 周刊，Serverless 和 FaaS 相关技术。（Cooperpress 出版）

  - [_Awesome Weekly_](https://github.com/jondot/awesome-weekly) - _更多周刊。_

- 每月（Monthly）
  - [The Deep Dive](https://indepth.dev/newsletter) - 月刊，一月两次，高级 Web 开发技术。

- 半年（Half a year）
  - [Technology Radar](https://www.thoughtworks.com/radar) - 六个月一期，[ThoughtWorks](https://www.thoughtworks.com/) 出品的技术雷达。

- 其它（Others）
  - [MongoDB Memo](https://mongodb.email/) - MongoDB 新闻。（Cooperpress 出版）

### 技术博客

_Technical blog._

- [2ality](https://2ality.com/archive.html) - JavaScript、Web 开发、移动计算相关。
- [Bob Nystrom](https://journal.stuffwithstuff.com/) - 游戏开发、编程语言。
- [The Design System Guide](https://thedesignsystem.guide/) - 设计系统指南。

[`Go Top ↑`](#awesome-development-resources)

## 在线资源

*Online Resources.*

_see also 👉  [Web 端软件资源](./awesome-software.md#浏览器端)_

### 在线实用工具

*Online utils tools.*

- [HTTP Archive](https://httparchive.org/) - Web 站点跟踪测试。
- [free-for.dev](https://free-for.dev/) - 软件开发人员可用的免费 SaaS、PaaS、IaaS 等服务。

- Toolset
  - [JSON Diff](https://www.jsondiff.com/) - 对比 JSON 数据差异。
  - [URL Encoder](https://www.urlencoder.org/) - URL 编解码，以及一系列小工具。
  - [tool.lu](https://tool.lu/) - 开发者工具集。
  - [Carbon](https://carbon.now.sh/) - 生成漂亮的源代码图片。
  - [FastIcon](https://fasticon.sawirstudio.com/) - 在线快速生成 Android 与 IOS 应用图标。
  - [Understand your dependencies](https://deps.dev/) - 在线分析开源模块，了解依赖代码的安全性、许可证等信息，**Google Cloud 提供**。
  - [What's that site running?](https://sitereport.netcraft.com/) - 探测一个网站背后的基础设施信息。

- HTTP/IP/DNS
  - [IPAddress](https://www.ipaddress.com/) - 在线查询某个站点的 IP 地址。
  - [Resolve.rs](https://resolve.rs/tools.html) - 查询本机 IP、DNS 服务器等。
  - [FreeSSL](https://freessl.org/) - 免费 SSL 证书在线申请。
  - [IKnowWhatYouDownload](https://iknowwhatyoudownload.com/) - 查看 IP 下载过的 BT 资源。
  - [Web Check](https://web-check.xyz/)

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
  - [pyrexp](https://pythonium.net/regex)
  - [RegexLearn](https://regexlearn.com/)
  - [RegexOne](https://regexone.com/)

- Converter
  - [Excel to JSON](https://exceltojson.com/) - Excel 转 JSON 数据。
  - [transform](https://transform.tools/) - 多语言转换器。
  - [json-to-excel](https://tableconvert.com/json-to-excel) - 表格数据转换器。
  - [URL to Any](https://www.urltoany.com/) - 将链接转换为多种形式。

### 公共 API

*Public api.*

- 数据集（Dataset）
  - [NASA API](https://api.nasa.gov/) - NASA 的开放 APIs。
    - [Explore NASA Imagery and Data](https://nasa-api-explorer.vercel.app/) - 可在线浏览 NASA 数据。
  - [World Bank API](https://documents.worldbank.org/en/publication/documents-reports/api) - 世界银行的开放 APIs。
  - [Open Library API](https://openlibrary.org/developers/api) - 开放图书馆的 APIs。

- 天气（Weather）
  - [OpenWeather](https://openweathermap.org/) - 全球城市天气预报。
  - [Visual Crossing](https://www.visualcrossing.com/)
  - [Weatherbit.io](https://www.weatherbit.io/)
  - [Open-Meteo](https://open-meteo.com/) - 天气服务，**开源**。

- 其它（Others）
  - [Public APIs](https://github.com/public-apis/public-apis) - 免费的公共 API 集合。
  - [Free Public APIs](https://www.freepublicapis.com/)
  - [Awesome Public Real-Time Datasets and Sources](https://github.com/bytewax/awesome-public-real-time-datasets) - 
  - [GIS Datasets](awesome-dev-gis.md#开放数据) - 开放地理数据集。
  - [QR Code Generator](https://goqr.me/api/) - 二维码生成。
  - [free-for.dev](https://free-for.dev/) - 免费开发资源。

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

- Badge Service
  - [Shields.IO](https://shields.io/)
  - [NodeICO](https://nodei.co/)
  - [Badgen](https://badgen.net/)
  - [Version Badge](https://badge.fury.io/)
  - [Badges](https://formidable.com/open-source/badges/)
  - [Markdown Badges](https://github.com/Ileriayo/markdown-badges)
- GitHub Repository Stats
  - [repography](https://repography.com/) - 可视化 github 仓库的贡献者、commit 等信息。
  - [repobeats](https://repobeats.axiom.co/) - 可视化 github 仓库的贡献者、issues 变化等信息。
  - [Star Charts](https://starchart.cc/) - GitHub 仓库星数量趋势图。
  - [star-history](https://www.star-history.com/)
- GitHub Profile READMEs
  - [gh-profile-readme-generator](https://rahuldkjain.github.io/gh-profile-readme-generator/) - 根据配置自动生成个人自述文档。
  - [Awesome GitHub Profile READMEs](https://zzetao.github.io/awesome-github-profile/)
  - [profile-readme-generator](https://github.com/maurodesouza/profile-readme-generator)
  - [GitHub Readme Stats](https://github.com/anuraghazra/github-readme-stats) - 显示个人 GitHub 仓库统计信息。
  - [GitHub Stats Visualization](https://github.com/jstrieb/github-stats) - 显示个人 GitHub 仓库统计信息。
  - [GitHub Profile Trophy](https://github.com/ryo-ma/github-profile-trophy) - 添加奖杯。
  - [algora.io](https://algora.io/profile/wang1212) - 开源简历。
  - [github-breakout](https://github.com/cyprieng/github-breakout)

[`Go Top ↑`](#awesome-development-resources)

## AI 编程工具

_AI native programming tools._

- [AGENTS.md](https://github.com/openai/agents.md) - 通用代理配置文件。
  - [Agent Rules](https://github.com/steipete/agent-rules)
  - [ai-prompts](https://github.com/instructa/ai-prompts)
  - [GPT-Prompt-Hub](https://github.com/LichAmnesia/GPT-Prompt-Hub/)
  - [ruler](https://github.com/intellectronica/ruler) - 统一管理 agent 规则配置。

- AI Coding Agent - IDE Extension
  - [Kilo Code](https://kilo.ai/)
    - [cline](https://github.com/cline/cline)
    - [Roo Code](https://roocode.com/)
  - [qodo gen](https://www.qodo.ai/)
  - [Continue](https://www.continue.dev/)

- AI Coding Agent - Terminal
  - _[cc-switch](https://github.com/farion1231/cc-switch) - 跨平台的配置管理工具。_
  - [Claude Code](https://www.anthropic.com/claude-code) - **Anthropic 发布**。
    - [everything-claude-code](https://github.com/affaan-m/everything-claude-code) - 最佳实践。
  - [Gemini CLI](https://github.com/google-gemini/gemini-cli) - **提供免费额度，Google 发布**。
  - [OpenAI Codex CLI](https://github.com/openai/codex) - 支持多个模型供应商，需提供 Key 才能使用，**OpenAI 发布**。
  - [OpenCode](https://github.com/anomalyco/opencode) - **开源**。
    - [oh-my-opencode](https://github.com/code-yeongyu/oh-my-opencode) - 提供多种编码智能体技能。
  - [Aider](https://github.com/Aider-AI/aider)
  - [amp](https://ampcode.com/) - 提供每日免费额度，Sourcegraph 发布。

- AI Coding Agent - IDE
  - [cursor](https://www.cursor.com/)
    - [dotcursorrules](https://dotcursorrules.com/)  
  - [windsurf](https://windsurf.com/editor) - **提供免费模型**。
  - [Antigravity](https://antigravity.google/) - 免费额度周刷新，**Google 发布**。
  - [Blackbox AI](https://www.blackbox.ai/) - 提供 VSCode 插件/IDE/CLI/Remote Agent，**提供免费模型**。
  - [qoder](https://qoder.com/) - 提供 IDE/CLI，**提供免费模型**。
  - [void](https://voideditor.com/) - **开源软件**。

- AI Coding Agent - Async Task
  - [jules](https://jules.google.com/) - 异步编码代理，**每天 15 个免费任务额度，Google 发布**。

- Vibe Coding - Web
  - [bolt](https://bolt.new/) - 通过 AI 直接生成页面应用项目代码，可免费使用。
  - [lovable](https://lovable.dev/)
  - [replit](https://replit.com/)

- 非结构化数据集管理（Unstructured Dataset Management）
  - [Nomic Atlas](https://atlas.nomic.ai/) - 非结构化数据集的探索、管理、检索和搜索。
  - [jina](https://jina.ai/) - 非结构化数据集搜索。

- Spec Coding
  - [spec-kit](https://github.com/github/spec-kit)

- Tools
  - MCP Server
    - [Chrome DevTools MCP](https://github.com/ChromeDevTools/chrome-devtools-mcp) - Chrome DevTools 自动化调用调试分析。
  - Skills
    - [superpowers](https://github.com/obra/superpowers) - 一个完整的软件开发工作流程。
    - [vercel-labs/agent-skills](https://github.com/vercel-labs/agent-skills) - React 应用开发和 Web UI 审查。

- Others
  - [Tabby](https://tabby.tabbyml.com/) - 开源、自托管的 AI 编码引擎服务。

### AI Coding Workspace

- [Warp](https://www.warp.dev/) - **商业产品**。
- [supacode](https://supacode.sh/)
- [Conductor](https://www.conductor.build/)
- [Commander](https://commanderai.app/)

[`Go Top ↑`](#awesome-development-resources)

## 软件工具

*Software tools.*

### Emoji

- [_Emoji Cheat Sheet_](./awesome-dev-cheat-sheet.md#bookmark-emoji-smile)
- [Emojibase](https://emojibase.dev/) - Emoji 数据集。
- [Twemoji](https://twemoji.twitter.com/) - 跨浏览器渲染一致的 Emoji 表情，**Twitter 开源**。

### Chrome 扩展程序

*Chrome extension.*

- [Sourcegraph](https://about.sourcegraph.com/) - 代码搜索工具，提供源代码快速搜索，智能代码提示，代码审查等功能。
- `Lighthouse` - 站点性能监测工具，可提供优化建议和报告，**官方扩展**。
- [Wappalyzer](https://chrome.google.com/webstore/detail/wappalyzer/gppongmhjkpfnbhagpmjfkannfbllamg) - 检测当前站点所使用到的 Web 开发技术，包括框架、库、服务器、编程语言等。
- [WhatRuns](https://chrome.google.com/webstore/detail/whatruns/cmkdbmfndkfgebldhnkbfhlneefdaaip) - 同上。
- [WhatFont](https://chrome.google.com/webstore/detail/whatfont/jabopobgcpjmedljpbcaablpmlmfcogm) - 检测网站中所使用到的字体。
- [JSON-handle](https://chrome.google.com/webstore/detail/json-handle/iahnhfdhidomcpggpaimmmahffihkfnj) - JSON 文档的浏览器和编辑器。
- [CSS Peeper](https://chrome.google.com/webstore/detail/css-peeper/mbnbehikldjhnfehhnaidhjhoofhpehk) - 页面 CSS 调试工具。
- [Headless Recorder](https://chrome.google.com/webstore/detail/headless-recorder/djeegiggegleadkkbgopoonhjimgehda) - 录制页面交互，生成 JS 无头脚本代码。
- Enhance the function of github. *(see also 👉 <https://github.com/stefanbuck/awesome-browser-extensions-for-github>)*
  - [Refined GitHub](https://github.com/sindresorhus/refined-github) - 增强 GitHub 网站界面功能，在许多细节方面做了改进。
  - [Octotree](https://www.octotree.io/) - 生成代码文件树，方便浏览仓库文件。
  - [OctoLinker](https://octolinker.now.sh/) - 源代码中引用的依赖包信息预览，例如 `import`, `require` 语句。
  - [File Icons for GitHub and GitLab](https://github.com/homerchen19/github-file-icons) - 为 GitHub、Gitlab、Bitbucket、gitea 和 gogs 网站提供不同类型文件的图标。
  - [Enhanced Github](https://github.com/softvar/enhanced-github) - 增强 GitHub 网站界面功能，显示仓库大小、每个文件的大小、下载链接和复制文件内容的按钮等。
  - [ZenHub for GitHub](https://github.com/marketplace/zenhub) - GitHub 项目管理工具。
  - [GitHub Dark](https://github.com/StylishThemes/GitHub-Dark) - GitHub 网站界面黑夜模式。
  - [GitHub Hovercard](https://justineo.github.io/github-hovercard/) - 悬浮卡片。
- [CodeCopy](https://github.com/zenorocha/codecopy) - 为网站上的代码块提供复制到粘贴板按钮。
- [ModHeader](https://modheader.com/) - 用于修改 HTTP 请求和响应标头。
- [daily.dev | The Homepage Developers Deserve](https://daily.dev/) - 开发者新闻汇总。

### 测试

*Various testing tools.*

- HTTP 基准测试（Benchmarks）
  - [_HTTP(S) Benchmark Tools_](https://github.com/denji/awesome-http-benchmark#https-benchmark-tools) - *HTTP 基准测试工具集。*
  - [_Web Frameworks Benchmark_](https://web-frameworks-benchmark.netlify.app/) - *Web 框架的公开基准测试，仅供参考。*

- Others
  - [hurl](https://github.com/Orange-OpenSource/hurl) - 一个命令行工具，可以运行以简单的纯文本格式定义的 HTTP 请求。
  - [Browser MCP](https://browsermcp.io/) - 将 AI 应用程序连接到你的浏览器以自动执行测试和任务。

### 代码编辑器/IDE

*Open source free IDE editor, and some commercial paid IDE.*

#### 在线编辑器（Online Editor）

- [StackBlitz](https://stackblitz.com/)
- [JSON Editor Online](http://jsoneditoronline.org/) - 在线 JSON 编辑器。
- [CodeTable](https://code.hackerearth.com/)
- [JDoodle](https://www.jdoodle.com/)
- [IdeOne](https://ideone.com/)
- [OnlineGDB](https://www.onlinegdb.com/)
- [CodeSandbox](https://codesandbox.io/) - 支持预配置的目标，例如 React.js 等。
- [CodePen](https://codepen.io/)
- [JSFiddle](https://jsfiddle.net/)
- [JSitor](https://jsitor.com/)

#### 桌面端（Desktop Editor）

- [Notepad++](https://notepad-plus-plus.org/) - 一款轻量级的文本编辑器，**开源软件**。
- [VS Code](https://code.visualstudio.com/) - 一款轻量级开发工具，功能很强大，深受开发者的青睐，是 Web 前端开发者的工作利器，**开源软件**。
  - [VSCodium](https://vscodium.com/) - 社区驱动、免费许可的 VS Code 版本。
  - [Create Your Own VS Code Themes](https://themes.vscode.one/) - 创建 VS Code 主题。
  - [Open VSX](https://open-vsx.org/) - 开源扩展注册表。
- [Sublime Text](http://www.sublimetext.com/) - 一款开源的轻量级编辑器，功能很强大，是在 VS Code、Atom 出现之前最受开发者欢迎的编辑器。
- [CudaText](https://cudatext.github.io/index.html) - 跨平台的代码编辑器，大文件性能较好，**开源软件**。
- [Eclipse](https://www.eclipse.org/) - 开源的重量级编辑器，功能非常强大，是 Java 开发者中使用最多的 IDE，**开源软件**。
- [UltraEdit](https://www.ultraedit.com/) - 文本编辑器，功能强大，性能较好，**商业软件**。
- [EmEditor](https://www.emeditor.com/) - 文本编辑器，功能强大，浏览大文件性能很好，**商业软件**。
- Vim
  - [neovim](https://neovim.io/) - 类 VIM 编辑器。
  - [helix](https://helix-editor.com/)
- [zed](https://zed.dev/) - Rust 编写的高性能编辑器。
- [nano](https://www.nano-editor.org/) - 简单轻量级编辑器。

#### 代码格式化

*Code formatting.*

- [Prettier](https://prettier.io/)
- [EditorConfig](https://editorconfig.org/)
- [dprint](https://github.com/dprint/dprint)

#### 编码统计

_Coding Statistics._

- [WakaTime](https://wakatime.com/)
  - [wakapi](https://wakapi.dev/) - 自托管服务，**开源免费**。
  - [hakatime](https://github.com/mujx/hakatime) - 自托管服务，**开源**。

- [Code Time](https://app.software.com/)

### 源代码管理

*Source code version management system and building tools.*

- [Git](https://git-scm.com/) - 目前最受欢迎的，使用最广泛的分布式源代码版本控制工具。
  - Learn
    - [Resources to learn Git](http://try.github.io/) - 学习 Git 的文档。
    - [Git Explorer](https://gitexplorer.com/) - Git 命令参考。
    - [Learn Git Branching](https://learngitbranching.js.org/) - 在线 Git 命令互动式学习。
    - [Beej's Guide to Git](https://beej.us/guide/bggit/html/split/)
  - Client
    - [Sourcetree](https://www.sourcetreeapp.com/) - 免费的 Git 客户端，支持 Windows 和 Mac。
    - [GitButler](https://github.com/gitbutlerapp/gitbutler) - 为现代人工智能驱动的工作流程而从零开始构建的版本控制工具，**开源**。
  - [A collection of .gitignore templates](https://github.com/github/gitignore) - 不同类型项目的 `.gitignore` 文件模板。
    - [gitignore.io](https://www.toptal.com/developers/gitignore) - 根据关键词生成 `.gitignore` 文件模板。
  - CLIs
    - [git-open](https://github.com/paulirish/git-open) - git 命令行工具，可直接在浏览器中打开仓库页面。
    - [gut](https://gut-cli.dev/) - 通过直观的命令和简化的工作流程，简化了使用 Git 复杂系统的过程，让您专注于代码。
    - [git-cliff](https://github.com/orhun/git-cliff) - 通过 Commits 记录自动生成 Changelog 内容。
  - 统计（statistics）
    - [git-stats](https://github.com/IonicaBizau/git-stats)
    - [Gitinspector](https://github.com/ejwa/gitinspector) - 生成统计报告。
    - [git-quick-stats](https://github.com/arzzen/git-quick-stats)
    - [git-sizer](https://github.com/github/git-sizer)
    - [Map of GitHub](https://github.com/anvaka/map-of-github) - 用地图呈现多个 Github 项目之间共同关注者的信息。
  - Others
    - [difit](https://github.com/yoshiko-pg/difit) - 以 GitHub 的风格查看本地 Git 提交变更。
    - [gitmoji](https://gitmoji.dev/) - Git 提交信息中的 emoji 表情。

- [Tortoise SVN](https://tortoisesvn.net/) - SVN 是一种传统的中心化管理的源代码版本控制工具，Tortoise SVN 提供了 GUI 来使用 SVN。

- 公共代码托管平台（Public code hosting platform）
  - [GitHub](https://github.com/)
    - [github1s](https://github.com/conwnet/github1s) - 可直接在浏览器的 VS Code 中打开 GitHub 仓库代码。
    - GitHub Actions
      - [checkout](https://github.com/actions/checkout) - 拉取仓库代码。
      - [super-linter](https://github.com/super-linter/super-linter)
      - [stale](https://github.com/actions/stale)
    - GitHub Apps
      - [imgbot](https://github.com/marketplace/imgbot) - 图片压缩优化。
      - [Renovate](https://github.com/renovatebot/renovate) - 依赖自动管理。
      - [Mend](https://github.com/marketplace/whitesource-bolt) - 漏洞扫描和修复。
  - [GitLab](https://about.gitlab.com/) - 支持本地部署。
  - [Bitbucket](https://bitbucket.org/)
  - [Gitee](https://gitee.com/) - 码云，国内[开源中国](https://www.oschina.net/)推出。

- 自托管 Git 服务（Self-hosted Git service）
  - [Gitea](https://gitea.io/) - 本地部署，**开源项目**。
  - [Gogs](https://gogs.io/) - 本地部署，**开源项目**。

### API 文档管理

*API document management and testing.*

- [Postman](https://www.getpostman.com/) - 一个非常棒的 API 管理工具，**商业软件，提供免费版本**。
- [Insomnia](https://insomnia.rest/) - API 接口测试工具，**商业软件**。
- [hoppscotch](https://hoppscotch.io/) - API 接口测试、管理，**开源软件**。
- [HTTPie](https://httpie.org/) - HTTP 客户端，类似 curl，人类可读，**开源软件**。
- [Mockoon](https://mockoon.com/) - Mock API 服务，**开源软件**。
- [Bruno](https://docs.usebruno.com/) - Git 友好的 HTTP 客户端，**开源软件**。

### 服务器远程管理

*Server remote management tools, such as SSH client, etc.*

- Multi-platform
  - [termius](https://termius.com/) - 现代化 SSH 客户端，提供免费版本，**商业产品**。

- Windows
  - [WinSCP](https://winscp.net/) - 使用 SSH 的图形化 SFTP 客户端，同时支持 SCP 协议，用于远程文件传输，**开源免费**。
  - [PuTTY](https://www.putty.org/) - 一个集 Telnet、SSH、rlogin、纯 TCP 以及串行接口连接软件，配合 WinSCP 可以很好的远程管理 Linux 服务器，也支持 Unix 平台，**开源免费**。
  - [Bitvise SSH Client](https://www.bitvise.com/ssh-client) - SSH 文件传输、终端、隧道，**免费软件**。
  - [mRemoteNG](https://mremoteng.org/) - 多远程下一代连接管理器，mRemote 的分支，**开源免费**。
  - [FileZilla](https://filezilla-project.org/index.php) - FTP、FTPS、SFTP 客户端，**开源免费**。

- Linux/Unix

### 命令行工具

*Command line tools.*

#### 终端

_Terminal, Console, Shell, and Command Line._

_see also 👉 https://github.com/cdleon/awesome-terminals_

- Multi-platform
  - [hyper](https://hyper.is/) - 基于开放的 Web 标准，为命令行界面用户打造美观且可扩展的用户体验。
  - [Tabby](https://tabby.sh/) - 全功能跨平台终端应用。
  - [WezTerm](https://wezterm.org/) - Rust 编写的全功能高性能终端。
  - [Ghostty](https://github.com/ghostty-org/ghostty) - 极高性能的终端模拟器。
  - [Alacritty](https://github.com/alacritty/alacritty) - Rust 编写的极简高性能终端。
  - [Wave](https://www.waveterm.dev/) - AI-Native，集成了文件预览、文件编辑、人工智能、网页浏览和工作区组织。
  - [PowerShell](https://github.com/PowerShell/PowerShell)

- Windows
  - [Windows Terminal](https://github.com/microsoft/terminal)
  - [ConEmu](https://conemu.github.io/)
  - [Git Bash](https://gitforwindows.org/)
  - [Clink](https://mridgers.github.io/clink/)
  - [Cmder](https://cmder.app/) - 基于 ConEmu 和 Clink 特性，采用 Monokai 颜色主题，支持 Git 等。

#### Windows

*Used on Windows platform.*

- [MSYS2](https://www.msys2.org/) - 基于 Cygwin 和 MinGW-w64 对 MSYS 的重写，支持 Bash、Git 等更多特性。
- [MinGW](http://www.mingw.org/) - Minimalist GNU for Windows，不支持 POSIX。
- [Cygwin](http://www.cygwin.com/) - GNU 和开源工具的集合，支持 POSIX。
- [Far Manager](https://www.farmanager.com/) - Windows 系统纯文本的文件管理器。
- [watchman](https://facebook.github.io/watchman/) - 文件监视服务。

#### Linux

*Used on Linux platform.*

- [Modern Unix](https://github.com/ibraheemdev/modern-unix) - 常见 Unix 命令更好的替代品。
  - [tldr](https://tldr.sh/) - 类似于 `man` 命令，简化版的命令手册文档。
  - [htop](https://htop.dev/) - 类似于 `top` 命令，交互式进程浏览器。
  - [eza](https://github.com/eza-community/eza) - 类似于 `ls` 命令。
  - [fd](https://github.com/sharkdp/fd) -  类似于 `find` 命令，更简单好用。
  - [bat](https://github.com/sharkdp/bat) - 类似于 `cat` 命令，支持语法高亮等特性。
  - [ripgrep](https://github.com/BurntSushi/ripgrep) - 类似于 `grep` 命令。
  - df
    - [duf](https://github.com/muesli/duf) - 类似于 `df` 命令，查看硬盘使用情况的工具，支持多个平台。
    - [dust](https://github.com/bootandy/dust)
    - [gdu](https://github.com/dundee/gdu)
  - [curl](https://curl.se/) - 类似 `wget`，发送 HTTP 请求，支持多个平台。
  - [zoxide](https://github.com/ajeetdsouza/zoxide) - 类似 `cd`，更智能的记录常用目录。
  - [witr](https://github.com/pranshuparmar/witr) - 聚合 `ps`/`top` 等命令的输出，探查系统进程为何会运行。

- [Bash](https://www.gnu.org/software/bash/)
  - [bash-it](https://bash-it.readthedocs.io/) - bash 工具集，提供主题等功能，类似 on-my-zsh。
  - [oh-my-bash](https://github.com/ohmybash/oh-my-bash)

- [Z-Shell](https://www.zsh.org/)
  - [on-my-zsh](https://ohmyz.sh/) - 管理 Z-Shell 配置的框架。
  - [powerlevel10k](https://github.com/romkatv/powerlevel10k) - zsh 主题。

- [The Fuck](https://github.com/nvbn/thefuck) - 命令行错误命令纠正工具（多平台支持）。
- [screenFetch](https://github.com/KittyKatt/screenFetch) - 显示系统详细信息。
- [Glances](https://nicolargo.github.io/glances/) - 系统性能指标监控工具（多平台支持）。
- [ncdu](https://dev.yorhel.nl/ncdu) - 磁盘使用情况统计。
- [fzf](https://github.com/junegunn/fzf) - 模糊查找器。
- [sslh](https://github.com/yrutschle/sslh) - 实现端口复用。
- [BusyBox](https://www.busybox.net/) - 实用的 Linux 命令集合。
- [LF](https://github.com/gokcehan/lf) - 终端文件管理工具命令包。
- [wget](https://www.gnu.org/software/wget/) - 文件下载。
- [atuin](https://github.com/atuinsh/atuin) - shell 历史查询、搜索。

#### Android

- [termux](https://termux.dev/) - 一款 Android 终端模拟器和 Linux 环境应用 ，无需 root 权限或任何设置即可直接使用。

#### 其它

*Others.*

- [glow](https://github.com/charmbracelet/glow) - 在命令行预览 Markdown 文档。
- [Certbot](https://certbot.eff.org/) - 管理 [Let's Encrypt](https://letsencrypt.org/) 证书工具，为网站启用 HTTPS，**开源软件**。
- [gron](https://github.com/tomnomnom/gron) - 使 JSON 数据更易读，**开源软件**。
- [fx](https://github.com/antonmedv/fx) - 命令行 JSON 处理工具，**开源软件**。
- [gping](https://github.com/orf/gping) - 图形化 `ping` 命令结果。
- [tcping](https://elifulkerson.com/projects/tcping.php) - 类似 `ping` 命令，使用 TCP 端口。
- [subfinder](https://github.com/projectdiscovery/subfinder) - 查找子域名。
- [dog](https://dns.lookup.dog/) - 命令行 DNS 客户端。
- [nativefier](https://github.com/nativefier/nativefier) - 可将 Web 网站转换成本地应用。
- [hotel](https://github.com/typicode/hotel) - 利用 Web 网页启动多个服务应用并使用本地域名或者 https 协议。
- File
  - [csvkit](https://csvkit.readthedocs.io/en/latest/index.html) - 命令行处理 csv 文件。
- [Lazyssh](https://github.com/Adembc/lazyssh) - 终端 SSH 管理工具。

### WSL

*[Windows Subsystem for Linux](https://docs.microsoft.com/en-us/windows/wsl/) resources.*

- [wsl2-hacks - Updated for Ubuntu 20.04 / 20.10](https://github.com/shayne/wsl2-hacks) - 一些针对 Ubuntu 20.04 / 20.10 的技巧。
- [LxRunOffline](https://github.com/DDoSolitary/LxRunOffline) - 用于管理适用于 Linux 的 Windows 子系统 (WSL) 的全功能实用程序。
- [WSL2Proxy](https://github.com/wizcas/wsl2proxy) - 配置网络代理的脚本。
- [go-wsl2-host](https://github.com/shayne/go-wsl2-host)

### 实用工具

*Utils tools.*

- [asdf](https://github.com/asdf-vm/asdf) - 可扩展的版本管理器，支持 Ruby、Node.js、Elixir、Erlang 等多种语言。
- [staticrypt](https://github.com/robinmoisson/staticrypt) - HTML 文件加密。

- 幻灯片（Slideshow）
  - [Cleaver](http://jdan.github.io/cleaver/) - Markdown 文件生成幻灯片。
  - [nodeppt](https://github.com/ksky521/nodeppt) - Markdown 文件生成幻灯片。
  - [reveal.js](https://revealjs.com/)
  - [Slidev](https://sli.dev/)

#### 网络代理

_Network Proxy._

- Windows
  - [v2rayN](https://github.com/2dust/v2rayN) - **开源**。

- MacOS
  - [ClashMac](https://clashmac.app/) - **开源**。
 
- Android
  - [v2rayNG](https://github.com/2dust/v2rayNG) - **开源**。
  - [Clash Meta For Android](https://github.com/MetaCubeX/ClashMetaForAndroid) - **开源**。

- Multi-platform
  - Windows、MacOS、Linux
    - [Clash for Windows](https://www.clashforwindows.net/)
    - [Clash Verge](https://github.com/clash-verge-rev/clash-verge-rev) - **开源**。
    - [Clash Nyanpasu](https://github.com/libnyanpasu/clash-nyanpasu) - **开源**。
    - [Clash Party](https://github.com/mihomo-party-org/mihomo-party) - **开源**。
  - Windows、MacOS、Linux、Android
    - [FlClash](https://github.com/chen08209/FlClash) - **开源**。
  - Windows、MacOS、Android、iOS
    - [Karing](https://github.com/KaringX/karing) - **开源**。
  - Windows、MacOS、Linux、Android、iOS
    - [Hiddify](https://github.com/hiddify/hiddify-app)  

[`Go Top ↑`](#awesome-development-resources)

## 工具套件

*Tool kit.*

- [free-for.dev](https://free-for.dev/) - **免费**的开发资源服务列表。

- Web 统计分析（Web Statistical Analysis）
  - [Ackee](https://ackee.electerious.com/) - 基于 Node.js 的站点分析工具，**开源可自托管**。
  - [Cube.js](https://cube.dev/) - Web 应用分析解决方案，**开源可自托管**。
  - [Counter](https://counter.dev/) - **开源免费**的 Web 站点统计分析平台。
  - [Splitbee](https://splitbee.io/) - Web 站点分析统计平台，个人项目免费。

- 抓包工具（Packet Capture）
  - [Fiddler Everywhere](https://www.telerik.com/fiddler) - **提供免费版本**。
  - [mitmproxy](https://www.mitmproxy.org/) - Python 开发的 HTTPS 代理，**开源免费**。
  - [whistle](https://wproxy.org/whistle/) - 支持 HTTP/HTTPS/SOCKS/反向代理，**开源免费**。
  - [ProxyBridge](https://github.com/InterceptSuite/ProxyBridge) - 系统级代理，支持拦截不走系统代理的客户端应用，**开源免费**。

- 其它（Others）
  - [screego](https://screego.net/#/) - 屏幕共享服务器。
  - [netdata](https://www.netdata.cloud/) - 系统指标监控 Web 平台，**开源免费**。
  - [Skia](https://skia.org/) - 2D 渲染引擎，在 Chrome、Chrome OS、Android、Flutter、Mozilla Firefox 等产品中使用。
  - [nocodb](https://www.nocodb.com/) - NoCode 平台，将任何数据库转换为电子表格，Airtable 的开源替代品，**开源软件**。
  - [Talk](https://github.com/vasanthv/talk) - 点对点的 Web 视频会议和屏幕共享应用，**开源软件**。
  - [nb](https://xwmx.github.io/nb/) - 命令行和本地 Web 笔记、文档管理、检索应用程序。
  - [Web File Browser](https://filebrowser.org/) - 基于 Web 的云文件浏览器。
  - [Wiki.js](https://js.wiki/) - Wiki 系统，**开源软件**。

### 静态站点工具

_Static site tool._

- 静态站点生成器（Static Site Generator）
  - [Gatsby](https://www.gatsbyjs.org/) - 静态站点生成器，基于 React.js 的开源框架，可快速开发 Web 网站和应用。
    - [docz](https://www.docz.site/)
  - [Docusaurus](https://v2.docusaurus.io/) - 快速构建优化、快速的网站，**Facebook 发布**。
  - [MkDocs](https://www.mkdocs.org/)
  - [Nextra](https://nextra.vercel.app/) - 基于 Next.js 的静态站点生成器。
  - [GitBook](https://www.gitbook.com/) - 对开源和非盈利团队免费。
  - [docsify](https://docsify.js.org/)
  - [VuePress](https://vuepress.vuejs.org/)

- 静态站点托管服务（Static Site Hosting Service）
  - [vercel](https://vercel.com/)
  - [render](https://render.com/)
  - [netlify](https://www.netlify.com/)
  - [surge](https://surge.sh/help/getting-started-with-surge)

- 评论系统（Comment System）
  - [gitalk](https://github.com/gitalk/gitalk) - 基于 github 的 issues。
  - [utterances](https://github.com/utterance/utterances) - 基于 github 的 issues。
  - [giscus](https://giscus.app/) - 基于 github 的 Discussions。

[`Go Top ↑`](#awesome-development-resources)

## 面试指南

*Interview guidelines.*

- [Tech Interview Handbook](https://techinterviewhandbook.org/) - 通用的技术面试指南。
- [Reverse interview](https://github.com/viraptor/reverse-interview) - 面试时候可以反问的一些问题。
- [Coding Interview University](https://github.com/jwasham/coding-interview-university)
- [System Design Interview](https://github.com/checkcheckzz/system-design-interview) - 系统设计面试。（ :warning: 不再更新）
- [Front End Interview Handbook](https://www.frontendinterviewhandbook.com/) - 前端面试手册。

[`Go Top ↑`](#awesome-development-resources)

### 编码练习

*Some coding exercises and challenges website.*

- [LeetCode](https://leetcode-cn.com/) - 在线笔试算法题练习。
  - [LeetGPU](https://leetgpu.com/) - GPU 编程练习。
- [InterviewBit](https://www.interviewbit.com/) - 计算机知识学习，模拟面试平台。
  - [Technical Interview Questions](https://www.interviewbit.com/technical-interview-questions/) - 面试指南。
- [Codewars](https://www.codewars.com/) - 通过挑战解决代码问题提高编码水平。
- [牛客网](https://www.nowcoder.com/) - 在线刷题。

### 面试题

*Interview questions.*

- Generic
  - [Awesome Interviews](https://github.com/DopplerHQ/awesome-interview-questions) - 计算机技术相关的面试题。（ :warning: 不再更新）

- Web Front-end
  - [Front-end Developer Interview Questions](https://h5bp.org/Front-end-Developer-Interview-Questions/)
  - [JavaScript Interview Questions & Answers](https://github.com/sudheerj/javascript-interview-questions)
  - [React Interview Questions & Answers](https://github.com/sudheerj/reactjs-interview-questions)
  - [GreatFrontEnd](https://www.greatfrontend.com/) - **部分付费**。

## 更多

*More uncategorized resources.*

- [Learn Anything](https://learn-anything.xyz/) - 知识路径图谱。
- [Perfection Kills](http://perfectionkills.com/)

_[Open Source Collective](https://opencollective.com/opensource)_

[`Go Top ↑`](#awesome-development-resources)
