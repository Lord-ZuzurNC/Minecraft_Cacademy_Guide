# Minecraft Arkensia Guide

> Une nouvelle grosse update + changement de nom, Arkensia 4.0 Beta, est sortie. Ce tutoriel devrait être mis à jour bientôt.
> Pour le moment, ne faites pas de mise à jour ni d'installation de nouveau serveur car la 4.1 devrait bientôt sortir à la suite des retours des joueurs.
> 
> A big new update + rebrand, Arkensia 4.0 Beta, is released. This tutorial should soon be updated.
> For now, do not upgrade nor create your new server as 4.1 will soon be released to address the first player feedback.

| #   | 🇫🇷 Français                              | 🇬🇧 English                                  |
| --- | --------------------------------------- | ------------------------------------------ |
| 1   | [Introduction](#-français---english)    | [Introduction](#-français---english)       |
| 2   | [Tuto](#tuto)                           | [Tuto](#tuto)                              |
| 3   | [Prérequis](#prérequis--prerequisites)  | [Prerequisites](#prérequis--prerequisites) |
| 4   | [Précisions](#précisions--details)      | [Details](#précisions--details)            |
| 5   | [Problèmes](#problèmes--issues)         | [Issues](#problèmes--issues)               |
| 6   | [Remerciements](#remerciements--thanks) | [Thanks](#remerciements--thanks)           |

---

## 🇫🇷 Français / 🇬🇧 English

### 🇫🇷 Français 🇫🇷

Ceci est un **tutoriel de customisation uniquement**, vous devez suivre le tutoriel d'installation depuis le serveur discord de RoiCheese puis suivre ce tutoriel si vous souhaitez customiser votre serveur.

**Eligos** a créé le tuto initial en français.

Rejoignez le serveur discord "Cacademy" (lien dans les remerciements de RoiCheese) et accédez au [fil](https://discord.com/channels/1463127240173949042/1476164016173879409).

J'ai fait la traduction en anglais.

### 🇬🇧 English 🇬🇧

That is a **customization tutorial only**, you'll need to follow the installation tutorial from RoiCheese discord server then follow this tutorial to customize your server.

**Eligos** created the tutorial initially in French.

Join the "Cacademy" discord (link in the RoiCheese thanks) and go to his [thread](https://discord.com/channels/1463127240173949042/1476164016173879409).

I did the English translation.

---

## Tuto

<details>
<summary>🇫🇷 Français 🇫🇷</summary>

Ce modpack est divisé en un modpack client et un serveur.
- Le modpack client est disponible sur le site de [CurseForge](https://www.curseforge.com/minecraft/modpacks/arkensia).
- Le modpack serveur est disponible uniquement en rejoignant le serveur discord.

Les mods sont à installer côté client et côté serveur, sauf indication contraire.

⚠️ Pour rappel, le modpack est conçu pour être joué sur serveur.

Vous pouvez jouer en self-host, mais ce ne sera pas optimal.

Il est fortement recommandé de faire un nouveau monde en suivant ce tuto.
</details>

Si vous voulez suivre le tutoriel en français veuillez lire ce [README_fr](README_fr.md).

Pour plus d'astuces veuillez lire ce [Astuces-Tips](Astuces-Tips.md).

<details>
<summary>🇬🇧 English 🇬🇧</summary>

This modpack is divided into a client and a server modpack.
- The client modpack is available on [CurseForge](https://www.curseforge.com/minecraft/modpacks/arkensia).
- The server modpack is only available if you join the discord.

The mods are to be installed on both side server and client unless stated otherwise.

⚠️ As a reminder, this modpack has been created to be played with a server.

You can self-host, but this will not be optimum.

It is heavily advised to create a new world while following this tuto.
</details>

If you want to follow the English tutorial please read this [README_en](README_en.md).

For more tips please read this [Astuces-Tips](Astuces-Tips.md).

---

## Prérequis / Prerequisites

<details>
<summary>🇫🇷 Français 🇫🇷</summary>

Ce tutoriel assume que :
- Vous avez installé le modpack serveur depuis le discord Cacademy sur un serveur self-host ou un service d'hosting (recommandé, le plus simple) comme [Minestrator](https://minestrator.com/a/ROICHEESE) (lien affilié de 👑RoiCheese, -10% code `ROICHEESE` pour le premier mois).
- Vous avez installé le modpack client depuis le site de [CurseForge](https://www.curseforge.com/minecraft/modpacks/arkensia) sur votre PC.

> Notez que tous les autres services d'hosting n'ont **<ins>pas</ins>** le véritable modpack serveur, il faudra donc les traiter comme un self-host et tout faire à la main.
> 
> Si self-host alors les ports à ouvrir sont:
> - server.properties → **22055** + **25575**
> - config/voicechat/voicechat-server.properties → **42158**
> - config/cobblecheesescore.json → **44310**
</details>

<details>
<summary>🇬🇧 English 🇬🇧</summary>

This tutorial is assuming that:
- You did install the server modpack from the Cacademy server on a self-host server or a hosting service (recommended) like [Minestrator](https://minestrator.com/a/ROICHEESE) (affiliated link of 👑RoiCheese, -10% code `ROICHEESE` for the first month).
- You did install the client modpack from the [CurseForge](https://www.curseforge.com/minecraft/modpacks/arkensia) site on your PC.

> Please note that any other hosting service will **<ins>not</ins>** have the true server modpack, thus you'll have to treat it as a self-host and do everything accordingly.
> 
> If you selfhost then you'll have to open these ports:
> - server.properties → **22055** + **25575**
> - config/voicechat/voicechat-server.properties → **42158**
> - config/cobblecheesescore.json → **44310**
</details>

---

## Précisions / Details

<details>
<summary>🇫🇷 Français 🇫🇷</summary>

Lorsque le tuto indique un chemin de dossier, par exemple :
```bash
C:\Users\"user"\curseforge\minecraft\Instances\Cacademy\config\cobbleride
```
👉 "user" est à remplacer par le nom de votre compte.

Si vous vous appelez `Timothée`, cela donnera :
```bash
C:\Users\Timothée\curseforge\minecraft\Instances\Cacademy\config\cobbleride
```

Ces chemins sont pour une installation <ins>Windows</ins>, si vous êtes sur Linux vous devrez adapter en conséquence.

Ces chemins sont pour <ins>CurseForge</ins>, il vous suffira de remplacer pour Modrinth ou Prism ou tout autre launcher si vous n'utilisez pas CurseForge.


Dans les fichiers du jeu, il existe un dossier contenant des fichiers nommés **t1**, **t2**, **t3**... jusqu’à **t9**.

Ce sont des fichiers qui répertorient des items (principalement issus de mods), comme les fossiles par exemple.

Ils déterminent les chances d’apparition de ces objets dans les coffres (ce sont en quelque sorte des listes de loot).

Dans les fichiers que le tuto vous demande de remplacer :
- La liste des items légendaires sont ajoutés,
- Pour les autres items moddées, il est simplement indiqué au jeu de choisir aléatoirement un item dans ces listes.
</details>

<details>
<summary>🇬🇧 English 🇬🇧</summary>

When the tuto indicates a folder path, for example:
```bash
C:\Users\"user"\curseforge\minecraft\Instances\Cacademy\config\cobbleride
```
👉 "user" is to be replaced with your username.

If your username is `Timothée`, it will give:
```bash
C:\Users\Timothée\curseforge\minecraft\Instances\Cacademy\config\cobbleride
```

These paths are given for <ins>Windows</ins>, if you are under Linux you will need to adapt accordingly.

These paths are for <ins>CurseForge</ins>, you'll need to change them for Modrinth or Prism or any other MC launcher if you do not use CurseForge.

In the game files, there is a folder with files called **t1**, **t2**, **t3**... until **t9**.

These are files that declare items (mainly from mods) like fossils.

They determine the probability of appearing in chests (that's a kind of list of loot).

In the file the tuto ask you to replace:
- Legendary items are added,
- For all other modded items, it simply tells the game to randomly pick an item from these lists.
</details>

---

## Problèmes / Issues

### 🇫🇷 Français 🇫🇷

Si vous rencontrez un problème avec le tutoriel vous pouvez soit créer un ticket ici ou bien en parler sur le serveur discord dans ce [fil](https://discord.com/channels/1463127240173949042/1476168680206368880).

### 🇬🇧 English 🇬🇧

If you encounter any issue with this tuto you can either create an issue here or ask for help in this discord [thread](https://discord.com/channels/1463127240173949042/1476168680206368880) (French thread, you can create a new English thread if you don't speak french).

---

## Remerciements / Thanks

### 🇫🇷 Français 🇫🇷

BIG THANKS pour **👑RoiCheese**.

> Allez voir ses réseaux sociaux : [Youtube](https://www.youtube.com/@RoiCheese), [Twitch](https://www.twitch.tv/roicheese), [Discord](https://discord.gg/fYmPwMBjdB), et si vous le pouvez et vous sentez généreux vous pouvez aussi le soutenir sur [Paypal](https://www.paypal.com/paypalme/che3sepay).

Je voudrais aussi spécialement remercier des membres discords :
- Eligos - Qui, encore une fois, a créé ce tuto de A à Z.
- Octoj - Avec qui nous avons eu de longues discussions sur le modpack, avec Eligos.
- Tous les autres membres des discords de "Cacademy" ainsi que "Cobblemon Academy".

Eligos souhaite également remercier :
- Johann.but
- Atnos
- KaNaWeeD447
- Raws
- Akwaa

### 🇬🇧 English 🇬🇧

BIG THANKS to **👑RoiCheese**.

> Check out his social networks: [Youtube](https://www.youtube.com/@RoiCheese), [Twitch](https://www.twitch.tv/roicheese), [Discord](https://discord.gg/fYmPwMBjdB), and if you can and feel generous help him via [Paypal](https://www.paypal.com/paypalme/che3sepay).

I would also like to specifically thank these discord members:
- Eligos - Who, again, created this tuto in its entirety.
- Octoj - With whom we had conversations, with Eligos, about the modpack.
- All other person of the "Cacademy" and "Cobblemon Academy" Discord servers.

Eligos would also like to thank:
- Johann.but
- Atnos
- KaNaWeeD447
- Raws
- Akwaa