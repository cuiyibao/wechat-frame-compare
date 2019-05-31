<!--
 * @Description: 文件描述
 * @Author: yb001
 * @Date: 2019-05-30 18:04:05
 * @LastEditTime: 2019-05-30 19:19:09
 * @LastEditors: yb001
 -->
# 小程序框架选型之路

* 最近凹凸实验室搞了一波《小程序多端框架全面测评》，uni-app团队投入一周写多个平台的测试demo完成了深度测试，参考两个文章进行了小程序框架选型

## 多端框架选择

* wepy只支持小程序

* taro提供taro convert把原生小程序代码的转taro代码，语法支持不全，且编译过程经常会出现路径错误、转换错误、语义错误等问题，日志打印的错误可查找性很差，编译过程的报错会直接报到taroize相关的文件解析代码

* taro官方文档支持混写（https://nervjs.github.io/taro/docs/hybrid.html），可惜官网的例子就跑不起来，没人维护，尝试使用混写写demo，各种报错


## H5页面需兼容现有的SSR框架