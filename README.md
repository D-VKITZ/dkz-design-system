![Module](https://img.shields.io/badge/DEVKiTZ-Design_System-a855f7?style=for-the-badge&labelColor=fa1e4e)
![Version](https://img.shields.io/badge/version-v2.0.0-a855f7?style=flat-square&labelColor=0d0d14)
![License](https://img.shields.io/badge/license-MIT-00ff88?style=flat-square&labelColor=0d0d14)
![CSS3](https://img.shields.io/badge/CSS3-Custom_Properties-1572B6?style=flat-square&logo=css3&logoColor=white)

# DkZ Design System v2

> **CSS Custom Properties Framework** - Part of the [DEVKiTZ](https://github.com/D-VKITZ) Ecosystem

---

## Color Palette

```
CORE COLORS              EXTENDED
-----------              --------
# #060608  --bg          # #3b82f6  --blue
# #fa1e4e  --accent      # #a855f7  --purple
# #00ff88  --green       # #06b6d4  --cyan
# #ffb800  --yellow      # #0d0d14  --surface
# #ff3b5c  --red         # #12121c  --surface2
# #e8e8f0  --text        # #8888a0  --text2
```

## Typography

```
Inter (Google Fonts)         JetBrains Mono
--------------------         --------------
Display: 32px / 900          Code: 13px / 400
H1:      24px / 700          Stats: 28px / 900
H2:      20px / 600          Mono SM: 11px
Body:    14px / 400          Labels: 10px
Small:   12px / 400
```

## Components

| Component | CSS Class | Effect |
|:----------|:----------|:-------|
| Glass Card | .glass-card | backdrop-filter blur 20px |
| Neon Button | .btn-ghost | box-shadow glow green |
| Status Dot | .status-dot | 8px circle with glow |
| Progress Bar | .progress-fill | green-to-cyan gradient |
| Sticky Header | .dkz-header | sticky top blur 20px |
| Tab Nav | .tab.active | green underline indicator |

## Quick Start

```css
:root {
  --bg: #060608;
  --accent: #fa1e4e;
  --green: #00ff88;
  --yellow: #ffb800;
  --red: #ff3b5c;
  --font: 'Inter', system-ui, sans-serif;
  --mono: 'JetBrains Mono', monospace;
}
```

---

<p align="center">
<sub>DEVKiTZ - Made with love by 777 - 2026</sub><br>
<sub>devkitz.eu | dkz.app | github.com/D-VKITZ</sub>
</p>

---

## Documentation

| Resource | Link |
|:---------|:-----|
| Rules | [D-VKITZ/KERN/RULES.md](https://github.com/D-VKITZ/KERN/blob/main/RULES.md) |
| Patterns | [D-VKITZ/KERN/PATTERNS.md](https://github.com/D-VKITZ/KERN/blob/main/PATTERNS.md) |
| Playbook | [D-VKITZ/KERN/PLAYBOOK.md](https://github.com/D-VKITZ/KERN/blob/main/PLAYBOOK.md) |
| llms.txt | [D-VKITZ/KERN/llms.txt](https://github.com/D-VKITZ/KERN/blob/main/llms.txt) |