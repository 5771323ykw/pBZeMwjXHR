# 课堂管理系统 java142

## 项目概述

课堂管理系统是基于Spring Boot和Vue的前后端分离系统。系统包括教师授课管理、学生选退课、聊天室、签到和笔记管理等模块，致力于提高课堂互动与效率。

## 技术栈

- 后端：Spring Boot、MyBatis、Redis、WebSocket
- 前端：VueCLI、Axios、Element UI

## 功能模块

### 课程管理模块

- 教师功能：添加、编辑、删除课程
- 学生功能：选课、退课

### 聊天室

- 在线用户列表查看
- 实时聊天功能

### 签到模块

- 教师端发起课程签到，生成签到码
- 学生端输入签到码完成签到，状态实时更新

### 笔记管理

- 浏览公开笔记
- 使用MarkDown语法添加和编辑笔记

## 系统角色

- 教师
- 学生

## 运行环境

- 后端项目：`classroom-manager`
- 前端项目：`classroom-manager-front`
- 建议使用Node服务器运行前端项目

## 部署步骤

（具体部署步骤根据实际情况编写）

1. 部署后端项目到服务器
2. 配置数据库和Redis
3. 部署前端项目到Node服务器
4. 配置WebSocket端口

## 目录结构

```
项目目录/
├── classroom-manager          # 后端项目
└── classroom-manager-front    # 前端项目
```

## 核心亮点

- 使用MyBatis和Redis优化数据库操作
- 整合WebSocket实现实时信息转发
- 引入Axios及配置代理服务器解决跨域问题
- 使用js-cookie管理用户登录状态
- 支持MarkDown语法编辑笔记，引入Mavon-Editor插件

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)


## 项目截图

![](https://img10.360buyimg.com/ddimg/jfs/t1/343715/9/6503/25110/68d2e4d3F9886bce3/25d20dea07b165f2.jpg)

![](https://img12.360buyimg.com/ddimg/jfs/t1/343288/34/6501/24517/68d2e4d3F1898be52/f17e40495b4d5d75.jpg)

![](https://img11.360buyimg.com/ddimg/jfs/t1/349731/30/6257/26743/68d2e4d4F1bc8f38c/b1942623b334c37f.jpg)

![](https://img11.360buyimg.com/ddimg/jfs/t1/331248/31/16666/24001/68d2e4d4F7102580c/9b09bc44e07a9caf.jpg)

![](https://img13.360buyimg.com/ddimg/jfs/t1/331070/18/15947/31557/68d2e4d4F83bf1513/b26965020447ad33.jpg)

![](https://img10.360buyimg.com/ddimg/jfs/t1/347706/20/6765/25649/68d2e4d4Fef1b5e4d/138c938ea57835f2.jpg)

![](https://img13.360buyimg.com/ddimg/jfs/t1/288763/40/24815/36699/68d2e4d5F3861b66c/40d2bb1d6adff34e.jpg)

