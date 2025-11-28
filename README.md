# slwf01pro21 - ESPHome firmware for the SMARTLIGHT SLWF-01pro (v.2.1). Air conditioner Wi-Fi module for Midea, Idea, Neoclima, Electrolux, Beko and many more.

https://smartlight.me/smart-home-devices/wifi-devices/wifi-dongle-air-conditioners-midea-idea-electrolux-for-home-assistant

# Changelog (compared to Smartlight's original slwf01pro21.yaml):

## slwf01pro21-eng:
- removed code comments
- migrated original slwf01pro21.yaml to new style ESPHome platform configuration
- changed value of wifi_ap_password from "slwf01pro" to !secret wifi_ap_password (you must add wifi_ap_password: my_wifi_ap_password to secrets.yaml)
- changed value of autoconf to true
- changed value of beeper to false
- added api_encryption_key to subtitutions & api settings (you must add api_encryption_key: my_api_encryption_key to secrets.yaml)
- added esphome_ota_password to subtitutions & ota settings (you must add esphome_ota_password: my_esphome_ota_password to secrets.yaml)
- added translateable entity names to subtitutions: factory_reset_button_name, display_toggle_name, swing_step_name, outdoor_temperature_name, power_usage_name, humidity_setpoint_name, beeper_switch_name, wifi_signal_sensor_name, uptime_sensor_name, uptime_days_sensor_name, uptime_days_unit_of_measurement
- renamed entities: display_toggle_name, swing_step_name, outdoor_temperature_name, power_usage_name, humidity_setpoint_name, beeper_switch_name, wifi_signal_sensor_name, uptime_days_sensor_name

## slwf01pro21-hun:
- all from above
- translated the UI into Hungarian
