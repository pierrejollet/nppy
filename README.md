# nppy

## Présentation du projet

Le projet nppy est simplement un init de projet Python permettant de faire un git clone du répertoire pour lancer un skeleton déjà prêt du projet.
Le projet va être amené à évoluer au fil du temps, et sera la base d'appel d'un fichier bash pour automatiser la génération d'un projet Python.

_Exemple de l'objectif_

`pierre$ ./nppy.sh`

Depuis cette commande, plusieurs questions sont posées :

- Nom du projet
- Liste des tables que l'on souhaite créer
- Les différents services à créer
- ...

A partir de ces questions, et du clone du répertoire _nppy_, des fichiers seront créés en suivant les besoins de l'utilisateur.

## Initialisation de l'environnement

Avant d'automatiser le fichier bash, voici les commandes à lancer manuellement.

- `python3.12 -m venv venv` - _Création de l'environnement virtuel_

- `source venv/bin/activate` - _Activation de l'environnement virtuel_

- `pip3.12 install -r requirements.txt` - _Installation des requirements_

- `uvicorn app:app --reload` - _Lancement du serveur virtuel_

## Contact

Leave a message
