<!--
 * @Description: 文件描述
 * @Author: cuiyibao001
 * @Date: 2019-05-27 12:08:21
 * @LastEditTime: 2019-05-30 17:39:19
 * @LastEditors: cuiyibao001
 -->
# 小程序框架对比

## chameleon (DD)

* 开源时间短，不兼容支付宝、百度、头条小程序

## mpvue (MT)

* 维护力度差，一套代码不能兼容H5和小程序，想兼容H5需修改部分代码

## taro (JD)

* react系写法，维护力度强，ui组件文档不完善

## uni-app (Dcloud)

* 依赖开发工具HBuilderX，部分源代码不开源

## wepy (TX)

* 不兼容H5

## star数对比(2018-07-23)

* wepy(12000+) > mpvue(11000+) > taro(6000+)

## star数对比(2019-05-27)

* taro(18773) > wepy(17806) > mpvue(17472) > uni-app(7537) > chameleon(5138)

## 框架 选择Taro

* 类react写法，符合团队现用的技术栈

* 维护力度强，star数增长快

* 业务主要需兼容H5和微信小程序两部分，taro可以很好的兼容

## 组件库 选择vant-weapp

* taro-ui的文档不够完善，可视化没有做

* 现有的微信组件库只有vant-weapp的文档做了可视化

* vant-weapp风格比较简单，容易做包装
