# slwf01pro21 - ESPHome firmware for the SMARTLIGHT SLWF-01pro (v.2.1). Air conditioner Wi-Fi module for Midea, Idea, Neoclima, Electrolux, Beko and many more.

https://smartlight.me/smart-home-devices/wifi-devices/wifi-dongle-air-conditioners-midea-idea-electrolux-for-home-assistant

# Changelog (compared to Smartlight's original slwf01pro21.yaml):

## slwf01pro21-eng:
- migrated original slwf01pro21.yaml to new style ESPHome platform configuration
- changed value of wifi_ap_password from "slwf01pro" to !secret wifi_ap_password (you must add wifi_ap_password: my_super_secret_password to secrets.yaml)
- changed value of autoconf to true
- changed value of beeper to false

## slwf01pro21-hun:
- migrated original slwf01pro21.yaml to new style ESPHome platform configuration
- translated the UI into Hungarian
- changed value of wifi_ap_password from "slwf01pro" to !secret wifi_ap_password (you must add wifi_ap_password: my_super_secret_password to secrets.yaml)
- changed value of autoconf to true
- changed value of beeper to false
