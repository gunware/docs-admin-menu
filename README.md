
# Documentation du projet gw-admin

Ce projet contient un ensemble de scripts et de fichiers de configuration pour une application Lua, potentiellement liée à un serveur de jeu ou à une autre application serveur-client.

## Structure du projet

Voici les principaux fichiers et dossiers présents dans ce projet :

### Fichiers principaux

- **banner.gif** : Une image utilisée dans l'interface utilisateur du projet.
- **client.lua** : Script Lua côté client. Ce fichier contient probablement des fonctionnalités exécutées côté client dans un environnement de jeu ou d'application.
- **config_client.lua** : Fichier de configuration spécifique au client.
- **config_server.lua** : Fichier de configuration spécifique au serveur.
- **custom_data.json** : Fichier JSON contenant des données personnalisées. Ces données peuvent être des paramètres ou des informations spécifiques au fonctionnement du script.
- **Handling.json** : Un fichier JSON contenant des informations sur le "handling", probablement des paramètres ou des configurations spécifiques.
- **fxmanifest.lua** : Manifest du projet, souvent utilisé pour déclarer les ressources dans un environnement tel que FiveM. Ce fichier spécifie les métadonnées sur les scripts du projet.
- **server.lua** : Script Lua côté serveur. Ce fichier contient les fonctionnalités exécutées sur le serveur.
- **vendors/** : Dossier contenant des bibliothèques ou des dépendances supplémentaires.

## Installation

### Prérequis

- Lua installé sur le système (si ce projet est basé sur Lua).
- Environnement serveur compatible (par exemple, FiveM si le projet est un mod pour un serveur de jeu GTA V).

### Instructions d'installation

1. Clonez le dépôt Git :
   ```bash
   git clone https://github.com/votre-utilisateur/gw-admin.git
   ```
2. Placez les fichiers dans le répertoire de votre serveur ou environnement de développement.
3. Modifiez les fichiers de configuration selon vos besoins :
   - `config_client.lua`
   - `config_server.lua`

4. Lancez les scripts en suivant les instructions spécifiques à votre environnement serveur.

## Utilisation

- Le fichier `client.lua` contient le code exécuté côté client.
- Le fichier `server.lua` contient le code exécuté côté serveur.
- Les fichiers JSON (`custom_data.json`, `Handling.json`) sont utilisés pour gérer les paramètres ou les configurations supplémentaires.

## Contribuer

1. Forkez le projet.
2. Créez une nouvelle branche (`git checkout -b feature/nouvelle-feature`).
3. Faites vos modifications et committez-les (`git commit -am 'Ajout de nouvelle feature'`).
4. Poussez la branche (`git push origin feature/nouvelle-feature`).
5. Créez une Pull Request.

## Licence

Ce projet est sous licence MIT. Voir le fichier `LICENSE` pour plus de détails.
