X11/xorg setup
==============

## Requirements:
`i3-wm, i3blocks, i3lock-color, betterlockscreen, feh, polybar, picom, maim`

additional/optional
`lightdm` for a display/login manager (replace with your favorite)
`polkit-gnome`/`polkit-gnome-authentication-agent` to fix issues with the default polkit (this might be an issue just in wayland, but I prefer gnome's to the default one anyway)
`pipewire, pipewire-pulse, pipewire-alsa, pavucontrol` for sound control, optionally `sonusmix` for messing with sinks and sources
`alacritty` or a different terminal emulator
any relevant fonts.
`rofi` as a launch menu replacement
TODO: add a notification manager for x11

## Other things
I've deliberately removed the `jkl;` navigation options in i3, and set the modifier key to Mod4 (`super`)
polybar setup is minimal and adapted from a random github repo, definitely needs work
picom config is basically just out of the box and needs more.
