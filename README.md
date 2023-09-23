# Lucky-API-Frontend

## 项目介绍

Lucky-API 接口开放平台前端代码仓库。 这是一个提供 API 接口供开发者调用的平台用户可以登录、注册，开通接口调用权限。接口的调用会被统计，后续可能收费。管理员可以发布接口、下线接口、接入接口，以及在线调试接口。

## 项目背景

1. 前端开发都需要使用后端接口来获取数据。
2. 网上有很多现成的 API 接口调用平台

自己动手做一个 API 接口平台：

1. 用户可以访问前台，登录、注册，开通、关闭接口调用权限。
2. 管理员可以对接口进行增删改查

要求：

1. 防止攻击（安全性）
2. 不能随意调用（限制、开通）
3. 统计调用次数
4. 流量保护
5. API 接入

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

## 项目界面

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
