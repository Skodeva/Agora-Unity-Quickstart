# Hello Unity3D Agora

*Read this in other languages: [English](README.en.md)*

这个开源示例项目演示了如何在 Unity3D 中快速集成 Agora Unity SDK，实现在 Unity 中的音频通话。

在这个示例项目中包含了以下功能：

- 加入通话和离开通话；

你也可以在这里查看进阶版的示例项目：[Spacewar-with-AMG-Voice-SDK-Unity](https://github.com/AgoraIO/Spacewar-with-AMG-Voice-SDK-Unity)


## 运行示例程序
首先在 [Agora.io 注册](https://dashboard.agora.io/cn/signup/) 注册账号，并创建自己的测试项目，获取到 AppID。将 AppID 填写进 HelloUnity3D.cs

```
private static string appId = "YOUR APP ID";
```

然后在 [Agora.io SDK](https://www.agora.io/cn/blog/download/) 下载 **Agora Unity SDK**，解压后

- 把SDK中 **libs/Android/** 下的内容，复制到项目的 **Assets/Plugins/Android/AgoraAudioKit.plugin/libs/** 文件夹下
- 把SDK中 **libs/iOS/** 下的内容，复制到项目的 **Assets/Plugins/iOS/** 文件夹下
- 把SDK中 **libs/macOS/** 下的内容，复制到项目的 **Assets/Plugins/macOS/** 文件夹下
- 把SDK中 **libs/x86/** 下的内容，复制到项目的 **Assets/Plugins/x86/** 文件夹下
- 把SDK中 **libs/x86_64/** 下的内容，复制到项目的 **Assets/Plugins/x86_64/** 文件夹下
- 把SDK中 **libs/Scripts/AgoraGamingSDK/** 下的内容，复制到项目的 **Assets/Scripts/AgoraGamingSDK/** 文件夹下

最后使用 Unity 打开本项目即可运行。

## 运行环境
* Unity 5.5 +

## 联系我们

- 完整的 API 文档见 [文档中心](https://docs.agora.io/cn/)
- 如果在集成中遇到问题, 你可以到 [开发者社区](https://dev.agora.io/cn/) 提问
- 如果有售前咨询问题, 可以拨打 400 632 6626，或加入官方Q群 12742516 提问
- 如果需要售后技术支持, 你可以在 [Agora Dashboard](https://dashboard.agora.io) 提交工单
- 如果发现了示例代码的bug, 欢迎提交 [issue](https://github.com/AgoraIO/Hello-Unity3D-Agora/issues)

## 代码许可

The MIT License (MIT).
