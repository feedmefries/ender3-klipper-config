# Ender 3 Pro Klipper Configuration

## Initial Setup

See the readme in the [machine_specific](./config/machine_specific/README.md) 
directory forinstructions on how to setup your printer.

You will also need to configure the moonraker authorization block in the `moonraker_auth.conf` file (you will need to create this)
with your specified authorization settings:

```
# file: moonraker_auth.conf

[authorization]
force_logins: True
cors_domains:
  *.local
  *.lan
  *://app.fluidd.xyz

trusted_clients:
    192.168.0.0/16
    10.1.0.0/16
```

## Changelog

See the [CHANGELOG](./CHANGELOG.md) for information on the latest changes.
