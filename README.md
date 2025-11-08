# 前言

随着移动互联网的发展，线上订餐已经成为现代大学生日常生活的一部分。本项目旨在设计并开发一款基于微信小程序的高校订餐系统，为广大师生提供便捷、高效的餐饮服务。

## 内容介绍

本项目主要包括以下几个模块：用户模块、商家模块、菜品模块、订单模块和支付模块。用户可以通过微信小程序浏览附近商家的菜品信息，进行在线点餐、支付和评价。商家可以通过后台管理系统发布菜品信息、处理订单和查看营业数据。系统采用SSM框架（Spring、SpringMVC、MyBatis）进行开发，保证了项目的高效性和稳定性。

## 技术介绍

- **语言：** Java
- **使用框架：** Spring、SpringMVC、MyBatis，微信小程序
- **前端技术：** JS、Vue、CSS3，Uniapp
- **开发工具：** IDEA/Eclipse，Uniapp
- **数据库：** MySQL 5.7/8.0
- **数据库管理工具：** phpstudy/Navicat
- **JDK版本：** jdk1.8
- **Maven：** apache-maven 3.8.1-bin
- **前端环境：** Node.Js 12\14\16

## 核心代码

以下是项目中的一段核心代码，展示了如何通过MyBatis实现菜品信息的查询：

```java
// Mapper接口
public interface DishesMapper {
    List<Dishes> selectDishesByCategoryId(int categoryId);
}

// Mapper XML配置
<select id="selectDishesByCategoryId" resultType="Dishes">
    SELECT * FROM dishes WHERE category_id = #{categoryId}
</select>
```

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

## 项目截图
![封面图片](https://img11.360buyimg.com/ddimg/jfs/t1/324553/2/19835/101847/68c59b4eFc5b6f5f8/bbb8d5be72f22c26.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/336640/38/10493/69313/68c59b26Fcc671f61/fc373166cc488817.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/329574/29/12852/59477/68c59b26Fd5e1f922/5cc5131bf7fd4df4.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/328902/9/19600/36438/68c59b27F44bf31ed/939474f2bc6d0846.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/327043/30/19378/42430/68c59b27Fd7eefeb0/013d59c322824e8f.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/325467/30/19550/33979/68c59b27F1ca68af7/e269a9ff6ecd0a9a.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/328925/23/19509/25547/68c59b27F7c8bb1e2/ff4235ba1972cba8.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/340753/38/10417/31949/68c59b27Fc68979bf/f51583b36c39f622.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/348178/27/2359/15971/68c59b27F2d6ad61d/303adb1ba5d336f1.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/327383/29/19794/37149/68c59b28F431de07b/e72267619bce36b9.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
