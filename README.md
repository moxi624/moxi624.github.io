<p align=center>
  <a href="http://www.moguit.cn">
    <img src="./doc/images/gitee/favicon2.ico" alt="蘑菇博客" style="width:200px;height:200px">
  </a>
</p>
<p align=center>
   蘑菇博客，一个基于微服务架构的前后端分离博客系统
</p>
<p align="center">
<a target="_blank" href="https://www.oracle.com/technetwork/java/javase/downloads/index.html">
    	<img src="https://img.shields.io/hexpm/l/plug.svg" ></img>
		<img src="https://img.shields.io/badge/JDK-1.8+-green.svg" ></img>
        <img src="https://img.shields.io/badge/springboot-2.2.2.RELEASE-green" ></img>
<img src="https://img.shields.io/badge/SpringCloud-Hoxton.RELEASE-brightgreen" ></img><img src="https://img.shields.io/badge/vue-2.5.17-green" ></img>
<img src="https://img.shields.io/badge/swagger-2.6.1-green" ></img>
<img src="https://img.shields.io/badge/mybatis--plus-3.1.2-green" ></img></a></p>

## 站点演示

首先特别感谢阿里云提供的 [学生“在家实践” 计划](https://developer.aliyun.com/adc/student/?spm=a2c6h.14062461.J_7747362070.1.5b6933e1X3rvHS)，免费提供的6个月的2核4G 1M的服务器，所以就刚好以此用来做蘑菇博客的演示站点，同时我也在搭建的时候，顺便录制了一套视频：[利用阿里云免费服务器搭建个人博客](https://www.bilibili.com/video/BV1c5411b7EZ?t=17) ，感兴趣的小伙伴可以参考视频一起完成部署~

> 【演示前端】：http://demoweb.moguit.cn/
>
> 【演示后端】：http://demoadmin.moguit.cn/
>
> 【演示账号】：mogu2018   mogu2018

## 项目地址

目前项目托管在Gitee和Github平台上中，欢迎大家star 和 fork 支持~

- Gitee地址：https://gitee.com/moxi159753/mogu_blog_v2
- Github地址：https://github.com/moxi624/mogu_blog_v2

##  运行配置

蘑菇博客使用了一些监控的Spring Cloud组件，但是并不一定都需要部署，必须启动的服务包含

`nacos`，`nginx`，`rabbitmq`， `redis`，`mysql`，`mogu-sms`，`mogu-picture`， `mogu-web`, `mogu-admin`

其它的服务都可以不启动，也不影正常使用，可以根据自身服务器配置来启动

最低配置：1核2G `需要开启虚拟内存`

推荐配置：2核4G【双十一特惠】

> 【阿里云】双十一拼团 2核4G3M 664元/3年（强烈推荐） [点我进入](http://a.aliyun.com/f1.l0DRK)
>
> 【阿里云】云服务器双11狂欢特惠，1核2G 最低仅需84.97元/年  [点我传送](https://www.aliyun.com/1111/home?userCode=w7aungxw)
>
> 【腾讯云】双十一活动2核4G 100G盘700元/3年（老用户重新用微信QQ注册即可） [点我进入](https://curl.qcloud.com/8Nfp3pRy)

## 关注&交流

刚刚创建了一个QQ群<a target="_blank" href="//shang.qq.com/wpa/qunwpa?idkey=88bc57d77601a3c5ae97fe6d9c0bfa25c2ae166d8f0b9f6da6f7294097be6d08"><img border="0" src="./doc/images/qq/group.png" alt="蘑菇博客交流群" title="蘑菇博客交流群"></a>，目前项目还存在很多不足之处，欢迎各位老哥进群交流~

|                QQ群（备注：蘑菇博客）                 |               QQ（备注：蘑菇博客）               |
| :---------------------------------------------------: | :----------------------------------------------: |
| <img src="./doc/images/qq/qqGroup.png" width="200" /> | <img src="./doc/images/qq/qq.png" width="200" /> |

## 视频教程

特别感谢 [俺是程序狮](https://space.bilibili.com/277038643) 在B站上给蘑菇博客录制的视频教程，课程讲的非常细致，手把手带着开发博客系统，感兴趣的小伙伴可以去学习和支持一下~

- [项目介绍](https://www.bilibili.com/video/BV1Si4y1u7H4)
- [结构介绍与本地Nginx本地图片服务器启动](https://www.bilibili.com/video/BV1AA411e7W5)
- [mysql脚本准备](https://www.bilibili.com/video/BV1kv411v7ND)
- [后台服务启动](https://www.bilibili.com/video/BV1Nv411i7wu)
- [RabbitMQ启动](https://www.bilibili.com/video/BV1mD4y1U7GT)
- [前端项目启动](https://www.bilibili.com/video/BV1B541187Ez)
- [后台管理系统的前端工程结构介绍](https://www.bilibili.com/video/BV1D54y1U78F)
- [后台管理系统登录页](https://www.bilibili.com/video/BV1854y127d6)
- [后台管理系统登录页2](https://www.bilibili.com/video/BV1DD4y1d7Tx)
- [登录页请求处理](https://www.bilibili.com/video/BV1aT4y1w7Ux)
- [前端发起登录认证](https://www.bilibili.com/video/BV1Rp4y1Y7fj)
- [vuerouter路由配置](https://www.bilibili.com/video/BV14A411n72S)
- .....