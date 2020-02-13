**Exercice 2 - Prise en main de l'interpreteur de commandes**
============

*Manuel*
------------

**2.1**
La commande which sert à localiser une commande, il determine le path (chemin d'accès d'un fichier).

**2.2**
Pour rechercher un terme dans le manual, il faut utiliser /"mot_recherché". Pour naviguer de termes en
termes il faut utiliser la commande "n" pour next et "N" pour previous.

**2.3**
Pour quitter la page du manuel, il suffit d'utiliser la commande "q" comme indiqué sur le terminal.

**2.4** 
La section 6 parle des jeux, économiseurs d'écran et gadgets.


*Navigation dans l'arborescence des fichier*
------------
Commande pour naviguer dans les fichiers : 
*ls : afficher le contenu du dossier
*cd :aller dans le dossier 
*cd .. : aller dans le dossier parent
*cd - revenir dans le précédent dossier
*cd / : aller au dossier racine (root)

**2.5**
Quand on essaie d'accéder au dossier root on a un refus d'accès (permission denied).
**2.6**
Lorsque l'on met sudo, la console dit que cd est inconu car sudo permet de lancer des programmes en mode admin et cd n'est pas un programme , juste une commade bash.
**2.8**
La commande sudo rm Nom_Du_Fichier permet de supprimer un fichier et uniquement un fichier et non pas un dossier (directory).
**2.9**
Pour supprimer un dossier, il faut utiliser la commande rmdir Nom_Du_Dossier.
**2.10**
La commande précédente ne marche que si le dossier est VIDE.
**2.11**
La commande pour supprimer un dossier et son contenu est : sudo rm -r nomDuDossier.

*Commandes importantes*
------------
**1**
Pour afficherl'heure : date .
**2**
ls : afiche le contenu
la : raccourci de ls -A -> affiche aussi ceux commençant par un .
**3**
Le programme ls se situe dans /usr/bin/ls
**4** 
La commande ll est un aliais de ls (ls -l), elle sert à donner plus d'infomation sur la liste des fichiers comme la date par exemple. Il n'existe pas d'entrée dans la manuel conercant cette commande.
**5**
La commande pour afficher ce qu'il y a dans bin est : ls /bin
**6**
Que fait la commande ls .. : montre ce qu'il y a dans le répertoire parent
**7**
Quelle commande donne le chemin complet du dossier courant : pwd
**8**
Que fait la commande echo 'yo' > plop exécutée 2 fois ?
La commande crée le fichier plop et met yo dedans. (Si on le refait, alors il supprimera ce qu'il y a dans plop pour ne mettre uniquement yo.
**9**
Que fait la commande echo 'yo' >> plop exécutée 2 fois ?
Pareil que au-dessus mais au lieu de supprimer cequ'il y a dans le fichier il ajoute à la fin de celui-ci.
**10**
A quoi sert la commande file ? Essayez la sur des fichiers de types différents
file détermine le type du fichier.
**11**
Créez un fichier toto qui contient la chaîne Hello Toto ! ; créer ensuite un lien titi vers ce fichier
avec la commande ln toto titi. Modifiez à présent le contenu de toto et affichez le contenu de titi :
qu’observe-t-on ? Supprimez le fichier toto ; quelle conséquence cela a-t-il sur titi ?
**12**
Créez à présent un lien symbolique tutu sur titi avec la commande ln -s titi tutu. Modifiez le
contenu de titi ; quelle conséquence pour tutu ? Et inversement ? Supprimez le fichier titi ; quelle
conséquence cela a-t-il sur tutu ?
**13**
Affichez à l’écran le fichier /var/log/syslog. Quels raccourcis clavier permettent d’interrompre et
reprendre le défilement à l’écran 2nd paragraph. *Italic*, **bold**, and `monospace`. Itemized lists
look lthis one
  * that onethe other one








