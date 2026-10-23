# Courses Drive – mises à jour

Ce dépôt sert uniquement à distribuer les nouvelles versions de l'application Windows **Courses Drive**.

## 📘 Manuel d'utilisation

**[Télécharger le manuel (PDF)](https://github.com/JustWizox/courses-drive-mises-a-jour/raw/main/Manuel-Courses-Drive.pdf)** : 20 pages illustrées, de l'installation à la commande vocale.

## ⬇️ Télécharger l'application

La dernière version est dans **[Releases](https://github.com/JustWizox/courses-drive-mises-a-jour/releases/latest)** : `Courses-Drive.exe`.
Pose l'exe dans un dossier et lance-le ; ensuite, l'application se met à jour toute seule (Paramètres → Mises à jour).

## Comment fonctionnent les mises à jour

- Chaque version publiée contient `Courses-Drive.exe` et `version.json` (numéro, date, notes, taille, empreinte SHA-256).
- L'application vérifie ici s'il existe une version plus récente, contrôle l'empreinte du fichier, puis remplace seulement le programme : les données de l'utilisateur ne sont jamais touchées.
- Le code source de l'application n'est pas publié ici.
