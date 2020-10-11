# V2Ray Heroku

## 警告⚠：此技术仅限用于个人查看学术或科研娱乐使用！！！若用于其他违法目的，后果自负！！！

## 概述

用于在 Heroku 上部署 V2Ray Websocket + tls

## 镜像

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://dashboard.heroku.com/new?template=https%3A%2F%2Fgithub.com%2FHXHGTS%2Fv2ray-heroku)

## ENV 设定

### UUID生成方法

Windows下用cmd执行:
```
powershell [guid]::NewGuid() | find /v "Guid" | find /v "--" | find "-"
```
Linux下用bash执行:
```
uuidgen
```
## 注意

部署时一定不要用默认的uuid，记得替换！！！

WebSocket 路径为 `/`。

`alterId` 为 `2`。
