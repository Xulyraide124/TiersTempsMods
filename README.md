# ⚔️ Temporal Tier (Time Dilation Mod) pour Hollow Knight

**Auteur :** Xulyraide124

**Version Actuelle :** 1.0.4

Un mod pour Hollow Knight introduisant une mécanique de **Dilatation du Temps** (tier temps) contrôlable par le joueur, équilibrée par un **buff permanent de +1/3 de la vie (HP)** de tous les ennemis. 

## ✨ Fonctionnalités

### 1\. Dilatation du Temps (Touche P)

  * **Contrôle :** Maintenez la touche **P** enfoncée pour ralentir le temps de jeu global (mouvements, projectiles, animations) à **30%** de sa vitesse normale.
  * **Compensation :** Le Chevalier (Knight) bénéficie d'une compensation de vitesse via la Réflexion (Reflection) pour se déplacer et attaquer à une vitesse proche de la normale, offrant une fenêtre tactique cruciale.

### 2\. Équilibrage de la Difficulté

  * **Buff HP :** Tous les ennemis et Boss reçoivent un bonus permanent de **+1/3 de leur HP maximum**. Ce buff est appliqué à chaque chargement de scène pour maintenir le défi.

-----

## 💾 Installation pour les Joueurs

### Prérequis

  * Avoir installé le **Hollow Knight Modding API (HKMP)**.
  * et lumafly 
### Étapes

1.  Téléchargez le zip .
2.  extrairez le fichier zip `TiersTempsMods.zip` dans le dossier `Mods` de votre installation de Hollow Knight :
    ```
    ...C:\Program Files (x86)\Steam\steamapps\common\Hollow Knight\hollow_knight_Data\Managed\Mods
    ```
3.  Le mod est actif en jeu. Maintenez **P** pour l'utiliser.

-----

##  Guide pour les Développeurs (Contribution)

Ce dépôt est configuré comme un projet **Visual Studio** standard pour le modding de Hollow Knight.

### Structure du Dépôt

| Fichier/Dossier | Rôle |
| :--- | :--- |
| `TiersTempsMods.sln` | Fichier de solution Visual Studio. |
| `TiersTempsMods/` | Dossier du projet C\# contenant les sources (`ModClass.cs`). |
| `TiersTempsMods/TiersTempsMods.dll` | Fichier binaire compilé (release). |
| `README.md` | Ce fichier de documentation. |

### Dépendances

Pour compiler, vous aurez besoin des références aux DLLs de Hollow Knight et de l'HKMP. Les principales classes utilisées sont :

  * `Modding.Mod`
  * `UnityEngine.MonoBehaviour` (pour `TiersTempsUpdater`)
  * `System.Reflection` (pour la compensation de vitesse).



## 🚀 Prochaines Étapes de Développement

Je prévoyons de migrer la fonctionnalité vers un **Charme Personnalisé (Custom Charm)** dans la version 2.0.0. Cela impliquera l'implémentation des interfaces `ICustomCharm` (si l'API le permet) et la gestion des slots de charme.

N'hésitez pas à ouvrir des *Issues* ou soumettre des *Pull Requests* pour des corrections de bugs ou des améliorations \!

-----



**Crédits :**

  * **Jeu Original :** Team Cherry
  * **Outils de Modding :** Les développeurs de l'Hollow Knight Modding API.
  * **Auteur :** Xulyraide124
