## LightRed

light red with white accent Colors for [Home Assistant](https://www.home-assistant.io) <br>
[![hacs_badge](https://img.shields.io/badge/HACS-Default-orange.svg?style=for-the-badge)](https://github.com/custom-components/hacs)

## Installation

1. Add the following code to your `configuration.yaml` file (reboot required).

```yaml
frontend:
  ... # your configuration.
  themes: !include_dir_merge_named themes
  ... # your configuration.
```

2. (Optional) add 
the following to the same file to make the header smaller (you need to install [cch](https://github.com/maykar/compact-custom-header) too):
```yaml
cch:
  clock_am_pm: false
  clock_format: '24'
  hide_help: true
  options: clock
  swipe: true
  swipe_animate: swipe
  swipe_prevent_default: true
  voice: hide
```

#### HACS

1. Add https://github.com/Metal-Eagle/LightRed to you HACS
2. Go to the Community Store.
3. Search for `LightRed`.
4. Navigate to `LightRed`.
5. Press Install.


### Credit

The Home assistant [forum](https://community.home-assistant.io/)