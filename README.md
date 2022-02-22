# esphome-zb-gw03

![GitHub actions](https://github.com/syssi/esphome-zb-gw03/actions/workflows/ci.yaml/badge.svg)
![GitHub stars](https://img.shields.io/github/stars/syssi/esphome-zb-gw03)
![GitHub forks](https://img.shields.io/github/forks/syssi/esphome-zb-gw03)
![GitHub watchers](https://img.shields.io/github/watchers/syssi/esphome-zb-gw03)
[!["Buy Me A Coffee"](https://img.shields.io/badge/buy%20me%20a%20coffee-donate-yellow.svg)](https://www.buymeacoffee.com/syssi)

ESPHome custom firmware for ZB-GW03 eWeLink Ethernet Zigbee Gateway.

## Compatible hardware

ZB-GW03 Zigbee to LAN bridge/gateway based on Espressif ESP32 and a Silicon Labs EFR32MG21 Zigbee radio (CoolKit-Technologies "SM-011 V1.0" module).

### Supported devices

* ZB-GW03 eWeLink Ethernet Zigbee Gateway (ZB-GW03-V1.0, ZB-GW03-V1.2, ZB-GW03-V1.3), also sold rebranded as:
  * Eachen eWeLink ZigBee Smart Hub
    * https://ewelink.eachen.cc/product/eachen-ewelink-zigbee-bridge-pro-zbbridge-pro/
    * https://ewelinkcommunity.net/device-lists/zigbee/eachen-zb-gw03/
  * SmartWise Zigbee Bridge Pro
    * https://www.okosabbotthon.hu/smartwise-zigbee-bridge-pro

## Requirements

* [ESPHome 2021.9.3](https://github.com/esphome/esphome/releases).

## Quick start guides

* [Flash ESPHome and use the ZB-GW03 as Zigbee Coordinator](docs/flashing.md)
* [How to convert the router into a coordinator](docs/router.md)

## Known issues

* Watchdog heartbeat timeouts if you use ESPHome `>2021.9.3` ([#8][i8])
  https://github.com/oxan/esphome-stream-server/issues/14

[i8]: https://github.com/syssi/esphome-zb-gw03/issues/8

## References

* https://templates.blakadder.com/ewelink_ZB-GW03
* https://github.com/arendst/Tasmota/discussions/12764
* https://github.com/tube0013/tube_gateways
* https://github.com/thegroove/esphome-zbbridge
* https://github.com/oxan/esphome-stream-server
* [https://github.com/CoolKit-Technologies/DevDocs/blob/master/Zigbee/SM-011应用指导书.md](https://github.com/CoolKit-Technologies/DevDocs/blob/master/Zigbee/SM-011%E5%BA%94%E7%94%A8%E6%8C%87%E5%AF%BC%E4%B9%A6.md)
  * https://github.com/zigpy/zigpy/discussions/586
* [https://community.home-assistant.io/t/zb-gw03-ewelink-ethernet-zigbee-gateway...](https://community.home-assistant.io/t/zb-gw03-ewelink-ethernet-zigbee-gateway-now-hacked-with-tasmota-zbbridge-so-can-be-used-via-mqtt-or-as-a-remote-zigbee-adapter-with-home-assistant-zha/341223)
