# EasiAuth
基于WPF和.NET6开发，通过模拟 `EasiAgent` 来实现希沃白板的免密自动登录。

## Thanks

ENAL [去Aiwb查看该项目](https://github.com/Awesome-Iwb/Awesome-Iwb?tab=readme-ov-file#-enal-%E5%B8%8C%E6%B2%83%E6%98%93%E7%99%BB)

开发这个项目是为了解决 ENAL 的一些问题，同时也提供了一个开源的 `EasiAgent` 模拟的实现。（ENAL 其实挺好用的，坏就坏在他不开源，所以我就想自己写一个，是这样的。 🤓☝️ ）

## Features

1. 使用手机号和密码实现希沃系列软件免密登录。
2. 支持设置后台管理密码。
3. 极低的资源占用，使用 WPF 开发，开源免费。
4. 支持配置文件热重载，支持远程集控。
5. 支持自定义账号昵称，支持自定义头像。
6. 使用 MVVM 架构开发。

## Packages

1. `CommunityToolkit.Mvvm`
2. `Microsoft.Extensions.Hosting`
3. `Microsoft.Toolkit.Uwp.Notifications`
4. `Microsoft.Windows.Compatibility`
5. `Microsoft.Xaml.Behaviors.Wpf`
6. `Newtonsoft.Json`
7. `EmbedIO`
8. `Flurl.Http`

## License

![GitHub License](https://img.shields.io/github/license/Awesome-Iwb/EasiAuth)

> © Copyright 2024-2025 **Chency Lew**. All rights reserved.