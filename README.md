# tmall 基于天猫的仿写商城系统
## 项目介绍
使用了SpringBoot + SSM 框架整合的一个模拟天猫电商系统,前端使用了Vue.js实现前后端分离项目
项目地址[tmall](http://106.13.178.79 "tmall")
## 主要功能模块
#### 购物车模块
- 立即购买
- 加入购物车
- 查看购物车页面
- 购物车页面增加删除结算

#### 订单模块
- 生成订单
- 确认支付
- 后台发货
- 确认收货
--评价

#### 后台增删查改
- 分类,产品,属性,用户的CRUD,产品图片上传

#### 产品展示
- 首页推送
- 产品排序

#### 搜索查询
- 基于ElasticSearch实现的产品信息检索

#### 登录验证
- 基于Shiro 实现的登录注册(加盐),以及登录验证

#### 缓存处理
- 基于Redis的 全站热点数据缓存
