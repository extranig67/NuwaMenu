# ✦ ElysiumModMenu — Among Us

A BepInEx IL2CPP mod menu for Among Us.
Host tools, ESP, anti-cheat protection, spoofing, chat improvements, and lobby automation — all in one place.

> ⚠️ **Heads up.**
> This menu includes powerful host-side and network tools. Use them in private lobbies with friends.
> Don't ruin other people's games.

---

## ⬇️ Download

Current version: **v1.3.5** — [ElysiumModMenu.dll](#)

---

## ✨ What's New in v1.3.5

* ⭐ Favorite Outfits system — save and restore up to 4 cosmetic loadouts
* 🎞️ FPS limiter with a configurable cap
* 👻 Auto Ghost After Start — become a ghost automatically when the game begins
* 🎨 Allow Duplicate Colors — lets multiple players use the same color
* 🛡️ Platform Ban from TXT — host-ban players based on custom platform tokens loaded from a file
* 🤖 Bot ban list with persistent storage (`ElysiumBotBanList.txt`)
* 🛰️ ESP Friend Code display toggle — can be hidden per-player via ignore list
* 👁️ Friend ESP ignore list — specific players won't show ESP info above their names
* 🌙 Dark chat theme toggle
* 💬 Custom ghost chat color — hex, configurable
* 🌍 Multi-language menu support — EN, DE, FR, ES, IT, PT, PL, NL, TR, CS, RO, HU, SV
* ✍️ Spell check — basic
* 📄 Anomaly log reports — opt-in diagnostic reporting for faster anti-cheat fixes
* 🌈 RGB menu color mode
* 🪪 Menu watermark toggle
* 🔐 Removed plaintext webhook config from older versions — auto-migrated on launch

---

## 👤 Account / Local Spoof

Everything here is client-side only unless noted otherwise.

* Level spoof
* Platform spoof with selectable platform
* Local name spoof — no RPC broadcast, only visible on your screen
* Local fake Friend Code — no symbol limit, client-only
* Network Friend Code spoof in serialized player data
* Unlock cosmetics
* Guest name unlock

Name effect examples:

```text
shimmer:Elysium
#68B6E7BlueName
<color=#68B6E7><b>RichName</b></color>
```

---

## 👁️ Visuals / ESP

* See ghosts
* See player roles
* Player info above nameplates: Host · Lv:X · Platform · FriendCode
* `spf` next to platform means platform spoof is active on that player
* Reveal roles during meetings
* Reveal votes
* See players inside vents
* Full Bright
* Tracers
* Free camera — WASD + scroll wheel to zoom
* Always show chat
* Read ghost chat

---

## 🛡️ Anti-Cheat / Protection

* RPC protection with configurable rate limit
* Block spoof RPC
* Block sabotage and meeting abuse
* Block game RPC in lobby
* Block chat flood
* Block meeting flood
* RPC sniffer with known mod menu IDs
* Pet Spam Shield — auto-ban pet spammers when you are host
* Anti vote-kick
* Auto-kick Fortegreen and bugged color players
* Auto-ban platform spoofers — host only
* Platform ban from TXT — block players by custom platform token
* Broken Friend Code detector
* Bot ban list with persistent storage
* Local persistent ban list
* Friend ESP ignore list — hide ESP info for specific players

Config files:

```text
ElysiumModMenuBanList.txt
ElysiumPlatformBanList.txt
ElysiumBotBanList.txt
ElysiumFriendEspIgnore.txt
```

---

## 💬 Chat

* Extended chat length
* Fast chat
* Links, email, and symbol support
* Chat history — Up / Down arrows
* Clipboard support — Ctrl+V, Ctrl+C, etc.
* Local chat log
* Whisper / private messages
* `/color` command
* Dark chat theme
* Custom ghost chat color — hex
* Spell check — basic
* Host filters for rainbow names and Fortegreen abuse
* Allow duplicate player colors

Chat log file: `ChatLog.txt`

---

## 👕 Cosmetics / Outfits

* Favorite Outfits — 4 slots to save and restore full cosmetic loadouts
* Apply any saved slot with one click
* Save your current outfit or the selected player's outfit

---

## 🧰 Host / Lobby Tools

* Auto Host
* Auto return after matches
* Fast start
* Wait for loaded players
* Force start
* Pre-game role manager
* Force impostors
* Force roles
* Kill all
* Kick all
* Report / eject / revive
* Morph / mass morph
* Spawn / despawn in lobby
* Insta start
* Smart end game
* No task mode
* No setting limits
* Auto Ghost After Start

---

## 🚪 Sabotage / Doors

* Trigger Reactor, O2, Comms, Lights — individually or all at once
* Fix all sabotages
* Close / open all doors
* Lock / unlock doors by room

---

## ⚙️ General / Misc

* FPS limiter
* Allow duplicate player colors
* More lobby info in the game list — host name, lobby age, platform, game code
* Multi-language menu — 13 languages
* RGB menu color mode
* Menu watermark toggle
* Custom keybinds for everything

---

## ⌨️ Menu Controls

Default toggle key: `Insert`

Rebind it inside the menu under Keybinds.

---

## 📝 Text Fields

The menu uses custom input fields. Long values are clipped visually, but you can keep typing normally.

| Key                       | Action                |
| ------------------------- | --------------------- |
| `Ctrl+V` / `Shift+Insert` | Paste                 |
| `Ctrl+C`                  | Copy field            |
| `Ctrl+X`                  | Cut field             |
| `Backspace`               | Delete last character |
| `Esc`                     | Stop editing          |

---

## 📦 Installation

You need BepInEx IL2CPP first.

1. Download BepInEx IL2CPP.
2. Extract it into your Among Us folder, next to `Among Us.exe`.
3. Run the game once, then close it.
4. Download `ElysiumModMenu.dll`.
5. Drop it here:

```text
Among Us/BepInEx/plugins/
```

6. Launch Among Us.

---

## 📁 Finding Your Among Us Folder

**Steam:** Library → Among Us → Manage → Browse local files

**Epic Games:** Library → Among Us → Manage → Open install folder

**Xbox App:** Manage → Files → Browse

**Itch.io:** Manage → Open folder in Explorer

---

## 🖼️ Custom Menu Background

Place your image here:

```text
Among Us/BepInEx/config/ElysiumModMenu/MenuBG.png
```

`.jpg` is also supported.

---

## 🧱 Build

The project targets .NET 6:

```powershell
dotnet build .\NjordMenu.csproj
```

Output:

```text
bin/Debug/net6.0/ElysiumModMenu.dll
```

---

## 📸 Screenshots

![Anti-cheat and protections](https://github.com/user-attachments/assets/c4a2a364-bd2f-44e4-a27c-8d299ddd8415)

![Host and lobby controls](https://github.com/user-attachments/assets/8373b7c4-a0d2-4762-bf02-38263ad04636)

![Visuals and ESP](https://github.com/user-attachments/assets/69735f5d-31db-462e-abdb-de2dcce11f6a)

---

## ⚠️ Disclaimer

ElysiumModMenu is not affiliated with Innersloth and is not officially supported by Among Us.
Use it at your own risk.

Don't crash public lobbies, grief random players, or abuse people with it. Support won't be given if you do.
