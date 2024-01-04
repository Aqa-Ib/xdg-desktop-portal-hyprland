# xdg-desktop-portal-hyprland

An [XDG Desktop Portal](https://github.com/flatpak/xdg-desktop-portal) backend
for Hyprland.

## Installing

First, make sure to install the required dependencies:

```
gbm
hyprland-protocols
hyprlang
libdrm
libpipewire-0.3
libspa-0.2
sdbus-cpp
wayland-client
wayland-protocols
```

Then run the build and install command:

```sh
git clone --recursive https://github.com/hyprwm/xdg-desktop-portal-hyprland
cd xdg-desktop-portal-hyprland/
cmake -DCMAKE_INSTALL_LIBEXECDIR=/usr/lib -B build
cmake --install /usr
```

## Running, FAQs, etc.

See
[the Hyprland wiki](https://wiki.hyprland.org/Useful-Utilities/Hyprland-desktop-portal)
