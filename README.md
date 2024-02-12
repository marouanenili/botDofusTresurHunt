# botDofusTresurHunt
ceci est une mise à jour de [DofusHelper](https://github.com/JustNao/DofusHelper) qui n'a pas été maintenu depuis des années et donc j'ai decidé de mettre à jour le code pour qu'il puisse utilisé les nouvelle librarie.
## installation et utilisation
1. Installer Python 3
2. Installer [FFX decompiler](https://ffdec.fr.softonic.com)
3. Decompiler le fichier sfw de dofus dans le dossier script (prenez que les class network.quelquechose se sont les seuls qui nous interesse pour decoder les requete TCP venant du serveur
4. Lancer le script build_protocol.py qui va lire les classe network et creer un fichier pkl du protocole.
5. lancer le script main.py et laisser la magie operer

les etapes 3 et 4 sont à refaire apres chaque mise à jour car les protocoles changent

## Les fonctionalité mise à jour pour l'instant :
### Treasure Hunt Bot
Mêmes fonctionnalités et fenêtre que le helper, mais tout est automatisé (sauf le combat). Par défaut, les déplacements s'effectuent pas un clic. Pour le bas le bot recherche l'icône de changement de barre de sort, il faut donc que vous soyez à la première page pour le calibrage au lancement de l'application. Pour le reste des déplacements, le milieu de l'écran est pris. Un fichier config.json est créé à la racine au premier lancement du bot où vous pouvez passer autopilot à true pour activer le mode monture autopilotée.
### Chat Searcher
Scan tous les messages du chat à la recherche de la chaîne de caractère donnée en input. Renvoie le message avec le nom du personnage dans la console. Plusieurs éléments de recherche sont possibles, en les séparant avec un ';'.

## Copy right
Merci à [laBot](https://github.com/louisabraham/LaBot) pour son reader/writer de packet.
Merci à [DofusHelper](https://github.com/JustNao/DofusHelper)¨pour la base de ce bot.
