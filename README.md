<p align="center">
  <img width="180" src="https://github.com/hardhackerlabs/themes/raw/master/media/logo/logo.png" alt="HardHacker">
</p>

<h1 align="center">
  HardHacker Theme for wezterm
</h1>

![screenshot](screenshot.png)

## Install

```shell
git clone https://github.com/hardhackerlabs/theme-wezterm
cp ./theme-wezterm/hardhacker.toml ~/.config/wezterm/colors/
```

And add the following configs into your wezterm.lua file

```
color_scheme = "hardhacker",
use_fancy_tab_bar = false,
window_decorations = "RESIZE",
```
