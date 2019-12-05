<h1 align="center">Serverless 框架开发资源汇总</h1>

本文收集了基于 Serverless 框架开发过程中会使用到的资料、问题以及第三方组件库。本文不是一遍关于如何学习 Serverless 框架开发的入门指南，只是一些资料的整理。

本仓库中的资料整理自网络，也有一些来自网友的推荐。在[这里](https://github.com/yugasun/awesome-serverless-framework/graphs/contributors)可以看到项目贡献者的完整名单。

## QQ交流群

- Serverless 框架开发交流群：871445853

## 目录

- [官方文档](#官方文档)
- [社区](#社区)
- [组件](#组件)
- [开发模板](#开发模板)
- [Demo](#demo)
- [实践文章](#实践文章)

## 置顶

- [Serverless 开发框架](https://github.com/serverless/serverless) 💯
- [Serverless 开发组件](https://github.com/serverless/components) 💯

## 官方文档

- [Serverless Framework 介绍](https://serverless.com/framework/docs/)
- [Serverless Components 开发指南](https://serverless.com/blog/what-are-serverless-components-how-use/)

[↑ 返回目录 ↑](#目录)

## 社区

- [Serverless Framework 官方社区](https://serverless.com/blog/)
- [Serverless Framework 中文社区](https://serverlesscloud.cn) 建设中...

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
- [@serverless/tencent-website](https://github.com/serverless-components/website) - 快速部署静态网站到腾讯云的组件

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
- [backend-websocket](https://github.com/serverless/components/tree/master/templates/backend-websocket) - 含有实时WebSocket APi的后端服务（AWS）
- [nextjs](https://github.com/serverless/components/tree/master/templates/website) - 基于 Next.js 框架的全栈模板（AWS）
- [fullstack-application](https://github.com/serverless/components/tree/master/templates/fullstack-application) - 基于React.js全栈开发（AWS）
- [backend-microservices](https://github.com/serverless/components/tree/master/templates/backend-microservices) - 后端微服务（AWS）
- [aws-lambda-function](https://github.com/serverless/components/tree/master/templates/aws-lambda-function) - 云函数（AWS）
- [tencent-python-rest-api](https://github.com/serverless/components/tree/master/templates/tencent-python-rest-api) - 基于Python的Restful API（腾讯云）
- [tencent-fullstack-vue-application](https://github.com/serverless/components/tree/master/templates/tencent-fullstack-vue-application) - 基于Vue.js全栈开发1（腾讯云）
- [fullstack-application-vue](https://github.com/yugasun/tencent-serverless-demo/tree/master/fullstack-application-vue) - 基于Vue.js全栈开发2（腾讯云）
- [tencent-fullstack-vue-application](https://github.com/serverless/components/tree/master/templates/tencent-fullstack-vue-application) - 基于React.js全栈开发（腾讯云）

[↑ 返回目录 ↑](#目录)

## Demo

- [yugasun/tencent-serverless-demo](https://github.com/yugasun/tencent-serverless-demo) - 基于腾讯云无服务开发合集

[↑ 返回目录 ↑](#目录)

## 实践文章

- [Serverless 实践篇](https://juejin.im/user/583b9227ac502e006c25d1a7/posts)

[↑ 返回目录 ↑](#目录)
