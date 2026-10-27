# Archetom

**开源 CRM 与 Java 应用基础。**

从可复用的基础类型、DDD 多模块脚手架，到配套的 CRM 后端和 Web 前端。

[English](https://github.com/Archetom/.github/blob/main/profile/README.en.md) · [全部项目](https://github.com/orgs/Archetom/repositories)

## Atom CRM

面向客户、销售与团队协作的 CRM。前后端独立构建，通过 OpenAPI 契约协作。

| 项目 | 用途 | 技术 |
| --- | --- | --- |
| [atom-crm](https://github.com/Archetom/atom-crm) | 客户与销售、合同与回款、工作任务、审批、报表和多租户权限 | Java · Spring Boot |
| [atom-crm-web](https://github.com/Archetom/atom-crm-web) | 配套 Web 界面，支持桌面与移动端 | React · TypeScript · Ant Design |

[快速开始](https://github.com/Archetom/atom-crm#快速开始) · [后端部署](https://github.com/Archetom/atom-crm/blob/main/docs/deployment.md) · [前端部署](https://github.com/Archetom/atom-crm-web/blob/main/docs/deployment.md) · [API 文档](https://github.com/Archetom/atom-crm/blob/main/docs/api-reference.md)

## Java 基础

| 项目 | 用途 |
| --- | --- |
| [Atom-Archetype](https://github.com/Archetom/Atom-Archetype) | 生成采用领域驱动设计的多模块 Java 项目，包含持久化、认证、事务和测试基础 |
| [Atom-Common](https://github.com/Archetom/Atom-Common) | 可独立使用的共享基础类型：错误码、错误上下文、统一结果、分页与轻量级耗时分析；不依赖 Spring |

要搭建新的 Java 服务，从 **Atom-Archetype** 开始；只需要基础类型，可直接使用 **Atom-Common**。要运行 CRM，按 **atom-crm** 和 **atom-crm-web** 的说明启动配套服务。版本、环境要求和许可证以各仓库为准。

## 参与贡献

欢迎通过对应仓库的 Issues 反馈问题、讨论需求，通过 Pull Requests 改进代码与文档。

- [后端贡献指南](https://github.com/Archetom/atom-crm/blob/main/CONTRIBUTING.md)
- [前端贡献指南](https://github.com/Archetom/atom-crm-web/blob/main/CONTRIBUTING.md)
- 安全问题请按对应仓库的安全政策私下报告：[后端](https://github.com/Archetom/atom-crm/blob/main/SECURITY.md) · [前端](https://github.com/Archetom/atom-crm-web/blob/main/SECURITY.md)。
