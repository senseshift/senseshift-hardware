# OpenHaptics Hardware

> Hardware Schematics for [OpenHaptics Firmware](https://github.com/openhaptics/openhaptics-firmware)

[![Discord](https://img.shields.io/discord/966090258104062023?label=Discord&logo=discord)](https://discord.gg/YUtRKAqty2)
[![Developer's Twitter](https://img.shields.io/twitter/follow/leon0399?color=%231DA1F2&label=Developer%27s%20Twitter&logo=twitter)](https://twitter.com/leon0399)

## Schematics

> Each configuration have it's own BOM and wiring diagram

### Haptic Vest

#### X16 Haptic Vest

> Supported devices: **TactSuit X16**

* [X16 Vest with PCA9685](Devices/X16%20Vest/ESP32%20%2B%20PCA9685/)
* [X16 Vest without PCA9685](Devices/X16%20Vest/ESP32%20%2B%20Integrated%20PWM/)

#### X40 Haptic Vest

> Supported devices: **TactSuit X40**, **Tactot**

* [X40 Vest with x2 PCA9685](Devices/X40%20Vest/ESP32%20%2B%20x2%20PCA9685%20%2B%20Integrated%20PWM/)

### Haptic Face Interface

> Supported devices: **Tactal**

* [x6 Facial Interface](Devices/Face%20Interface/ESP32%20+%20Integrated%20PWM/)

### Haptic Forearm Sleeve

> Supported devices: **Tactosy for Arms**

* [x6 Forearm Sleeve](Devices/Forearm%20Sleeves/ESP32%20+%20Integrated%20PWM/)

### Haptic Gauntlet

> Supported devices: **Tactosy for Hands**

* [x3 Hand Gauntlet](Devices/Hand%20Gauntlets/ESP32%20+%20Integrated%20PWM/)

### Haptic Feet Device

> Supported devices: **Tactosy for Feet**

* [x3 Feet Device](Devices/Feet%20Devices/ESP32%20+%20Integrated%20PWM/)

## OpenHaptics PCBs

PCBs are currently stored in [`feature/haptic-boards`](https://github.com/openhaptics/openhaptics-hardware/tree/feature/haptic-boards) branch (See PR [#3](https://github.com/openhaptics/openhaptics-hardware/pull/3)). Those designsed haven't been tested and will be merged, as soon as they are confirmed to be working 100%

## Licenses

[![CC-BY-SA-4.0](https://img.shields.io/github/license/openhaptics/openhaptics.github.io)](/LICENSE)

Each project directory has it's own `LICENSE` file inside and licensed under corresponding license. Otherwise, if no `LICENSE` file is provided, it is licensed under [CC-BY-SA-4.0](https://creativecommons.org/licenses/by-sa/4.0/) license
