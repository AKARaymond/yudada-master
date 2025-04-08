# AI 答题应用平台

一个面向真实业务场景的企业级 AI 答题应用平台，基于 **Vue 3 + Spring Boot + Redis + ChatGLM + RxJava + SSE** 等主流技术栈，实现了从答题应用创建、发布、分享、答题到智能总结的完整闭环。

用户可以快速生成个性化答题应用，体验 AI 驱动的答题与总结流程；管理员具备全面的审核、管理与数据分析功能，支持整个平台的内容和用户管理。

---

## 🚀 项目亮点

- 💡 支持 AI 智能生成题目与总结
- 📊 实现答题评分与统计分析
- 🔍 支持答题应用的搜索与分享
- 🔧 管理端支持内容审核与系统运维
- 📈 多维度性能与架构优化实践

---

## 🏗️ 技术架构

### 后端技术栈（Spring Boot）

- **开发框架**：Spring Boot + MyBatis-Plus + MyBatisX
- **数据库与缓存**：
  - MySQL（关系型数据库）
  - Redis（缓存中间件）
  - 腾讯云 COS（对象存储）
- **性能与分布式支持**：
  - Redisson 分布式锁 + 雪花算法（唯一 ID 生成）
  - ShardingSphere 分库分表支持
  - Caffeine 本地缓存提升访问效率
- **异步处理与消息推送**：
  - RxJava 响应式编程
  - 自定义线程池隔离
  - SSE（服务端推送机制）
- **AI 能力接入**：
  - 集成 ChatGLM 大语言模型，支持自然语言理解与生成
- **高可用设计**：
  - 幂等性保障
  - 多种设计模式（策略模式、责任链模式等）
  - 多维优化：性能 / 成本 / 稳定性 / 产品体验

---

### 前端技术栈（Vue 3）

- **工程化工具**：
  - Vue 3 + Vue CLI + TypeScript
  - ESLint + Prettier 代码规范
- **功能与组件**：
  - Arco Design UI 组件库
  - Pinia 状态管理
  - Axios 请求封装
  - 富文本编辑器
  - QRCode.js 二维码生成
  - OpenAPI 自动生成前端接口代码

---

### 💻 开发工具

- JetBrains WebStorm（前端 IDE）
- JetBrains IntelliJ IDEA（后端 IDE）
- CodeGeeX 智能编程助手

---

## 📷 系统架构图

![系统架构图](./架构图文件名.png) <!-- 将文件名替换为你上传的架构图图片名 -->

---

## 📝 TODO

- [ ] 用户行为日志采集
- [ ] 支持更多题型（选择题 / 判断题 / 图文题等）
- [ ] 接入更多大模型（如 GLM-4、文心一言等）
- [ ] 自动化测试与部署

---

## 📄 License

MIT License - Feel free to use and contribute!
