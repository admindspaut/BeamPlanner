# DEEPSOUND Beam Planner

Beam Planner prepares phased-array ultrasonic testing (PAUT) setups and writes them as `.SET` files for DEEPSOUND instruments.

**[Try it in your browser](https://beamplanner.dspaut.com)** · **[Download the latest release](https://github.com/admindspaut/BeamPlanner/releases/latest)**

This repository hosts the Windows installer and the issue tracker. The source code is not public.

---

## What it does

- Edit channels, probe and wedge on a 2D scan view
- See the probe, wedge and beam paths in 3D
- Check the echo (S-scan) response
- Save and open `.SET` setup files

## Trying it without installing

[beamplanner.dspaut.com](https://beamplanner.dspaut.com) runs the same screens in your browser, with no
licence and no download. It is there to show you what Beam Planner does before you buy it.

The browser version cannot open or save `.SET` files, keeps nothing between visits, and is fixed to
a 32-channel instrument. Install the Windows version for real work.

It sleeps when nobody is using it, so the first page load can take a few seconds.

## Requirements

| | |
|---|---|
| Operating system | Windows 10 or 11, 64-bit |
| .NET | Not needed. The installer carries its own runtime |
| WebView2 Runtime | Installed automatically when missing. That step needs an internet connection |
| License | Required to start. See below |

## Installing

1. Download the installer from the [latest release](https://github.com/admindspaut/BeamPlanner/releases/latest).
2. Run it. It installs to `C:\DEEPSOUND\BeamPlanner`.
3. Start Beam Planner from the Start menu.

The installer is not code-signed yet, so two warnings are expected and can be passed:

- Your browser may say the file is not commonly downloaded. Choose **Keep**.
- Windows SmartScreen may say the publisher is unknown. Choose **More info**, then **Run anyway**.

Installing a newer version over an older one keeps your license and your settings. Close Beam Planner before you run the installer.

## Updating

Beam Planner checks this page for new versions and tells you in the status bar when one is out. You can also check at any time from **Help ▸ Check for updates**.

Updating means downloading the new installer and running it. There is no in-app updater.

## License and activation

Beam Planner needs a license to start. One license covers one PC.

The activation window shows a **Device ID** for the PC you are on. Send us that value to get a license, and use the same window to enter the license key or load the `.lic` file we send back.

**Do not post license keys or Device IDs here.** Issues in this repository are public. For anything about licensing, activation, moving a license to another PC, or purchasing, write to **support@dspaut.com**.

## Reporting a problem or asking for a feature

Open an [issue](https://github.com/admindspaut/BeamPlanner/issues). Bug reports and feature requests are both welcome, and everyone can see what has already been asked for.

Keep licensing matters out of issues, as noted above.

---

© DEEPSOUND. Beam Planner is commercial software. The installer in this repository is provided for licensed customers.
