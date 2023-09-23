# Lucky-API-Frontend

## 项目介绍
> 一个丰富的 API 开放调用平台，提供了一些接口调用服务，方便大家使用。
> 
> 基于 **Spring Boot + Dubbo + Spring Cloud Alibaba + MyBatis Plus + Redis + React** 的 API 接口开放调用平台。这是一个提供 API 接口供开发者调用的平台，用户可以登录、注册，开通接口调用权限。接口的调用会被统计，后续可能收费。管理员可以发布接口、下线接口、接入接口，以及在线调试接口。
>
> 这是一个全栈前后端分离项目，仍有不足和需要扩展的地方，后续还会继续扩展优化。
>
> 后端代码仓库：https://github.com/T1uck/luckyApi-backend


## 项目背景

API平台有很多，但是不够统一，本平台帮助企业、个人统一开放接口，减少沟通成本，避免重复造轮子，为业务高效赋能。

**Lucky API平台力求给用户提供简洁、实用的接口调用体验，并且使用API签名校验保障接口调用的安全性**

## 技术选型

### 前端

-   Ant Design Pro
-   React
-   Ant Design Procomponents
-   Umi
-   Umi Request（Axios 的封装）

### 后端

-   Spring Boot
-   Spring Cloud Gateway
-   Dobbo
-   Nacos
-   Spring Boot Starter（SDK 开发）

## 功能模块 

> 🌟 亮点功能   
>
> 🚀 未来计划

- 用户、管理员
  - 登录注册注销
  - 个人主页
  - 管理员：接口管理
  - 管理员：接口分析
  
- 接口
  - 浏览接口信息
  - 🌟 数字签名校验接口调用权限
  - 🌟 SDK调用接口
  - 用户上传自己的接口（🚀）

## 项目展示

登陆界面

![image](https://github.com/T1uck/luckyApi-frontend/blob/master/public/api/%E7%99%BB%E9%99%86%E7%95%8C%E9%9D%A2.png)

API 商城界面

![image](https://github.com/T1uck/luckyApi-frontend/blob/master/public/api/API%E5%95%86%E5%9F%8E%E7%95%8C%E9%9D%A2.png)

接口调用界面

![image](https://github.com/T1uck/luckyApi-frontend/blob/master/public/api/%E6%8E%A5%E5%8F%A3%E8%B0%83%E7%94%A8%E7%95%8C%E9%9D%A2.png)

接口管理界面（管理员）

![image](https://github.com/T1uck/luckyApi-frontend/blob/master/public/api/%E6%8E%A5%E5%8F%A3%E7%AE%A1%E7%90%86%E7%95%8C%E9%9D%A2.png)

接口统计界面（管理员）

![image](https://github.com/T1uck/luckyApi-frontend/blob/master/public/api/%E6%8E%A5%E5%8F%A3%E7%BB%9F%E8%AE%A1%E5%88%86%E6%9E%90%E7%95%8C%E9%9D%A2.png)

个人中心界面

![image](https://github.com/T1uck/luckyApi-frontend/blob/master/public/api/%E4%B8%AA%E4%BA%BA%E4%B8%AD%E5%BF%83%E7%95%8C%E9%9D%A2.png)

## 快速上手

### 后端

1. 将各模块配置修改成你自己对应的端口、账号、密码等等
2. 启动Nacos、Mysql、Redis（如需修改依赖版本，请自行查找对应适配版本）
3. 将公共服务 easyapi-common 以及下载的 SDK 安装（install）到本地maven仓库
4. 按顺序启动服务

服务启动顺序如下，仅供参考：

1. easyapi-backend

2. easyapi-interface

3. easyapi-gateway

### 前端

环境要求：Node.js >= 16

安装依赖：

```
npm i @ant-design/pro-cli -g
npm i
```

启动：

```
npm run start:dev
```
