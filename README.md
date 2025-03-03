# esp32
esp32


## hardware

ESP32-S3-DevKitC-1（选择 WROOM N16R8 模组）
ep32-s3-n16r8

https://docs.espressif.com/projects/esp-dev-kits/zh_CN/latest/esp32s3/esp32-s3-devkitc-1/user_guide.html#id11

## project

```
client:
https://github.com/78/xiaozhi-esp32
server:
https://github.com/xinnan-tech/xiaozhi-esp32-server
```


## enviroment

### doc

```
https://ccnphfhqs21z.feishu.cn/wiki/F5krwD16viZoF0kKkvDcrZNYnhb
https://idf.espressif.com/zh-cn/index.html
https://docs.espressif.com/projects/esp-idf/zh_CN/latest/esp32s3/get-started/linux-macos-setup.html
```


## build

### config 

```
idf.py menuconfig
```

```

idf.py set-target esp32s3
```

### build

```
idf.py build
```

### download software

```
idf.py build flash monitor
```

### monitor 
```
idf.py -p COM3 monitor
idf.py -p PORT monitor
```

## xiaozhi-esp32

如果你已经拥有一个小智 AI 聊天机器人设备，可以登录 [xiaozhi.me](https://xiaozhi.me) 控制台进行配置。

👉 [后台操作视频教程（旧版界面）](https://www.bilibili.com/video/BV1jUCUY2EKM/)

## 技术原理与私有化部署

👉 [一份详细的 WebSocket 通信协议文档](docs/websocket.md)

在个人电脑上部署服务器，可以参考另一位作者同样以 MIT 许可证开源的项目 [xiaozhi-esp32-server](https://github.com/xinnan-tech/xiaozhi-esp32-server)
