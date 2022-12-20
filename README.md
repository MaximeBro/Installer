# Installeur Modpack Minecraft Custom

Ce projet a été réalisé grâce aux vidéos de - [KinderrKill](https://github.com/KinderrKill).
Ce projet reprend notamment le projet - [Minecraft-Installer](https://github.com/KinderrKill/Minecraft-Installer) et vise à créer une version acceptant les mods minecraft forge et fabric. Quelques fix ont également été apportés tels que la barre de progression de téléchargement, le téléchargement des fichiers via un serveur web distant, les configurations de lancement et la détection du jeu.

## Comment utiliser cet installeur ?

Vous pouvez customiser à votre guise cet installeur grâce aux fichiers de configs présents dans le .jar du projet.
Il est possible de définir un logo, une adresse de serveur web et une adresse de serveur de jeu, la liste des mods à utiliser et une version minecraft custom.

Extraire le projet grâce à une IDE telle qu'IntelliJ :
```shell
Gradle -> Tasks -> build -> jar
```

Si vous possédez Winrar (recommandé) :
```shell
Clic droit sur le .jar -> Ouvrir avec Winrar -> Launcher.properties
```

Enfin il vous suffit de faire un **double clic** sur le .jar pour l'exécuter.
