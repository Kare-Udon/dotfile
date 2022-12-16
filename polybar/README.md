# Polybar Configuration

## Files

`config.ini` is the configuration of Polybar.

`launch.sh` is a shell script to launch Polybar while i3-wm starts.

Create a folder called `polybar-scripts` to hold scripts.

The bar I am using is called `topbar`, so running `polybar topbar` to show the topbar.

## Scripts

The scripts I am using are:

- notification-github

    Get notification count of GitHub.

- openweathermap-fullfeatured

    Get detailed weather info.

- player-cmus

    Control cmus in the topbar.

- pulseaudio-microphone

    Control pulseaudio microphone things in the topbar.

You can get all these scripts from [polybar-scripts](https://github.com/polybar/polybar-scripts)

## Bar Settings

The components I am using:

Left:

- xworkspaces
- openweather-fullfeatured

Middle:

- date

Right:

- player-cmus
- notification-github
- cpu
- memory
- filesystem
- pulseaudio
- pulseaudio-microphone
- backlight
- battery
- powermenu
