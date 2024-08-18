# Sway Configuration for my current System76 Lemur Pro

This repository contains my custom configuration files for [Sway](https://swaywm.org/), a tiling Wayland compositor, designed for use on my System76 Lemur Pro running Pop!_OS.

## System Information

- **Device:** System76 Lemur Pro
- **Operating System:** Pop!_OS

## Key Features

- **Efficient Window Management:** The configuration is optimized for tiling and managing multiple workspaces, taking full advantage of the Lemur Pro's screen real estate.
- **Custom Keybindings:** Includes custom keybindings for common actions, such as launching applications and reloading the configuration.
- **Integrated Rofi:** Rofi is used as an application launcher and window switcher, integrated smoothly into the workflow.

## Keybindings

Here are some of the keybindings configured in this setup:

- **Reload Sway Configuration:**
  - `Mod + Shift + C`
- **Launch Rofi:**
  - `Mod + D`
- **Switch Workspaces:**
  - `Mod + [1-9]` to switch to workspaces 1-9
- **Move Focus Between Windows:**
  - `Mod + Arrow Keys` to navigate between windows
- **Launch Terminal:**
  - `Mod + Enter` to launch the default terminal (e.g., Alacritty)
- **Close Focused Window:**
  - `Mod + Shift + Q`

## Installation

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/Riley1101/sway.me ~/.config/sway
    ```

2. **Install Dependencies:**

    Ensure you have the necessary packages installed. For Pop!_OS, you can use:

    ```bash
    sudo apt install sway rofi alacritty
    ```

3. **Copy the Configuration Files:**

    Copy the configuration files to your Sway config directory:

    ```bash
    cp -r ~/.config/sway/* ~/.config/
    ```

4. **Start Sway:**

    Start Sway by logging out of your current session and selecting Sway from the login screen, or simply run:

    ```bash
    sway
    ```

## Customization

Feel free to customize the configuration to suit your preferences. The keybinding section in the configuration file (`config` file in the sway directory) is well-commented to help you understand and modify as needed.

## Troubleshooting

- **Sway won't start:** Ensure all dependencies are installed and the configuration syntax is correct. Use the terminal to debug any issues with:
  
  ```bash
  sway --debug

