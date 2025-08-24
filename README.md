<p align="center"><b>👉 USE AT YOUR OWN RISK</b></p>

<br>

The OC is built for `macOS Ventura`. If you prefer to use `macOS Monterey` or `macOS Sonoma`, replace the WiFi Kext (`AiportItlwm`) with the appropriate version from [OpenIntelWireless](https://github.com/OpenIntelWireless/itlwm).

## System Requirements

- **Motherboard**: Gigabyte B660M D3SH AX WIFI
- **CPU**: Intel Core i3 12100F
- **RAM**: 16x2 GB 3200 MHz
- **GPU**: AMD RX 6600 8 GB
- **Casing**: XPG Valor Air

## Not Working

- Airdrop
- iServices
- Bluetooth 5.0+ *(Only on Sonoma)*

Everything else is tested and working well.

## Misc. Workarounds

#### Bluetooth 

Bluetooth 5.0+ is working on `Monterey` and `Ventura` but requires latest version of [IntelBluetoothFirmware](https://github.com/OpenIntelWireless/IntelBluetoothFirmware) for `Sonoma`.

#### HiDPi Scaling

By default, macOS doesn't play well with non-retina displays. If you're using a 1440p monitor, use [BetterDisplay](https://github.com/waydabber/BetterDisplay). On 4K, you can perfectly scale to 1080p.

## LICENSE
MIT
