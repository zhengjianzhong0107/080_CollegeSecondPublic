---
### 👉作者QQ ：1556708905 微信：zheng0123Long (支持修改、部署调试、定制毕设)

### 👉接网站建设、小程序、H5、APP、各种系统等

### 👉选题+开题报告+任务书+程序定制+安装调试+ppt 都可以做
---

**毕业设计所有选题地址 [https://github.com/zhengjianzhong0107/allProject](https://github.com/zhengjianzhong0107/allProject)**

**博客地址：
[https://blog.csdn.net/2303_76227485/article/details/131516110](https://blog.csdn.net/2303_76227485/article/details/131516110)**

**视频演示：
[https://www.bilibili.com/video/BV1EX4y1v7eg/](https://www.bilibili.com/video/BV1EX4y1v7eg/)**

 

## 基于springboot+vue的高校二手交易系统(源代码+数据库)080

## 一、系统介绍

本项目前后端分离

本系统分为管理员、用户两种角色

用户角色包含以下功能：

- 登录、注册、(商品搜索、发布、收藏、下单)、评论、个人信息修改、密码修改、我的发布、我的订单、收藏夹

管理员角色包含以下功能：

- 登录、首页统计、用户管理、管理员管理、订单管理、商品管理、个人中心、密码修改

## 二、所用技术

后端技术栈：

- springboot
- JWT
- mysql
- mybatis
- 

前端技术栈：

- Vue
- Axios
- Echarts
- ElementUI

## 三、环境介绍

基础环境 :IDEA/eclipse, JDK1.8, Mysql5.7及以上, Maven3.6, node14

所有项目以及源代码本人均调试运行无问题 可支持远程调试运行

## 四、页面截图

![contents](./picture/picture1.png)
![contents](./picture/picture2.png)
![contents](./picture/picture3.png)
![contents](./picture/picture4.png)
![contents](./picture/picture5.png)
![contents](./picture/picture6.png)
![contents](./picture/picture7.png)
![contents](./picture/picture8.png)
![contents](./picture/picture9.png)
![contents](./picture/picture10.png)
![contents](./picture/picture11.png)
![contents](./picture/picture12.png)
![contents](./picture/picture13.png)
![contents](./picture/picture14.png)
![contents](./picture/picture15.png)
![contents](./picture/picture16.png)
![contents](./picture/picture17.png)
![contents](./picture/picture18.png)
![contents](./picture/picture19.png)
![contents](./picture/picture20.png)

## 五、浏览地址

前台访问地址：http://localhost:81/shop
-用户账号/密码：李四/123456

后台访问地址：http://localhost:81/login
-管理员账号/密码：admin/123456

## 六、部署教程

1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并执行项目的sql文件；

2. 使用IDEA/Eclipse导入CollegeSecondSpringboot项目，若为maven项目请选择maven，等待依赖下载完成；

3. 进入src/main/resources修改application.yml 里面的数据库配置和files/upload/path的图片路径

4. 启动主类src/main/java/com/example/collegesecondhand_springboot/CollegeSecondHandSpringbootApplication.java

5. vscode或idea打开CollegeSecondVue项目，

6. 在编译器中打开terminal，执行npm install 依赖下载完成后执行 npm run serve,执行成功后会显示访问地址

## 七、细节描述：

1、对 Axios 进行二次封装 ，模块化管理API接口。

2、使用 Vue-Route 向路由对象添加新路由 ，完成对用户路由权限的管理。

3、使用 Token对用户身份进行验证，通过路由守卫对登录状态以及接口请求进行基于 JWT 的页面拦截。

4、使用 Echarts 绘制条形图 、柱状图动态显示实时数据。

 
