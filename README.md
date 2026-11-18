# Riki — releases

Ce dépôt ne contient **aucun code source**. Il héberge uniquement les installeurs de Riki et le manifeste
de mise à jour (`latest.json`) utilisé par l'application pour se mettre à jour automatiquement.

## Télécharger

Dernière version : [Releases → Latest](../../releases/latest)

| Système | Fichier |
|---------|---------|
| Windows 10/11 (x64) | `Riki_<version>_x64-setup.exe` |
| Linux (x64) | `Riki_<version>_amd64.AppImage` |

Les mises à jour suivantes s'installent depuis l'application.

## Windows : avertissement SmartScreen

L'installeur n'est pas signé avec un certificat Authenticode. Au premier lancement, Windows peut afficher
« Windows a protégé votre ordinateur » : cliquer sur **Informations complémentaires**, puis **Exécuter quand même**.
L'installation se fait pour l'utilisateur courant, sans droits administrateur.

L'authenticité des mises à jour automatiques est garantie par une signature propre à l'updater de Riki,
vérifiée par l'application avant toute installation.

## Linux : AppImage

```sh
chmod +x Riki_*_amd64.AppImage
./Riki_*_amd64.AppImage
```
