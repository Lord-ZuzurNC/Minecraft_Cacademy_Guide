# English tuto 🇬🇧

| #   | Chapter                                                                                                                                            |
| --- | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | [Legendary & T4-T9 loot (Cobblemon chests)](#increasing-the-items-loot-to-loot-legendary-items-and-t4-to-t9-items-in-the-cobblemon-mod-injections) |
| 2   | [Natural spawn of legendaries + fix 4 calamities](#activate-the-natural-spawn-of-legendaries--fix-of-the-4-calamities-thanks-to-raws)              |
| 3   | [Global waystones](#make-waystones-global)                                                                                                         |
| 4   | [Remove sprint endurance cost (Cobbleride)](#removing-endurance-cost-when-sprinting-in-cobbleride)                                                 |
| 5   | [Alpha Pokémon spawn announce with coordinates](#modify-the-spawning-announce-of-aplha-pokémon-and-show-coordinates)                               |
| 6   | [Generate more structures](#activate-and-generate-more-structures)                                                                                 |
| 7   | [Useful mods compatible 3.1.X](#useful-mods--nice-and-compatible-31x)                                                                              |
| 8   | [Ultra Wormhole appearance chance](#increase-the-appearance-chance-of-ultra-wormhole)                                                              |
| 9   | [Legendary & T5-T9 loot (Blue Towers)](#add-the-item-loots-to-loot-legendaries-and-t5-to-t9-items-in-blue-towers)                                  |
| 10  | [Super Candies XS→XL crafts](#add-the-super-candies-xs--xl--thanks-to-johannbut)                                                                   |
| 11  | [Shiny alerts with player name](#activate-shiny-alerts-with-the-nearest-player-name-thanks-to-raws)                                                |
| 12  | [PokéRayou season 2 spawn](#add-the-spawn-like-in-pokerayou-season-2)                                                                              |
| 13  | [Legendaries as bosses in cobble raid dens](#add-legendaries-as-bosses-in-the-cobble-raid-dens-thanks-to-akwaa)                                    |
| 14  | [Translate FTBQuest in French](#translate-ftbquest-in-french)                                                                                      |
| 15  | [Useful commands](#useful-commands)                                                                                                                |

---

## Increasing the items loot to loot legendary items and T4 to T9 items in the Cobblemon mod injections

In the `1. chests` folder, you can find `.json` files.

Replace the original in:
```bash
C:\Users\"user"\curseforge\minecraft\Instances\Cacademy\datapacks\Academy\data\cobblemon\loot_table\injection\chests
```

## Activate the natural spawn of legendaries + fix of the 4 calamities (Thanks to Raws)

In the `2. spawn_pool_world` folder, you can find `.json` files.

Replace the original in:
```bash
C:\Users\"user"\curseforge\minecraft\Instances\Cacademy\datapacks\MythsandLegends-Datapack-
v1.0.4\data\cobblemon\spawn_pool_world
```

## Make waystones global

In the `3. waystones` folder, you can find `waystone-common.toml`.

Replace the original in:
```bash
C:\Users\"user"\curseforge\minecraft\Instances\Cacademy\config
```

## Removing endurance cost when sprinting in Cobbleride

In the `4. cobbleride` folder, you can find `config.json`.

Replace the original in:
```bash
C:\Users\"user"\curseforge\minecraft\Instances\Cacademy\config\cobbleride
```

## Modify the spawning announce of Alpha Pokémon and show coordinates

In the `5. cobblemonalphas` folder, you can find `config.json`.

Replace the original in:
```bash
C:\Users\"user"\curseforge\minecraft\Instances\Cacademy\config\cobblemonalphas
```

## Activate and generate more structures

In the `6. structurify` folder, you can find `structurify.json`.

Replace the original in:
```bash
C:\Users\"user"\curseforge\minecraft\Instances\Cacademy\config
```

## Useful mods / Nice and compatible 3.1.X

**Cobblemon Pasture Collector <ins>1.3.0</ins>**

Adds a block that automatically collects items produced by Pokémon in the pasture.

> That's not required to loot these items.

**Cobblestats Fabric <ins>1.9.2+1.21.1</ins>**

Shows IV, EV, detailed statistics, and information during fights.

> Client side only.

You can find these two mods in the `7. Mods` folder.

## Increase the appearance chance of Ultra Wormhole

In the `8. cobblemon_ultrabeasts_config` folder, you can find `cobblemon_ultrabeasts_config.json`.

To add in:
```bash
C:\Users\"user"\curseforge\minecraft\Instances\Cacademy\config
```

## Add the item loots to loot legendaries and T5 to T9 items in Blue Towers

In the `9. mvs` folder, you can find `.json` files.

Replace the original in:
```bash
C:\Users\"user"\curseforge\minecraft\Instances\Cacademy\datapacks\Academy\data\mvs\loot_table
```

## Add the Super Candies XS → XL  (Thanks to Johann.but)

In the `10. Bonbon` folder, you can find the compressed folder `bonbon.zip`.

To add in:
```bash
C:\Users\"user"\curseforge\minecraft\Instances\Cacademy\world\datapack
```

<details>
<summary>Craft table:</summary>
| Recipe                      | Item             |
| --------------------------- | ---------------- |
| 1* rayon de miel + 1* sculk | 1* Bonbon EXP XS |
| 6* XS                       | 1* S             |
| 3* S                        | 1* M             |
| 3* M                        | 1* L             |
| 3* L                        | 1* XL            |
</details>

## Activate Shiny alerts with the nearest player name (Thanks to Raws)

In the `11. Cobblemon-spawn-alerts client` folder, you can find `message_templates.json` and `pokemon.json`.

Replace the original in, **only on client side**:
```bash
C:\Users\"user"\curseforge\minecraft\Instances\Cacademy\config\cobblemon-spawn-alerts
```

## Add the spawn like in PokeRayou season 2

In the `12. Map Pokérayou S2` folder, you can find `.mca` files.

To add in:
```bash
C:\Users\"user"\curseforge\minecraft\Instances\Cacademy\world\region
```

If you have not yet generated a world, create a `world` folder and a `region` folder inside it.

Cacademy coordinates: **X=500 ; Y=79 ; Z=-260**

Pokérayou coordinates: **X=858 ; Y=142 ; Z=618**

## Add legendaries as bosses in the cobble raid dens (Thanks to Akwaa)

In the `13. raid` folder, you can find `.json` files.

Replace the original in:
```bash
C:\Users\"user"\curseforge\minecraft\Instances\Cacademy\datapack\Cacademymons\data\cobbleraiddens\raid\boss
```

## Translate FTBQuest in French

In the `14.FTB_quests` folder, you can find the `fr_fr.snbt` file.

To place in :
```bash
C:\Users\"user"\curseforge\minecraft\Instances\Cacademy\config/ftbquest/quests/lang
```

## Useful commands

| Command                                                                                      | Result                                 |
| -------------------------------------------------------------------------------------------- | -------------------------------------- |
| /ec lunarForecast                                                                            | To know the actual lunar phase         |
| /ec lunarForecast recompute                                                                  | Restart the service in case of error   |
| /ec setlunarevent [moon_name]                                                                | Trigger a lunar event                  |
| /setworldspawn                                                                               | Define the spawn point for new players |
| /locate structure …                                                                          | Locate the structures                  |
| /rctmod trainer summon_persistent [id_gym_leader]                                            | Spawn an arena champion                |
| /summon rctmod:trainer_association ~ ~ ~ {NoAI:1b,PersistenceRequired:1b,Rotation:[-90f,0f]} | Spawn the card trader NPC              |
| /schedulerestart                                                                             | Schedule a restart/stop/maintenance    |
| /whitelist add player_name                                                                   | Add a player to the server whitelist   |
