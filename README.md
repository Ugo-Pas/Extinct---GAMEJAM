# Extinct — GAMEJAM

Version courte  
Extinct est un prototype de jeu d'horreur développé pendant une Game Jam par une équipe de 5 étudiants en première année à Epitech. Le projet a été réalisé avec Unity (C#) autour du thème « horreur ».

## Contexte
- Équipe : 5 personnes (première année, Epitech)  
- Évènement : Game Jam (thème : horreur)  
- Moteur : Unity  
- Langage : C#  
Ce dépôt contient le projet Unity, les scènes, scripts et ressources utilisés pour le prototype présenté durant la Game Jam.

## Pitch
Vous incarnez un protagoniste perdu dans un lieu oppressant. Explorez, évitez les menaces, récupérez des indices et tentez de survivre assez longtemps pour découvrir la vérité sur ce qui s'est produit.

## Caractéristiques
- Ambiance sonore et visuelle orientée horreur
- Exploration et collecte d'objets
- Mécaniques simples de furtivité / fuite (prototype)
- Prototype réalisé sous contrainte de temps — gameplay et contenu limités mais extensibles

## Prérequis
- Unity Hub
- La version de Unity utilisée pour le projet : ouvrez `ProjectSettings/ProjectVersion.txt` pour connaître la version exacte recommandée.
- OS : Windows, macOS ou Linux (selon la plateforme ciblée dans Build Settings)

## Installation / Lancer le projet (rapide)
1. Cloner le dépôt :
   git clone https://github.com/Pekkatrol/Extinct---GAMEJAM.git
2. Ouvrir Unity Hub → Add → pointer sur le dossier du projet cloné.
3. Ouvrir le projet avec la version de Unity indiquée dans `ProjectSettings/ProjectVersion.txt`.
4. Dans Unity : ouvrez la scène principale (par défaut : `Assets/Scenes/Main.unity` — si le nom diffère, cherchez la scène principale dans `Assets/Scenes`).
5. Cliquer sur Play pour lancer en mode éditeur.
6. Pour créer une build : File → Build Settings → sélectionner la plateforme → Build.

## Contrôles (exemple — à adapter selon implémentation)
- Déplacement : W/A/S/D ou flèches
- Regarder / viser : souris
- Interagir / ramasser : E
- Sprint / courir : Left Shift
- Pause / menu : Esc

Vérifiez les scripts d'entrée (Input Manager / Input System) si les touches diffèrent.

## Structure du dépôt (aperçu)
- Assets/ — contenu Unity (scènes, scripts, prefabs, textures, sons)
- ProjectSettings/ — paramètres du projet Unity (inclut ProjectVersion.txt)
- README.md — ce fichier
- LICENSE — (si présent)

## Contribution
Ce dépôt est le résultat d'une Game Jam ; contributions et améliorations sont bienvenues :
- Ouvrez une issue pour proposer une amélioration ou signaler un bug.
- Proposez un pull request avec une description claire des changements.
- Respectez la cohérence du projet Unity (version, conventions de nommage, scenes/prefabs).

## Remarques sur les assets & licences
- Certains assets (sprites, sons, modèles) peuvent provenir de ressources gratuites ou payantes. Vérifiez les crédits et licences dans le dossier `Assets/` (souvent un fichier `README` ou `LICENSE_assets`).
- Si vous ajoutez des assets externes, merci d'indiquer la source et la licence dans un fichier `ASSETS.md` ou similaire.

## Équipe & crédits
Équipe : 5 étudiants première année, Epitech.  
Membres : Pekkatrol + 4 autres (ajoutez les noms ici).

Merci :
- Aux organisateurs de la Game Jam
- Aux auteurs des assets utilisés (listez-les ici si possible)

## Problèmes connus
- Prototype : contenu et mécaniques limitées dû au temps réduit de développement.
- Optimisations et tests plateformes non exhaustifs.
- (Ajoutez ici les bugs connus ou limitations identifiées)

## Contact
Pour toute question, rapport de bug ou collaboration :
- GitHub : [Pekkatrol](https://github.com/Pekkatrol)  
Ou ouvrez une issue dans ce dépôt.

## Licence
Ajoutez un fichier LICENSE à la racine du dépôt pour déclarer la licence souhaitée (par ex. MIT). Si vous n'avez pas de licence, le code n'est pas explicitement réutilisable par défaut.

Amusez-vous bien — et bon courage pour la suite du projet !
