# ESP-IDF HX711 component
ESP-IDF component for interfacing with the [Avia Semiconductor HX711 24-Bit ADC](http://www.dfrobot.com/image/data/SEN0160/hx711_english.pdf), based on a PlatformIO library by https://github.com/bogde/HX711 and originally adapted for ESP-IDF by https://github.com/akshayvernekar/HX711_IDF.

## Installation
### Manual
* Locate your `idf_component.yml` file and add the following to the `dependencies` section:
```yml
dependencies:
  # ...
  NickNirus/HX711_IDF:
    git: https://github.com/NickNirus/HX711_IDF
    version: <commit_hash> # replace with the full hash of the commit that should be used
```

* Build your ESP-IDF project or run 
```bash
idf.py update-dependencies
```