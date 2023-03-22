# koa-app
从0到1搭建一个koa 管理系统服务端
|-- koa-app
    |-- .babelrc										配置使用注解
    |-- .gitignore									git忽略项
    |-- app.js											主入口
    |-- package.json								
    |-- pnpm-lock.yaml							
    |-- bin													启动文件夹
    |   |-- www.js									启动配置
    |-- config											配置文件夹
    |   |-- config.js								配置文件--密钥--MySQL--Redis
    |   |-- httpRes.js							接口返回配置
    |   |-- swaggerDec.js						文档配置
    |-- controller									控制层--处理接口
    |   |-- user.js									
    |-- logs												日志存放文件夹
    |   |-- all-logs.log
    |   |-- log.2023-03-21.log
    |   |-- log.2023-03-22.log
    |-- middlewares									中间件
    |   |-- auth.js									接口权限判断
    |   |-- exception.js						错误处理
    |   |-- logger.js								日志打印
    |-- models											和数据库交互
    |   |-- user.js
    |-- routers											路由--使用swagger后可以删除
    |   |-- auth.js
    |   |-- index.js
    |   |-- user.js
    |-- sequelize										数据库表和实例
    |   |-- index.js
    |   |-- user.js
    |-- services										服务层
    |   |-- user.js
    |-- utils												工具类
        |-- error.js								错误工具类
        |-- log.js									日志工具类
        |-- redis.js								redis
        |-- success.js							成功工具类
        |-- token.js								签发和解析token
