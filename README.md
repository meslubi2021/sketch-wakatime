# sketch-wakatime

[![Coding time tracker](https://wakatime.com/badge/github/wakatime/sketch-wakatime.svg)](https://wakatime.com/badge/github/wakatime/sketch-wakatime)

Time tracking and metrics automatically generated from your [Sketch](http://www.sketchapp.com/) usage.


## Installation


1. Download the [latest release](https://github.com/wakatime/sketch-wakatime/releases/latest).

2. Unzip the file.

3. Open the `WakaTime.sketchplugin` file to install the plugin.

4. Use Sketch like you normally do and your time will automatically be tracked for you.

5. Enter your [api key](https://wakatime.com/settings#apikey) if prompted.

6. Visit <https://wakatime.com> to see your logged time.


## Screen Shots

![Project Overview](https://wakatime.com/static/img/ScreenShots/Screen-Shot-2016-03-21.png)


## Configuring

To change your api key, copy it from your [Settings page](https://wakatime.com/settings#apikey), then paste into Sketch `Plugins → WakaTime`.

Additional settings are in `$HOME/.wakatime.cfg` for [wakatime cli](https://github.com/wakatime/wakatime#configuring).


## Turn off Safari Web Inspector

Uncheck the setting in Safari → Develop → [computer name] → Automatically Show Web Inspector for JSContexts.

![Turn off Web Inspector](./safari-web-inspector.png)


## Troubleshooting

The Sketch plugin logs errors to `Console.app` and `~/.wakatime.log`.

For more info on debugging Sketch plugins see the [official docs](https://developer.sketch.com/plugins/debugging).

For more general troubleshooting information, see [wakatime/wakatime#troubleshooting](https://github.com/wakatime/wakatime#troubleshooting).
