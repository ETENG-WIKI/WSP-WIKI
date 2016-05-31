# 微信相关工具集

## [ngrok](https://ngrok.com/) 内网穿透

用于将内网端口映射到外网域名

* [下载](https://ngrok.com/download)

*  新建自定义配置文件ngrok.yml

```
authtoken: [注册登录获取](https://dashboard.ngrok.com/auth)
tunnels:
  wx:
    proto: http
    addr: 28080
    subdomain: wxzxh
```
*  启动本地 8080 端口，地址会映射到https://wxzxh.ngrok.io

```
ngrok start -config ngrok.yml wx
```

## [国内ngrok内网穿透服务](https://www.zhihu.com/question/38150862)


