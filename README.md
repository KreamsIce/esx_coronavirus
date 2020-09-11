# SCRIPT EN COURS DE DEVELOPPEMENT

# esx_coronavirus

## Téléchargement & Installation

### Utilisation de [fvm](https://github.com/KreamsIce/autokick)
```
fvm install --save --folder=esx esx_coronavirus
```

### Utilisation de Git
```
cd resources
git clone https://github.com/KreamsIce/autokick [esx]/esx_coronavirus
```

### Manuellement
- Téléchargez https://github.com/KreamsIce/esx_coronavirus.zip
- Mettez le dossier `esx_coronavirus` dans votre dossier `[esx]`

## Installation
- Insérez le contenu du fichier `esx_coronavirus.sql` dans votre base de données
- Dans le fichier `config.lua` définissez le pourcentage de chance de contamination
- Dans le fichier `server.cfg` ajoutez la ligne suivante :
```
start esx_coronavirus
```
- Redémarrez votre serveur FiveM
