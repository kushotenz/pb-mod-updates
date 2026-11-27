# PokeBrawl

**Real-time 3D Pokémon battles**, built in Godot with the models of Cobblemon and the artists credited below.
287 Pokémon, 46 Mega Evolutions and battle forms, 11 arenas: against the computer, 1 vs 1 online,
or a free-for-all for up to 4 players.

PokeBrawl is a free, non-profit fan project. This repository holds the game's builds: the
game keeps itself up to date from here.

## Download

All downloads are on the [latest release](https://github.com/kushotenz/PokeBrawl/releases/latest) of this page.

### Windows

**[Download PokeBrawl for Windows](https://github.com/kushotenz/PokeBrawl/releases/latest/download/PokeBrawl.zip)** (Windows 10/11, 64-bit)

1. Unzip `PokeBrawl.zip` into a folder of its own.
2. Open `PokeBrawl.exe`.
3. If Windows says "Windows protected your PC", choose *More info* > *Run anyway*.

### Mac

**[Download PokeBrawl for Mac](https://github.com/kushotenz/PokeBrawl/releases/latest/download/PokeBrawl-mac.zip)** (Apple Silicon with macOS 13+, or Intel with macOS 11+)

1. Unzip `PokeBrawl-mac.zip` and move `PokeBrawl.app` into *Applications*.
2. Open PokeBrawl.
3. The first time, macOS can't check the developer: open *System Settings* > *Privacy & Security*
   and click *Open Anyway* (only once).

### Android

**[Download PokeBrawl for Android](https://github.com/kushotenz/PokeBrawl/releases/latest/download/PokeBrawl-android.apk)** (Android 7.0 or newer)

1. Open the downloaded `PokeBrawl-android.apk` on your phone.
2. If Android asks, allow installing apps from this source (your browser or file manager), then tap *Install*.
3. If Play Protect warns about an unknown app, choose *Install anyway* (the game is not on the Play Store).

On a PC emulator (BlueStacks, LDPlayer) or an Intel Chromebook, take **[PokeBrawl-android-x86_64.apk](https://github.com/kushotenz/PokeBrawl/releases/latest/download/PokeBrawl-android-x86_64.apk)** instead.

### Good to know

- **Updates install themselves** (Windows and Mac): at start the game checks for a new version and
  offers it; one click downloads it, swaps the game and restarts it. On Android the game tells you
  when a new version is out and opens its download; install it over the old one, your saves stay.
- Online, everyone needs the same version (the game warns you if not); Windows, Mac and Android play together.
- Keyboard and mouse or a gamepad (Xbox or PlayStation), also at the same time.

Inside the zips: the game (with its music), `CREDITS.txt` and `GODOT-LICENSES.txt`.

## What is in

- **287 Pokémon** (the full list is below), each with its own model, animations, cry and
  way of moving: speed, jumps, dodges and, for many, flight.
- **303 moves and 114 abilities** from the games. Pick each Pokémon's four moves and
  its ability from what it learns; every move shows its power, cooldown, reach and timings.
- **Mega Evolution:** deal damage to fill the Mega bar, then Mega Evolve once per battle for
  20 seconds after a 2-second transformation. 46 forms, among them both Charizard and Mewtwo X/Y, the
  Legends Z-A Megas (Garchomp Z, Lucario Z, Greninja, Dragonite, Chandelure...) and Mega
  Rayquaza.
- **Forms picked in the lobby:** 7 forms in all, e.g. Urshifu's two styles and Toxtricity's Amped and Low Key forms.
- **Block & Parry:** hold Block to guard, tap it just before a hit to parry and leave the attacker open.
- **Languages:** English, Português (Brasil) and Español, picked on the first start.
- **Teams of three** with switching, a **random team** pick (hidden until the battle), and
  **shiny** Pokémon: every battle one of your team has a 1 in 30 chance to come out shiny.
- **Ditto** with its own fifth move, Transform: it becomes an exact copy of its rival.
- **Modes:** Battle against the computer (easy, normal, hard), Training, **Online 1 vs 1** and
  **Online free-for-all** for up to 4 players.
- **11 arenas:**
  - **Night Stadium:** A Galar stadium at night, packed and walled all round: nobody falls off.
  - **Grand Stadium:** The Night Stadium at almost five times the size, playable right up to the wall: room for big Pokémon and free-for-alls.
  - **Floating Stadium:** A platform over the void. Whoever is pushed off the edge is out.
  - **League Stadium:** The League's coliseum. The field closes in bit by bit: outside it you lose HP.
  - **Valley Meadow:** Out in the open by day: a wide meadow in a valley, a lake with a waterfall, woods and mountains. As big as the Grand Stadium.
  - **Orbit Station:** A battle platform floating in space, walled in by an energy barrier. Every 30 s a comet shower rains down: watch the marks and dodge.
  - **Magma Caldera:** A basalt island in a lake of lava. The lava channels in the floor glow before they burst: get off them. And now and then the volcano erupts and rains lava bombs.
  - **Frostfall Glacier:** A frozen lake under the northern lights. Thin ice creaks and cracks before it breaks: step off it or fall into the freezing water. And now and then a blizzard sweeps in, pushes everyone with the wind and drops icicles.
  - **Mewtwo's Cave:** A crystal cave deep underground, ringed by mossy ledges and glowing crystals, misty water all round. No tricks here, just the fight. And on a rock out in the water, Mewtwo watches with its arms folded.
  - **Seashell Cove:** A sunny beach in a tropical cove: firm sand fenced by a rope, palm trees, a pier and soft waves rolling in. No tricks, no hazards: just the fight. Keep an eye on the waterline, someone lives there.
  - **Starfall Altar:** A round altar of black stone adrift among the stars, a silver Poké Ball engraved in its floor. No tricks, no hazards: just the fight. Whoever goes over the edge is out.
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
<summary><b>All 287 Pokémon</b>, with their forms and Mega Evolutions (click to open)</summary>

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
| 15 | **Mewtwo** | Psychic |  | Mega Mewtwo X, Mega Mewtwo Y, Armored Mewtwo |
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
| 58 | **Samurott** | Water | Samurott |  |
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
| 69 | **Altaria** | Dragon / Flying |  | Mega Altaria |
| 70 | **Decidueye** | Grass / Ghost | Decidueye |  |
| 71 | **Mienshao** | Fighting |  |  |
| 72 | **Jirachi** | Steel / Psychic |  |  |
| 73 | **Hoopa** | Psychic / Ghost |  | Hoopa Unbound |
| 74 | **Munchlax** | Normal |  |  |
| 75 | **Wartortle** | Water |  |  |
| 76 | **Squirtle** | Water |  |  |
| 77 | **Ivysaur** | Grass / Poison |  |  |
| 78 | **Bulbasaur** | Grass / Poison |  |  |
| 79 | **Haunter** | Ghost / Poison |  |  |
| 80 | **Gastly** | Ghost / Poison |  |  |
| 81 | **Gabite** | Dragon / Ground |  |  |
| 82 | **Gible** | Dragon / Ground |  |  |
| 83 | **Scyther** | Bug / Flying |  |  |
| 84 | **Growlithe** | Fire |  |  |
| 85 | **Kadabra** | Psychic |  |  |
| 86 | **Abra** | Psychic |  |  |
| 87 | **Dragonair** | Dragon |  |  |
| 88 | **Dratini** | Dragon |  |  |
| 89 | **Pupitar** | Rock / Ground |  |  |
| 90 | **Larvitar** | Rock / Ground |  |  |
| 91 | **Lombre** | Water / Grass |  |  |
| 92 | **Lotad** | Water / Grass |  |  |
| 93 | **Kirlia** | Psychic / Fairy |  |  |
| 94 | **Ralts** | Psychic / Fairy |  |  |
| 95 | **Metang** | Steel / Psychic |  |  |
| 96 | **Beldum** | Steel / Psychic |  |  |
| 97 | **Monferno** | Fire / Fighting |  |  |
| 98 | **Chimchar** | Fire |  |  |
| 99 | **Buneary** | Normal |  |  |
| 100 | **Misdreavus** | Ghost |  |  |
| 101 | **Murkrow** | Dark / Flying |  |  |
| 102 | **Gligar** | Ground / Flying |  |  |
| 103 | **Piloswine** | Ice / Ground |  |  |
| 104 | **Swinub** | Ice / Ground |  |  |
| 105 | **Lampent** | Ghost / Fire |  |  |
| 106 | **Litwick** | Ghost / Fire |  |  |
| 107 | **Charcadet** | Fire |  |  |
| 108 | **Brionne** | Water |  |  |
| 109 | **Popplio** | Water |  |  |
| 110 | **Drizzile** | Water |  |  |
| 111 | **Floragato** | Grass |  |  |
| 112 | **Tadbulb** | Electric |  |  |
| 113 | **Vanillish** | Ice |  |  |
| 114 | **Vanillite** | Ice |  |  |
| 115 | **Nidorino** | Poison |  |  |
| 116 | **Nidoran-M** | Poison |  |  |
| 117 | **Magikarp** | Water |  |  |
| 118 | **Electabuzz** | Electric |  |  |
| 119 | **Elekid** | Electric |  |  |
| 120 | **Golbat** | Poison / Flying |  |  |
| 121 | **Zubat** | Poison / Flying |  |  |
| 122 | **Grovyle** | Grass |  |  |
| 123 | **Treecko** | Grass |  |  |
| 124 | **Combusken** | Fire / Fighting |  |  |
| 125 | **Torchic** | Fire |  |  |
| 126 | **Corphish** | Water |  |  |
| 127 | **Prinplup** | Water |  |  |
| 128 | **Piplup** | Water |  |  |
| 129 | **Staravia** | Normal / Flying |  |  |
| 130 | **Starly** | Normal / Flying |  |  |
| 131 | **Roselia** | Grass / Poison |  |  |
| 132 | **Budew** | Grass / Poison |  |  |
| 133 | **Croagunk** | Poison / Fighting |  |  |
| 134 | **Sneasel** | Dark / Ice | Sneasel |  |
| 135 | **Servine** | Grass |  |  |
| 136 | **Snivy** | Grass |  |  |
| 137 | **Dewott** | Water |  |  |
| 138 | **Palpitoad** | Water / Ground |  |  |
| 139 | **Tympole** | Water |  |  |
| 140 | **Gurdurr** | Fighting |  |  |
| 141 | **Timburr** | Fighting |  |  |
| 142 | **Krokorok** | Ground / Dark |  |  |
| 143 | **Sandile** | Ground / Dark |  |  |
| 144 | **Zorua** | Dark |  |  |
| 145 | **Fletchinder** | Fire / Flying |  |  |
| 146 | **Fletchling** | Normal / Flying |  |  |
| 147 | **Karrablast** | Bug |  |  |
| 148 | **Steenee** | Grass |  |  |
| 149 | **Bounsweet** | Grass |  |  |
| 150 | **Shroomish** | Grass |  |  |
| 151 | **Vibrava** | Ground / Dragon |  |  |
| 152 | **Trapinch** | Ground |  |  |
| 153 | **Swablu** | Normal / Flying |  |  |
| 154 | **Dartrix** | Grass / Flying |  |  |
| 155 | **Rowlet** | Grass / Flying |  |  |
| 156 | **Mienfoo** | Fighting |  |  |
| 157 | **Fraxure** | Dragon |  |  |
| 158 | **Axew** | Dragon |  |  |
| 159 | **Zweilous** | Dark / Dragon |  |  |
| 160 | **Deino** | Dark / Dragon |  |  |
| 161 | **Larvesta** | Bug / Fire |  |  |
| 162 | **Noibat** | Flying / Dragon |  |  |
| 163 | **Wimpod** | Bug / Water |  |  |
| 164 | **Poipole** | Poison |  |  |
| 165 | **Bisharp** | Dark / Steel |  |  |
| 166 | **Pawniard** | Dark / Steel |  |  |
| 167 | **Thwackey** | Grass |  |  |
| 168 | **Grookey** | Grass |  |  |
| 169 | **Kubfu** | Fighting |  |  |
| 170 | **Shelgon** | Dragon |  |  |
| 171 | **Bagon** | Dragon |  |  |
| 172 | **Carvanha** | Water / Dark |  |  |
| 173 | **Tyrogue** | Fighting |  |  |
| 174 | **Magneton** | Electric / Steel |  |  |
| 175 | **Magnemite** | Electric / Steel |  |  |
| 176 | **Skorupi** | Poison / Bug |  |  |
| 177 | **Snorunt** | Ice |  |  |
| 178 | **Dusclops** | Ghost |  |  |
| 179 | **Duskull** | Ghost |  |  |
| 180 | **Trumbeak** | Normal / Flying |  |  |
| 181 | **Pikipek** | Normal / Flying |  |  |
| 182 | **Tinkatuff** | Fairy / Steel |  |  |
| 183 | **Tinkatink** | Fairy / Steel |  |  |
| 184 | **Pikachu** | Electric |  |  |
| 185 | **Haxorus** | Dragon |  |  |
| 186 | **Hydreigon** | Dark / Dragon |  |  |
| 187 | **Volcarona** | Bug / Fire |  |  |
| 188 | **Noivern** | Flying / Dragon |  |  |
| 189 | **Golisopod** | Bug / Water |  | Mega Golisopod |
| 190 | **Naganadel** | Poison / Dragon |  |  |
| 191 | **Kingambit** | Dark / Steel |  |  |
| 192 | **Mew** | Psychic |  |  |
| 193 | **Rillaboom** | Grass |  |  |
| 194 | **Urshifu** | Fighting / Dark | Urshifu |  |
| 195 | **Latios** | Dragon / Psychic |  | Mega Latios |
| 196 | **Salamence** | Dragon / Flying |  | Mega Salamence |
| 197 | **Sharpedo** | Water / Dark |  | Mega Sharpedo |
| 198 | **Aerodactyl** | Rock / Flying |  | Mega Aerodactyl |
| 199 | **Ditto** | Normal |  |  |
| 200 | **Hitmonchan** | Fighting |  |  |
| 201 | **Hitmonlee** | Fighting |  |  |
| 202 | **Magnezone** | Electric / Steel |  |  |
| 203 | **Drapion** | Poison / Dark |  |  |
| 204 | **Gallade** | Psychic / Fighting |  | Mega Gallade |
| 205 | **Froslass** | Ice / Ghost |  | Mega Froslass |
| 206 | **Dusknoir** | Ghost |  |  |
| 207 | **Oshawott** | Water |  |  |
| 208 | **Hawlucha** | Fighting / Flying |  | Mega Hawlucha |
| 209 | **Toucannon** | Normal / Flying |  |  |
| 210 | **Zekrom** | Dragon / Electric |  |  |
| 211 | **Tinkaton** | Fairy / Steel |  |  |
| 212 | **Darkrai** | Dark |  | Mega Darkrai |
| 213 | **Charmander** | Fire |  |  |
| 214 | **Charmeleon** | Fire |  |  |
| 215 | **Froakie** | Water |  |  |
| 216 | **Frogadier** | Water |  |  |
| 217 | **Riolu** | Fighting |  |  |
| 218 | **Pichu** | Electric |  |  |
| 219 | **Gholdengo** | Steel / Ghost |  |  |
| 220 | **Honedge** | Steel / Ghost |  |  |
| 221 | **Doublade** | Steel / Ghost |  |  |
| 222 | **Aegislash** | Steel / Ghost |  |  |
| 223 | **Hitmontop** | Fighting |  |  |
| 224 | **Regigigas** | Normal |  |  |
| 225 | **Porygon-Z** | Normal |  |  |
| 226 | **Purugly** | Normal |  |  |
| 227 | **Delcatty** | Normal |  |  |
| 228 | **Eevee** | Normal |  |  |
| 229 | **Vaporeon** | Water |  |  |
| 230 | **Jolteon** | Electric |  |  |
| 231 | **Flareon** | Fire |  |  |
| 232 | **Espeon** | Psychic |  |  |
| 233 | **Umbreon** | Dark |  |  |
| 234 | **Leafeon** | Grass |  |  |
| 235 | **Glaceon** | Ice |  |  |
| 236 | **Sylveon** | Fairy |  |  |
| 237 | **Pelipper** | Water / Flying |  |  |
| 238 | **Toxel** | Electric / Poison |  |  |
| 239 | **Toxtricity** | Electric / Poison | Toxtricity |  |
| 240 | **Petilil** | Grass |  |  |
| 241 | **Lilligant** | Grass | Lilligant |  |
| 242 | **Dedenne** | Electric / Fairy |  |  |
| 243 | **Frigibax** | Dragon / Ice |  |  |
| 244 | **Arctibax** | Dragon / Ice |  |  |
| 245 | **Baxcalibur** | Dragon / Ice |  |  |
| 246 | **Weedle** | Bug / Poison |  |  |
| 247 | **Kakuna** | Bug / Poison |  |  |
| 248 | **Beedrill** | Bug / Poison |  | Mega Beedrill |
| 249 | **Drilbur** | Ground |  |  |
| 250 | **Excadrill** | Ground / Steel |  | Mega Excadrill |
| 251 | **Mareep** | Electric |  |  |
| 252 | **Flaaffy** | Electric |  |  |
| 253 | **Ampharos** | Electric |  | Mega Ampharos |
| 254 | **Cottonee** | Grass / Fairy |  |  |
| 255 | **Whimsicott** | Grass / Fairy |  |  |
| 256 | **Spheal** | Ice / Water |  |  |
| 257 | **Sealeo** | Ice / Water |  |  |
| 258 | **Walrein** | Ice / Water |  |  |
| 259 | **Feebas** | Water |  |  |
| 260 | **Milotic** | Water |  |  |
| 261 | **Machop** | Fighting |  |  |
| 262 | **Machoke** | Fighting |  |  |
| 263 | **Machamp** | Fighting |  |  |
| 264 | **Regice** | Ice |  |  |
| 265 | **Reshiram** | Dragon / Fire |  |  |
| 266 | **Skiddo** | Grass |  |  |
| 267 | **Gogoat** | Grass |  |  |
| 268 | **Sneasler** | Fighting / Poison |  |  |
| 269 | **Mime Jr.** | Psychic / Fairy |  |  |
| 270 | **Mr. Mime** | Ice / Psychic |  |  |
| 271 | **Mr. Rime** | Ice / Psychic |  |  |
| 272 | **Trubbish** | Poison |  |  |
| 273 | **Garbodor** | Poison |  |  |
| 274 | **Onix** | Rock / Ground |  |  |
| 275 | **Steelix** | Steel / Ground |  | Mega Steelix |
| 276 | **Aron** | Steel / Rock |  |  |
| 277 | **Lairon** | Steel / Rock |  |  |
| 278 | **Aggron** | Steel / Rock |  | Mega Aggron |
| 279 | **Wooper** | Water / Ground |  |  |
| 280 | **Quagsire** | Water / Ground |  |  |
| 281 | **Iron Valiant** | Fairy / Fighting |  |  |
| 282 | **Applin** | Grass / Dragon |  |  |
| 283 | **Dipplin** | Grass / Dragon |  |  |
| 284 | **Hydrapple** | Grass / Dragon |  |  |
| 285 | **Raikou** | Electric |  |  |
| 286 | **Entei** | Fire |  |  |
| 287 | **Suicune** | Water |  |  |

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
- **RedRibbonz** ([modrinth.com/user/RedRibbonz](https://modrinth.com/user/RedRibbonz)), from her MissingMons add-on:
  the Marshadow, Jirachi, Blacephalon, Poipole and Naganadel models, used with the artist's permission.
- **sanji1**: the Mega Charizard X and Y, Aerodactyl, Alakazam, Gallade, Garchomp, Gardevoir, Gyarados,
  Lopunny, Metagross, Salamence, Sharpedo, Tyranitar, Beedrill, Ampharos and Steelix models and Latios with its Mega,
  free to use with credit.
- **Cobblemon Delta** ([discord.gg/cobblemondelta](https://discord.gg/cobblemondelta)): the Mega Blaziken model,
  used with Cobblemon Delta's explicit permission.
- **Tontra** (Pokemans Pack): the Rayquaza, Mega Rayquaza, Zekrom, Reshiram, Kubfu, Urshifu (both styles) and Hoopa (confined and Unbound) models, used
  with the artist's permission.
- **Glitchscar**: the Raikou, Entei, Suicune and Hydrapple models, animations and textures, donated to PokeBrawl.
- **iMystxc** (MysticMons, [modrinth.com/mod/mysticmons](https://modrinth.com/mod/mysticmons)): the Buzzwole model, used with his permission.
- **Presii**: the Mega Venusaur and Mega Sableye models, used with the artist's permission.
- **Lenka** ([CobbleMotion](https://modrinth.com/resourcepack/cobblemotion)): the animations of many Pokémon (among them
  Sceptile, Scizor, Zoroark, Samurott, Decidueye, Electivire, Empoleon, Toucannon, Greninja, Gengar and
  Tyranitar, Spheal, Sealeo, Walrein, Lairon, Aggron and Quagsire) and the Bounsweet, Steenee and Tsareena models, used with the artist's permission.
- **Music:** Pokémon arrangements by **The Noble Demon**
  ([youtube.com/@TheNobleDemon](https://www.youtube.com/@TheNobleDemon)), used with credit as permitted by the artist; the
  original compositions are by GAME FREAK's composers.
- **Pokémon Showdown** (MIT) as the reference for moves and abilities, and the trainer
  sprites it serves: the games' own sprites, and trainers by **kyledove**, **Brumirage**,
  **Beliot419**, **hyo-oppa**, **ZacWeavile**, **Gnomowladny** and **Selena** (credited there).
- **Godot Engine** (MIT) and its third-party components: their notices and licenses are in
  `GODOT-LICENSES.txt`.

### Security & Testing

- **Ryou**, our developer who tests PokeBrawl and every update for security, so PokeBrawl stays safe and fair for every player.

The full list is in `CREDITS.txt`, inside the download.

Non-profit fan project. Pokémon and Pokémon character names are trademarks of Nintendo,
Creatures Inc., GAME FREAK and The Pokémon Company; this project is not affiliated with or
endorsed by them.
