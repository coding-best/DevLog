# Spring-boot-Web 项目

## 期望功能
- [x] 快速构建SpringBoot 微服务后台
- [x] 增加  JPA 编写 DAO 层
- [x] 使用 swagger2 编写 Api 文档
- [ ] 增加 Spring Cache 集成 Redis 注解缓存
- [ ] 尝试 Rocket MQ 消息队列推送


## 开发日志
- 2018.10.07 【初始化】初始化搭建项目基础框架，基础包设计，集成 Spring-boot, Swagger，Guava
- 2018.10.08 【新增】增加 JPA 依赖，新增 UserDO 模型，生成相关数据库表 't_szcoders_web_user' & 'hibernate_sequence'（自动生成）
- 2018.10.28 【新增】
	- 增加 User 相关 Controller & Service & DAO
	- 使用 JPA 编写 DAO 层，操作数据库
	- 使用 Swagger2 编写接口文档