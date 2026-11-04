# Ghostty Config

My personal Ghostty configuration featuring the Cyberpunk Icy theme, Hack font, custom keybindings and shell integration.

## Requirements

- [Ghostty](https://ghostty.org/)

## Installation

### 1. Open the configuration directory

Open your terminal and run:

```bash
mkdir -p ~/.config/ghostty
cd ~/.config/ghostty
```

### 2. Open the configuration file

Choose your preferred text editor.

**Nano:**

```bash
nano config.ghostty
```

**Vim:**

```bash
vim config.ghostty
```

### 3. Add the configuration

Copy the contents of [`config.ghostty`](config.ghostty) from this repository and paste them into your local file.

Save and close the editor.

- **Nano:** `Ctrl + O`, `Enter`, `Ctrl + X`
- **Vim:** Press `Esc`, type `:wq`, and press `Enter`

### 4. Validate the configuration

```bash
ghostty +validate-config
```

Restart Ghostty to apply the changes.

## Features

- Hack font
- Cyberpunk Icy theme
- Custom colors and cursor
- Custom keyboard shortcuts
- Shell integration
- SSH environment and terminfo integration
- Clipboard configuration
- Working directory inheritance

## Custom Keybindings

### Pipe (`|`) shortcut for 60% keyboards

Some 60% keyboards, especially with alternative layouts such as ABNT2, make it less convenient to type certain characters like the pipe (`|`).

This configuration provides an alternative shortcut:

```
keybind = alt+p=text:|
```

Press `Alt + P` to insert the pipe character (`|`) directly into the terminal.

You can customize this shortcut according to your keyboard layout and preferences.

## License

Feel free to use, modify and adapt this configuration.
