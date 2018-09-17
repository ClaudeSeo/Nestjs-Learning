# Nest.js 教程

如果喜欢本教程请点击右上角的 star 🌟，想订阅本教程请点击右上角 watch 👀

如有不解之惑，或是想要更多的详细教程，可以在 [New Issues](https://github.com/dzzzzzy/Nestjs-Learning/issues/new) 中写下你的问题或需求。

## 框架介绍

Nest 是构建高效，可扩展的 Node.js Web 应用程序的框架。 它使用现代的 JavaScript 或 TypeScript（保留与纯 JavaScript 的兼容性），并结合 OOP（面向对象编程），FP（函数式编程）和 FRP（函数响应式编程）的元素。

在底层，Nest 使用了 [Express](https://github.com/expressjs/express)，但也提供了与其他各种库的兼容，例如 [Fastify](https://github.com/fastify/fastify)，可以方便地使用各种可用的第三方插件。

### 主要特性

- 使用 Typescript，强类型语言、类型推断机制、编译期类型检查等，为后端开发和维护提供了很好的支持
- 模块化开发，让应用程序更容易分层，提供了易于使用的模块化管理机制
- 内置 IOC 容器，大量使用依赖注入，开发更便捷、更高效
- 轻松编写 AOP 代码，面向切面编程，轻松实现日志、拦截器、过滤器等功能
- 支持 TypeORM，最好的 Typescript ORM 框架，轻松编写 DAO 层的各类逻辑
- 轻松构建 MVC、API、websocket、微服务、等系统
- ......

### 框架 Github 地址: [Nest](https://github.com/nestjs/nest) 🎁

## 框架文档

[官方文档](https://docs.nestjs.com)

[中文文档](https://docs.nestjs.cn)

----------

## 相关技术

- [NodeJS](https://nodejs.org)
  - [v10文档(最新)](https://nodejs.org/dist/latest-v10.x/docs/api/)
- [Typescript](https://www.typescriptlang.org)
  - 📚 [官方文档](https://www.typescriptlang.org/docs/home.html)
  - 📚 [中文文档](https://www.tslang.cn/docs/home.html)
- [GraphQL](https://github.com/graphql/graphql-js)
  - 📚 [官方文档](https://graphql.org)
  - 📚 [中文文档](https://graphql.cn)
  - GraphQL IDE [graphql-playground](https://github.com/prisma/graphql-playground)
- [TypeORM](https://github.com/typeorm/typeorm)
  - 📚 [官方文档](http://typeorm.io)
- ......

----------

## Nest 学习手册

- 基础
  - [Controller](./docs/controller.md)
  - Provider
  - Module
  - Middleware
  - Exception Filter
  - Pipe
  - Guard
  - Interceptor

## Demo

- [CRUD Restful API Demo](./demo/rest-api/README.md)
- [GraphQL API Demo](./demo/graphql-api/README.md)

## TypeORM 问题汇总

- [分页查询问题](./issues/typeorm/pagination/README.md)

----------

***TODO***

- [ ] 相关技术学习总结
- [ ] 开发技巧总结
- [ ] 常见问题汇总
- [ ] demo
