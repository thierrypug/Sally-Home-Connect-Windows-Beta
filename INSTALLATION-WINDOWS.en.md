# Installing Sally Home Connect on Windows

🇫🇷 [Version française](INSTALLATION-WINDOWS.md)

## What you need

- Windows 10 or Windows 11, 64-bit;
- administrator rights to install the program;
- a recent browser (Edge, Chrome, Firefox).

Node.js is included in the installer: nothing else to install.

**To control real devices**, you also need a USB stick plugged into the computer:

| Technology | Supported sticks |
|---|---|
| Zigbee | Sonoff ZBDongle-P, Sonoff ZBDongle-E, ConBee II |
| EnOcean | EnOcean USB 300 |

**Without hardware**, you can discover everything with the demo (simulated home and devices).

## Download

1. Open the **Releases** tab of the GitHub repository.
2. Download the file of the latest version, for example:

   ```text
   SallyHomeConnect-Setup-Beta-v0.2.3-beta.exe
   ```

3. Double-click the downloaded file.

Windows may show "Windows protected your PC": the installer is not signed yet.
Click **More info** then **Run anyway**.

## Install

1. Accept Windows' permission request.
2. Choose the installer's language (your Windows language is selected by default).
3. Keep the suggested folder (`C:\Program Files\Sally Home Connect`).
4. Leave the Desktop icon checked. Check "Start Sally with Windows" if you want it to start
   every time the computer starts.
5. Finish the installation: Sally starts and your browser opens.

**Already have an older beta?** Just install over it: your home is kept (from version 0.2.0 on).

## First start

The browser opens on:

```text
https://localhost
```

It shows a security warning: that's normal, Sally uses its own certificate, created on your
computer. Click **Advanced** then **Continue to localhost**.

A welcome wizard then guides you: language, name of your home, and the addresses to open Sally on your phone.
Sally's interface follows your browser's language; you can change it at any time in **Settings**.

Plug in your USB stick **before** starting Sally: it finds it by itself. Then add your devices
with the **Add a device** button.

## Shortcuts

In the Start menu, **Sally Home Connect** folder:

- **Sally Home Connect**: your home (also on the Desktop);
- **Sally Home Connect - Demo**: the simulated home, on `https://localhost:3443`;
- **Stop Sally Home Connect**: stops Sally and the demo;
- **README** and **Uninstall Sally Home Connect**.

Sally runs without a window. Clicking the shortcut again simply reopens the browser.

## On your phone

Connect the phone to the same Wi-Fi as the computer and open:

```text
https://sally.local
```

Accept the security warning as on the computer. You can then add Sally to the phone's home screen
(browser menu → "Add to Home screen").

If `sally.local` doesn't open (some antivirus software blocks these addresses), use the address with numbers
shown in **Settings → Sally's address**.

## Where is my data?

Not in the program folder, but here:

```text
C:\Users\YourName\AppData\Local\Sally Home Connect
```

It contains the home (rooms, devices), routines, settings, backups, the Zigbee network
and the logs (`logs`). Uninstalling keeps this folder.

## If Sally doesn't start

- A message shows where the log is: `AppData\Local\Sally Home Connect\logs\sally.log`.
- Send us this file through the **Issues** tab or to **sallyhomeconnect@gmail.com**.

## Uninstall

```text
Settings > Apps > Installed apps > Sally Home Connect > Uninstall
```

The program is removed; your data stays in your user folder.
