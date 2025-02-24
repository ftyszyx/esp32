# esp32
esp32


## hardware

ESP32-S3-DevKitC-1（选择 WROOM N16R8 模组）


## project

```
https://github.com/78/xiaozhi-esp32
```


## enviroment

### doc

```
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