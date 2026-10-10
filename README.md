# JetBoard Mod for Satisfactory (beta)

This mod brings the [JetBoard](https://jakanddaxter.fandom.com/wiki/JET-Board) from the [Jak & Daxter series](https://jakanddaxter.fandom.com/wiki/Jak_and_Daxter_series) into [Satisfactory](https://www.satisfactorygame.com).

[video demo](assets/videos/jetboard-demo-vid.mp4)

It's particularly inspired by my love for [Haven Forest](https://youtu.be/rxbE-NjpPuY) in Jak II. The beautiful atmosphere has stayed with me since a kid, and as a huge fan of Satisfactory, I thought why not have some fun combining them. It's also inspired by the great work the [OpenGOAL](https://opengoal.dev/) team is doing. And of course, see [credits](credits.md) for more details.

## How to install this mod

1. Head to the [releases](https://github.com/jonzo84/jetboard-satisfactory-public/releases) page and download the latest release.
2. Extract the ZIP.
3. Close Satisfactory and Satisfactory Mod Manager.
4. Open `START SETUP.cmd`.
5. In the dropdown, select your Satisfactory install location if it's not auto-selected, eg `C:\Program Files (x86)\Steam\steamapps\common\Satisfactory`.
6. Click **Install / Repair**.
7. When files are verified, click **Launch** (or just open Satisfactory from Steam).

## How to access the JetBoard in Satisfactory

1. Unlock it from the HUB in Tier 3.

![JetBoard Unlock](assets/screenshots/jetboard-milestone.png)

2. Build the JetBoard in the Equipment Workshop.

![JetBoard Build](assets/screenshots/build-jetboard.png)

3. Equip the JetBoard in your second leg slot. You can wear Blade Runners normally.

![Equip JetBoard](assets/screenshots/equip-jetboard.png)

4. Make sure you've got fuel! Just like with the Jet Pack, the higher the energy density, the faster you'll go.

---

## Troubleshooting

If Windows blocks a downloaded script, right-click the downloaded ZIP, select **Properties**, tick **Unblock** if shown, **Apply**, then extract it again. Do not change your machine's PowerShell execution policy.

Setup uses the bundled SML 3.12.0 ZIP when included, checking its checksum first. Smaller download-only bundles fetch SML from its official GitHub release when needed. Approve the Windows permission prompt only when installing to a protected folder.

If the download fails: retry **Install / Repair**, or download the
[official SML Windows ZIP](https://github.com/satisfactorymodding/SatisfactoryModLoader/releases/download/v3.12.0/SML-Windows.zip). Click **Select SML ZIP** and choose it. Setup verifies it automatically.

**Verify** checks installed files. After a fresh launch from setup, click **Verify** again at the main menu to check startup markers.

Click **Collect diagnostics**, then **Open log location**. Review the single `.log` file. Logs may contain game paths and selected gameplay/network errors. Home-directory names and IPs are redacted.

## In game

Each player: `/hoverboard` in chat, equip the board in the back slot, stand on dry ground, close menus, press **Secondary Fire** (normally right mouse button). `/hoverboard off` is the recovery dismount command.

## Manual install

Close the game. **Steam > Satisfactory > Manage > Browse local files**.

| Archive | Extract contents directly into |
|---|---|
| `Hoverboard-Windows.zip` | `FactoryGame/Mods/GameFeatures/Hoverboard/` |
| `SML-Windows.zip` | `FactoryGame/Mods/SML/` |

Check that `Hoverboard.uplugin` and `SML.uplugin` sit directly in those respective folders, not in extra nested folders. Move old mod folders outside Mods before replacing them. Keep `Credits.md` with any copy you share.

---

## Credits

- See Credits.md