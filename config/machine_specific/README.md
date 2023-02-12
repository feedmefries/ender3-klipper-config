# Machine-specific configuration files

This directory contains machine-specific configuration files. If you have not done so already, you should copy the corresponding configuration templates
for your board version from the [templates](../../templates) directory to this directory. You should at least have the following files:

* `pins.cfg`: This file contains the pin mappings for your board. ([4.2.2](../../templates//board-4.2.2/pins.cfg) [4.2.7](../../templates/board-4.2.7/pins.cfg))
- `probe_offset.cfg`: This contains the offset value for your probe.

```cfg
[bltouch]
z_offset: <your Z-offset value here>
# i.e. z_offset: 0.300
```

You may also want to copy the following files if supported by your board:

* `display.cfg`: This file contains the configuration for the display. ([4.2.2](../../templates//board-4.2.2/display.cfg))

**UNTESTED**: 4.2.2 stock display with 4.2.7 board.

The configuration files in this directory will be used by the printer.cfg file to configure the machine.

The configuration files in this directory are not tracked by git. This allows you to make changes to the configuration files without having to worry
about accidentally committing them to the repository.
