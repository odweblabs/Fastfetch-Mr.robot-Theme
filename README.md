

# 🤖 Fastfetch Mr. Robot Theme

[Preview](./fastfetch/assets/mr.robot.png)

> A sleek **Mr. Robot inspired Fastfetch theme** — bring a dark, hacker-style aesthetic to your terminal.

---

## 🧠 About

This repository provides a custom theme for Fastfetch, inspired by the iconic visuals of Mr. Robot.

The goal is simple:
create a **minimal, cinematic, hacker-like terminal experience**.

---

## ✨ Features

* 🟥 Mr. Robot themed color palette
* 🖤 Dark, clean and minimal layout
* 🧠 Structured system info modules
* 🖼️ Custom image / ASCII support
* ⚡ Fast & lightweight

---

## 📸 Preview

[Preview](./fastfetch/assets/banner.png)

---

## ⚙️ Requirements

Before installing the theme, make sure you have:

* Fastfetch installed
* A Nerd Font (for proper icons)

### 🔤 Recommended Fonts

* JetBrainsMono Nerd Font
* FiraCode Nerd Font

---

## 📦 Install Fastfetch

### 🐧 Linux

**Arch Linux**

```bash
sudo pacman -S fastfetch
```

**Ubuntu / Debian**

```bash
sudo apt install fastfetch
```

**Fedora**

```bash
sudo dnf install fastfetch
```

---

### 🍎 macOS

Using Homebrew:

```bash
brew install fastfetch
```

---

## 🚀 Theme Installation

### 1. Clone the repository

```bash
git clone https://github.com/odweblabs/Fastfetch-Mr.robot-Theme.git
cd Fastfetch-Mr.robot-Theme
```

---

## ⚙️ Configuration (IMPORTANT)

Fastfetch uses a config file located in your home directory.

### 🐧 Linux Config Path

```bash
~/.config/fastfetch/config.jsonc
```

### 🍎 macOS Config Path

```bash
~/.config/fastfetch/config.jsonc
```

> 💡 If the folder doesn't exist, create it:

```bash
mkdir -p ~/.config/fastfetch
```

---

### 🔄 Apply the Theme

Copy the theme config:

```bash
cp mr-robot.jsonc ~/.config/fastfetch/config.jsonc
```

---

### ▶️ Run Fastfetch

```bash
fastfetch
```

---

## 🎨 Customization

You can edit the config file to personalize your setup:

```bash
nano ~/.config/fastfetch/config.jsonc
```

### You can customize:

* 🎨 Colors
* 🧩 Modules (CPU, GPU, OS, etc.)
* 🖼️ Image / ASCII logo
* 📐 Layout & spacing

---

## 💡 Tips

### Auto-run on terminal start

Add this line to your shell config:

**Bash**

```bash
~/.bashrc
```

**Zsh**

```bash
~/.zshrc
```

Then add:

```bash
fastfetch
```

---

## 🧑‍💻 Inspiration

* Mr. Robot terminal aesthetics
* Cybersecurity & hacker culture
* Minimal UNIX environments

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create a feature branch
3. Commit your changes
4. Open a Pull Request

---

## ⭐ Support

If you like this theme:

* ⭐ Star the repository
* 🍴 Fork it
* 🧠 Share it

---

## 📜 License

This project is licensed under:

**GNU General Public License v2.0**

---

## 🔥 Future Improvements

* [ ] Multiple color variants (green / red / mono)
* [ ] One-line installer script
* [ ] Animated preview (GIF)
* [ ] Modular configs

---
