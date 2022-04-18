# sfu-demo
基于 `medooze-media-server` 的 webrtc sfu demo，供学习使用。

This demo forked from [medooze/sfu](https://github.com/medooze/sfu)

## 1. 克隆项目
```bash
$ git clone git@github.com:1eeing/sfu-demo.git
```

## 2. 安装依赖
```bash
$ npm install
```

## 3. 配置 https 证书文件
在根目录下创建 certs 文件夹，将自己的 `cert.pem` 和 `key.pem` 文件放入其中

## 4. 启动项目
```bash
$ npm start
```

## QA
- 1. 原版 demo 中的视频加密的写法似乎已经在最新的 webrtc 接口定义中找不到了，估计是废弃了，因此加入房间时第三个输入框 `key` 不要输入
