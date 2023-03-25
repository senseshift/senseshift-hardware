# X40 Haptic Vest

> X40 Haptic Vest with 3V/5V vibro motors, optionally powered by LiPo battery

> **Warning**  
> **Disclaimer:** This design is a **functional prototype**, not a complete product. There is absolutely no warranty, and you will make this design at your OWN risk. I will not be responsible for any damages associated with this design.

## Compatible Devices

* TactSuit X40, Tactot

## Guides:

* [Build Guide](https://docs.google.com/document/d/1j84h-7OIkRO9KTNtq_mKxri_7PsSNUnL/view) by ProBendingVR

## Bill of materials

| Component                                      | Quantity |    Price | Link  |
| :--------------------------------------------- | -------: | -------: | :---- |
| `ESP32-DevKitC`                                |       x1 | ~US $1.3 | `n/a` |
| `PCA9685` PWM Driver                           |       x2 | ~US $3.0 | `n/a` |
| `ULN2803A`                                     |       x5 | ~US $0.3 | `n/a` |
| 3V/5V Vibro Motors                             |      x40 | ~US $1.1 | `n/a` |
| `TP4056` (Optional)                            |       x1 | ~US $0.3 | `n/a` |
| `MT3608` (Optional)                            |       x1 | ~US $0.4 | `n/a` |
| LiPo Battery (Optional)                        |       x1 | ~US $7.0 | `n/a` |
| `MAX17043` or `MAX17048` Fuel Gauge (Optional) |       x1 | ~US $5   | `n/a` |

## Schematic

### Required Pins

* SDA: `21`
* SCL: `22`
* PWA pins: `32`, `33`, `25`, `26`, `27`, `14`, `13`

### Wiring Diagram

![Schematic](schematic_bb.png)
