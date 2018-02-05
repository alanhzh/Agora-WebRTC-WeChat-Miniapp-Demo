# Agora Web SDK(WebRTC) 与微信小程序 WebView 的集成示例

在这个示例项目中包含了以下功能：

- 使用微信小程序 WebView 控件集 成 Agora Web SDK
- 目前该示例不支持 iOS 设备

## 准备环境
- 准备一个已经集成了 Agora Web SDK 的线上环境，可以参见 [Agora-Web-Tutorial-1to1](https://github.com/AgoraIO/Agora-Web-Tutorial-1to1)
- 准备一个小程序开发者账号

## 配置工作
- 在小程序控制界面将您配置线上 Agora Web SDK 的环境的域名加入信任列表
- 线上环境的域名必须已备案，且以 .com 结尾，不然摄像头权限会获取失败。

## 运行示例程序
1. 修改 project.config.json，在 appid 中填入您自己的小程序 appid
2. 修改 index.wxml，将里面的 src 指向您的线上环境地址
3. 使用小程序开发工具打开项目，然后预览示例即可

## 联系我们

- 完整的 API 文档见 [文档中心](https://docs.agora.io/cn/)
- 如果在集成中遇到问题, 你可以到 [开发者社区](https://dev.agora.io/cn/) 提问
- 如果有售前咨询问题, 可以拨打 400 632 6626，或加入官方Q群 12742516 提问
- 如果需要售后技术支持, 你可以在 [Agora Dashboard](https://dashboard.agora.io) 提交工单
- 如果发现了示例代码的bug, 欢迎提交 [issue](https://github.com/AgoraIO/Agora-WebRTC-WeChat-Miniapp-Demo/issues)

## 代码许可

The MIT License (MIT).
