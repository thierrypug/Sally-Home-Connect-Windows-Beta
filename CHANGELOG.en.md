# Changes

🇫🇷 [Version française](CHANGELOG.md)

## Version 0.2.6-beta — Simpler, and it saves energy

- **adding a device** starts with what you are adding: **Light, Shutters, Heating, Relay** or **Other** (you type what
  it is yourself, and it becomes the device's name); then the brand; Sally only asks "Zigbee or EnOcean?" when needed
  (for NodOn, the reference tells you: a 2 = EnOcean, a 4 = Zigbee) and reads the right pairing steps aloud;
- **automatic savings**: a window open for more than 30 seconds puts the room's heating on frost protection, then it
  returns to its mode when closed; a forgotten light in a room empty for 30 minutes is switched off; the home screen
  shows **what Sally saved you this month, in euros** (Settings → Savings to switch them off);
- **routines**: new **"Go back to how it was at the end"** switch (window closed → each device returns to its previous
  state) and new condition **"the heating is not off"**;
- **dashboard** (Rooms → Dashboard): one box per room, in the colour of what is happening there; you can add a **photo
  of your floor plan** and place each room on it;
- **invite your family with a QR code**: they scan it with their phone and are signed in, with no code to type (once
  only, for 24 hours);
- the **"Leaving"** tile becomes **"I'm home"** when you are out; **the eye** to see your access code while typing it;
  **change your name**; **"Small" display size** by default (change it in Settings);
- **EnOcean shutter**: **Stop** button, and tapping the arrow of the current movement again stops it;
- pairing instructions fixed (EnOcean module: press for more than 5 seconds; bulbs that don't support remote reset);
  a device that is unplugged and removed from Sally really leaves the Zigbee network.

## Version 0.2.5-beta — Sally 2.0: family life

- **family life**: household members (adults and children), **messages** between them delivered at the right moment
  (when they get up, when they walk into a room…), **reminders**, **gentle wake-up** without an alarm (heating, light
  rising slowly, shutters), **"good night"** that tells you what is still open, **night light**, **morning summary**;
- **"I'm leaving" / "I'm home"** and **who's home?**; when the alarm is on, one minute to come in before the alert;
- **shared shopping list**, with a copy readable on your phone at the shop;
- on holiday, Sally **replays your home's habits**; return date: heating back to comfort before you arrive;
- **voice control in 5 languages**, without the Internet; Sally **answers out loud** (female voice by default,
  you can pick another one in Settings → Sally's voice);
- **alerts spoken aloud**, shown as a card on the home screen until you **clear** them; "It's the wall switch"
  for a lamp switched off at the wall;
- **NodOn**: double relay, dry contact, energy meter, EnOcean motion sensor and shutter;
  **pairing guide by brand** in the add-device assistant;
- fixes: Zigbee stick blocked after a remote reset, live lamp percentage, readable drop-down lists.

## Version 0.2.4-beta — Sally 2.0: access code, purchase and updates (included in 0.2.5)

- **your home is protected by an access code**: without it, nobody can control it, even on your Wi-Fi. You choose
  it the first time you start Sally (if you had a 0.2 beta, Sally asks for it when you open it); each phone stays
  signed in;
- **family accounts** and time-limited **guest access**, possibly limited to a few rooms
  (Settings → Accounts and access);
- **recovery code** if you forget your access code;
- **buy Sally from the app** (Settings → Buy Sally): after paying, Sally activates by itself (sales open soon;
  during the beta, the purchase page lets you write to us with your code);
- **updates**: if you allow the Internet, Sally tells you about a new version (Settings → Updates); on the
  Raspberry Pi, it installs with one tap and goes back to the previous version by itself if something goes wrong;
- three new Help topics: Access code and accounts, Updates, Buying Sally.

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
