# YardLink for Lymow

A free Windows app for the **Lymow One Plus** robot mower.

YardLink is unofficial, not made by Lymow. Lymow's R&D team reviewed it and
approved sharing it with the community.

It signs in with your own Lymow account (email and password, Google or
Apple) and talks to your mower through
Lymow's cloud, the same way the phone app does. It does not change the mower
or its firmware.

## Download

**[Get the latest version](https://github.com/HalcyonLogic/yardlink-releases/releases/latest)**: download
`YardLink-for-Lymow-Setup-<version>.exe` and run it.

- Windows 10 or 11, 64-bit.
- Installs for your Windows user only, with no administrator rights needed.
- Uninstall from Windows Settings > Apps.

## What it does

- Status, battery, signal, live map and camera, with the map shown under the
  camera view
- Several mowers on one account: switch between them, as in the phone app,
  or see them all on one map with All Mowers
- Mowing progress as the mower reports it: cut ground filled in, finished
  zones solid
- Start, pause, dock, mow all zones or chosen zones
- Mowing settings, global and per zone
- Scheduled tasks, the same as the phone app's Task Setup
- Two-night split mowing: one cut direction tonight, the cross direction
  tomorrow, so big zones don't run for 12 hours straight
- Mower errors explained in the Lymow app's own words, with how to fix them
- Alerts as Windows notifications
- Tells you when a newer YardLink is published (checked once a day; can be
  turned off)

It opens in a phone-shaped window that looks and works like the Lymow app.

You set up the mower itself in the Lymow phone app. YardLink then finds it on
your account.

## Is it safe?

- Each release lists its VirusTotal scan and SHA-256 checksum, so you can
  check that your download is the file that was scanned.
- The app isn't code-signed, so Windows may say "unknown publisher". Click
  **More info**, then **Run anyway**. AVG or Avast may analyse it for a moment
  the first time it runs.
- Your sign-in is stored only on your PC, encrypted by Windows. The app talks
  only to Lymow's cloud and the free Open-Meteo weather service.
- At Lymow's request the source code isn't public. If you'd like to review it,
  open an issue here and it can be shared with you privately.

## Feedback

Bug reports and ideas are welcome in
[Issues](https://github.com/HalcyonLogic/yardlink-releases/issues).

## License

MIT, see [LICENSE](LICENSE). Lymow and Lymow One Plus are Lymow's. YardLink is
not affiliated with or endorsed by Lymow.
