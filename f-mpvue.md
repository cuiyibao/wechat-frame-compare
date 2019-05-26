# Mpvue

## 基本介绍

* mpvue 是一个使用 Vue.js 开发小程序的前端框架。框架基于 Vue.js 核心，mpvue 修改了 Vue.js 的 runtime 和 compiler 实现，使其可以运行在小程序环境中，从而为小程序开发引入了整套 Vue.js 开发体验。

* github地址：https://github.com/Meituan-Dianping/mpvue

* 中文文档：http://mpvue.com/#_1

## 兼容性

* 微信小程序、支付宝小程序、百度小程序、头条小程序

## DSL

* vue语法，采用.vue

## 主要特性

* 彻底的组件化开发能力：提高代码复用性
* 完整的 Vue.js 开发体验
* 方便的 Vuex 数据管理方案：方便构建复杂应用
* 快捷的 webpack 构建机制：自定义构建策略、开发阶段 hotReload
* 支持使用 npm 外部依赖
* 使用 Vue.js 命令行工具 vue-cli 快速初始化项目
* H5 代码转换编译成小程序目标代码的能力

## 配套设施

* mpvue-loader 提供 webpack 版本的加载器
* mpvue-webpack-target webpack 构建目标
* postcss-mpvue-wxss 样式代码转换预处理工具
* px2rpx-loader 样式转化插件
* mpvue-quickstart mpvue-quickstart
* mpvue-simple 辅助 mpvue 快速开发 Page / Component 级小程序页面的工具
* 其它

## 框架原理

* mpvue 保留了 vue.runtime 核心方法，无缝继承了 Vue.js 的基础能力
* mpvue-template-compiler 提供了将 vue 的模板语法转换到小程序的 wxml 语法的能力
* 修改了 vue 的建构配置，使之构建出符合小程序项目结构的代码格式： json/wxml/wxss/js 文件

## 生命周期

![Image text](./img/mpvue/frame-cycle.jpg)

## 缺点

* 代码更新处于停滞不前的状态
* 文档维护力度差  最近更新日期：2018.8.10
