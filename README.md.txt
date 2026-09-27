# 🔥 Free Fire Max Sensitivity Generator & Calculator

A Python tool designed to calculate, optimize, and export custom sensitivity settings, DPI configurations, and Fire Button layouts for **Free Fire Max**.

Designed for players wanting maximum drag headshot precision, smooth 180° rotations, and optimal scope tracking across low-end, mid-range, and flagship high-end devices.

---

## ✨ Features

- 🎯 **Tailored Sensitivity Calculations**: Generates General, Red Dot, 2x, 4x, Sniper Scope, and Free Look sensitivities.
- 📱 **Device Performance Adaptation**: Tailors multipliers based on device RAM (`low`, `mid`, `high`).
- 🖐️ **Claw Layout Adjustments**: Specific settings tuned for 2-finger, 3-finger, or 4-finger players.
- 🌟 **Expert Player Profiles**: Built-in presets inspired by pro players (`nobru`, `totalgaming`, `white444`).
- 📊 **Visual Terminal Sliders**: Render progress bar visualization directly in terminal output.
- 📄 **Multi-Format Export**: Save your config as plain text (`.txt`), structured JSON (`.json`), or a responsive mobile-friendly HTML card (`.html`).

---

## 🚀 Quick Start

### 1. Interactive Mode (Wizard)
Run the script without arguments or with `-i` to enter the step-by-step terminal wizard:

```bash
python3 ffmax_sensitivity.py -i
```

### 2. Command Line Arguments
Calculate settings for **One-Tap Headshots** on a low-end phone:
```bash
python3 ffmax_sensitivity.py --playstyle one-tap --device low --claw 2-finger --export html
```

Load **White444 Expert Preset** and export to JSON:
```bash
python3 ffmax_sensitivity.py --expert white444 --export json --output white444_preset.json
```

---

## ⚙️ Options & Arguments

| Parameter | Short | Options / Defaults | Description |
| :--- | :--- | :--- | :--- |
| `--interactive` | `-i` | None | Run interactive wizard step-by-step |
| `--playstyle` | `-p` | `one-tap`, `rusher`, `sniper`, `balanced` | Playstyle archetype focus |
| `--device` | `-d` | `low`, `mid`, `high` | Device RAM/Performance category |
| `--claw` | `-c` | `2-finger`, `3-finger`, `4-finger` | Control button layout style |
| `--dpi` | | Default: `360` | Screen default DPI |
| `--expert` | `-e` | `nobru`, `totalgaming`, `white444` | Preset inspired by pro creator |
| `--export` | | `txt`, `json`, `html` | File format to export results |
| `--output` | `-o` | Filename path | Output file destination |

---

## 💡 Best Practice Tips for Drag Headshots

1. **Fire Button Position**: Place the fire button lower down on screen (around 40-48% size) to leave ample vertical drag room.
2. **First Drag Motion**: Slightly pull the fire button down before snapping upwards towards the enemy head.
3. **Screen Surface**: Use finger sleeves or keep the phone display clean to prevent friction during fast drag flicks.
