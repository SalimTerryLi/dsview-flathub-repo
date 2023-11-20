# PlotJuggler Flatpak

Flatpak build of [PlotJuggler](https://github.com/facontidavide/PlotJuggler).

ROS plugins are not supported by now.

## Locally build & install

Assuming `flatpak-builder` is installed, then simply run:

```sh
flatpak-builder --user --install --force-clean build com.facontidavide.PlotJuggler.yml
```

This will create a build directory named `build`.
