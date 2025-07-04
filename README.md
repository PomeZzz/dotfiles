
# 🖥️ Dotfiles - Gnome Gruvbox Style

Aesthetic and functional dotfiles tailored for the GNOME desktop environment, featuring the warm and cozy **Gruvbox** theme. This setup includes personalized configurations, extensions, fonts, and a minimal, elegant UI.

---

## 📸 Preview

![Preview](/ScreanShoots/obsidian.png)

---

## 📑 Table of Contents

- [📦 Installation](#installation)  
- [⚙️ Applications](#applications)  
- [🔤 Fonts](#fonts)  
- [🖼️ Gallery](#gallery)  
- [🖼️ Wallpapers](#wallpapers)

---

## 📦 Installation

Start by installing the required components, then copy the configuration files into your `~/.config` directory.

```bash
# Clone this repository
git clone https://github.com/username/repository.git

# Navigate to the project directory
cd repository
```

### 1. Themes and Icons

Install the GTK theme and icon set from the following sources:

- 🎨 [Gruvbox GTK Theme](https://github.com/Fausto-Korpsvart/Gruvbox-GTK-Theme)  
- 🧩 [Papirus Icon Theme](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme)  
- 🗂️ [Gruvbox Papirus Folder Icons](https://github.com/xelser/gruvbox-papirus-folders)

Once downloaded, or by extracting the files from my `gtk-3.0` and `gtk-4.0` folders, place them into your `~/.config` directory. Make sure to check which version of GNOME you have; some versions may only require placing the files in the `.theme` and `.icons` folders, but others may require placing them in `gtk-4.0` for proper functionality. Full instructions are available [here](https://github.com/Fausto-Korpsvart/Gruvbox-GTK-Theme).

---

### 2. Terminal Setup

For the terminal, you can install **Warp** from the official website:

```bash
# Download Warp from the official site: https://warp.dev/linux

# Go to the folder where the .deb file was downloaded
cd ~/Downloads

# Install the .deb file (replace the name if it's different)
sudo dpkg -i warp-terminal.deb

# Fix dependencies if necessary
sudo apt-get install -f

# Alternatively, use the install script
curl https://warp.dev/install.sh | bash
```

And paste my config in the **Warp File**

---

### 3. GNOME Extensions && GNOME Extensions Config

```
# 1 Clone the repo
git clone https://github.com/PomeZzz/dotfiles.git
cd repo location

```


```
# 2 make the file executable
chmod +x gnome-extensions-config.sh
```
#### 3. Install the necessary extensions

This step is NOT automatic. The extensions.conf file only imports the settings, but does not install extensions if you don't already have them installed.
💡 To install GNOME extensions:

You can use the official extension store:
🔗 https://extensions.gnome.org

**List of Extensions**
- Blur my Shell
- Color Picker
- Just Perfection
- Media Controls
- Open Bar
- Panel Note

```
# 4 Imports de configuration
./gnome-extensions-config.sh import

```
If you have the extensions installed and turned on, the settings should be applied automatically. Log out and log back in to see the effects.

---

### 5. FastFetch set up

First you have to download fastfetch on your terminal, Fastfetch official site [Here](https://github.com/fastfetch-cli/fastfetch)

Once you have installed FastFetch, download the FastFetch folder from my dotfiles and replace your folder with mine to have my configuration.

---

## Optional Dependencies

You may need to install the following optional utilities:

```bash
cbonsai neofetch pokemon-colorscripts-git feh jp2a htop
```

## Terminal Utilities

```bash
nvim
```

---

## ⚙️ Applications

Here are the key applications I use for this setup:

- **VSCode** (with Hack Nerd Font and Gruvbox Material Modern theme)
- **Obsidian** (Markdown editor with Gruvbox theme)
- **Spotify** (No Theme Yet)
- **nvim**
- **Discord** (No Theme yet)
- **Firefox** (with Gruvbox theme)

## GTK, Icon Themes

- [Gruvbox GTK Theme](https://github.com/Fausto-Korpsvart/Gruvbox-GTK-Theme)
- [Papirus Icon Theme](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme)
- [Gruvbox Papirus Folder Icons](https://github.com/xelser/gruvbox-papirus-folders)

---

## 🔤 Fonts

For system fonts, I primarily use **Ubuntu Nerd Fonts**. You can download them from the official Nerd Fonts repository [here](https://www.nerdfonts.com/).

---

## 🖼️ Gallery

![FastFetch Screenshot](/ScreanShoots/FastFetch.png)
![Files Screenshot](/ScreanShoots/Files.png)
![Obsidian Screenshot](/ScreanShoots/obsidian.png)
![Wallpaper Screenshot](/ScreanShoots/wallpaper.png)
![Superfile Screenshot](/ScreanShoots/Superfile.png)
---

## 🖼️ Wallpapers

Enjoy these wallpapers to complement your setup:

![Dock Wallpaper](/dotfiles/Wallpapers/dock.png) 
![Montana Wallpaper](/dotfiles/Wallpapers/montana.jpg) 
![Wall Wallpaper](/dotfiles/Wallpapers/wall.jpg)
