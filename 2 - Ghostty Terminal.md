# ✅ macOS Ghostty Setup

## 1. Create the Ghostty configuration directory

Ghostty on macOS stores the default configuration in `$HOME/Library/Application Support/com.mitchellh.ghostty/config`. However, I prefer to store it under `~/.config`. To create it manually, run:

```sh
mkdir -p ~/.config/ghostty
```

## 2. Create and open the config file

This command will create the file if it does not already exist:

```sh
code ~/.config/ghostty/config
```

## 3. Paste your configuration

Paste the following content into the file:

```
# Themes
theme = catppuccin-mocha
font-family = Jetbrain Nerd Font
font-size = 20

# Window
background-opacity = 0.95
gtk-titlebar = false
window-height = 25
window-width = 100

# Keybinds
## copy to clipboard, change copy from ctrl+shift+c
keybind = ctrl+c=copy_to_clipboard
## paste from clipboard, change paste from ctrl+shift+v
keybind = ctrl+v=paste_from_clipboard
## move 1 word to left
keybind = ctrl+left=esc:b
## move 1 word to right
keybind = ctrl+right=esc:f
## delete 1 word to left
keybind = ctrl+backspace=text:\x1b\x7f
## delete 1 word to right
keybind = ctrl+delete=esc:d
## open new tab, change from ctrl+shift+t
keybind = ctrl+t=new_tab
## reload ghostty config, change from ctrl+shift+comma
keybind = ctrl+comma=reload_config
```

## 4. Save and exit

Save the file and close your editor.

## 5. Apply the configuration

Either restart Ghostty or press the **Reload Config** shortcut in Ghostty:

```
Ctrl + ,
```