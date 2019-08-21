# danslajungle-site

Trouver les -lieux prévenant- (friendly places) à Montréal

## Pour contribuer

### Ajouter un lieu

Les fiches se trouvent dans le dossier `/Montréal`.  
Pour rédiger une fiche on commence par insérer en ligne n°1 trois tirets, puis les données (meta-données) et on referme par trois tirets.  
Par exemple : 

```yaml
---  
nom: La fine équipe
---
```

Pour chaque fiche les données suivantes peuvent ou doivent être présentes :

- nom: nom du lieu les premières lettre en majuscule
- adresse: l'adresse du lieu au format `numéro, type Nom Orientation` par exemple : _1372, rue Notre-Dame Ouest_ (en respectant les majuscules ;) )
- osm: numéro de noeud [OpenStreetMap](https://wiki.openstreetmap.org/wiki/FR:N%C5%93ud)
- site: site web du lieu
- par: _pseudo github_ du rédacteur - par exemple : [I-da](https://github.com/I-da)

Pour la localisation du lieu :

- Vérifier que le noeud et les métas associées (nom, adresse, type) correspondent bien au lieu donné.
- Si besoin, il est possible de modifier les données directement sur [OpenStreetMap](https://www.openstreetmap.org) :
  - En cas d'informations obsolètes ou manquantes.
  - Si le lieu n'est pas référencé.
  
Localiser les lieux (ou ajouter des informations supplémentaires à propos des lieux) sur Open Street Map offre une meilleure visibilité de ces lieux et peut contribuer à leur référencement.

### Ajouter une ville

Dans le fichier _\_config.yml_, vous devez ajouter une collections :

```yaml
collections:
  montreal:
    output: true
  votre-ville:
    output: true
```

Il faut également créer un dossier _\_votre-ville_ en insérant un fichier _index.md_ identique à celui présent dans les autres collections.

## Pour installer un environnement de développement en local

Installer _jekyll_ et peut-être _ruby_ :  
https://jekyllrb.com/docs/installation/

```bash
$ bundle install
$ jekyll serve
```
