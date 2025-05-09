# FCSC 2024 Kraken

Un ami à vous se méfie des mots de passe classiques et des primitives cryptographiques usuelles utilisées pour les valider. Bon développeur, il a codé à ses heures perdues un système personnalisé de validation de “mots de passe” (en quelque sorte …). Il vous affirme que son système exotique est inviolable et vous met au défi de retrouver ses credentials depuis son binaire d’authentification qu’il utilise sur son propre serveur. Pourrez-vous lui prouver que son système est faillible ?


![release_the_kraken.png](release_the_kraken.png)


```
Pour utiliser Kraken Docker, vous pouvez d'abord le compiler avec « make build » (qui utilise le plugin « docker compose »), puis exécuter « make exec » pour y installer un shell.

Le dossier hôte actuel sera monté dans le dossier « /app » du conteneur, ce qui vous permettra d'ajouter vos propres fichiers et d'interagir avec eux.
```


Fichiers :
- [Dockerfile.kraken](Dockerfile.kraken)
- [Makefile](Makefile)
- [snapshot_blob.bin](snapshot_blob.bin)



Auteur : rbe

Origine : [Kraken](https://hackropole.fr/fr/challenges/reverse/fcsc2024-reverse-kraken/)


-----------


## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2024-reverse-kraken.git

> cd fcsc2024-reverse-kraken


-----------

## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/reverse/fcsc2024-reverse-kraken/