# TaskSprite/待办组件

TaskSprite 是一款 Windows 桌面待办工具。点击桌宠即可打开待办面板，随手记下今天要做的事。待办、设置和自定义桌宠图片保存在本机，无需注册账号。

**[下载 Windows x64 安装包（1.0.0）](https://github.com/fang-123559/TaskSprite-releases/releases/download/v1.0.0/TaskSprite_1.0.0_x64-setup.exe)** · [查看最新版与更新记录](https://github.com/fang-123559/TaskSprite-releases/releases/latest)

## 主要功能

- 用「今日」「逾期」「全部」查看待办，支持设置日期、标记完成和拖动排序。
- 拖动桌宠调整位置，或换成自己的图片。托盘菜单可以打开待办面板和切换置顶。
- 在设置或托盘菜单中切换「开启自启动」。默认关闭，开启后会随 Windows 登录启动。

## 安装与更新

1. 从上方链接下载 `.exe` 安装包。已有旧版时，先从系统托盘退出 TaskSprite。
2. 双击安装包并按提示完成安装。打开 TaskSprite 后，点击桌宠即可添加待办。
3. 以后可以从待办面板手动检查更新。应用内更新会验证 Tauri updater 签名。

<details>
<summary>核对安装包 SHA-256</summary>

下载同一版本的 [SHA256SUMS.txt](https://github.com/fang-123559/TaskSprite-releases/releases/download/v1.0.0/SHA256SUMS.txt)，在安装包所在文件夹打开 PowerShell，运行：

```powershell
Get-FileHash -Algorithm SHA256 -LiteralPath '.\TaskSprite_1.0.0_x64-setup.exe'
```

将输出的 `Hash` 与清单里的安装包记录核对。1.0.0 安装包没有 Authenticode 签名，Windows 可能显示「未知发布者」或 SmartScreen 提示。

</details>

## 隐私与许可

查看[隐私说明](./PRIVACY.md)。第三方许可证与归属说明随安装包提供，可在安装目录中查看。
