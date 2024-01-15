---
title: Go Proxy Bingai
emoji: 🌍
colorFrom: gray
colorTo: indigo
sdk: docker
pinned: false
---

# go-proxy-bingai在huggingface教程

## 一键部署地址

一键部署地址，使用作者镜像：https://huggingface.co/spaces/Harry-zklcdc/go-proxy-bingai?duplicate=true&visibility=public

一键部署地址，使用冻死企鹅镜像：https://huggingface.co/spaces/dongsiqie/bing?duplicate=true&visibility=public

## 环境变量

需要两个必填的环境变量Space variables Public

`USER_KievRPSSecAuth`：随便填写一个字符串，也可以生成一个uuid填写进去，作用是免登陆

`HEADLESS`：固定值 false，huggingface部署必须传这个参数，否则无法自动过机器人验证

## 使用教程

部署完成以后，可以直接免登陆使用

如果需要画图或者使用插件，必须使用cookie登陆才可以，以下链接可以获取自己的cookie然后填写到`go-proxy-bingai`镜像中

[国内免魔法获取cookie](https://dongsiqie.me/wiki/bingcookie3.html)
