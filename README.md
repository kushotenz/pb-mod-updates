# PokeBrawl

**Real-time 3D Pokémon battles**, built in Godot with the models of Cobblemon and Cobbleverse.
88 Pokémon, 39 Mega Evolutions and battle forms, 6 arenas: against the AI, 1 vs 1 online,
or a free-for-all for up to 4 players.

PokeBrawl is a free, non-profit fan project. This repository holds the game's builds: the
game keeps itself up to date from here.

## Download

Get **`PokeBrawl.zip`** from the [latest release](https://github.com/kushotenz/pb-mod-updates/releases/latest)
(Windows, 64-bit), unzip it into a folder of its own and open `PokeBrawl.exe`.

- If Windows says "Windows protected your PC", choose *More info* > *Run anyway*.
- **Updates install themselves:** at start the game checks for a new version and offers it;
  one click downloads it, swaps the game and restarts it.
- Online, everyone needs the same version (the game warns you if not).
- Keyboard and mouse or a gamepad (Xbox or PlayStation), also at the same time.

Inside the zip: the game (with its music), `CREDITS.txt` and `GODOT-LICENSES.txt`.

## What is in

- **88 Pokémon** (the full list is below), each with its own model, animations, cry and
  way of moving: speed, jumps, dodges and, for many, flight.
- **224 moves and 61 abilities** from the games. Pick each Pokémon's four moves and
  its ability from what it learns; every move shows its power, cooldown, reach and timings.
- **Mega Evolution:** deal damage to fill the Mega bar, then Mega Evolve once per battle for
  20 seconds, with its own cinematic. 39 forms, among them both Charizard and Mewtwo X/Y, the
  Legends Z-A Megas (Garchomp Z, Lucario Z, Greninja, Dragonite, Chandelure...), Eternamax
  Eternatus, Ultra Necrozma and Armored Mewtwo.
- **Forms picked in the lobby:** 9 forms in all, e.g. Deoxys' four formes, Urshifu's two styles,
  the Origin formes of Giratina, Palkia and Dialga, Necrozma's Dusk Mane and Dawn Wings.
- **Teams of three** with switching, a **random team** pick (hidden until the battle), and
  **shiny** Pokémon: every battle one of your team has a 1 in 30 chance to come out shiny.
- **Ditto** with its own fifth move, Transform: it becomes an exact copy of its rival.
- **Modes:** Battle against the AI (easy, normal, hard), Training, **Online 1 vs 1** and
  **Online free-for-all** for up to 4 players.
- **6 arenas:**
  - **Night Stadium:** A Galar stadium at night, packed and walled all round: nobody falls off.
  - **Grand Stadium:** The Night Stadium at almost five times the size, playable right up to the wall: room for big Pokémon and free-for-alls.
  - **Floating Stadium:** A platform over the void. Whoever is pushed off the edge is out.
  - **League Stadium:** The League's coliseum. The field closes in bit by bit: outside it you lose HP.
  - **Valley Meadow:** Out in the open by day: a wide meadow in a valley, a lake with a waterfall, woods and mountains. As big as the Grand Stadium.
  - **Orbit Station:** A battle platform floating in space, walled in by an energy barrier. Every 30 s a comet shower rains down: watch the marks and dodge.
- **Status conditions** as in the games, adapted to real time (burn, paralysis, poison, bad
  poison, sleep, freeze), confusion, stat changes and **weather** (sun, rain, sandstorm, snow),
  with the abilities that use them.
- Homing energy balls, beams and streams you aim, melee moves that dash at the rival,
  deflecting projectiles with strong physical moves, and a lock-on that can switch targets.
- Your trainer and name in the profile: trainers throw their Poké Balls and react to the battle.
- In English (a Spanish translation is included and follows your system language).

## Controls

| Action | Keyboard and mouse | Xbox | PlayStation |
|---|---|---|---|
| Move / camera | WASD / mouse | Left / right stick | Left / right stick |
| Jump (in the air again: fly, for flyers) | Space | A | ✕ |
| Dodge | Shift | B | ○ |
| Lock on | Tab or middle click | RS | R3 |
| Moves 1-4 | Q, E, right click, F | LB, RB, LT, RT | L1, R1, L2, R2 |
| Team (switch) | T | Y | △ |
| Mega Evolution | X | X | □ |
| Transform (Ditto) | C | - | - |
| Zoom | Mouse wheel | - | - |
| Pause (settings in it) | Esc | Menu | Options |

Every key can be changed in *Options*, also during a battle from the pause menu.

## The roster

<details>
<summary><b>All 88 Pokémon</b>, with their forms and Mega Evolutions (click to open)</summary>

| # | Pokémon | Types | Forms (picked in the lobby) | Mega Evolution / battle forms |
|---|---|---|---|---|
| 1 | **Ash's Pikachu** | Electric |  |  |
| 2 | **Snorlax** | Normal |  |  |
| 3 | **Charizard** | Fire / Flying |  | Mega Charizard X, Mega Charizard Y |
| 4 | **Blastoise** | Water |  | Mega Blastoise |
| 5 | **Venusaur** | Grass / Poison |  | Mega Venusaur |
| 6 | **Lucario** | Fighting / Steel |  | Mega Lucario, Mega Lucario Z |
| 7 | **Gengar** | Ghost / Poison |  | Mega Gengar |
| 8 | **Garchomp** | Dragon / Ground |  | Mega Garchomp, Mega Garchomp Z |
| 9 | **Greninja** | Water / Dark |  | Mega Greninja |
| 10 | **Scizor** | Bug / Steel |  | Mega Scizor |
| 11 | **Arcanine** | Fire |  |  |
| 12 | **Alakazam** | Psychic |  | Mega Alakazam |
| 13 | **Bellsprout** | Grass / Poison |  |  |
| 14 | **Dragonite** | Dragon / Flying |  | Mega Dragonite |
| 15 | **Mewtwo** | Psychic |  | Armored Mewtwo, Mega Mewtwo X, Mega Mewtwo Y |
| 16 | **Tyranitar** | Rock / Dark |  | Mega Tyranitar |
| 17 | **Lugia** | Psychic / Flying |  |  |
| 18 | **Ho-Oh** | Fire / Flying |  |  |
| 19 | **Ludicolo** | Water / Grass |  |  |
| 20 | **Gardevoir** | Psychic / Fairy |  | Mega Gardevoir |
| 21 | **Torkoal** | Fire |  |  |
| 22 | **Metagross** | Steel / Psychic |  | Mega Metagross |
| 23 | **Rayquaza** | Dragon / Flying |  | Mega Rayquaza |
| 24 | **Infernape** | Fire / Fighting |  |  |
| 25 | **Lopunny** | Normal |  | Mega Lopunny |
| 26 | **Mismagius** | Ghost |  |  |
| 27 | **Honchkrow** | Dark / Flying |  |  |
| 28 | **Gliscor** | Ground / Flying |  |  |
| 29 | **Mamoswine** | Ice / Ground |  |  |
| 30 | **Chandelure** | Ghost / Fire |  | Mega Chandelure |
| 31 | **Armarouge** | Fire / Psychic |  |  |
| 32 | **Bellibolt** | Electric |  |  |
| 33 | **Vanilluxe** | Ice |  |  |
| 34 | **Marshadow** | Fighting / Ghost |  |  |
| 35 | **Raichu** | Electric |  | Mega Raichu X, Mega Raichu Y |
| 36 | **Nidoking** | Poison / Ground |  |  |
| 37 | **Gyarados** | Water / Flying |  | Mega Gyarados |
| 38 | **Electivire** | Electric |  |  |
| 39 | **Crobat** | Poison / Flying |  |  |
| 40 | **Sceptile** | Grass |  | Mega Sceptile |
| 41 | **Blaziken** | Fire / Fighting |  | Mega Blaziken |
| 42 | **Crawdaunt** | Water / Dark |  |  |
| 43 | **Empoleon** | Water / Steel |  |  |
| 44 | **Staraptor** | Normal / Flying |  | Mega Staraptor |
| 45 | **Roserade** | Grass / Poison |  |  |
| 46 | **Toxicroak** | Poison / Fighting |  |  |
| 47 | **Weavile** | Dark / Ice |  |  |
| 48 | **Serperior** | Grass |  |  |
| 49 | **Samurott** | Water |  |  |
| 50 | **Seismitoad** | Water / Ground |  |  |
| 51 | **Conkeldurr** | Fighting |  |  |
| 52 | **Krookodile** | Ground / Dark |  |  |
| 53 | **Zoroark** | Dark |  |  |
| 54 | **Haxorus** | Dragon |  |  |
| 55 | **Hydreigon** | Dark / Dragon |  |  |
| 56 | **Volcarona** | Bug / Fire |  |  |
| 57 | **Noivern** | Flying / Dragon |  |  |
| 58 | **Yveltal** | Dark / Flying |  |  |
| 59 | **Golisopod** | Bug / Water |  | Mega Golisopod |
| 60 | **Naganadel** | Poison / Dragon |  |  |
| 61 | **Kingambit** | Dark / Steel |  |  |
| 62 | **Mew** | Psychic |  |  |
| 63 | **Rillaboom** | Grass |  |  |
| 64 | **Urshifu** | Fighting / Dark | Rapid Strike |  |
| 65 | **Deoxys** | Psychic | Attack, Defense, Speed |  |
| 66 | **Latios** | Dragon / Psychic |  | Mega Latios |
| 67 | **Salamence** | Dragon / Flying |  | Mega Salamence |
| 68 | **Sharpedo** | Water / Dark |  | Mega Sharpedo |
| 69 | **Aerodactyl** | Rock / Flying |  | Mega Aerodactyl |
| 70 | **Ditto** | Normal |  |  |
| 71 | **Hitmonchan** | Fighting |  |  |
| 72 | **Hitmonlee** | Fighting |  |  |
| 73 | **Magnezone** | Electric / Steel |  |  |
| 74 | **Drapion** | Poison / Dark |  |  |
| 75 | **Gallade** | Psychic / Fighting |  | Mega Gallade |
| 76 | **Froslass** | Ice / Ghost |  | Mega Froslass |
| 77 | **Dusknoir** | Ghost |  |  |
| 78 | **Oshawott** | Water |  |  |
| 79 | **Hawlucha** | Fighting / Flying |  | Mega Hawlucha |
| 80 | **Toucannon** | Normal / Flying |  |  |
| 81 | **Eternatus** | Poison / Dragon |  | Eternamax Eternatus |
| 82 | **Tinkaton** | Fairy / Steel |  |  |
| 83 | **Darkrai** | Dark |  | Mega Darkrai |
| 84 | **Giratina** | Ghost / Dragon | Origin |  |
| 85 | **Palkia** | Water / Dragon | Origin |  |
| 86 | **Dialga** | Steel / Dragon | Origin |  |
| 87 | **Necrozma** | Psychic | Dusk Mane, Dawn Wings | Ultra Necrozma |
| 88 | **Miraidon** | Electric / Dragon |  |  |

</details>

## Community

**[Join the PokeBrawl Discord](https://discord.com/invite/pokebrawl)**

On the Discord server:

- **Bug reports:** what happened and when. In the game, F9 opens the log folder: attach the
  newest files, they show us exactly what went wrong.
- **Wishes:** a Pokémon you want to play, a move, an arena, a feature.
- **Updates:** every new version is announced there first.
- **People to battle** online, and tournaments.

## Credits

**PokeBrawl: original by xjoje6, rebuilt and expanded by kusho**, with [Godot Engine](https://godotengine.org). It stands on other people's work:

- **Cobblemon** ([gitlab.com/cable-mc/cobblemon](https://gitlab.com/cable-mc/cobblemon)), by the Cobblemon team: the Pokémon
  models, animations and textures (CC BY-NC 3.0, adapted), move effects, sounds, cries and
  battle UI pieces (MPL 2.0), and species data.
- **Cobbleverse** ([modrinth.com/modpack/cobbleverse](https://modrinth.com/modpack/cobbleverse)): the models, animations, textures and
  cries from the mods and resource packs it brings, among them **Mega Showdown** (Mega
  Evolutions, forms, Mega Stones and their effects) and **ZA Mega** (the Legends Z-A Megas).
  All rights stay with the Cobbleverse team and the authors of those mods and packs.
- **Music:** Pokémon arrangements by **The Noble Demon**
  ([youtube.com/@TheNobleDemon](https://www.youtube.com/@TheNobleDemon)), used with credit as permitted by the artist; the
  original compositions are by GAME FREAK's composers.
- **Pokémon Showdown** (MIT) as the reference for moves and abilities, and the trainer
  sprites it serves (the games' own sprites).
- **Godot Engine** (MIT) and its third-party components: their notices and licenses are in
  `GODOT-LICENSES.txt`.

The full list is in `CREDITS.txt`, inside the download.

Non-profit fan project. Pokémon and Pokémon character names are trademarks of Nintendo,
Creatures Inc., GAME FREAK and The Pokémon Company; this project is not affiliated with or
endorsed by them.
