# TrixCore
TrixCore est un plugin permettant de relier vos serveurs à votre cms !

TrixCore supporte actuellement : 
- bukkit et ses dérivés (spigot, paperspigot, mohist etc..)
- bungeecord et ses dérivées (waterfall, travertime)
- sponge
- velocity

## Téléchargement

Pour télécharger TrixCore vous avez deux options : 
- télécharger le plugin all-in-one c'est a dire qui supporte toutes les plateformes
- télécharger le plugin spécifique a la plateforme de votre serveur

### Versions

- [TrixCore (all-ine-one) v1.0.3](https://github.com/TrixCMS-V-2/trixcore-for-minecraft/releases/download/v1.0.3/trixcore.jar)
- [TrixCore (bukkit) v1.0.3](https://github.com/TrixCMS-V-2/trixcore-for-minecraft/releases/download/v1.0.3/trixcore-bukkit-1.0.3.jar) [![](https://jitpack.io/v/eu.trixcms/trixcore-minecraft-bukkit.svg)](https://jitpack.io/#eu.trixcms/trixcore-minecraft-bukkit)
- [TrixCore (bungee) v1.0.3](https://github.com/TrixCMS-V-2/trixcore-for-minecraft/releases/download/v1.0.3/trixcore-bungee-1.0.3.jar) [![](https://jitpack.io/v/eu.trixcms/trixcore-minecraft-bungee.svg)](https://jitpack.io/#eu.trixcms/trixcore-minecraft-bungee)
- [TrixCore (sponge) v1.0.3](https://github.com/TrixCMS-V-2/trixcore-for-minecraft/releases/download/v1.0.3/trixcore-sponge-1.0.3.jar) [![](https://jitpack.io/v/eu.trixcms/trixcore-minecraft-sponge.svg)](https://jitpack.io/#eu.trixcms/trixcore-minecraft-sponge)
- [TrixCore (velocity) v1.0.2](https://github.com/TrixCMS-V-2/trixcore-for-minecraft/releases/download/v1.0.2/trixcore-velocity-1.0.2.jar) [![](https://jitpack.io/v/eu.trixcms/trixcore-minecraft-velocity.svg)](https://jitpack.io/#eu.trixcms/trixcore-minecraft-velocity)


## Installation

Pour installer TrixCore vous n'avez qu'a glisser le plugins dans le dossier plugins (ou mods suivant la plateforme). 

Puis vous n'aurez qu'a lancer votre serveur et taper la commande :

> trixcore setup **votre port**

ou <port> correspond au port qui sera utilisé pour la communication. Le port ne peut pas être inférieur à 1000.

Si vous souhaitez réinitialiser TrixCore tapez :

> trixcore reset 

## Développements 

Pour ajouter des fonctionnalités à TrixCore referez-vous aux repository de la plateforme visée.

- [trixcore-sponge](https://github.com/TrixCMS-V-2/trixcore-minecraft-sponge) [![](https://jitpack.io/v/eu.trixcms/trixcore-minecraft-sponge.svg)](https://jitpack.io/#eu.trixcms/trixcore-minecraft-sponge)
- [trixcore-bukkit](https://github.com/TrixCMS-V-2/trixcore-minecraft-bukkit) [![](https://jitpack.io/v/eu.trixcms/trixcore-minecraft-bukkit.svg)](https://jitpack.io/#eu.trixcms/trixcore-minecraft-bukkit)
- [trixcore-bungee](https://github.com/TrixCMS-V-2/trixcore-minecraft-bungee) [![](https://jitpack.io/v/eu.trixcms/trixcore-minecraft-bungee.svg)](https://jitpack.io/#eu.trixcms/trixcore-minecraft-bungee)
- [trixcore-velocity](https://github.com/TrixCMS-V-2/trixcore-minecraft-velocity) [![](https://jitpack.io/v/eu.trixcms/trixcore-minecraft-velocity.svg)](https://jitpack.io/#eu.trixcms/trixcore-minecraft-velocity)


- [trixcore-api](https://github.com/TrixCMS-V-2/trixcore-minecraft-api) [![](https://jitpack.io/v/eu.trixcms/trixcore-minecraft-api.svg)](https://jitpack.io/#eu.trixcms/trixcore-minecraft-api)
- [trixcore-common](https://github.com/TrixCMS-V-2/trixcore-minecraft-common) [![](https://jitpack.io/v/eu.trixcms/trixcore-minecraft-common.svg)](https://jitpack.io/#eu.trixcms/trixcore-minecraft-common)

Un exemple de plugin ajoutant des fonctionnalités est disponible ici : 
[trixcore-minecraft-example](https://github.com/TrixCMS-V-2/trixcore-minecraft-example)

## Builds

Pour buid les plugins :

> mvn clean install

et vous trouverez les artifacts dans chaque dossiers ainsi que la version all-in-one dans le dossier "dist"
