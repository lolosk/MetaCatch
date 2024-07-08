# MetaCatch

MetaCatch est une application Android simple qui permet aux utilisateurs de visualiser et de supprimer les métadonnées des photos. Elle a été développée en Java et XML en utilisant Android Studio.

## Fonctionnalités

- Visualiser les métadonnées d'une photo, y compris la date/heure, le modèle de l'appareil photo, et les coordonnées GPS.
- Supprimer les métadonnées d'une photo et télécharger l'image sans les métadonnées.

## Captures d'écran

![Screenshot1](screenshots/screenshot1.png)
![Screenshot2](screenshots/screenshot2.png)

## Installation

### Prérequis

- Android Studio installé
- Un appareil Android ou un émulateur

### Étapes pour cloner et exécuter le projet

1. Clonez le dépôt :

    ```bash
    git clone https://github.com/lolosk/MetaCatch.git
    ```

2. Ouvrez le projet dans Android Studio :

    - Sélectionnez `Open an existing Android Studio project`.
    - Naviguez jusqu'au répertoire où vous avez cloné le projet et sélectionnez-le.

3. Construisez le projet et exécutez-le sur un appareil ou un émulateur Android.

### Génération du fichier APK

1. Allez dans `Build` > `Build Bundle(s) / APK(s)` > `Build APK(s)` dans Android Studio.
2. Le fichier APK généré sera disponible dans le répertoire `app/build/outputs/apk/debug`.

## Utilisation

1. Ouvrez l'application MetaCatch sur votre appareil Android.
2. Cliquez sur `Voir les métadonnées` pour sélectionner une photo et afficher ses métadonnées.
3. Cliquez sur `Effacer les métadonnées` pour supprimer les métadonnées et télécharger l'image sans métadonnées.

## Structure du projet

```bash
MetaCatch/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   │   └── lolosk/
│   │   │   │       └── metacatch/
│   │   │   │           └── MainActivity.java
│   │   │   ├── res/
│   │   │   │   ├── layout/
│   │   │   │   │   └── activity_main.xml
│   │   │   │   ├── drawable/
│   │   │   │   ├── mipmap/
│   │   │   │   ├── values/
│   │   │   │   ├── xml/
│   │   │   │   │   └── file_paths.xml
│   │   │   └── AndroidManifest.xml
│   ├── build.gradle.kts
├── build.gradle.kts
├── settings.gradle.kts
```

## Licence

Ce projet est sous licence MIT. Voir le fichier `LICENSE` pour plus de détails.


---

Développé avec par [lolosk](https://github.com/lolosk)
