## LightRed

light red with white accent Colors for [Home Assistant](https://www.home-assistant.io) 


## Installation

#### Manual Installation
1. copy the `themes` folder into your home-assistant folder
2. add this to your `configuration.yaml`

```yaml
frontend:
  themes: !include_dir_merge_named themes
```

3. restart home-assistant
4. select the theme in your user's profile (bottom left)

**Optional**: I recommend installing [Custom Header](https://github.com/maykar/custom-header)

#### HACS

1. Go to the Community Store.
2. Search for `LightRed`.
3. Navigate to `LightRed`.
4. Press Install.
