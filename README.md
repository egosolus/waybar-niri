## Niri Waybar Configuration - Tokyo Night (DWM Style)

A simple and aesthetic Waybar configuration designed for the **Niri** Wayland compositor. This configuration adopts the **DWM style**: minimalist, functional, and strictly organized—while utilizing the **Tokyo Night** color palette.


### Preview

![Waybar](screenshots/waybar_screenshot.png)

### Features

* **DWM Style Layout:** Strict separation of elements: workspaces on the left, window title in the center, and system status on the right.
* **Niri Integration:** Dedicated modules for Niri workspaces (`niri/workspaces`) and window titles (`niri/window`).

### WM Used
[Niri]

### Files

This repository contains two main configuration files:

| File Name | Description |
| :--- | :--- |
| `config.jsonc` | The main Waybar configuration defining modules, positions, and Niri-specific settings. |
| `style.css` | The styling file, implementing the Tokyo Night color scheme and module-specific visuals. |

### Prerequisites

* **Waybar:** The custom status bar for Wayland.
* **Niri:** The required Wayland compositor (as modules are Niri-specific).
* **Fonts:** `JetBrainsMono Nerd Font` (used for icons and text).
* **`pavucontrol`:** Required for the `pulseaudio` module's click action.

### Installation

1.  Clone this repository or download the two files (`config.jsonc` and `style.css`).
2.  Place the files in your Waybar configuration directory, typically:
    ```bash
    ~/.config/waybar/
    ```

[Niri]:https://github.com/YaLTeR/niri 
