# jeebiz-xxljob

#### 组件简介

> 基于 [xxl-job](https://www.xuxueli.com/xxl-job/) 源代码的扩展

- 增加服务端接口，用于客户端自动注册任务
- 配合 [xxljob-spring-boot-starter](https://github.com/hiwepy/xxljob-spring-boot-starter) 实现客户端任务自动注册与启动

#### 使用说明


##### 2、在`application.yml`文件中指定数据库

```yaml
spring: 
  # 数据源配置：
  datasource:
    type: com.alibaba.druid.pool.DruidDataSource
    driver-class-name: com.mysql.cj.jdbc.Driver
    url: jdbc:mysql://47.96.82.188:3306/xxl-job?zeroDateTimeBehavior=convertToNull&useUnicode=true&characterEncoding=UTF-8&allowMultiQueries=true
    username: xxl-job
    password: 6kDrpABLjMXGFNdc
```

## Jeebiz 技术社区

Jeebiz 技术社区 **微信公共号**、**小程序**，欢迎关注反馈意见和一起交流，关注公众号回复「Jeebiz」拉你入群。

|公共号|小程序|
|---|---|
| ![](https://raw.githubusercontent.com/hiwepy/static/main/images/qrcode_for_gh_1d965ea2dfd1_344.jpg)| ![](https://raw.githubusercontent.com/hiwepy/static/main/images/gh_09d7d00da63e_344.jpg)|