# xfce4-night-switcher


xfce4 Genmon plugin to handle theme switching and toggling

### Notice

This repo is meant to be tailored to your configuration. set_day_mode and set_night_mode are both custom to my machine, and you will need to change them to fit your needs. All settings are included in the script, not in xsettings (see alternative section if this is an issue)

### Requirements
- genmon
- xfce
- xconf-query

### Toggling

You can toggle the theming and ignore the current time temporarily by clicking the moon icon. This will toggle the mode until the next check. To keep the mode up for longer before reverting back to using sunrise/sunset times, increase the Period field in the Generic Monitor's configuration.


## Resources

-[Genmon plugin docs](https://docs.xfce.org/panel-plugins/xfce4-genmon-plugin/start)

-[Genmon plugin](https://github.com/xfce-mirror/xfce4-genmon-plugin)

## Alternatives

[xfce4-night-mode](https://github.com/bimlas/xfce4-night-mode)

- I created this project after seeing this alternative. I opted to not use xsettings

- xwallpaper may be a bettter alternative than using xconf-query for setting the wallpaper in some cases

## TODO

- switch indicator icon between modes. 
