---
layout: page
---

# Petit guide pour les personnes souhaitant contribuer

Ce "petit" guide est peut-être indigeste. Si tu as envie de contribuer et que tu n'es pas à l'aise, on pourra peut-être t'aider ? Par exemple avec une session en visio-conférence ou en présentiel ou bien répondre à tes questions par mail ou peut-être via un autre canal de communication qui te semblera plus adapté.  
  
Dans tous les cas, on sera ravi de te répondre si tu [nous contactes](/nous-contacter)

## Intentions

_Les intentions ne sont pas figées, pour l'instant on en est là_

- nous souhaitons rendre la lecture des fiches accessibles au plus grand nombre :
  - style simple, petites phrases, mots usuels
  - on essaye de préserver l'homogénéité des infos pratiques
  - l'orthographe et la grammaire sont moins importants que l'inclusivité
    - tu peux faire des _fôtes_ et on ne touche pas à tes phrases sauf si tu le demandes explicitement
    - il est possible que l'on te contacte pour échanger si on ne comprends pas un passage
- peut-être moins écrire sur du général et plus faire ressortir les singularités
  - tu peux décrire le lieu
  - comment le lieu se décrit
  - si tu es à l'aise avec ça, on trouve sympa si tu ajoutes une section plus personnelle où tu t'exprimes en "je"
- quand on insère une fiche on a eu un échange avec une ou plusieurs personnes du lieu :
  - est-ce qu'elles sont -ok- avec les [attentes collectives](https://danslajungle.oisiflorus.com/attentes-collectives) ?
  - est-ce que l'on peut mettre son prénom en contact pour accueillir et protéger ?
  - est-ce qu'elles sont -ok- pour lire la fiche ?

## Les données descriptives des fiches lieux

Une fiche lieu commence par un bloc de données qui ressemble à un truc du genre :

```markdown
---
nom: La Cagette
tags:
    - vegan
    - végétarien
---
```

- trois petits tirets pour démarrer
- une liste de données se fabrique en utilisant le format suivant : _clé: valeur_ - pour les données comportant plusieurs valeurs, on utilise un tiret à la ligne avec deux espaces d'indentation (cf. tags) 
- On referme la zone de données par trois petits tirets

C'est plus facile à faire qu'à expliquer, je crois ;)

### Données prises en compte

Voici la liste des données actuellement prises en compte dans la présentation de la fiche

```markdown
---
nom: <titre de la fiche>
type: <liste de types de lieux>
description: <texte descriptif affiché sur la page sommaire>
adresse: <adresse>
osm: <noeud openstreetmap.org (pour construire un lien OSM sur l'adresse)>
email: <courriel pour contacter le lieu>
tel: <téléphone pour contacter le lieu au format : 0 xxx xxx xxx pour la france métropolitaine>
site: <site web du lieu>
services: <cafés suspendus, précarité menstruelle, toilettes accessibles au non-client·e·s>
transport: <arrêt de tram ou de bus>
responsable: <prénom de la personne que nous avons prévenue et qui pourra accueillir>
par: <lea contribut·eur·rice qui a initié la fiche. Il s'agit d'un identifiant github.com>
tags: <liste d'attributs du lieu>
---
```

#### attributs de types

Liste des _types_ actuellement utilisés : bar, pub, tiers-lieu, thé, boutique, glacier, galerie, garage, supermarché, association, café, restaurant, jeux, végan, végétarien, librairie, vélo, épicerie, shop, coworking, atelier, bricolage, chanvre, concert, camping, salle de spectacle, centre de loisirs.  
  
Les types sont convertis en icônes lorque la fiche du lieu s'affiche  

#### attributs de tags

Voici une liste des _tags_ actuellement utilisés : vegan, végétarien

## Types de médias

- photos
- audio
- vidéo
