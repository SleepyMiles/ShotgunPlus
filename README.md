# ShotgunPlus 🔫

The shotgun, made worth buying. Every player needs the mod; the store and scrap settings come from the host.

## FEATURES
- **Pellets per shot** (10 with Buck Shells). Close range is deadly, long range is weak because of the spread. With Buck Shells, each pellet that hits a player does 20 damage; enemies take 1, 2, 2, 3, 3... hits depending on how many pellets land. Nutcrackers shoot pellets too
- **Pellets you can see.** A quick orange streak per pellet (the vanilla bullet colour) that stops where it hits, no bouncing off walls, plus a small muzzle-flare puff at the hit. Choose streaks and puffs, puffs only, or off (vanilla)
- **R to reload.** Rebindable in the game's Controls menu. One press loads both shells into an empty gun in one smooth reload (when they're the same shell). E no longer reloads, so you can pick things up while holding the gun
- **Fire modes,** switched with **T** (rebindable):
  - **Spread:** the normal spread
  - **Choke:** one pellet that flies straight, then bursts into the normal spread after 8 m (adjustable). A hit before that counts as one pellet; it's for far targets
  - **Double** (off by default): both barrels at once. Needs 2 shells loaded
- **Ammo in the top right,** next to the reload hint, like ```Reload (1/2): [R]```. With More Shotgun Shells, it shows what's loaded in the shells' colours, like ```Reload (Slug, Buck): [R]```
- **In the store:** Shotgun for **800**, Buck Shells for **50** each. Bought ones are tools: they scan like a flashlight (no scrap value) and are kept if everyone dies
- **As scrap:** shells show up on every moon. Shotguns can show up as scrap too, but that's off by default
- **Full damage on Maneaters and Cadaver Blooms.** In vanilla they lose only 1 HP per hit, whatever hits them. A shotgun hit now does its full damage (a baby Maneater still can't be hurt). Each can be turned off

## MORE SHELLS 🎯
Want Slug, Bird, Magnum and Dragon shells? Get the add-on **[More Shotgun Shells](https://thunderstore.io/c/lethal-company/p/SleepyMiles/MoreShotgunShells/)**. ShotgunPlus on its own has the Buck Shell (the vanilla shell).

## CONFIG ⚙
```BepInEx/config/Miles.ShotgunPlus.cfg```

| Setting | Default | |
|---|---|---|
| Store / ShotgunPrice | 800 | -1 = not sold |
| Store / ShellPrice | 50 | -1 = not sold |
| Scrap / ShellRarity | 10 | 0 = never |
| Scrap / ShotgunRarity | 0 | 0 = never |
| Fire Modes / Choke | true | |
| Fire Modes / ChokeDistance | 8 | Meters |
| Fire Modes / Double | false | |
| Enemy Damage / Maneater | true | |
| Enemy Damage / CadaverBloom | true | |
| Visuals / PelletLook | TracersAndSparks | TracersAndSparks, SparksOnly or Off |
| Visuals / ShowAmmo | true | |

Store, scrap, fire mode and enemy damage settings follow the host. Visuals are your own.

## CREDITS 💛
- **Hexicube** ([BetterShotgun](https://github.com/Hexicube/BetterShotgun), MIT) and **Entity378** ([HexiBetterShotgunFixed](https://thunderstore.io/c/lethal-company/p/Entity378/HexiBetterShotgunFixed/)): the pellet idea, spread and damage
- **Hypick** ([BetterShotgun](https://thunderstore.io/c/lethal-company/p/Hypick/BetterShotgun/), MIT): reload key, ammo display, store and scrap registration
