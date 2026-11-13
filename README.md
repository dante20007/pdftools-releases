# pdftools — paquets installables

Ce dépôt ne contient **aucun code** : seulement les applications de bureau de
[pdftools](https://github.com/dante20007/pdftools) prêtes à installer, et le fichier que
l'application lit pour savoir si une version plus récente existe.

Il est public pour une seule raison : l'application doit pouvoir vérifier ses mises à jour
sans embarquer de jeton d'accès. Le code source, lui, reste privé.

## Installer

Prenez le dernier paquet dans **[Releases](../../releases)** :

| Système | Fichier |
|---|---|
| Windows | `pdftools-<version>-setup.exe` |
| macOS (Apple Silicon) | `pdftools-<version>-arm64.dmg` |

Rien n'est signé : Windows affiche « Informations complémentaires → Exécuter quand même »,
macOS demande un clic droit → « Ouvrir » au premier lancement.

## Vos documents

pdftools traite les PDF **sur votre appareil**. L'application n'envoie aucun document nulle
part : la seule chose qu'elle demande à Internet, c'est le numéro de la dernière version
publiée ici.
