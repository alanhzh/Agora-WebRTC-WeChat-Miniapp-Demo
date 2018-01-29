# Agora WebRTC与微信小程序WebView的集成示例

在这个示例项目中包含了以下功能：

- 使用微信小程序WebView控件集成Agora WebRTC SDK

## 准备环境
- 准备一个已经集成了Agora WebRTC的线上环境
- 准备一个小程序开发者账号

## 配置工作
- 在小程序控制界面将您配置线上Agora WebRTC的环境的域名加入信任列表
- 线上环境的域名必须已备案，且以com结尾，不然摄像头权限会获取失败。

## 运行示例程序
1. 修改project.config.json，在appid中填入您自己的小程序appid
2. 修改index.wxml，将里面的src指向您的线上Agora WebRTC地址
3. 使用小程序开发工具打开项目，然后预览示例即可

## 联系我们

- 完整的 API 文档见 [文档中心](https://docs.agora.io/cn/)
- 如果在集成中遇到问题, 你可以到 [开发者社区](https://dev.agora.io/cn/) 提问
- 如果有售前咨询问题, 可以拨打 400 632 6626，或加入官方Q群 12742516 提问
- 如果需要售后技术支持, 你可以在 [Agora Dashboard](https://dashboard.agora.io) 提交工单
- 如果发现了示例代码的bug, 欢迎提交 [issue](https://github.com/AgoraIO/Agora-iOS-Tutorial-Swift-1to1/issues)

## 代码许可

The MIT License (MIT).
