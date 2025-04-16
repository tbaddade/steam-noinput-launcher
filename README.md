# Steam NoInput Launcher

## ENGLISH | DEUTSCH (unten)

A simple macOS app to launch Steam with Steam Input and joystick support disabled.  
Useful for users who experience issues with racing wheels, gamepads or HID devices not behaving correctly when Steam is running.

### 🚀 Features

- Launches Steam with `-nojoy -input_disable_steam_controller`
- Prevents Steam Input from overriding your hardware (e.g., Logitech wheels)
- Works on macOS 13–15
- Lightweight and open source

> ℹ️ **Note:** Changing Steam's controller settings alone often has no effect on certain devices like racing wheels.  
> This launcher ensures Steam Input is truly disabled by passing launch arguments to the Steam app directly.

### 📦 Installation

1. Download the `.app` bundle from [Releases](https://github.com/tbaddade/steam-noinput-launcher/releases)
2. Move it to `/Applications` or your preferred location
3. Optional: Add it to the Dock or Login Items
4. Double-click to launch Steam with input disabled

### 🛠️ Build it yourself

You can build your own version using Automator or Platypus. See [src/launch-steam.sh](src/launch-steam.sh) for the command used.

### 📄 License

MIT License

---

## Deutsch

Eine einfache macOS-App, um Steam **ohne Steam Input oder Gamecontroller-Support** zu starten.

Perfekt für Nutzer, bei denen Lenkräder, Gamepads oder HID-Geräte unter Steam nicht korrekt funktionieren.

### 🚀 Funktionen

- Startet Steam mit den Parametern `-nojoy -input_disable_steam_controller`
- Verhindert, dass Steam Input dein Gerät beeinflusst (z. B. Nullstellung von Lenkrädern)
- Funktioniert unter macOS Ventura, Sonoma und darüber hinaus
- Schlank, quelloffen, ohne Installation von Tools nötig

> ℹ️ **Hinweis:** Änderungen in den Steam-Einstellungen zur Deaktivierung von Steam Input reichen oft nicht aus, insbesondere bei Lenkrädern.  
> Diese App sorgt durch spezielle Startparameter dafür, dass Steam Input wirklich deaktiviert ist.

### 📦 Installation

1. Lade das `.app`-Bundle von [Releases](https://github.com/tbaddade/steam-noinput-launcher/releases) herunter
2. Verschiebe es in `/Programme` oder einen Ort deiner Wahl
3. Optional: Ins Dock oder Autostart legen
4. Mit Doppelklick starten – Steam wird ohne Input geladen

### 🛠️ Selbst bauen

Du kannst die App auch selbst mit Automator oder Platypus bauen. Das verwendete Skript findest du unter [src/launch-steam.sh](src/launch-steam.sh)

### 📄 Lizenz

MIT-Lizenz


## Credits

**Icon** by [aramsoneson](https://macosicons.com/#/u/aramsoneson)