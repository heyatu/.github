<p align="center">
  <img src="https://raw.githubusercontent.com/heyatu/.github/main/profile/assets/hero.gif" width="100%" alt="Hey Atu：你过你的日子，AI 一直在干活。Pi 在你的 Mac 上运行，你在哪里都能用。">
</p>

<p align="center">
  <a href="https://heyatu.com/zh/"><b>下载 Mac 版</b></a>
  &nbsp;·&nbsp;
  <a href="#从终端安装">从终端安装</a>
  &nbsp;·&nbsp;
  <a href="https://github.com/heyatu/.github/blob/main/profile/README.md">English</a>
</p>

Hey Atu 是跑在你自己电脑上的 AI。它在你的 Mac 或 Linux 上运行
[Pi](https://github.com/earendil-works/pi)，用你的文件、你的工具和你选的模型。
你用手边的设备和它说话，你走开了，它接着干。

<img src="https://raw.githubusercontent.com/heyatu/.github/main/profile/assets/scene-continue.gif" width="100%" alt="同一个对话：早上在终端开始，中午在 iPhone 上补充，晚上在桌面 App 里继续。">

<img src="https://raw.githubusercontent.com/heyatu/.github/main/profile/assets/scene-files.gif" width="100%" alt="示例：让 Atu 整理桌面，文件聚成一个球，再分进 6 个文件夹，什么都不删。">

<img src="https://raw.githubusercontent.com/heyatu/.github/main/profile/assets/scene-chats.gif" width="100%" alt="示例：一天里的所有聊天交给 Atu，变成 Todo、Updates 和 Wiki。">

## 工作方式

<img src="https://raw.githubusercontent.com/heyatu/.github/main/profile/assets/how-it-works.svg" width="100%" alt="iPhone、iPad、桌面 App 和终端经 relay 连到你电脑上的 Pi。">

- **Chats**：用语音或文字和 Atu 说话。
- **Todo**：你说要做的事，Atu 帮你跟进。
- **Updates**：你关心的事有变化，Atu 告诉你。
- **Wiki**：你学到的东西，Atu 整理成你自己的页面。

## 开始使用

| 设备 | 状态 |
|---|---|
| Mac | [下载](https://heyatu.com/download/mac) |
| 终端（macOS、Linux） | 见下方命令 |
| AI 应用（Claude、ChatGPT、Codex） | [Hey Atu 插件](https://github.com/heyatu/heyatu-plugin) |
| iPhone、iPad、Apple Watch | 即将推出 |

### 从终端安装

```sh
curl -fsSL https://heyatu.com/install | sh
```

## 隐私

- 文件、工具和会话都留在你的电脑上。
- 设备与电脑之间的消息端到端加密。
- relay 只转发，不读取、不存储、不记录内容。
- 你的电脑不开放任何入站端口。
- 可选的 AI 应用连接（MCP）走 TLS，不是端到端加密。
