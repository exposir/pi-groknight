# pi-groknight

**GrokNight** theme for [pi](https://github.com/earendil-works/pi-coding-agent) — a faithful port of xAI [Grok Build](https://github.com/xai-org/grok-build)'s default dark theme (`groknight` / `grok-night` / `dark`).

> Palette extracted from the grok-build sources:
> `crates/codegen/xai-grok-pager-render/src/theme/groknight.rs` and
> `crates/codegen/xai-grok-pager-render/assets/grok-night.tmTheme` (Apache-2.0).

## Style

- **Neutral gray base**: `#141414` main background, `#0a0a0a` terminal base, `#1c1c1c` code blocks
- **Magenta accent**: `#bb9af7` as the signature color for assistant/thinking/tool titles
- **TokyoNight palette**: blue `#7aa2f7`, green `#9ece6a`, red `#f7768e`, yellow `#e0af68`, cyan `#7dcfff`

## Palette

| Slot | Color | Hex |
|------|-------|-----|
| Terminal base | ![#0a0a0a](https://img.shields.io/badge/-%230a0a0a.svg) | `#0a0a0a` |
| Main background | ![#141414](https://img.shields.io/badge/-%23141414.svg) | `#141414` |
| Code block background | ![#1c1c1c](https://img.shields.io/badge/-%231c1c1c.svg) | `#1c1c1c` |
| Highlight background | ![#242424](https://img.shields.io/badge/-%23242424.svg) | `#242424` |
| Primary text | ![#e1e1e1](https://img.shields.io/badge/-%23e1e1e1.svg) | `#e1e1e1` |
| Secondary text | ![#c8c8c8](https://img.shields.io/badge/-%23c8c8c8.svg) | `#c8c8c8` |
| Accent (magenta) | ![#bb9af7](https://img.shields.io/badge/-%23bb9af7.svg) | `#bb9af7` |
| Blue | ![#7aa2f7](https://img.shields.io/badge/-%237aa2f7.svg) | `#7aa2f7` |
| Cyan | ![#7dcfff](https://img.shields.io/badge/-%237dcfff.svg) | `#7dcfff` |
| Green | ![#9ece6a](https://img.shields.io/badge/-%239ece6a.svg) | `#9ece6a` |
| Yellow | ![#e0af68](https://img.shields.io/badge/-%23e0af68.svg) | `#e0af68` |
| Orange | ![#ff9e64](https://img.shields.io/badge/-%23ff9e64.svg) | `#ff9e64` |
| Red | ![#f7768e](https://img.shields.io/badge/-%23f7768e.svg) | `#f7768e` |

## Install

### From GitHub (this repo)

```bash
pi install git:github.com/exposir/pi-groknight
```

### From npm (once published)

```bash
pi install npm:pi-groknight
```

### Manual

Copy `themes/groknight.json` into `~/.pi/agent/themes/`.

## Usage

After installing, run `/settings` in pi and pick **groknight** under Theme, or set it directly in `~/.pi/agent/settings.json`:

```json
{
  "theme": "groknight"
}
```

## License

MIT. Ported from [xai-org/grok-build](https://github.com/xai-org/grok-build) (Apache-2.0); the palette is xAI's.
