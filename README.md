While this is still under active development it is best to reference a previous working commit like this:
```yaml
external_components:
  - source:
      type: git
      url: https://github.com/clydebarrow/esphome
      ref: fd15094c0860df23d532881df36cfd16c7da1091 #previous commit - wont be needed in the future
    components: [ lvgl ]
```

Demo for the Sunton 7" LCD
![sunton070](https://github.com/clowrey/esphome-sunton-esp32-8048s070c/assets/6935928/9c064e33-e2dd-4bf4-b7e9-9c3e3bd6f8c8)
