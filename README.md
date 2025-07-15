## KCM Integration for LXQt

Desktop files for single KConfig Modules for `kwin_wayland`:

 * Input Settings (Keyboard, Mouse and Touchpad)
 * Shortcuts
 * Monitor
 * KWin Wayland Settings

Package `systemsettings` from KDE Plasma is needed at least, for some modules `plasma-desktop `
may be needed. See `kcmshell6 --list` for all modules available in your installation.

### Installation

Local installation (recommended):

```
git clone https://github.com/lxqt/lxqt-kcm-integration`
cp lxqt-kcm-integration/applications/*.desktop ~/.local/share/applications/

```
Systemwide installation is possible with CMake as usual.
