# koa-ts-server-template

## 介绍

koa的ts模板,并接入规范化工具

commit规范化遵从[Angular commit message规范](https://github.com/angular/angular/blob/master/CONTRIBUTING.md#commit)

### 用到的中间件

1. 解析请求：koa-bodyparser
2. 路由：@koa/router
3. 压缩：koa-compress
4. 缓存：koa-etag
5. 日志：koa-logger
6. 中间件管理：koa-compose 
7. session : koa-session