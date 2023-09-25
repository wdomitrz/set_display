# set_display

Script for setting display and dpi automatically.

## Requirements

It can be used with [i3](https://github.com/i3/i3) or other window managers and desktop environments that handle dpi in the default way.

## Usage

`set_display` sets display automatically including DPI detection.

### Environmental variables

To overwrite dpi, set `DPI` environmental variable, for example:

```sh
DPI=96 set_display
```

To force usage of a single display, you can set `SINGLE_DISPLAY` enviromental variable to `1`.

### Dpi detection

To display dpi automatically detected by the seript use `show_dpi` subcommand.

```sh
set_display show_dpi
```

### Setting dpi

To set automatically detected dpi use:

```sh
set_display set_dpi
```

Dpi can also be overwritten with `DPI` environmental variable, or `--dpi` flag.
