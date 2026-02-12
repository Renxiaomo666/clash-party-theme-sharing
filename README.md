# Clash Party's Catppuccin Theme (2.0)

[English](#english) | [中文](#chinese)
<img width="1012" height="764" alt="image" src="https://github.com/user-attachments/assets/5090d34d-6fa0-414b-8c10-613281f4e3db" />

---

## English

### 📖 Introduction
This is a custom color theme for **HeroUI (NextUI)** based on the famous [Catppuccin](https://github.com/catppuccin/catppuccin) palette.  
The primary color has been modified to a fresh **teal (`#2eb8b8`)** while keeping all other Catppuccin colors unchanged.

It includes two complete variants:
- 🌻 **Latte** (light mode)
- 🌿 **Mocha** (dark mode)

Perfect for applications that need a clean, modern interface with a touch of nature.

### ✨ Features
- Full HeroUI CSS variable coverage
- HSL format – easily adjust opacity
- Carefully crafted color steps (50–900)
- Light & Dark themes automatically applied via `.light` / `.dark` classes or `data-theme` attribute
- Focus color, divider opacity, content scales all customized

### 🎨 Color Palette
| Role         | Light Theme (Latte) | Dark Theme (Mocha) |
|--------------|---------------------|--------------------|
| Background   | `#eff1f5`           | `#1e1e2e`          |
| Text         | `#4c4f69`           | `#cdd6f4`          |
| Primary      | `#2eb8b8` (teal)    | `#7ae2e2` (soft teal) |
| Secondary    | `#8839ef` (mauve)   | `#cba6f7`          |
| Success      | `#40a02b`           | `#a6e3a1`          |
| Warning      | `#fe640b`           | `#f9e2af`          |
| Danger       | `#d20f39`           | `#f38ba8`          |

> Full variable list is available inside the CSS file.

### 🚀 Installation
1. Download `Catppuccin 2.0.css`.
2. Import it into your project:
   - **Via HTML**:
     ```html
     <link rel="stylesheet" href="path/to/Catppuccin 2.0.css">
     ```
   - **Via CSS/SCSS**:
     ```css
     @import 'path/to/Catppuccin 2.0.css';
     ```
3. Make sure your HeroUI provider supports theme switching (the file already includes `.light` / `.dark` selectors).

### ⚙️ Usage
The theme will be automatically applied when the parent element has class `light` / `dark` or attribute `data-theme="light"` / `data-theme="dark"`.

Example:
```html
<html class="light">   <!-- Latte -->
<html class="dark">    <!-- Mocha -->
