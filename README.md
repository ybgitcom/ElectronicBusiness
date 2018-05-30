# ElectronicBusiness
c
共十二天的内容。
第一天：了解电商行业、了解淘淘商城。后台工程搭建。框架整合ssm。
第二天：商品管理。商品列表展示。商品添加中的商品类目选择。
第三天：商品添加：上传图片。Nginx、FastDFS。
第四天：商品添加实现：富文本编辑器的使用、商品的规格参数实现。
第五天：前台系统搭建。展示首页、展示商品类目。
第六天、第七天：首页大广告位的展示。Cms系统实现、redis缓存（集群）首页大广告位展示。
第八天：搜索功能的实现。使用solr实现（solr集群）。
第九天：商品详情页面实现，网页静态化freemaker实现。
第十天：单点登录系统实现，session共享。
第十一天：购物车、订单系统
第十二天：Quartz任务调度框架。项目部署、项目总结。


技术选型
数据库：mysql
Dao层：mybatis、数据库连接池（德鲁伊druid）
缓存：redis
搜索：solr
Service层：spring
表现层：springmvc、jstl、EasyUI、jsp、freemaker
图片服务器：FastDFS（分布式文件系统）
反向代理服务器：nginx
定时器：Quartz
Web服务器：tomcat
工程管理：maven


一、Dao层：整合mybatis和spring
需要的jar包：
1、mybatis的jar包
2、Mysql数据库驱动
3、数据库连接池
4、Mybatis和spring的整合包。
5、Spring的jar包
配置文件：
1、mybatis的配置文件：SqlMapConfig.xml
2、Spring的配置文件：applicationContext-dao.xml
1、数据源
