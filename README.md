# Better Planetside


## Download

Get the latest release from:

- https://github.com/cedric12354/Better-Planetside/releases

Release assets include:

- Windows installer: `Better-Planetside-Installer-vX.Y.Z.exe`
- Windows portable archive: `Better-Planetside-Windows-vX.Y.Z.zip`
- Linux archive: `Better-Planetside-Linux-vX.Y.Z.tar.gz`

## Windows

### Option 1: Installer (recommended)

1. Download `Better-Planetside-Installer-vX.Y.Z.exe`.
2. Run the installer.
3. Start **Better Planetside** from the Start Menu or desktop shortcut.

### Option 2: Portable ZIP

1. Download `Better-Planetside-Windows-vX.Y.Z.zip`.
2. Extract it.
3. Run `Better Planetside.exe`.

## Linux (.tar.gz)

The Linux release is distributed as a `.tar.gz` archive (not AppImage).

1. Install `xprop` (required for in-game overlay focus detection).
2. Download `Better-Planetside-Linux-vX.Y.Z.tar.gz`.
3. Extract it:
   ```bash
   tar -xzf Better-Planetside-Linux-vX.Y.Z.tar.gz
   ```
4. Go into the extracted folder:
   ```bash
   cd "Better Planetside"
   ```
5. Make the binary executable (first run only):
   ```bash
   chmod +x "Better Planetside"
   ```
6. Start the app:
   ```bash
   ./Better\ Planetside
   ```

Install `xprop` on common distros:

- Ubuntu/Debian:
  ```bash
  sudo apt install x11-utils
  ```
- Fedora:
  ```bash
  sudo dnf install xprop
  ```
- Arch:
  ```bash
  sudo pacman -S xorg-xprop
  ```

## First Launch

1. Open the app.
2. Add your character in the Characters tab.
3. Configure overlay options.
4. Run PlanetSide 2 in **Borderless Windowed** mode.

## Updates

- Use **Settings -> Check for updates**.
- The app can download and apply updates automatically.

## Config Location

- Windows: `%APPDATA%\BetterPlanetside\config.json`
- Linux: `$XDG_CONFIG_HOME/BetterPlanetside/config.json` (fallback: `~/.config/BetterPlanetside/config.json`)

