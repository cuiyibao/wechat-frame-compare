<!--
 * @Description: 文件描述
 * @Author: yb001
 * @Date: 2019-05-30 19:22:21
 * @LastEditTime: 2019-05-31 11:37:48
 * @LastEditors: yb001
 -->
# 小程序工程化

* 参考网站：https://juejin.im/post/5c66724bf265da2dea0514e5#heading-20

## 原生小程序的坑

* 小程序本身不支持常用的css预编译器,导致样式规范随意散落在各个文件，无法统一进行管理，而现代前端开发中不论是less,sass,stylus 都可以提升css效率；
* 缺少统一的request拦截请求；
* 缺少统一的路由管理；
* 缺少集中式的API地址和ENV环境变量管理；
* 缺少统一的本地缓存读取管理；
* 重复的webview页面；
* 不支持ES7以上的高级语法，如async await等特性；
* 不管是体验版还是开发版只能存在一种环境，一旦发布预览测试环境切换繁琐；
* 上线前需要手动修改线上环境，容易出错......

## 构建工具确定（倾向glup）

## 项目模板搭建

### 使用css预处理器（less）

### 引入组件库（vant-weapp）

### 公共代码封装（request、router）

### API地址和ENV环境管理

### 统一的webview

### 解决多环境切换问题

### 自动打包部署环境