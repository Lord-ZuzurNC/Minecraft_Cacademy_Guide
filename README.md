# Minecraft Cacademy Guide

## 🇫🇷 Français / 🇬🇧 English

### 🇫🇷 Français 🇫🇷

**Eligos** a créé le tuto initial en français.

Rejoignez le serveur discord "Cacademy" (lien dans les remerciements de RoiCheese) et accédez au [fil](https://discord.com/channels/1463127240173949042/1476164016173879409).

J'ai fait la traduction en anglais.

### 🇬🇧 English 🇬🇧

**Eligos** created the tutorial initially in french.

Join the "Cacademy" discord (link in the RoiCheese thanks) and go to his [thread](https://discord.com/channels/1463127240173949042/1476164016173879409).

I did the english translation.

---

## Tuto

<details>
<summary>🇫🇷 Français 🇫🇷</summary>

Ce modpack est sindé en un modpack client et un serveur.
- Le modpack client est disponible sur le site de [CurseForge](https://www.curseforge.com/minecraft/modpacks/cacademy).
- Le modpack serveur est disponible uniquement en rejoignant le serveur discord.

Les mods sont à installer côté client et côté serveur, sauf indication contraire.

⚠️ Pour rappel, le modpack est conçu pour être joué sur serveur.

Vous pouvez jouer en self-host, mais ce ne sera pas optimal.

Il est fortement recommendé de faire un nouveau monde en suivant ce tuto.
</details>

Si vous voulez le tutoriel en français veuillez suivre ce [README_fr](README_fr.md).

<details>
<summary>🇬🇧 English 🇬🇧</summary>

This modpack is divided into a client and a server modpack.
- The client modpack is available on [CurseForge](https://www.curseforge.com/minecraft/modpacks/cacademy).
- The server modpack is only available if you join the discord.

The mods are to be installed on both side server and client but if instruction says othewise.

⚠️ As a reminder, this modpack has been created to be played with a server.

You can self-host, but this will not be optimum.

It is heavily advised to create a new world while following this tuto.
</details>

If you want to follow the english tutorial please follow this [README_en](README_en.md).

---

## Prérequis / Prerequisites

<details>
<summary>🇫🇷 Français 🇫🇷</summary>

Ce tutriel assume que :
- Vous avez installé le modpack serveur depuis le discord Cacademy sur un serveur self-host ou un service d'hosting (recommandé, le plus simple) comme [Minestrator](https://minestrator.com/a/ROICHEESE) (lien affilié de 👑RoiCheese, -10% code `ROICHEESE`).
- Vous avez installé le modpack client depuis le site de [CurseForge](https://www.curseforge.com/minecraft/modpacks/cacademy) sur votre PC.

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
- You did install the server modpack from the Cacademy server on a self-host server or a hosting service (recommanded) like [Minestrator](https://minestrator.com/a/ROICHEESE) (affiliated link of 👑RoiCheese, -10% code `ROICHEESE`).
- You did install the client modpack from the [CurseForge](https://www.curseforge.com/minecraft/modpacks/cacademy) site on your PC.

> Please note that any other hosting service will **<ins>not</ins>** the true server modpack, thus you'll have to trat it as a self-host and do everything accordingly.
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

Ces chemins sont pour une installation <ins>Windows</ins>, si vous êtes sur Linux vous devrez adapter accordémment.

Ces chemins sont pour <ins>CurseForge</ins>, il vous suffira de remplacer pour Modrinth ou Prism ou tout autre laucher si vous n'utilisez pas CurseForge.


Dans les fichiers du jeu, il existe un dossier contenant des fichiers nommés **t1**, **t2**, **t3**... jusqu’à **t9**.

Ce sont des fichiers qui répertorient des items (principalement issus de mods), comme les fossiles par exemple.

Ils déterminent les chances d’apparition de ces objets dans les coffres (ce sont en quelque sorte des listes de loot).

Dans les fichiers que le tuto vous demande de remplacer :
- La liste des items légendaires sont ajoutés,
- Pour les autres items moddées, il est simplement indiqué au jeu de choisir aléatoirement un item dans ces listes.
</details>

<details>
<summary>🇬🇧 English 🇬🇧</summary>

When the tuto indicate a folder path, for example:
```bash
C:\Users\"user"\curseforge\minecraft\Instances\Cacademy\config\cobbleride
```
👉 "user" is to be replaced with your username.

If your username is `Timothée`, it will  gives:
```bash
C:\Users\Timothée\curseforge\minecraft\Instances\Cacademy\config\cobbleride
```

These paths are given for <ins>Windows</ins>, if you are under Linux you will need to adapt accordingly.

These paths are for <ins>CurseForge</ins>, you'll need to change them for Modrinth or Prism or any other MC launcher if you do not use CurseForge.

In the game files, it exists a folder with files called **t1**, **t2**, **t3**... until **t9**.

These are file who declares items (mainly from mods) like fossils.

They determins the probability of appearing in chests (that's a kind of list of loot).

In the file the tuto ask you to replace:
- Legendary items are addes,
- For all other modded items, that's simply indicating to pick randomly an item from these lists.
</details>

---

## Limitation Github / Github Limitation

### 🇫🇷 Français 🇫🇷

> Github limite la taille des fichiers à 100MB. Certains fichiers dans ce repo sont trop gros donc ils sont divisé en plusieurs partis de 100MB.
>
> Pour re-fusionner des fichiers divisés il vous faut installer [VSCode](https://code.visualstudio.com/) (mais je recommande plutôt [VSCodium](https://vscodium.com/)) ainsi que le plugin gratuit "File & Folder Splitter Pro".
>
> Faites un click droit sur un des fichiers divisé et cliquez sur "Join Split Files". Je donne, plus bas, une liste exhaustive de fichiers divisés pour que vous puissiez les fusionner sans devoir les chercher manuellement.

### 🇬🇧 English 🇬🇧

> Github limits the size of file to 100MB. Some files in the repo will be more than this limit so I splitted up these files into 100MB chunks.
>
> To join back these files into 1 you'll need to install [VSCode](https://code.visualstudio.com/) (but I personnally advise using [VSCodium](https://vscodium.com/)), install the "File & Folder Splitter Pro" plugin (it's free).
>
> You'll have to right click and "Join Split Files". I'll provide, bellow, an exhaustive list of all splitted files to avoid searching manually.

### File and Folder Splitter Pro

![File and Folder Splitter Pro VSCode plugin](resources/VSCode_File-Splitter.png)

### Fichiers divisés / Splitted files

```yaml
Aucun / None
```

---

## Problèmes / Issues

### 🇫🇷 Français 🇫🇷

Si vous rencontrez un problème avec le tutoriel vous pouvez soit créer un ticket ici ou bien en parler sur le serveur discord dans ce [fil](https://discord.com/channels/1463127240173949042/1476168680206368880).

### 🇬🇧 English 🇬🇧

If you encounter any issue with this tuto you can either create an issue here or ask for help in this discord [thread](https://discord.com/channels/1463127240173949042/1476168680206368880).

---

## Remerciements / Thanks

### 🇫🇷 Français 🇫🇷

BIG THANKS pour **👑RoiCheese**.

> Allez voir ses réseaux sociaux : [Youtube](https://www.youtube.com/@RoiCheese), [Twitch](https://www.twitch.tv/roicheese), [Discord](https://discord.gg/fYmPwMBjdB), et si vous le pouvez et vous sentez généreux vous pouvez aussi le soutenir sur [Paypal](https://www.paypal.com/paypalme/che3sepay).

Je voudrais aussi spécialement recmercier des membres discords :
- Eligos - Qui, encore une fois, à créé ce tuto de A à Z.
- Octoj - Avec qui nous avons eu de longues discussions sur le modpack, avec Eliigos.
- Tous les autres membres des discords de "Cacademy" ainsi que "Cobblemon   Academy".

Eligos souhaite également remercier :
- Johann.but
- Atnos
- KaNaWeeD447
- Raws
- Akwaa

### 🇬🇧 English 🇬🇧

BIG THANKS to **👑RoiCheese**.

>Look out his social networks: [Youtube](https://www.youtube.com/@RoiCheese), [Twitch](https://www.twitch.tv/roicheese), [Discord](https://discord.gg/fYmPwMBjdB), and if you can and feel generous help him via [Paypal](https://www.paypal.com/paypalme/che3sepay).

I would also like specifically thanks these discord members:
- Eligos - Who, again, created this tuto in its entirety.
- Octoj - Which we had conversation, with Eligos, about the modpack.
- All other person of the "Cacademy" and "Cobblemon Academy" Discord servers.

Eligos would also like to thanks:
- Johann.but
- Atnos
- KaNaWeeD447
- Raws
- Akwaa