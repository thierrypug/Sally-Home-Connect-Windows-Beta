# Sally Home Connect — Windows beta

🇫🇷 [Version française](README.md)

**Your smart home, no rewiring, and your data stays at home.**

Sally Home Connect controls your lights, plugs, shutters and heating from your computer and your phone,
**100% locally**: no account, no cloud, no data from your home ever leaves it.

> **We're looking for testers!** Try Sally and tell us what you think:
> [Issues](../../issues) tab or **sallyhomeconnect@gmail.com**

## Download

👉 [**Download the latest version**](../../releases/latest): file `SallyHomeConnect-Setup-Beta-v….exe`

- Windows 10 or 11, 64-bit
- **30-day free trial**, with all features
- Nothing else to install: Node.js is included
- The installer is available in English, French, German, Spanish and Italian
- **No hardware? A demo** with a simulated home and simulated devices is included

Step-by-step guide: [INSTALLATION-WINDOWS.en.md](INSTALLATION-WINDOWS.en.md)

## What Sally can do

- A simple dashboard, on computer and phone
- Lights, plugs, roller shutters, heating (French "fil pilote" and thermostats), sensors
- Routines ("when… if… then…"), scenes, weekly heating schedules
- Home modes: home, away, night, holidays (with simulated presence)
- Energy use and cost tracking (peak and off-peak hours)
- Alerts: water leak, smoke, low battery, device not responding
- **Voice control that works without Internet**: your voice never leaves your home
  (French only for now)
- Interface in English, French, German, Spanish and Italian

## Compatible hardware

Sally finds the USB stick plugged into the computer by itself:

| Technology | Supported sticks |
|---|---|
| Zigbee | Sonoff ZBDongle-P, Sonoff ZBDongle-E, ConBee II |
| EnOcean | EnOcean USB 300 |

Several thousand Zigbee devices are recognised (Philips Hue, IKEA, Aqara, Sonoff, NodOn, Legrand…),
thanks to a library shipped with Sally: nothing is looked up on the Internet.

## Truly local home automation

- No online account, no subscription, no cloud service.
- Everything works without Internet.
- Sally never accesses the Internet without your permission. Only the weather can be fetched, if you allow it in Settings.

## Good to know about this beta

- Anyone connected to your Wi-Fi can control the home: accounts and guest access are coming soon.
- The final version of Sally is designed for a **Raspberry Pi**, running day and night without a screen. It is not
  published yet: the home you create during the trial can be transferred to it without redoing anything.
- The beta is **free** and provided **as is, without warranty**: it is a trial version and some bugs may remain.
  It collects no data: everything stays on your computer.
- What's new in each version: [CHANGELOG.en.md](CHANGELOG.en.md)

## Give us your feedback

What works, what's blocking, what's missing, your hardware… we want to hear it all:
[Issues](../../issues) tab or **sallyhomeconnect@gmail.com** (English is fine!)

## Rights

Sally Home Connect is software protected by copyright. This beta is lent for trial purposes:
it may not be modified, copied or redistributed without the author's permission.
