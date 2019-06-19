# 联系方式
- 手机：13388611621
- Email：shengchaojie@163.com
- 微信：chaojiesuper

# 个人信息

 - 盛超杰/男/1992
 - 本科/浙江海洋大学计算机系
 - 工作年限：5年
 - 技术博客：[https://www.jianshu.com/u/eccd5acf909e](https://www.jianshu.com/u/eccd5acf909e)
 - Github: [https://github.com/shengchaojie](https://github.com/shengchaojie)

 - 期望职位：资深Java开发工程师
 - 期望薪资：税前月薪24~30K，特别喜欢的公司可例外
 - 期望城市：杭州


# 工作经历

## 大搜车 （ 2018年10月 ~ 至今 ）
- 核心开发
- 项目管理相关工作，保障项目按时高质量上线。
- 定期在团队进行技术分享，其中Dubbo源码解析在公司内再次分享。

### 供应链金融项目
供应链项目主要产品为接车贷，库融贷，订单贷，服务于车商，解决车商资金流问题。后端开发团队一共6人，每3人进行一个版本开发，我负责其中一个组的PM以及核心开发。

- 团队中人员水平参差不齐，代码质量很差，bug很多，我承担代码质量的OKR，将代码提交流程改为Merge Reuqest，根据代码中存在问题沉淀后端编码规范，负责Code Review ,总结每一个版本存在的问题，提高了提测质量以及线上bug率。
- 供应链项目的业务流程节点众多，代码臃肿不堪，在库融贷那期开发中，将每一个节点封装成Action,将公用逻辑上沉，变化逻辑通过SPI实现，使其符合对修改封闭，对扩展开放的设计原则。在这个重构基础上，订单贷的开发周期很短。
- 金融项目的核心是资金方，我们项目在逐步介入各个资金方，在代码中出现很多的if/else语句，通过门面模式，将资金方的路由封装在门面类里，使其符合对修改封闭，对扩展开放的设计原则。
- 在项目做自动化测试中，不希望自动化的数据影响到其他服务，也不希望其他服务的下线影响到我们运行的自动化脚本，针对Dubbo接口开发 DubboEasyMock方案，将需要mock的接口转发到EasyMock上面。第一版采用Filter机制，发现依赖服务下线会影响Mock执行，第二版参考MockClusterWrapper通过SPI的包装类包装Cluster，使其不通过Cluster调用直接转发到EasyMock。该插件推广全部门使用，并且为公司申请专利。
- 服务化重构交易域以及应用域。
### 商城中台
商城作为一个中台项目，对接各个业务方的商城需求，虽然现在还存在定制化开发，我们的愿景是通过不断打磨，成为一个即插即用的项目。目前开发3人，我负责项目管理以及核心开发。
- 项目中订单下单逻辑，并且各个业务方的逻辑不尽相同，通过策略模式对订单校验以及订单组装，同步订单中心，同步支付中心等逻辑重构，通过Context不同走对应不同策略，保障业务的快速接入。
- 负责订单域以及履约域的开发
- 持续重构

## 桔瓣科技 （ 2017年9月 ~ 2018年10月 ）
- 核心开发
- 部分版本项目管理
### 同城配送项目
- TBD

### 单点登陆以及权限中心项目
- TBD

# 技能清单

以下均为我熟练使用的技能

- 前端框架：React/ANTD
- java框架：Spring/Dubbo/TTL/Guava/Mybatis/Disconf/ElasticJob等
- 数据库相关：MySQL/MongoDB/Redis
- 中间件相关：RocketMQ/Zookeeper/Logstash/FileBeat等
- 容器相关：Docker/Rancher
- 其他工具：Charles/plantUML/OmniGraffle/Xmind

# 致谢
感谢您花时间阅读我的简历，期待能有机会和您共事。

