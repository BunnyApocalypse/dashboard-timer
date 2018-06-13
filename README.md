# dashboard-timer

Dashboard is a set of systemd timers and services that will turn off and on monitors running GNOME at specific times. It can replace any past uses of xrandr to do this task on Wayland, so long as they are running GNOME.

## Configuration

* Edit the [timer files](https://wiki.archlinux.org/index.php/Systemd/Timers) for your desired times to turn the monitor on and off

## Usecases

* Turning on and off an office dashboard at specific times so that it doesn't waste energy running when people aren't around
