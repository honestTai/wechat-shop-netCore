<div align="center">

# WeChat Shop · 微信商城源码示例

**从控制器到数据模型，探索微信商城后端实现。**  
**Explore a WeChat shop backend, from controllers to data models.**

[浏览控制器 / Explore controllers](Controllers/) · [GitHub](https://github.com/honestTai/wechat-shop-netCore) · [HRouter](https://hrouter.net/home)

</div>

通过现有控制器、数据模型、视图与 Entity Framework 目录，了解一个微信商城后端项目的组织方式。

Explore the controllers, models, views, and Entity Framework layout of a WeChat shop backend project.

**适合谁 / Who it’s for**  
希望阅读早期 ASP.NET Core 商城项目结构的开发者。  
Developers exploring the structure of an early ASP.NET Core shop project.

## 源码导航 · Source map

| 目录 / File | 用途 / Purpose |
| --- | --- |
| `Controllers/` | 商城后台与 API 控制器 / Shop administration and API controllers |
| `Models/` | 数据模型 / Data models |
| `EntityFramework/` | 数据访问相关代码 / Data access code |
| `Views/` | 服务端视图 / Server-rendered views |
| `Startup.cs` / `Program.cs` | 应用启动 / Application startup |
| `ztbiyesheji.csproj` | 项目与依赖配置 / Project and dependencies |

## 项目状态 · Project status

这是一个历史源码项目，项目文件目标为 `netcoreapp2.0`，包含 ASP.NET Core 2.0.8 与 MySQL Entity Framework Core 8.0.13 依赖。适合阅读实现与整理迁移方案；本轮仅补充文档，没有验证构建、运行或部署。

This historical source project targets `netcoreapp2.0`, with ASP.NET Core 2.0.8 and MySQL Entity Framework Core 8.0.13 dependencies. Explore the implementation and plan modernization; this documentation update does not establish build, runtime, or deployment readiness.

仓库未提供独立的许可证文件，复用前请向作者确认授权范围。  
No standalone license file is present in the repository root; contact the author to clarify reuse permissions.


## 作者与 HRouter · About the author

我是 **honestTai**，开发工具，也运营 [HRouter](https://hrouter.net/home)。这里持续分享实用代码、AI 应用、Skills 与插件，把工作中的需求变成可复用的项目。  
I’m **honestTai**, the developer and operator behind HRouter. I share practical code, AI apps, skills, and plugins built around real workflows.

本项目本身无需接入 HRouter。如果你也使用 AI 编程工具，欢迎了解我运营的 HRouter 模型路由服务。  
This project does not require HRouter. If you also work with AI coding tools, explore my HRouter model-routing service.

[了解 HRouter · Explore HRouter](https://hrouter.net/home) · [发现更多项目 · More projects](https://github.com/honestTai)

**觉得有用，欢迎 Star；有想法，欢迎到 Issues 交流。**  
**Star the project if it helps, and share your ideas in Issues.**
