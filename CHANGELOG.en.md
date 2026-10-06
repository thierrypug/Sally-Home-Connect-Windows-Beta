# Changes

🇫🇷 [Version française](CHANGELOG.md)

## Version 0.2.3-beta — Sally speaks your language

- **the installer now asks for your language**: English, French, German, Spanish or Italian
  (your Windows language is selected by default);
- Start menu shortcuts, the README and the error message (if Sally can't start) are in the chosen language;
- documentation available in English on GitHub.

## Version 0.2.2-beta — Welcome, and backup fixed

- **welcome wizard** on first launch: language, name of your home, then the addresses to open Sally on your phone;
- **Settings → Sally's address**: the addresses to type on your phone, with the `.local` name and the address with
  numbers (useful when an antivirus blocks `.local` addresses);
- the **name of your home** is shown at the top of the home screen (editable in Settings → My home);
- **important fix**: restoring a backup containing the Zigbee network failed; it's fixed;
- getting ready for the Raspberry Pi: "My Raspberry Sally" in Settings finds a Raspberry Pi on your network and sends
  it your home (the Raspberry Pi version will be published soon);
- new Help topic: "Moving to a Raspberry Pi".

## Version 0.2.1-beta — Sally talks, and a user guide

- Sally talks while you add a device (with a voice installed on the computer, without Internet);
  a button lets you mute her;
- she asks which room to put the device in; rooms are shown as buttons, and a missing room is created;
- **switches and remote controls**: Sally asks what they should control and creates the link by herself;
- **new Help tab**: a complete user guide, in 5 languages.

## Version 0.2.0-beta — Sally entirely rebuilt

Sally Home Connect was rebuilt from scratch: simpler, faster, and still 100% local.

- new dashboard, on computer and phone, with five colour themes;
- rooms with picture, temperature, humidity and presence;
- lights, plugs, roller shutters, heating ("fil pilote" and thermostats), sensors;
- "when… if… then…" routines, scenes, weekly heating schedules;
- home modes: home, away, night, holidays (with simulated presence);
- energy and cost, peak and off-peak hours;
- alerts (leak, smoke, low battery, device not responding) and home log;
- device wizard in the app; backup and restore in one file;
- **voice control that works without Internet** (French only for now);
- **demo**: a simulated home and devices, to try everything without hardware;
- weather of the day, only if you allow it (off by default);
- interface in 5 languages.

Known limits: anyone on the Wi-Fi can control the home (until accounts arrive); Sally's own HTTPS certificate
triggers a browser warning the first time; the installer is not signed yet.

## Versions 0.1.x

First Windows betas (Sally version 1). Devices from a 0.1 beta must be added again in version 0.2.
