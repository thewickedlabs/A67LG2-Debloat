# A67LG2 Debloat

Pick which preinstalled bloatware, carrier apps and factory test tools to remove.

A KernelSU Next module for the **Foxxd A67L Gen 2**.

During install it asks about each app: **Volume Up = remove, Volume Down = keep**. With no answer
in 10 seconds, the app is kept.

TikTok Lite · AirTalk · AirVoice · TagMobile · AirVoice Welcome · Face Unlock · LinkTurbo ·
RuntimeTest · ValidationTools · CameraCalibration · CamTa · TuiAuxiService · IFAA Manager ·
Soter Service · Omacp · SGPS · UASetting

Apps are hidden systemlessly. Removing Face Unlock also tells the system it's gone, and removing
LinkTurbo also stops its background service.

## Requirements

- Foxxd A67L Gen 2
- Rooted with KernelSU Next

The installer stops without changing anything if either is missing.

## Install

1. Download `A67LG2-Debloat.zip` from Releases.
2. KernelSU Next → Modules → Install from storage → select the zip.
3. Reboot.

## Uninstall

Disable or remove the module and reboot. Every app comes back.

One exception: for AirTalk, AirVoice and TagMobile, the Play Store updates installed on top of the
stock apps are uninstalled. After restoring, those apps are back at their factory version until the
Play Store updates them again.

## License

[WTFPL](LICENSE).

---

Wicked Labs · https://www.cyberspace7.org
