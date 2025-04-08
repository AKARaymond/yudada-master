项目简介
这是一个面向真实业务场景的企业级 AI 答题应用平台，基于 Vue 3 + Spring Boot + Redis + ChatGLM + RxJava + SSE 等前后端主流技术栈构建，实现了从答题应用创建、发布、分享、答题到智能总结的完整闭环。

该平台支持用户快速生成个性化答题应用，提供 AI 驱动的答题体验与自动总结能力，便于分享和传播；管理员具备全面的内容审核与平台运营管理功能，支持多维度的数据统计分析。

技术架构
后端技术栈（Spring Boot）
核心框架：Spring Boot（主框架）、MyBatis-Plus & MyBatisX（ORM 与代码自动生成）

存储系统：

MySQL（关系型数据库）

Redis（缓存中间件）

腾讯云 COS（文件对象存储）

性能与分布式能力：

Redisson 分布式锁 + 雪花算法（ID 生成）

ShardingSphere 分库分表架构

Caffeine 本地缓存（热点数据优化）

异步与响应式：

RxJava 响应式编程框架

自定义线程池隔离机制

SSE（Server-Sent Events）实现服务端消息推送

AI 能力集成：

集成 ChatGLM 大语言模型 实现答题总结与智能对话

高可用设计：

幂等性保障机制

多种设计模式应用（如策略模式、责任链模式）

多维优化策略（性能、稳定性、成本、产品体验）

前端技术栈（Vue + Taro）
Web 前端（Vue 3）
框架与工具：

Vue 3 + Vue CLI

TypeScript + ESLint + Prettier（前端工程化）

组件与状态管理：

Arco Design UI 组件库

Pinia 状态管理

Axios（请求库）

功能模块：

富文本编辑器（答题配置）

QRCode.js 二维码生成

OpenAPI 自动生成 API 接口代码

小程序端（Taro + React）
Taro 跨端开发框架（支持微信小程序、H5）

React 框架构建

Taro UI 组件库

开发工具
JetBrains WebStorm（前端开发）

JetBrains IntelliJ IDEA（后端开发）

CodeGeeX（智能编程助手）
