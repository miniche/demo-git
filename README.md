# demo-git

git est un logiciel de gestion de versions décentralisé. C'est un logiciel libre créé par Linus Torvalds, auteur du noyau Linux, et distribué selon les termes de la licence publique générale GNU version 2. En 2016, il s’agit du logiciel de gestion de versions le plus populaire qui est utilisé par plus de douze millions de personnes.

## Particularités techniques
Similaire en cela à BitKeeper, Git ne repose pas sur un serveur centralisé. C'est un outil de bas niveau[réf. souhaitée], qui se veut simple et performant, dont la principale tâche est de gérer l'évolution du contenu d'une arborescence.

Git indexe les fichiers d'après leur somme de contrôle calculée avec la fonction de hachage SHA-1. Quand un fichier n'est pas modifié, la somme de contrôle ne change pas et le fichier n'est stocké qu'une seule fois. En revanche, si le fichier est modifié, les deux versions sont stockées sur le disque.

Contrastant avec les architectures de logiciel de gestion de versions habituellement utilisées jusqu'alors, Git repose entièrement sur un petit nombre de structures de données élémentaires. Linus Torvalds expliquait ainsi : « Par bien des aspects, vous pouvez considérer git comme un simple système de fichiers. Il est adressé par contenu, et possède la notion de versionnage, mais je l'ai vraiment conçu en prenant le point de vue d'un spécialiste des systèmes de fichiers (après tout, j'ai l'habitude de travailler sur des noyaux) et je n'avais absolument aucune envie de créer un système de gestion de version traditionnel. »5 Les premières versions de Git offraient une interface rudimentaire pour manipuler ces objets internes avant que les fonctionnalités courantes de gestion de version ne soient ensuite progressivement ajoutées et raffinées.

Git est considéré comme performant, au point que certains autres logiciels de gestion de version (Darcs, Arch), qui n'utilisent pas de base de données, se sont montrés intéressés par le système de stockage des fichiers de Git pour leur propre fonctionnement6,7. Ils continuent toutefois à proposer des fonctionnalités plus évoluées.

Dès le début, Git a été pensé dans le but de fonctionner de façon décentralisée, c'est d'ailleurs l'une des clefs de son succès[réf. souhaitée]. La décentralisation de Git a aussi beaucoup apporté au développement des logiciels libres, puisque le besoin de demander un compte sur un dépôt SVN ou CVS centralisé devient obsolète. Il suffit de forker un projet ou de le cloner pour commencer à travailler dessus (avec tout l'historique du projet en local) et ensuite de proposer sa contribution (pull request) au dépôt principal (mainteneur principal du projet).

Les serveurs Git utilisent par défaut le port 9418 pour le protocole spécifique à Git. Les protocoles HTTP, HTTPS et SSH (et leurs ports standards) peuvent aussi être utilisés.

## Sources

Wikipedia
