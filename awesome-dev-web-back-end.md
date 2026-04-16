<div align="center">
  <h1>Awesome-Web-Back-End-List</h1>

  <p>:heart: 收藏列表 - :+1: 很棒的 Web 服务器端相关技术知识，技术标准、理论、模式、架构等。</p>
  <p><i>Favorites list - great web server-side related technical knowledge, technical standards, theories, patterns, architectures, etc.</i></p>
</div>

<br />

## 目录

*Resource navigation list.*

- [技术标准规范（Technical Standard Specification）](#技术标准规范)
- [技术参考文档（Technical Reference Document）](#技术参考文档)
- [操作系统（Operating System）](#操作系统)
- [服务器（Server）](#服务器)
- [数据库（Database）](#数据库)
- [实用工具（Tools）](#实用工具)
  - [文档（Docs）](#文档)
  - [日志（Logs）](#日志)
  - [命令行工具（CLI Tools）](./awesome-dev-resource.md#命令行工具)
- [数据平台服务（Data platform services）](#数据平台服务)
- [文章（Article）](#文章)
- [更多（More）](#更多)

## 技术标准规范

*Technical standard specification.*

- [OpenAPI](https://www.openapis.org/) - 定义了一种 REST APIs 标准。
  - [OpenAPI.Tools](https://openapi.tools/)
- [AsyncAPI](https://www.asyncapi.com/) - 事件驱动的 APIs 规范，改编自 OpenAPI。
- [OAuth](https://oauth.net/)
  - [OpenID Connect](https://openid.net/connect/)

*More others 👉 [Awesome-Development-Technical-Standard-Specifications](awesome-dev-specifications.md)*

[`Go Top ↑`](#awesome-web-back-end-list)

## 技术参考文档

*Official and unofficial technical reference documents.*

- [REST API Tutorial](https://restfulapi.net/) - REST API 教程。
  - [Learn REST](http://rest.elkstein.org/)

- 微服务（Microservices）
  - [Microservices Guide](https://martinfowler.com/microservices/) - 微服务指南。
  - [microservices.io](https://microservices.io/) - 微服务相关概念文章。

- [Caching Tutorial](https://www.mnot.net/cache_docs/)

[`Go Top ↑`](#awesome-web-back-end-list)

## 操作系统

*Server operating system.*

- [Linux](https://www.linux.org/)
  - [Ubuntu](https://ubuntu.com/) - 最为流行的 Linux 发行版，提供图形化界面等资源。
  - [Debian](https://www.debian.org/)

[`Go Top ↑`](#awesome-web-back-end-list)

## 服务器

*Containers that run server-side programs and provide static resource services.*
  
- [Nginx](http://nginx.org/en/) - 轻量级、高性能、高并发的 Web 服务器，主要作为负载均衡、反向代理、静态资源服务的前端服务器。
  - [Free Nginx](https://freenginx.org/) - 社区驱动的开源分支。
  - [OpenResty](http://openresty.org/) - 算是 Nginx + Lua 的开发平台，提供了很多优质的 Nginx 插件。
  - [Kong](https://konghq.com/) - 现代 API 服务平台，提供诸如 API 网关等功能，其本身也利用了 OpenResty，是一个 Lua 模块 Nginx 插件。
  - [ngxtop](https://github.com/lebinh/ngxtop) - Python 编写的工具，实时分析 nginx 的运行指标。
  - [rhit](https://github.com/Canop/rhit) - nginx 日志浏览器，指标分析工具。
  - [NGINX Config](https://www.digitalocean.com/community/tools/nginx) - Nginx 配置在线生成工具，**非官方**。
  - [Nginx Proxy Manager](https://nginxproxymanager.com/) - nginx 代理服务管理器，提供 UI 交互界面，**开源软件**。

- [HAProxy](https://www.haproxy.org/) - 可靠、高性能的负载均衡器。
- [Varnish HTTP Cache](https://varnish-cache.org/) - 专用 HTTP 缓存服务器。
- [Apache](http://httpd.apache.org/) - 世界上最著名的 Web 静态服务器。

- [Tomcat](http://tomcat.apache.org/) - Java Web 开发中的 Servlet 容器。	

- [PostgREST](https://postgrest.org/) - 可利用 PostgreSQL 构建 RESTful API 的 web 服务器。

[`Go Top ↑`](#awesome-web-back-end-list)

## 数据库

- [PostgreSQL](https://www.postgresql.org/) - 世界上最受欢迎的开源关系数据库，**开源**。
  - [pglite](https://github.com/electric-sql/pglite) - 轻量级 Postgre，可在浏览器、Node.js 环境中使用，**非 PostgreSQL 官方发布**。
- [RethinkDB](https://rethinkdb.com/) - 构建实时 Web 应用的数据库，**开源**。
- [SQLite](https://www.sqlite.org/)
  - [sqlite-viewer](http://inloop.github.io/sqlite-viewer/) - 在线浏览器工具。
  - [libSQL](https://github.com/tursodatabase/libsql) - 开源社区版本，**非 SQLite 官方发布**。

### 数据库管理系统

_Database Management System._

- [DBeaver Community](https://dbeaver.io/) - 图形化数据库管理工具软件，**多平台支持，开源免费**。
- [Falcon](https://github.com/plotly/falcon) - SQL 客户端，支持数据可视化，**多平台支持，开源免费**。
- [SQLPad](https://sqlpad.github.io/sqlpad/) - Web SQL 客户端，支持数据可视化，**开源软件**。

[`Go Top ↑`](#awesome-web-back-end-list)

## 实用工具

*Utils tools.*

- [Typesense](https://typesense.org/) - 搜索引擎，可作为 Algolia 和 Elasticsearch 的替代方案，**开源**。
- [DocSearch](https://docsearch.algolia.com/) - Algolia 提供的文档搜索引擎，**开源免费**。
- [OpenReplay](https://openreplay.com/) - 类似 FullStory、LogRocket 等产品的开源替代品，可自托管，**开源**。

### 文档

- [apiDoc](https://apidocjs.com/) - 生成 RESTful web APIs 文档，支持多种后端语言。
- [Swagger](https://swagger.io/tools/open-source/) - **开源**。

### 日志

- [logdy](https://logdy.dev/)

[`Go Top ↑`](#awesome-web-back-end-list)

## 数据平台服务

_Data platform services._

- User data analysis
  - [umami](https://github.com/umami-software/umami) - 轻量的 Google Analytics 替代品。
  - [PostHog](https://github.com/PostHog/posthog)

[`Go Top ↑`](#awesome-web-back-end-list)

## 文章

*Some articles related to server-side problem solutions.*

- [How To Safely Store A Password](https://codahale.com/how-to-safely-store-a-password/)
- [Nginx Caching](https://serversforhackers.com/c/nginx-caching) - 利用 Nginx 进行缓存。

[`Go Top ↑`](#awesome-web-back-end-list)

## 更多

*More other unclassified resources.*

- [*Awesome Node.js List*](./awesome-dev-nodejs.md)

[`Go Top ↑`](#awesome-web-back-end-list)
