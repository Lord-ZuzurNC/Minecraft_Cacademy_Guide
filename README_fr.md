# Tuto français 🇫🇷

| # | Chapitre |
|---|---|
| 1 | [Loots légendaires T4-T9 (coffres Cobblemon)](#augmenter-les-loots-ditems-pour-faire-apparaître-les-légendaires-et-les-items-t4-à-t9-dans-les-injections-du-mod-cobblemon) |
| 2 | [Spawn naturel des légendaires + fix des 4 fléaux](#activer-le-spawn-naturel-des-légendaires--correction-des-4-fléaux-merci-à-raws) |
| 3 | [Waystones globales](#rendre-les-waystones-globales) |
| 4 | [Supprimer le coût de sprint (Cobbleride)](#supprimer-le-coût-dendurance-du-sprint-avec-cobbleride) |
| 5 | [Annonce spawn Pokémon alpha avec coordonnées](#modifier-lannonce-lors-du-spawn-dun-pokémon-alpha-et-afficher-les-coordonnées) |
| 6 | [Générer plus de structures](#activer-et-générer-davantage-de-structures) |
| 7 | [Mods utiles compatibles 3.1.X](#mods-utiles--sympas-et-compatibles-31x) |
| 8 | [Taux d'apparition des Ultra-Brèches](#augmenter-le-taux-dapparition-des-ultra-brèches) |
| 9 | [Loots légendaires T5-T9 (Tours Bleues)](#ajouter-les-loots-ditems-pour-faire-apparaître-les-légendaires-et-items-t5-à-t9-dans-les-tours-bleues) |
| 10 | [Craft Super Bonbons XS→XL](#ajouter-le-craft-des-super-bonbons-xs--xl-merci-à-johannbut) |
| 11 | [Alertes Shiny avec nom du joueur](#activer-les-alertes-shiny-avec-le-nom-du-joueur-merci-à-raws) |
| 12 | [Spawn PokéRayou saison 2](#mettre-le-spawn-de-pokérayou-saison-2) |
| 13 | [Légendaires boss dans cobble raid dens](#ajouter-les-légendaires-en-temps-que-boss-dans-cobble-raid-dens-merci-à-akwaa) |
| 14 | [Commandes utiles](#commandes-utiles) |

---

## Augmenter les loots d’items pour faire apparaître les légendaires et les items T4 à T9 dans les injections du mod Cobblemon

Dans le dossier `1. chests`, vous trouverez des fichiers `.json`.

À placer à la place des originaux dans :
```bash
C:\Users\"user"\curseforge\minecraft\Instances\Cacademy\datapacks\Academy\data\cobblemon\loot_table\injection\chests
```

## Activer le spawn naturel des légendaires + correction des 4 fléaux (Merci à Raws)

Dans le dossier `2. spawn_pool_world`, vous trouverez des fichiers `.json`.

À placer à la place des originaux dans :
```bash
C:\Users\"user"\curseforge\minecraft\Instances\Cacademy\datapacks\MythsandLegends-Datapack-
v1.0.4\data\cobblemon\spawn_pool_world
```

## Rendre les waystones globales

Dans le dossier `3. waystones`, vous trouverez le fichier `waystone-common.toml`.

À remplacer dans :
```bash
C:\Users\"user"\curseforge\minecraft\Instances\Cacademy\config
```

## Supprimer le coût d’endurance du sprint avec Cobbleride

Dans le dossier `4. cobbleride`, vous trouverez le fichier `config.json`.

À remplacer dans :
```bash
C:\Users\"user"\curseforge\minecraft\Instances\Cacademy\config\cobbleride
```

## Modifier l’annonce lors du spawn d’un Pokémon alpha et afficher les coordonnées

Dans le dossier `5. cobblemonalphas`, vous trouverez le fichier `config.json`.

À remplacer dans :
```bash
C:\Users\"user"\curseforge\minecraft\Instances\Cacademy\config\cobblemonalphas
```

## Activer et générer davantage de structures

Dans le dossier `6. structurify`, vous trouverez le fichier `structurify.json`.

À remplacer dans :
```bash
C:\Users\"user"\curseforge\minecraft\Instances\Cacademy\config
```

## Mods utiles / sympas et compatibles 3.1.X

**Cobblemon Pasture Collector <ins>1.3.0</ins>**

Ajoute un bloc qui collecte automatiquement les objets que les Pokémon produisent lorsqu’ils sont dans un pâturage.

> Pas obligatoire pour le loot des Pokémon placés en pâturage.

**Cobblestats Fabric <ins>1.9.2+1.21.1</ins>**

Affiche les IV, EV, statistiques détaillées et informations en combat.

> Uniquement côté client.

Vous pourrez trouver ces deux mods dans le dossier `7. Mods`.

## Augmenter le taux d’apparition des Ultra-Brèches

Dans le dossier `8. cobblemon_ultrabeasts_config`, vous trouverez le fichier `cobblemon_ultrabeasts_config.json`.

À ajouter dans :
```bash
C:\Users\"user"\curseforge\minecraft\Instances\Cacademy\config
```

## Ajouter les loots d’items pour faire apparaître les légendaires et items T5 à T9 dans les Tours Bleues

Dans le dossier `9. mvs`, vous trouverez des fichiers `.json`.

À remplacer dans :
```bash
C:\Users\"user"\curseforge\minecraft\Instances\Cacademy\datapacks\Academy\data\mvs\loot_table
```

## Ajouter le craft des Super Bonbons XS → XL (Merci à Johann.but)

Dans le dossier `10. Bonbon`, vous trouverez le fichier compressé `bonbon.zip`.

À remplacer dans :
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

## Activer les alertes Shiny avec le nom du joueur (Merci à Raws)

Dans le dossier `11. Cobblemon-spawn-alerts client`, vous trouverez `message_templates.json` et `pokemon.json`.

À remplacer **uniquement côté client** dans :
```bash
C:\Users\"user"\curseforge\minecraft\Instances\Cacademy\config\cobblemon-spawn-alerts
```

## Mettre le spawn de PokéRayou saison 2

Dans le dossier `12. Map Pokérayou S2` vous trouverez des fichiers `.mca`.

À remplacer dans :
```bash
C:\Users\"user"\curseforge\minecraft\Instances\Cacademy\world\region
```

Si vous n’avez pas encore généré votre monde, créez le dossier `world` puis dans ce dernier le dossier `region`.

Coordonnées Cacademy : **X=500 ; Y=79 ; Z=-260**

Coordonnées Pokérayou : **X=858 ; Y=142 ; Z=618**

## Ajouter les légendaires en tant que boss dans cobble raid dens (Merci à Akwaa)

Dans le dossier `13. raid`, vous trouverez des fichiers `.json`.

À remplacer dans :
```bash
C:\Users\"user"\curseforge\minecraft\Instances\Cacademy\datapack\Cacademymons\data\cobbleraiddens\raid\boss
```

## Commandes utiles

| Commande                                                                                     | Résultat                                                |
| -------------------------------------------------------------------------------------------- | ------------------------------------------------------- |
| /ec lunarForecast                                                                            | Permet de connaître le cycle lunaire actuel             |
| /ec lunarForecast recompute                                                                  | Redémarre le service en cas d’erreur                    |
| /ec setlunarevent [nom_de_la_lune]                                                           | Déclenche un événement lunaire                          |
| /setworldspawn                                                                               | Définit le point d’apparition des nouveaux joueurs      |
| /locate structure …                                                                          | Permet de localiser une structure                       |
| /rctmod trainer summon_persistent [id_gym_leader]                                            | Fait apparaître un champion d’arène                     |
| /summon rctmod:trainer_association ~ ~ ~ {NoAI:1b,PersistenceRequired:1b,Rotation:[-90f,0f]} | Fait apparaître le PNJ d’échange des cartes de dresseur |
| /schedulerestart                                                                             | Configurer un restart/stop/maintenance                  |
| /whitelist add nom_du_joueur                                                                 | Ajoute un joueur à la whitelist du serveur              |
