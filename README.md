# Tubumu

## 概述

1. [Orchard Core Framework](https://orchardcore.readthedocs.io/en/latest/)
2. [EntityFramework Core](https://docs.microsoft.com/en-us/ef/core/) (Microsoft SQL Server)
3. [Redis](https://github.com/MicrosoftArchive/redis/releases)
4. [Jwt](https://jwt.io/)
5. [Swagger](https://swagger.io/)
6. [SignalR](https://docs.microsoft.com/zh-cn/aspnet/core/signalr/introduction?view=aspnetcore-2.2)
7. [AutoMapper](http://automapper.org/)
8. [NLog](https://www.nuget.org/packages/NLog.Web.AspNetCore/) (Base on OrchardCore.Logging.NLog)
9. [Vue](https://cn.vuejs.org/) ([Element-UI](http://element-cn.eleme.io/#/zh-CN))

## 安装

1. 安装 [Redis](https://github.com/MicrosoftArchive/redis/releases)
2. 还原数据库：src\Database\Tubumu.bak
3. 打开解决方案
4. 在 appsettings.json 中修改数据库连接字符串
5. 运行
6. 请求：<http://localhost:5000/Login>

> 测试账号：system, admin
> 测试密码：111111

## 已知问题

1. CKFinder 不可用。尝试集成 RoxyFileman 但有些问题。
2. Remote 验证邮箱、用户名或手机是否存在尚未移植完成。
3. Cors 尚未测试。