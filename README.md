# Java健康档案管理系统 health-record

#### 介绍

 **SpringBoot2.X VUE2.6 Antd1.7.2  TkMyBatis Shiro1.5.0 Java1.8 管理系统 JVM 权限设计 可作为毕业设计和快速开发 健康管理系统** 

#### 联系作者

 **见文末** 

#### 演示地址
```
https://binfenyeke.com/admin-platform-health
账号: admin
密码: 123456
```
若演示地址不可用，可翻到文末扫码联系作者微信或者留言

#### 软件架构说明

#### 前端技术架构

1. Antd-VUE
2. 页面,按钮级别权限控制。
3. 多个组件封装，调用方便。
4. Antv图表组件。
5. WebPack
6. ES6
7. 多环境打包。
8. VUE路由，过滤器，自定义指令。
9. 代码简洁，符合编码规范。

#### 后端技术架构

1. SpringBoot2.x
2. Shiro权限框架
3. Redis6.X最新版
4. MyBatis注解版
5. MySQL6.7
6. 分模块开发，自定义启动脚本，JVM调优
7. 多环境,前后端完全分离。
8. 代码生成器。
9. orika传输对象映射器。

#### 系统截图展示

1. 系统登陆注册
- 登陆界面
![登陆界面](https://images.gitee.com/uploads/images/2021/0407/144617_c84a3623_1808544.png "登陆界面.png")
- 用户注册
![输入图片说明](https://images.gitee.com/uploads/images/2021/0407/144643_c4a01d2a_1808544.png "用户注册.png")

2. 系统管理模块
- 系统主页
![输入图片说明](https://images.gitee.com/uploads/images/2021/0407/144723_bfe25e6e_1808544.png "系统主页.png")

- 菜单管理
![输入图片说明](https://images.gitee.com/uploads/images/2021/0407/144745_f1bfae94_1808544.png "菜单管理.png")

- 角色管理
![输入图片说明](https://images.gitee.com/uploads/images/2021/0407/144814_fdd13577_1808544.png "角色管理.png")

- 系统用户管理
![输入图片说明](https://images.gitee.com/uploads/images/2021/0407/144848_377d684e_1808544.png "系统用户.png")

3. 系统监控模块

- 系统日志
![输入图片说明](https://images.gitee.com/uploads/images/2021/0407/144924_3b2f4530_1808544.png "系统日志.png")

- 系统监控-服务器
![输入图片说明](https://images.gitee.com/uploads/images/2021/0407/144951_63057840_1808544.png "系统监控-服务器.png")

- 系统监控-JVM
![输入图片说明](https://images.gitee.com/uploads/images/2021/0407/145009_3c73aff7_1808544.png "系统监控-JVM.png")

- 系统日志
![输入图片说明](https://images.gitee.com/uploads/images/2021/0407/145030_74ace011_1808544.png "系统日志.png")

- 请求追踪
![输入图片说明](https://images.gitee.com/uploads/images/2021/0407/145038_8c739825_1808544.png "请求追踪.png")

4. 健康管理模块

- 健康档案管理
![输入图片说明](https://images.gitee.com/uploads/images/2021/0407/145122_17407462_1808544.png "健康档案管理.png")

- 健康监测
![输入图片说明](https://images.gitee.com/uploads/images/2021/0407/145138_fa124982_1808544.png "健康监测.png")

- 健康知识
![输入图片说明](https://images.gitee.com/uploads/images/2021/0407/145159_66366c52_1808544.png "健康知识.png")

- 我的留言
![输入图片说明](https://images.gitee.com/uploads/images/2021/0407/145225_51519baa_1808544.png "我的留言.png")

- 留言管理
![输入图片说明](https://images.gitee.com/uploads/images/2021/0407/145241_5989aa4f_1808544.png "留言管理.png")

#### 项目代码展示

1. 前端VUE代码截图展示
![前端代码](https://singer-coder-public.oss-cn-chengdu.aliyuncs.com/%E5%89%8D%E7%AB%AFVUE%E4%BB%A3%E7%A0%81%E6%88%AA%E5%9B%BE.png "前端代码.png")

2. 后端Java代码截图展示
![后端代码](https://singer-coder-public.oss-cn-chengdu.aliyuncs.com/%E5%90%8E%E7%AB%AF%E4%BB%A3%E7%A0%81%E6%88%AA%E5%9B%BE%E5%B1%95%E7%A4%BA.png "后端代码.png")

#### 系统功能模块概要
+ 系统登陆/注册
+ 系统主页
  - 系统主页折线图统计
    * 系统主页折线图统计
    + 系统模块导航
    - 系统在线数，访问数统计
+ 系统管理
  - 系统用户管理
    * 系统用户条件查询
    + 系统用户修改
    - 系统用户删除
	- 系统用户新增
  - 系统菜单管理
    * 系统菜单条件查询
    + 系统菜单修改(可级联修改)
    - 系统菜单删除
	- 系统菜单新增
  - 系统角色管理
    * 系统角色条件查询
    + 系统角色修改
    - 系统角色删除
	- 系统角色新增
  - 系统字典管理
    * 系统字典条件查询
    + 系统字典修改
    - 系统字典删除
	- 系统字典新增
+ 系统监控
  - 在线用户管理
    * 在线用户条件查询
    + 在线用户踢出
  - 系统日志管理
    * 系统日志条件查询
    + 系统日志分析
	+ 系统访问IP分析
  - 系统请求追踪
    * 请求耗时追踪
    + 请求方法追踪
	+ 请求URL追踪
	+ 请响应状态追踪
  - 系统信息
    * JVM信息监控
    + 服务器信息监控
	+ 请求URL追踪
	+ 请响应状态追踪
+ 健康档案
  - 健康档案管理
    * 健康档案条件查询
    + 健康档案新增
	* 健康档案修改
    + 健康档案批量删除
+ 留言信息管理
  - 留言列表
    * 留言列表条件查询
    + 留言列表新增
	* 留言列表修改
    + 留言列表批量删除
	+ 查看留言
  - 我的留言
    * 留言列表条件查询
    + 留言列表新增
	* 留言列表修改
    + 留言列表批量删除
	+ 查看留言
+ 健康监测管理
  - 监测记录
    * 监测记录条件查询
    + 监测记录新增
	* 监测记录修改
    + 监测记录批量删除
+ 健康知识管理
  - 健康知识
    * 健康知识条件查询
    + 健康知识新增
	* 健康知识修改
    + 健康知识批量删除

#### 演示地址
```
https://binfenyeke.com/admin-platform-health
账号: admin
密码: 123456
```
若演示地址不可用，可扫码联系作者微信或者留言

####  **联系作者** 

 **这是作者的微信二维码，如需本项目源代码，可扫码联系联系作者。 17381852768 微信同号**  

![微信二维码-1](https://singer-coder-public.oss-cn-chengdu.aliyuncs.com/%E5%BE%AE%E4%BF%A1%E4%BA%8C%E7%BB%B4%E7%A0%81-1.png "微信二维码-1.png")

**这是作者的技术技术交流群二维码，如已过期请扫码联系作者拉群** 

![输入图片说明](https://singer-coder-public.oss-cn-chengdu.aliyuncs.com/%E6%8A%80%E6%9C%AF%E4%BA%A4%E6%B5%81%E7%BE%A4.png "技术交流群.png")

#### 安装教程

#### 后端安装方法
1.  mvn clean package
2.  tar -zxvf health-record-api.tar.gz (解压tar包)
3.  cd health-record-api
5.  sh /sbin/startup.sh dev

#### 前端安装方法
1.  yarn install (安装node_moudle)
2.  yarn start (启动)
3.  yarn build:pro (构建生产包)
#### 使用说明

见上面安装方法

#### 参与贡献
1.  Fork 本仓库
2.  新建 Feature_xxx 分支
3.  提交代码
4.  新建 Pull Request
