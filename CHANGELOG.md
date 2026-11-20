## v1.0.0

首个发布版本。将设计截图还原为指定尺寸的 MasterGo 分层画板。

- 支持按指定宽度等比计算画板高度，也可直接指定宽高。
- 文本、按钮、容器、图标和插画独立成层。中文使用苹方，数字使用 MiSans Latin；普通图标选自字节跳动官方 IconPark，复杂插画使用 GPT Image 2 重绘。
- 三轮截图对照与修复覆盖布局、间距、背景、字体、组件及整页回归。

## 安装和使用

将技能文件夹保存为 `~/.codex/skills/ai-design-reconstruction`，开启新的 Codex 对话。连接 MasterGo 后，上传有权复刻的截图，提供目标文件链接和画板尺寸，并调用 `$ai-design-reconstruction`。完整操作和依赖见 README。
