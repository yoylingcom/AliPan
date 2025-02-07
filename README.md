# 阿里云盘列表程序 - Spring Boot

## 演示及开发环境

> https://pan.rawchen.com
>
> JDK 8 + IDEA 2021.2.3

## 使用

* 确保java8及以上环境，在[releases](https://github.com/rawchen/AliPan/releases)页面下载jar运行文件。
* 通过`java -jar AliPan.jar`运行该程序，默认访问地址：[http://localhost:8899](http://localhost:8899)。
* 通过以下 [refresh_token获取方法](https://pan.rawchen.com/token)拿到后，粘贴到jar包同路径下生成的配置文件`AliPanConfig`中（可记事本编辑）。

## 开发

* 确保java8及以上环境，下载项目后通过IDEA打开，可配置application.yml中的端口号等，通过Maven打包jar运行，没有IDEA也可配置Maven命令执行`mvn clean package`。

**refresh_token获取方法：**
> https://pan.rawchen.com/token


## 功能（持续开发中）
* - [x] Thymeleaf模板引擎
* - [x] 展示文件夹与文件列表
* - [x] 文件在线查看（各类图片、文档、文本、音频、视频、PDF等）
* - [x] 分享链接
* - [x] 目录树
* - [x] README.md
* - [x] 目录树监听
* - [x] 右键弹出菜单
* - [x] 文件夹加密
* - [x] 后台自定义配置
* - [x] 后退监听
* - [x] RefreshToken续期
* - [x] 手机谷歌、夸克浏览器下载
* - [x] 调用PotPlayer
* - [x] 调用迅雷下载

## 高级

在`application.yml`中你可以自定义`parent_file_id`(要展示的节点目录)。
需要密码保护文件夹则新建`password`文件放置该文件夹。
注意该密码文件无任何后缀名，在`application.yml`可自定义加密文件名。

## 案例截图

![](https://cdn.jsdelivr.net/gh/rawchen/JsDelivr/static/AliPan/01.png)

![](https://cdn.jsdelivr.net/gh/rawchen/JsDelivr/static/AliPan/02.png)

![](https://cdn.jsdelivr.net/gh/rawchen/JsDelivr/static/AliPan/03.png)