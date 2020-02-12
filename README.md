<h1 align="center">Serverless 框架开发资源汇总</h1>

本文收集了基于 Serverless 框架开发过程中会使用到的资料、问题以及第三方组件库。本文不是一遍关于如何学习 Serverless 框架开发的入门指南，只是一些资料的整理。

## 技术交流群

- Serverless 框架开发QQ群：`871445853`
- Serverless 框架开发微信群：`serverlesscloud`，（先添加群助手，备注后进群）

## 目录

- [官方文档](#官方文档)
- [社区](#社区)
- [组件](#组件)
- [开发模板](#开发模板)
- [案例](#案例)
- [实践文章](#实践文章)
- [贡献者](#贡献者)

## 置顶

- [Serverless 开发框架](https://github.com/serverless/serverless) 💯
- [Serverless 开发组件](https://github.com/serverless/components) 💯
- [腾讯云 Serverless Components 开发模板](https://github.com/yugasun/serverless-component-template) 💯

## 官方文档

- [Serverless Framework 介绍](https://serverless.com/framework/docs/)
- [Serverless Components 开发指南](https://serverless.com/blog/what-are-serverless-components-how-use/)

[↑ 返回目录 ↑](#目录)

## 社区

- [Serverless Framework 官方社区](https://serverless.com/blog/)
- [Serverless Framework 中文社区](https://serverlesscloud.cn)

[↑ 返回目录 ↑](#目录)

## 组件

- [@serverless/website](https://github.com/serverless-components/website) - 快速部署静态网站到 AWS S3
- [@serverless/backend](https://github.com/serverless-components/backend) - 快速部署后端服务到 AWS Lambda
- [@serverless/backend-socket](https://github.com/serverless-components/backend-socket) - 快速部署 WebSocket 后端服务到 AWS Lambda
- [@serverless/api](https://github.com/serverless-components/api) - AWS API网关组件
- [@serverless/cdn](https://github.com/serverless-components/cdn) - AWS CDN组件
- [@serverless/aws-dynamodb](https://github.com/serverless-components/aws-dynamodb) - AWS DynamoDB 组件
- [@serverless/tencent-apigateway](https://github.com/serverless-components/tencent-apigateway) - 腾讯云API网关组件
- [@serverless/tencent-cos](https://github.com/serverless-components/tencent-cos) - 腾讯云云对象存储组件
- [@serverless/tencent-scf](https://github.com/serverless-components/tencent-scf) - 腾讯云函数组件
- [@serverless/tencent-express](https://github.com/serverless-components/tencent-express) - 快速部署基于 Express.js 的后端服务到腾讯云函数的组件
- [@serverless/tencent-koa](https://github.com/serverless-components/tencent-koa) - 快速部署基于 Koa.js 的后端服务到腾讯云函数的组件
- [@serverless/tencent-website](https://github.com/serverless-components/tencent-website) - 快速部署静态网站到腾讯云的组件
- [@serverless/tencent-cdn](https://github.com/serverless-components/tencent-cdn) - 腾讯云 CDN 组件
- [@serverless/tencent-flask](https://github.com/serverless-components/tencent-flask) - 腾讯云 Flask 框架组件
- [@serverless/tencent-egg](https://github.com/serverless-components/tencent-egg) - 腾讯云 Egg.js 框架组件
- [@serverless/tencent-laravel](https://github.com/serverless-components/tencent-laravel) - 腾讯云 Laravel 框架组件
- [@serverless/tencent-websocket](https://github.com/serverless-components/tencent-websocket) - 腾讯云 Websockets 组件
- [@twn39/tencent-fastify](https://github.com/twn39/tencent-fastify) - 快速部署基于 fastify.js 的后端服务到腾讯云函数的组件
- [@twn39/tencent-php-slim](https://github.com/twn39/tencent-php-slim) - 快速部署基于 Slim PHP 微框架的后端服务到腾讯云函数的组件

[↑ 返回目录 ↑](#目录)


## 开发模板

模板使用方法，例如使用 [fullstack-application-vue](https://github.com/yugasun/tencent-serverless-demo/tree/master/fullstack-application-vue) 模板创建项目

全局安装 `serverless cli`

```bash
$ npm intstall serverless -g
```

下载项目模板：

```bash
$ serverless create --template-url https://github.com/yugasun/tencent-serverless-demo/tree/master/fullstack-application-vue
```

- [aws-app-sync-dynamodb](https://github.com/serverless/components/tree/master/templates/aws-app-sync-dynamodb) - GraphQL + DynamoDB 的API服务（AWS）
- [backend-monolith](https://github.com/serverless/components/tree/master/templates/backend-monolith) - 全面的后端服务（AWS）
- [backend-websocket](https://github.com/serverless/components/tree/master/templates/backend-websocket) - 含有实时 WebSocket API 的后端服务（AWS）
- [nextjs](https://github.com/serverless/components/tree/master/templates/website) - 基于 Next.js 框架的全栈模板（AWS）
- [fullstack-application](https://github.com/serverless/components/tree/master/templates/fullstack-application) - 基于 React.js 全栈开发（AWS）
- [backend-microservices](https://github.com/serverless/components/tree/master/templates/backend-microservices) - 后端微服务（AWS）
- [aws-lambda-function](https://github.com/serverless/components/tree/master/templates/aws-lambda-function) - 云函数（AWS）
- [tencent-python-rest-api](https://github.com/serverless/components/tree/master/templates/tencent-python-rest-api) - 基于 Python 的 RESTful API（腾讯云）
- [tencent-fullstack-vue-application](https://github.com/serverless/components/tree/master/templates/tencent-fullstack-vue-application) - 基于Vue.js全栈开发1（腾讯云）
- [fullstack-application-vue](https://github.com/yugasun/tencent-serverless-demo/tree/master/fullstack-application-vue) - 基于 Vue.js 全栈开发2（腾讯云）
- [tencent-fullstack-vue-application](https://github.com/serverless/components/tree/master/templates/tencent-fullstack-vue-application) - 基于 React.js 全栈开发（腾讯云）
- [tencent-eggjs](https://github.com/serverless/components/tree/master/templates/tencent-eggjs) - Egg.js 框架的开发模板（腾讯云）
- [tencent-flask](https://github.com/serverless/components/tree/master/templates/tencent-flask) - Flask 框架开发模板（腾讯云）
- [tencent-laravel](https://github.com/serverless/components/tree/master/templates/tencent-laravel) - Laravel 框架开发模板（腾讯云）
- [admin-system](https://github.com/yugasun/tencent-serverless-demo/tree/master/fullstack-application-vue) - Serverless + Egg.js 后台管理系统（腾讯云）

[↑ 返回目录 ↑](#目录)

## 案例

- [yugasun/tencent-serverless-demo](https://github.com/yugasun/tencent-serverless-demo) - 基于腾讯云无服务开发案例合集

[↑ 返回目录 ↑](#目录)

## 实践文章

- [Serverless 应用开发指南](https://serverless.ink/)
- [Serverless 实践博客](https://yugasun.com/)
- [玩转 Serverless - 知乎专栏](https://zhuanlan.zhihu.com/ServerlessGo)

[↑ 返回目录 ↑](#目录)

## 贡献者

[贡献者名单](https://github.com/yugasun/awesome-serverless-framework/graphs/contributors)

[↑ 返回目录 ↑](#目录)
