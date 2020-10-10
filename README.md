# V2Ray Heroku

## 概述

用于在 Heroku 上部署 V2Ray Websocket + tls

## 镜像

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://dashboard.heroku.com/new?template=https%3A%2F%2Fgithub.com%2FHXHGTS%2Fv2ray-heroku)

## ENV 设定

### UUID

Windows下用cmd执行:
```
powershell [guid]::NewGuid() | find /v \"Guid\" | find /v \"--\" | find \"-\"
```

## 注意

WebSocket 路径为 `/`。

`alterId` 为 `2`。
