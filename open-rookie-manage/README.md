# open-rookie

#### 介绍

    open-rookie-manage后台管理系统第一阶段项目,整体框架参考ruoyi-cloud
    前端技术栈 ES6、vue、vuex、vue-router、vue-cli、axios、element-ui
    后端技术栈 Spring Boot、Spring Cloud & Alibaba、Nacos、Sentinel


#### 软件架构

    open-rookie-manage          -- 后端框架
        ├── open-rookie-ui              // 前端框架 [80]
        ├── open-rookie-gateway         // 网关模块 [8080]
        ├── open-rookie-auth            // 认证中心 [9200]
        ├── open-rookie-api             // 接口模块
        │       └── open-rookie-api-system                          // 系统接口
        ├── open-rookie-common          // 通用模块
        │       └── open-rookie-common-core                         // 核心模块
        │       └── open-rookie-common-datascope                    // 权限范围
        │       └── open-rookie-common-datasource                   // 多数据源
        │       └── open-rookie-common-log                          // 日志记录
        │       └── open-rookie-common-redis                        // 缓存服务
        │       └── open-rookie-common-seata                        // 分布式事务
        │       └── open-rookie-common-security                     // 安全模块
        │       └── open-rookie-common-swagger                      // 系统接口
        ├── open-rookie-modules         // 业务模块
        │       └── open-rookie-system                              // 系统模块 [9201]
        │       └── open-rookie-gen                                 // 代码生成 [9202]
        │       └── open-rookie-job                                 // 定时任务 [9203]
        │       └── open-rookie-file                                // 文件服务 [9300]
        ├── open-rookie-visual          // 图形化管理模块
        │       └── open-rookie-visual-monitor                      // 监控中心 [9100]
        ├──pom.xml                // 公共依赖

#### 安装教程



#### 使用说明



#### 参与贡献




#### 特技

