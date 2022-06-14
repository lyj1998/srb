# srb
一个简单的金融练手项目
# 01-尚融宝项目介绍



@[TOC](文章目录)

---

# 前言

尚融宝是一个网络借贷信息中介服务平台，为个人投资者、个人融资用户和小微企业提供专业的线上信贷及出借撮合服务。
行业案例：人人贷 https://www.renrendai.com/、拍拍贷 https://www.paipaidai.com/

---



# 一、课程介绍
![](https://img-blog.csdnimg.cn/cd0c9ab6686148a8a26ac3594f11eb67.png)

# 二、项目架构
![](https://img-blog.csdnimg.cn/fe02b86639ca4730b7def7549bc7f9e7.png)
①：用户通过不同的终端访问应用程序
②：终端经由cdn网络或防火墙访问nginx集群
③：穿过负载均衡服务器后来到前端服务器集群
④：前端服务器通过微服务网关将业务请求分发到微服务模块
⑤：微服务与微服务之间通过Feign作远程访问
⑥：通过sentinel做云端保护和限流
⑦：所有的服务器会在nacos注册中心和配置中心的治理下工作
⑧：云服务器存储用的是阿里云oss

# 三、项目功能演示
## 1.后台管理系统!
![在这里插入图片描述](https://img-blog.csdnimg.cn/9a82232a26144acc8e98050e0eeec26c.png)

## 2.前台网站系统
![在这里插入图片描述](https://img-blog.csdnimg.cn/aeb3a83ff7c34dac8ad5ead6723b1037.png)
# 五、业务流程总结
![在这里插入图片描述](https://img-blog.csdnimg.cn/b7a857cdc7604fa2a8e3574676c94a15.png)


