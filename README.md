# <img src="images/c2m.ico" width="32" height="32" /> C2M - Call of Duty Map Exporter

<table style="border-collapse:collapse;border:0;margin:0;padding:0;">
  <tr>
    <td style="padding:2px 16px 2px 0;white-space:nowrap;"><b>Originally Developed By:</b></td>
    <td style="padding:2px 12px 2px 0;">Sheilan</td>
    <td style="padding:2px 0;">
      <a href="https://github.com/sheilan102"><img src="/images/github.ico" width="24" height="24"></a>
      <a href="http://paypal.me/ksheilan"><img src="/images/paypal.ico" width="24" height="24"></a>
    </td>
  </tr>
  <tr>
    <td style="padding:2px 16px 2px 0;white-space:nowrap;"><b>Developed For Version 3 By:</b></td>
    <td style="padding:2px 12px 2px 0;">Astral</td>
    <td style="padding:2px 0;">
      <a href="https://github.com/o-Astral-o"><img src="/images/github.ico" width="24" height="24"></a>
      <a href="https://paypal.me/astralmodz"><img src="/images/paypal.ico" width="24" height="24"></a>
    </td>
  </tr>
</table>

## 🎮 Supported Games

| Game                                                | Methods                        |
|-----------------------------------------------------|--------------------------------|
| Call of Duty: Modern Warfare                        | Base Game, CoD4x               |
| Call of Duty: World at War                          | Base Game, Plutonium           |
| Call of Duty: Modern Warfare 2                      | Base Game, IW4x                |
| Call of Duty: Black Ops                             | Base Game, Plutonium           |
| Call of Duty: Modern Warfare 3                      | Base Game, Plutonium           |
| Call of Duty: Black Ops 2                           | Base Game, Plutonium, Redacted |
| Call of Duty: Ghosts                                | Base Game, Cordycep, IW6x      |
| Call of Duty: Advanced Warfare                      | Base Game, Cordycep            |
| Call of Duty: Online                                | Cordycep                       |
| Call of Duty: Black Ops 3                           | Base Game, Cordycep            |
| Call of Duty: Infinite Warfare                      | Base Game, Cordycep            |
| Call of Duty: Modern Warfare Remastered             | Base Game, Cordycep            |
| Call of Duty: World War II                          | Base Game                      |
| Call of Duty: Black Ops 4                           | Base Game, Shield/Project BO4  |
| Call of Duty: Modern Warfare 2019                   | Cordycep                       |
| Call of Duty: Modern Warfare 2 Campaign Remastered  | Base Game, Cordycep            |
| Call of Duty: Black Ops Cold War                    | Base Game                      |
| Call of Duty: Vanguard                              | Cordycep                       |
| Call of Duty: Modern Warfare II                     | Cordycep                       |
| Call of Duty: Modern Warfare III                    | Cordycep                       |
| Call of Duty: Black Ops 6                           | Cordycep                       |

## ⬇️ Export Formats

| Format  | Description       | Usage                            |
|---------|-------------------|----------------------------------|
| .C2M    | Custom C2M Format | Holds all map data               |
| .OBJ    | Wavefront OBJ     | Holds Map Geometry or Model data |
| .MAP    | Quake/Radiant Map | Holds Static Model Instance data |

## 🎯 Getting Started
### Base Game / Modded Clients
- Load into a map in game
- Edit **Load Settings** to your liking
- Press **Load Game** and wait for C2M to parse the map data
- Edit **Export Settings** to your liking
- Press **Export Map** and wait for C2M to export the map files
### Cordycep
- Load game through Cordycep
- Load a map file e.g: `loadwc *mp_rust*`
- Continue just the same as you would for Base Game

## ⬆️ Importers
[Unreal Engine (Coming Soon)](https://github.com/o-Astral-o)

## 🔍 Tutorials
[Unreal Engine (Coming Soon)](https://www.youtube.com/@Astral_CG)

## 🛠️ Support
[AGR Tech Support Discord](http://discord.c2mproject.com)

[C2Mv3 GitHub](https://github.com/o-Astral-o/C2Mv3/releases)

## ❓ FAQ
| Question                                        | Answer                                                                | Affected Games                      |
|-------------------------------------------------|-----------------------------------------------------------------------|-------------------------------------|
| Why is some Map Geometry missing?               | This is Super Terrain, which we currently don't support               | Black Ops 4 +                       |
| Why is there a bunch of props at 0,0,0?         | These are Splined Model Instances, which we currently don't support   | Black Ops 4 +                       |
