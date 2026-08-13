# pi-groknight

**GrokNight** 主题 for [pi](https://github.com/earendil-works/pi-coding-agent) — 忠实移植自 xAI [Grok Build](https://github.com/xai-org/grok-build) 的默认暗色主题（`groknight` / `grok-night` / `dark`）。

> 配色提取自 grok-build 源码 `crates/codegen/xai-grok-pager-render/src/theme/groknight.rs`
> 与 `crates/codegen/xai-grok-pager-render/assets/grok-night.tmTheme`（Apache-2.0）。

## 风格

- **中性灰底**：`#141414` 主背景、`#0a0a0a` 终端底、`#1c1c1c` 代码块
- **品红强调**：`#bb9af7` 作为助手/思考/工具标题的标识色（GrokNight 的标志）
- **TokyoNight 配乐**：蓝 `#7aa2f7`、绿 `#9ece6a`、红 `#f7768e`、黄 `#e0af68`、青 `#7dcfff`

## 调色板

| 类别 | 颜色 | Hex |
|------|------|-----|
| 终端背景 | ![#0a0a0a](https://img.shields.io/badge/-%230a0a0a.svg) | `#0a0a0a` |
| 主背景 | ![#141414](https://img.shields.io/badge/-%23141414.svg) | `#141414` |
| 代码块背景 | ![#1c1c1c](https://img.shields.io/badge/-%231c1c1c.svg) | `#1c1c1c` |
| 高亮背景 | ![#242424](https://img.shields.io/badge/-%23242424.svg) | `#242424` |
| 主文本 | ![#e1e1e1](https://img.shields.io/badge/-%23e1e1e1.svg) | `#e1e1e1` |
| 次要文本 | ![#c8c8c8](https://img.shields.io/badge/-%23c8c8c8.svg) | `#c8c8c8` |
| 强调（品红） | ![#bb9af7](https://img.shields.io/badge/-%23bb9af7.svg) | `#bb9af7` |
| 蓝 | ![#7aa2f7](https://img.shields.io/badge/-%237aa2f7.svg) | `#7aa2f7` |
| 青 | ![#7dcfff](https://img.shields.io/badge/-%237dcfff.svg) | `#7dcfff` |
| 绿 | ![#9ece6a](https://img.shields.io/badge/-%239ece6a.svg) | `#9ece6a` |
| 黄 | ![#e0af68](https://img.shields.io/badge/-%23e0af68.svg) | `#e0af68` |
| 橙 | ![#ff9e64](https://img.shields.io/badge/-%23ff9e64.svg) | `#ff9e64` |
| 红 | ![#f7768e](https://img.shields.io/badge/-%23f7768e.svg) | `#f7768e` |

## 安装

### 从 GitHub（本仓库）

```bash
pi install git:github.com/exposir/pi-groknight
```

### 从 npm（发布后）

```bash
pi install npm:pi-groknight
```

### 手动

把 `themes/groknight.json` 复制到 `~/.pi/agent/themes/`。

## 使用

安装后在 pi 中输入 `/settings`，在 Appearance / Theme 中选择 **groknight**；或直接在 `~/.pi/agent/settings.json` 中设置：

```json
{
  "theme": "groknight"
}
```

## 许可

MIT。移植自 [xai-org/grok-build](https://github.com/xai-org/grok-build)（Apache-2.0），配色归 xAI 所有。
