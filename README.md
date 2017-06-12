# gschecker
INSPIRE service metadata creation from GeoServer capabilities

## Installation de gschecker:

Cloner le dépôt Git:
```
$ git clone https://github.com/geopicardie/gschecker.git
```

Se placer dans le dossier de l'application:
```
$ cd gschecker
```

Créer un environnement virtuel Python:
```
$ virtualenv venv
```

Activer l'environnement virtuel:
Sous Windows
```
$ venv\Scripts\activate
```
Sous Linux:
```
$ source venv\bin\activate
```

Installer les modules Python nécessaires
```
$ pip install -r requirements.txt
```

## Configuration de gschecker

Créer une copie du fichier `gsconfig_geopicardie.json`

Le renommer en `gsconfig.json` et l'adapter.

## Exécution de gschecker

Exécuter le fichier `gschecker.py`

Les fichiers XML résultants seront créés dans un dossier `results`  
