# 🎨 Saturated Colors Resource Pack

A Minecraft Java Edition resource pack that boosts color saturation by 200% for a vibrant, vivid visual experience.

## ✅ Supported Versions
- Minecraft Java 1.20.1
- Minecraft Java 1.21
- Minecraft Java 1.21.1

## 📦 Installation

1. Download the `Saturated-Colors` folder (or the `.zip`)
2. Place it in your `.minecraft/resourcepacks/` folder
3. Launch Minecraft → Options → Resource Packs → Enable **Saturated Colors**
4. Enjoy vivid colors!

## ✨ Features

- **200% Color Saturation** — Colors pop with full vibrancy using a GLSL core shader
- **Zero FPS Impact** — The shader runs at the final blit stage, with no extra rendering passes
- **No mods required** — Works with vanilla Minecraft Java Edition
- **Compatible** with OptiFine, Sodium, and Iris (when using core shaders mode)

## ⚙️ How It Works

Uses Minecraft's built-in **core shader system** (`blit_screen`) to apply an HSV-based saturation boost at the final screen render stage — the most efficient possible approach with no impact on game performance.

## 📝 License

Free to use and share. Credit appreciated but not required.
