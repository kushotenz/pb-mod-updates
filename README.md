# PokeBrawl

**Real-time 3D Pokémon battles**, built in Godot with the models of Cobblemon and Cobbleverse.
238 Pokémon, 38 Mega Evolutions and battle forms, 9 arenas: against the AI, 1 vs 1 online,
or a free-for-all for up to 4 players.

PokeBrawl is a free, non-profit fan project. This repository holds the game's builds: the
game keeps itself up to date from here.

## Download

All downloads are on the [latest release](https://github.com/kushotenz/pb-mod-updates/releases/latest) of this page.

### Windows

**[Download PokeBrawl for Windows](https://github.com/kushotenz/pb-mod-updates/releases/latest/download/PokeBrawl.zip)** (Windows 10/11, 64-bit)

1. Unzip `PokeBrawl.zip` into a folder of its own.
2. Open `PokeBrawl.exe`.
3. If Windows says "Windows protected your PC", choose *More info* > *Run anyway*.

### Mac

**[Download PokeBrawl for Mac](https://github.com/kushotenz/pb-mod-updates/releases/latest/download/PokeBrawl-mac.zip)** (Apple Silicon with macOS 13+, or Intel with macOS 11+)

1. Unzip `PokeBrawl-mac.zip` and move `PokeBrawl.app` into *Applications*.
2. Open PokeBrawl.
3. The first time, macOS can't check the developer: open *System Settings* > *Privacy & Security*
   and click *Open Anyway* (only once).

### Android

**[Download PokeBrawl for Android](https://github.com/kushotenz/pb-mod-updates/releases/latest/download/PokeBrawl-android.apk)** (Android 7.0 or newer)

1. Open the downloaded `PokeBrawl-android.apk` on your phone.
2. If Android asks, allow installing apps from this source (your browser or file manager), then tap *Install*.
3. If Play Protect warns about an unknown app, choose *Install anyway* (the game is not on the Play Store).

### Good to know

- **Updates install themselves** (Windows and Mac): at start the game checks for a new version and
  offers it; one click downloads it, swaps the game and restarts it. On Android the game tells you
  when a new version is out and opens its download; install it over the old one, your saves stay.
- Online, everyone needs the same version (the game warns you if not); Windows, Mac and Android play together.
- Keyboard and mouse or a gamepad (Xbox or PlayStation), also at the same time.

Inside the zips: the game (with its music), `CREDITS.txt` and `GODOT-LICENSES.txt`.

## What is in

- **238 Pokémon** (the full list is below), each with its own model, animations, cry and
  way of moving: speed, jumps, dodges and, for many, flight.
- **254 moves and 88 abilities** from the games. Pick each Pokémon's four moves and
  its ability from what it learns; every move shows its power, cooldown, reach and timings.
- **Mega Evolution:** deal damage to fill the Mega bar, then Mega Evolve once per battle for
  20 seconds after a 2-second transformation. 38 forms, among them both Charizard and Mewtwo X/Y, the
  Legends Z-A Megas (Garchomp Z, Lucario Z, Greninja, Dragonite, Chandelure...) and Mega
  Rayquaza.
- **Forms picked in the lobby:** 4 forms in all, e.g. Urshifu's two styles and Toxtricity's Amped and Low Key forms.
- **Coming soon:** Dialga, Palkia, Giratina, Necrozma, Eternatus, with Ultra Necrozma and Eternamax Eternatus. You can already
  see them on the wall.
- **Block & Parry:** hold Block to guard, tap it just before a hit to parry and leave the attacker open.
- **Languages:** English, Português (Brasil) and Español, picked on the first start.
- **Teams of three** with switching, a **random team** pick (hidden until the battle), and
  **shiny** Pokémon: every battle one of your team has a 1 in 30 chance to come out shiny.
- **Ditto** with its own fifth move, Transform: it becomes an exact copy of its rival.
- **Modes:** Battle against the AI (easy, normal, hard), Training, **Online 1 vs 1** and
  **Online free-for-all** for up to 4 players.
- **9 arenas:**
  - **Night Stadium:** A Galar stadium at night, packed and walled all round: nobody falls off.
  - **Grand Stadium:** The Night Stadium at almost five times the size, playable right up to the wall: room for big Pokémon and free-for-alls.
  - **Floating Stadium:** A platform over the void. Whoever is pushed off the edge is out.
  - **League Stadium:** The League's coliseum. The field closes in bit by bit: outside it you lose HP.
  - **Valley Meadow:** Out in the open by day: a wide meadow in a valley, a lake with a waterfall, woods and mountains. As big as the Grand Stadium.
  - **Orbit Station:** A battle platform floating in space, walled in by an energy barrier. Every 30 s a comet shower rains down: watch the marks and dodge.
  - **Magma Caldera:** A basalt island in a lake of lava. The lava channels in the floor glow before they burst: get off them. And now and then the volcano erupts and rains lava bombs.
  - **Frostfall Glacier:** A frozen lake under the northern lights. Thin ice creaks and cracks before it breaks: step off it or fall into the freezing water. And now and then a blizzard sweeps in, pushes everyone with the wind and drops icicles.
  - **Mewtwo's Cave:** A crystal cave deep underground, ringed by mossy ledges and glowing crystals, misty water all round. No tricks here, just the fight. And on a rock out in the water, Mewtwo watches with its arms folded.
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
<summary><b>All 238 Pokémon</b> (+ 5 coming soon), with their forms and Mega Evolutions (click to open)</summary>

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
| 15 | **Mewtwo** | Psychic |  | Mega Mewtwo X, Mega Mewtwo Y |
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
| 31 | **Blacephalon** | Fire / Ghost |  |  |
| 32 | **Armarouge** | Fire / Psychic |  |  |
| 33 | **Primarina** | Water / Fairy |  |  |
| 34 | **Zeraora** | Electric |  | Mega Zeraora |
| 35 | **Sobble** | Water |  |  |
| 36 | **Inteleon** | Water |  |  |
| 37 | **Sprigatito** | Grass |  |  |
| 38 | **Meowscarada** | Grass / Dark |  |  |
| 39 | **Sableye** | Dark / Ghost |  | Mega Sableye |
| 40 | **Ceruledge** | Fire / Ghost |  |  |
| 41 | **Bellibolt** | Electric |  |  |
| 42 | **Vanilluxe** | Ice |  |  |
| 43 | **Marshadow** | Fighting / Ghost |  |  |
| 44 | **Raichu** | Electric |  | Mega Raichu X, Mega Raichu Y |
| 45 | **Nidoking** | Poison / Ground |  |  |
| 46 | **Gyarados** | Water / Flying |  | Mega Gyarados |
| 47 | **Electivire** | Electric |  |  |
| 48 | **Crobat** | Poison / Flying |  |  |
| 49 | **Sceptile** | Grass |  | Mega Sceptile |
| 50 | **Blaziken** | Fire / Fighting |  | Mega Blaziken |
| 51 | **Crawdaunt** | Water / Dark |  |  |
| 52 | **Empoleon** | Water / Steel |  |  |
| 53 | **Staraptor** | Normal / Flying |  | Mega Staraptor |
| 54 | **Roserade** | Grass / Poison |  |  |
| 55 | **Toxicroak** | Poison / Fighting |  |  |
| 56 | **Weavile** | Dark / Ice |  |  |
| 57 | **Serperior** | Grass |  |  |
| 58 | **Samurott** | Water |  |  |
| 59 | **Seismitoad** | Water / Ground |  |  |
| 60 | **Conkeldurr** | Fighting |  |  |
| 61 | **Krookodile** | Ground / Dark |  |  |
| 62 | **Zoroark** | Dark | Zoroark |  |
| 63 | **Talonflame** | Fire / Flying |  |  |
| 64 | **Mimikyu** | Ghost / Fairy |  |  |
| 65 | **Escavalier** | Bug / Steel |  |  |
| 66 | **Tsareena** | Grass |  |  |
| 67 | **Breloom** | Grass / Fighting |  |  |
| 68 | **Flygon** | Ground / Dragon |  |  |
| 69 | **Altaria** | Dragon / Flying |  |  |
| 70 | **Decidueye** | Grass / Ghost | Decidueye |  |
| 71 | **Mienshao** | Fighting |  |  |
| 72 | **Jirachi** | Steel / Psychic |  |  |
| 73 | **Munchlax** | Normal |  |  |
| 74 | **Wartortle** | Water |  |  |
| 75 | **Squirtle** | Water |  |  |
| 76 | **Ivysaur** | Grass / Poison |  |  |
| 77 | **Bulbasaur** | Grass / Poison |  |  |
| 78 | **Haunter** | Ghost / Poison |  |  |
| 79 | **Gastly** | Ghost / Poison |  |  |
| 80 | **Gabite** | Dragon / Ground |  |  |
| 81 | **Gible** | Dragon / Ground |  |  |
| 82 | **Scyther** | Bug / Flying |  |  |
| 83 | **Growlithe** | Fire |  |  |
| 84 | **Kadabra** | Psychic |  |  |
| 85 | **Abra** | Psychic |  |  |
| 86 | **Dragonair** | Dragon |  |  |
| 87 | **Dratini** | Dragon |  |  |
| 88 | **Pupitar** | Rock / Ground |  |  |
| 89 | **Larvitar** | Rock / Ground |  |  |
| 90 | **Lombre** | Water / Grass |  |  |
| 91 | **Lotad** | Water / Grass |  |  |
| 92 | **Kirlia** | Psychic / Fairy |  |  |
| 93 | **Ralts** | Psychic / Fairy |  |  |
| 94 | **Metang** | Steel / Psychic |  |  |
| 95 | **Beldum** | Steel / Psychic |  |  |
| 96 | **Monferno** | Fire / Fighting |  |  |
| 97 | **Chimchar** | Fire |  |  |
| 98 | **Buneary** | Normal |  |  |
| 99 | **Misdreavus** | Ghost |  |  |
| 100 | **Murkrow** | Dark / Flying |  |  |
| 101 | **Gligar** | Ground / Flying |  |  |
| 102 | **Piloswine** | Ice / Ground |  |  |
| 103 | **Swinub** | Ice / Ground |  |  |
| 104 | **Lampent** | Ghost / Fire |  |  |
| 105 | **Litwick** | Ghost / Fire |  |  |
| 106 | **Charcadet** | Fire |  |  |
| 107 | **Brionne** | Water |  |  |
| 108 | **Popplio** | Water |  |  |
| 109 | **Drizzile** | Water |  |  |
| 110 | **Floragato** | Grass |  |  |
| 111 | **Tadbulb** | Electric |  |  |
| 112 | **Vanillish** | Ice |  |  |
| 113 | **Vanillite** | Ice |  |  |
| 114 | **Nidorino** | Poison |  |  |
| 115 | **Nidoran-M** | Poison |  |  |
| 116 | **Magikarp** | Water |  |  |
| 117 | **Electabuzz** | Electric |  |  |
| 118 | **Elekid** | Electric |  |  |
| 119 | **Golbat** | Poison / Flying |  |  |
| 120 | **Zubat** | Poison / Flying |  |  |
| 121 | **Grovyle** | Grass |  |  |
| 122 | **Treecko** | Grass |  |  |
| 123 | **Combusken** | Fire / Fighting |  |  |
| 124 | **Torchic** | Fire |  |  |
| 125 | **Corphish** | Water |  |  |
| 126 | **Prinplup** | Water |  |  |
| 127 | **Piplup** | Water |  |  |
| 128 | **Staravia** | Normal / Flying |  |  |
| 129 | **Starly** | Normal / Flying |  |  |
| 130 | **Roselia** | Grass / Poison |  |  |
| 131 | **Budew** | Grass / Poison |  |  |
| 132 | **Croagunk** | Poison / Fighting |  |  |
| 133 | **Sneasel** | Dark / Ice |  |  |
| 134 | **Servine** | Grass |  |  |
| 135 | **Snivy** | Grass |  |  |
| 136 | **Dewott** | Water |  |  |
| 137 | **Palpitoad** | Water / Ground |  |  |
| 138 | **Tympole** | Water |  |  |
| 139 | **Gurdurr** | Fighting |  |  |
| 140 | **Timburr** | Fighting |  |  |
| 141 | **Krokorok** | Ground / Dark |  |  |
| 142 | **Sandile** | Ground / Dark |  |  |
| 143 | **Zorua** | Dark |  |  |
| 144 | **Fletchinder** | Fire / Flying |  |  |
| 145 | **Fletchling** | Normal / Flying |  |  |
| 146 | **Karrablast** | Bug |  |  |
| 147 | **Steenee** | Grass |  |  |
| 148 | **Bounsweet** | Grass |  |  |
| 149 | **Shroomish** | Grass |  |  |
| 150 | **Vibrava** | Ground / Dragon |  |  |
| 151 | **Trapinch** | Ground |  |  |
| 152 | **Swablu** | Normal / Flying |  |  |
| 153 | **Dartrix** | Grass / Flying |  |  |
| 154 | **Rowlet** | Grass / Flying |  |  |
| 155 | **Mienfoo** | Fighting |  |  |
| 156 | **Fraxure** | Dragon |  |  |
| 157 | **Axew** | Dragon |  |  |
| 158 | **Zweilous** | Dark / Dragon |  |  |
| 159 | **Deino** | Dark / Dragon |  |  |
| 160 | **Larvesta** | Bug / Fire |  |  |
| 161 | **Noibat** | Flying / Dragon |  |  |
| 162 | **Wimpod** | Bug / Water |  |  |
| 163 | **Poipole** | Poison |  |  |
| 164 | **Bisharp** | Dark / Steel |  |  |
| 165 | **Pawniard** | Dark / Steel |  |  |
| 166 | **Thwackey** | Grass |  |  |
| 167 | **Grookey** | Grass |  |  |
| 168 | **Kubfu** | Fighting |  |  |
| 169 | **Shelgon** | Dragon |  |  |
| 170 | **Bagon** | Dragon |  |  |
| 171 | **Carvanha** | Water / Dark |  |  |
| 172 | **Tyrogue** | Fighting |  |  |
| 173 | **Magneton** | Electric / Steel |  |  |
| 174 | **Magnemite** | Electric / Steel |  |  |
| 175 | **Skorupi** | Poison / Bug |  |  |
| 176 | **Snorunt** | Ice |  |  |
| 177 | **Dusclops** | Ghost |  |  |
| 178 | **Duskull** | Ghost |  |  |
| 179 | **Trumbeak** | Normal / Flying |  |  |
| 180 | **Pikipek** | Normal / Flying |  |  |
| 181 | **Tinkatuff** | Fairy / Steel |  |  |
| 182 | **Tinkatink** | Fairy / Steel |  |  |
| 183 | **Pikachu** | Electric |  |  |
| 184 | **Haxorus** | Dragon |  |  |
| 185 | **Hydreigon** | Dark / Dragon |  |  |
| 186 | **Volcarona** | Bug / Fire |  |  |
| 187 | **Noivern** | Flying / Dragon |  |  |
| 188 | **Golisopod** | Bug / Water |  | Mega Golisopod |
| 189 | **Naganadel** | Poison / Dragon |  |  |
| 190 | **Kingambit** | Dark / Steel |  |  |
| 191 | **Mew** | Psychic |  |  |
| 192 | **Rillaboom** | Grass |  |  |
| 193 | **Urshifu** | Fighting / Dark | Urshifu |  |
| 194 | **Latios** | Dragon / Psychic |  | Mega Latios |
| 195 | **Salamence** | Dragon / Flying |  | Mega Salamence |
| 196 | **Sharpedo** | Water / Dark |  | Mega Sharpedo |
| 197 | **Aerodactyl** | Rock / Flying |  | Mega Aerodactyl |
| 198 | **Ditto** | Normal |  |  |
| 199 | **Hitmonchan** | Fighting |  |  |
| 200 | **Hitmonlee** | Fighting |  |  |
| 201 | **Magnezone** | Electric / Steel |  |  |
| 202 | **Drapion** | Poison / Dark |  |  |
| 203 | **Gallade** | Psychic / Fighting |  | Mega Gallade |
| 204 | **Froslass** | Ice / Ghost |  | Mega Froslass |
| 205 | **Dusknoir** | Ghost |  |  |
| 206 | **Oshawott** | Water |  |  |
| 207 | **Hawlucha** | Fighting / Flying |  | Mega Hawlucha |
| 208 | **Toucannon** | Normal / Flying |  |  |
| 209 | **Zekrom** | Dragon / Electric |  |  |
| 210 | **Tinkaton** | Fairy / Steel |  |  |
| 211 | **Darkrai** | Dark |  | Mega Darkrai |
| 212 | **Charmander** | Fire |  |  |
| 213 | **Charmeleon** | Fire |  |  |
| 214 | **Froakie** | Water |  |  |
| 215 | **Frogadier** | Water |  |  |
| 216 | **Riolu** | Fighting |  |  |
| 217 | **Pichu** | Electric |  |  |
| 218 | **Gholdengo** | Steel / Ghost |  |  |
| 219 | **Honedge** | Steel / Ghost |  |  |
| 220 | **Doublade** | Steel / Ghost |  |  |
| 221 | **Aegislash** | Steel / Ghost |  |  |
| 222 | **Hitmontop** | Fighting |  |  |
| 223 | **Regigigas** | Normal |  |  |
| 224 | **Porygon-Z** | Normal |  |  |
| 225 | **Purugly** | Normal |  |  |
| 226 | **Delcatty** | Normal |  |  |
| 227 | **Eevee** | Normal |  |  |
| 228 | **Vaporeon** | Water |  |  |
| 229 | **Jolteon** | Electric |  |  |
| 230 | **Flareon** | Fire |  |  |
| 231 | **Espeon** | Psychic |  |  |
| 232 | **Umbreon** | Dark |  |  |
| 233 | **Leafeon** | Grass |  |  |
| 234 | **Glaceon** | Ice |  |  |
| 235 | **Sylveon** | Fairy |  |  |
| 236 | **Pelipper** | Water / Flying |  |  |
| 237 | **Toxel** | Electric / Poison |  |  |
| 238 | **Toxtricity** | Electric / Poison | Toxtricity |  |
| - | **Dialga** · *coming soon* | Steel / Dragon |  |  |
| - | **Palkia** · *coming soon* | Water / Dragon |  |  |
| - | **Giratina** · *coming soon* | Ghost / Dragon |  |  |
| - | **Necrozma** · *coming soon* | Psychic |  | Ultra Necrozma |
| - | **Eternatus** · *coming soon* | Poison / Dragon |  | Eternamax Eternatus |

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

**PokeBrawl: created by xjoje6 & kusho**, with [Godot Engine](https://godotengine.org). It stands on other people's work:

- **Cobblemon** ([gitlab.com/cable-mc/cobblemon](https://gitlab.com/cable-mc/cobblemon)), by the Cobblemon team: the Pokémon
  models, animations and textures (CC BY-NC 3.0, adapted), move effects, sounds, cries and
  battle UI pieces (MPL 2.0), and species data.
- **Mega Showdown** ([modrinth.com/mod/cobblemon-mega-showdown](https://modrinth.com/mod/cobblemon-mega-showdown)): many of the Mega and
  form models below were published there; each model's artist is credited by name. All rights stay
  with them.
- **RedRibbonz** ([modrinth.com/user/RedRibbonz](https://modrinth.com/user/RedRibbonz)), from her MissingMons add-on:
  the Marshadow, Jirachi, Blacephalon, Poipole and Naganadel models, used with the artist's permission.
- **sanji1**: the Mega Charizard X and Y, Aerodactyl, Alakazam, Gallade, Garchomp, Gardevoir, Gyarados,
  Lopunny, Metagross, Salamence, Sharpedo and Tyranitar models and Latios with its Mega,
  free to use with credit (Mega Showdown).
- **Cobblemon Delta** ([discord.gg/cobblemondelta](https://discord.gg/cobblemondelta)): the Mega Blaziken model
  (Mega Showdown), used with Cobblemon Delta's explicit permission.
- **Tontra** (Pokemans Pack): the Rayquaza, Mega Rayquaza, Kubfu and Urshifu (both styles) models, used
  with the artist's permission.
- **Presii**: the Mega Venusaur and Mega Sableye models (Mega Showdown), used with the artist's permission.
- **Lenka** ([CobbleMotion](https://modrinth.com/resourcepack/cobblemotion)): the animations of many Pokémon (among them
  Sceptile, Scizor, Zoroark, Samurott, Decidueye, Electivire, Empoleon, Toucannon, Greninja, Gengar and
  Tyranitar) and the Bounsweet, Steenee and Tsareena models.
- **Alexiocraft** (MundialMons): the Mienshao model.
- **DiEn** (TDmon): the Seismitoad model.
- **Quinn284**: the Mega Blastoise and Mega Gengar models (Mega Showdown).
- **Theeraphat**: the Mega Mewtwo X and Y and Mega Sceptile models (Mega Showdown).
- **Horret**: the Mega Greninja model (Mega Showdown).
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
