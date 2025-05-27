# README

## 测试环境数据库
docker run -itd --name tenheigh-mysl -p 3306:3306 -e MYSQL_ROOT_PASSWORD=12345678 mysql 

### 数据库
* name: tenheigh
* 字符集: utf8mb4
* collation: utf8mb4_general_ci

## 目录结构
* src 存放项目代码
* README.md 项目说明文档
    *  config 存放配置的bean
    *  controller 存放控制器
    *  dto 存放数据传输对象
    *  entity 存放实体类
    *  exception 存放异常类
    *  service 存放业务逻辑
    *  util 存放工具类
    