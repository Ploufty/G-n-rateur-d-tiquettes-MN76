# Générateur d'étiquettes déplaçables

Application web statique pour créer et manipuler des étiquettes texte ou image au tableau numérique.

## Fonctionnalités

- Création d'étiquettes texte.
- Génération des étiquettes texte dans l'ordre ou dans le désordre.
- Import d'une liste `.txt`.
- Découpage par mot, par ligne ou par lettre.
- Ajout de plusieurs images d'un coup.
- Déplacement souris / tactile / stylet.
- Suppression par glisser-déposer dans la corbeille.
- Colonnes rapides : 2, 3, 4, Oui / Non, Vrai / Faux.
- Colonnes personnalisées.
- Menu affichable / masquable.
- Position du menu : haut, bas, gauche, droite.
- Mode clair / sombre.
- Sauvegarde et ouverture au format `.etiq`.

## Polices disponibles dans l’application

- Arial
- Century Gothic
- Marelle 2
- Marelle Baton 2
- OpenDyslexic
- Comic Sans MS

## Format de sauvegarde

Les activités sont sauvegardées dans un fichier `.etiq`.

Techniquement, c'est du JSON contenant :

- les étiquettes texte ;
- les images intégrées en base64 ;
- les positions ;
- les tailles ;
- les colonnes ;
- les réglages d'interface.

L'intérêt : un seul fichier peut être déplacé, copié ou partagé.

## Polices

Polices proposées dans l’application :

- Arial
- Century Gothic
- Marelle 2
- Marelle Baton 2
- OpenDyslexic
- Comic Sans MS

Les polices système utilisent celles disponibles sur l’ordinateur.

Pour un rendu fiable sur une version web publiée, les polices pédagogiques peuvent être placées dans le dossier `assets/fonts` avec les noms suivants :

- `Marelle2-Regular.ttf`
- `MarelleBaton2-Regular.ttf`
- `OpenDyslexic-Regular.otf`

Si ces fichiers ne sont pas présents dans le projet, le navigateur peut utiliser les polices installées sur l’ordinateur. Si aucune police correspondante n’est disponible, une police de secours est utilisée automatiquement.

### Liens utiles

Marelle 2 et Marelle Baton 2 :  
https://marelle.forge.apps.education.fr/#telecharger

OpenDyslexic :  
https://opendyslexic.org/

## Aide à l’installation des polices sur Windows

1. Vous téléchargez la police souhaitée depuis son site officiel.
2. Vous ouvrez le fichier de police téléchargé, puis vous le décompressez si nécessaire.
3. Vous installez la police sur Windows. Deux solutions sont possibles :
   - placer ou glisser les fichiers de police dans le dossier `C:\Windows\Fonts` ;
   - ou faire un clic droit sur le fichier de police, puis choisir « Installer pour tous les utilisateurs ».
4. Vous redémarrez le navigateur si la police n’apparaît pas immédiatement dans l’application.

Remarque : si une police n’est pas présente dans le projet et n’est pas installée sur l’ordinateur, le navigateur utilise automatiquement une police de secours.
