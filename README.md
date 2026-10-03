# Générateur d'étiquettes déplaçables

Application web statique pour créer et manipuler des étiquettes texte ou image au tableau numérique.

## Fonctionnalités

- Création d'étiquettes texte.
- Génération des étiquettes texte dans l'ordre ou dans le désordre.
- Import d'une liste `.txt`.
- Découpage par virgule ou ligne (par défaut : « petit chien » reste une seule étiquette), par ligne, par mot ou par lettre.
- Ajout de plusieurs images d'un coup.
- Déplacement souris / tactile / stylet.
- Suppression par glisser-déposer dans la corbeille.
- Colonnes rapides : 2, 3, 4, Oui / Non, Vrai / Faux.
- Colonnes personnalisées.
- Menu masquable d’un appui sur sa languette ; position haut, bas, gauche ou droite.
- Plein écran en un appui.
- Adapté au TNI / VPI : grandes cibles tactiles, déplacement simultané de plusieurs étiquettes, pas de zoom ni de menu contextuel parasite sur le plateau.
- Interface aux couleurs d'Apps1D76 (charte DSFR, police Marianne).
- Paramètres d'affichage communs aux outils Apps1D76 : thème clair / sombre / système, taille du texte, animations, contraste renforcé.
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
- la position du menu.

L'intérêt : un seul fichier peut être déplacé, copié ou partagé.

## Polices

Une police installée sur l’ordinateur est toujours utilisée en priorité. Sinon, l’application utilise les fichiers du dossier `assets/fonts`. Sous la liste des polices, un message indique si la police choisie est disponible ; à défaut, Arial est utilisée.

**Marelle 2**, **Marelle Baton 2** et **OpenDyslexic** sont intégrées au projet (licence SIL OFL 1.1, voir `assets/fonts`) : elles fonctionnent partout, sans installation.

### Liens utiles

Marelle 2 et Marelle Baton 2 (pour les installer aussi dans d’autres logiciels) :  
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
