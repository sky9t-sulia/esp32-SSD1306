# SSD1306 driver as component for esp-idf projects

All the code I got from here: https://github.com/nopnop2002/esp-idf-ssd1306

## Usage

Add following lines to your `idf_component.yml` file

```yaml
dependencies:
  sky9t_sulia/esp32-ssd1306:
    git: https://github.com/sky9t-sulia/esp32-ssd1306.git
  another_dependency:
    git: https://github.com/user/another_dependency.git
  ...
