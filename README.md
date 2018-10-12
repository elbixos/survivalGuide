# Le guide de survie en milieu hostile

L'objectif de ce guide est de recenser un certain nombre de solutions pour un utilisateur voulant utiliser des logiciels spécifiques sur une machine ou ils ne sont pas installés.

On peut imaginer quelques situations où cela peut vous intéresser :

- vous êtes étudiant et vos logiciels favoris ne sont pas installés actuellement dans vos salles de TP.

- vous êtes chez votre grand mère qui a un vieux pc dont vous ne savez pas trop quelle est la config.

- vous voulez travailler sur une machine puis repartir sans trop laisser de traces, soit :

  - parce que vous êtes bien poli

  - parce que vous cherchez de la furtivité.

Ce guide sera focalisé sur des logiciels libres.

Par la suite, j'appellerais **hôte** la machine que sur laquelle vous allez travailler.

Le guide est construit par souci d’efficacité comme une liste de cas d'applications et la solution associée.

Il vous faudra pour chaque solution une **clef usb**.

## 1. Etudiant / hôte Windows : Portables Apps

Vous êtes donc étudiant, voulez utiliser un logiciel sur l'une des multiples machines d'une des salles de TP, bootée sous windows.
Vous n'avez pas les droits **admin** sur les **hôtes**.

### la solution moisie
Certaines applis peuvent être installées par l'utilisateur. C'est le cas de python par exemple.

Une première solution consiste donc à transporter sur votre **clef usb** tous les installateurs des applis dont vous avez besoin. Cela fonctionne. Prenez des installateurs pour 32bits, ils tourneront à peu près partout. MAIS :

- Installer prend du temps.

- vous changez de machine ou de salle => il faut recommencer.

### Les applications portables.
L'idée est d'avoir une application, dans un dossier qui contient tout ce dont a besoin l'application.

la page [https://portableapps.com/apps](https://portableapps.com/apps) recense un grand nombre de ces applications pour **windows**. Parfois, les concepteurs d'une application peuvent aussi proposer une version **portable** de leur application.

1. Téléchargez l'installateur.

2. Lancez l'installateur qui
installe l'application dans un répertoire de votre **clef usb**.

3. Allez dans la salle info de votre choix, sur la machine de votre choix, et lancez l'appli depuis votre clef usb.

### portablesApps.com

La stratégie précédente est à ce point efficace que certains se sont dit qu'ils pouvaient même éviter de chercher les versions portables de leurs applications.

Par exemple, vous installez sur votre clef usb la **plateforme portableApps**. Vous la trouverez à cette adresse : [https://portableapps.com](https://portableapps.com).

C'est la solution que j'ai retenue et qui me permet de promener avec moi :
- atom
- firefox
- python + pygame
- ...

Vous trouverez un jour ici un tutoriel sur comment j'ai fait. Sinon, cherchez.

*Remarque :* **framakey** est une alternative francaise à portableApps.

## 2. Etudiant / hôte Linux : AppImages

Vous êtes donc étudiant, voulez utiliser un logiciel sur l'une des multiples machines d'une des salles de TP, bootée sous linux.
Vous n'avez pas les droits **admin** sur les **hôtes**.

Même raisonnement que précédemment : il nous faut des applis portables, sous **linux**

### Les appImages

A priori, les **appImages** peuvent être une solution multi distribution. Le site du créateur de ces appimages est içi. [https://appimage.org/](https://appimage.org/)

Vous pouvez mettre vos appImages sur la même clef que vos applications portables windows.

### D'autres systèmes.

Atom, par exemple, donne dans son readme la procédure pour obtenir un logiciel portable sous linux.
Suivez la et copiez les répertoires utiles sur votre clef usb.

## 3. Machine à réparer / installer => clef bootable.

Votre machine ne boote plus, ou vous voulez installer linux quelque part ?

Il est plus ou moins impératif d'avoir toujours une clef bootable sur soi de sa distribution préférée.

Par exemple : la **live-usb** vous permettra :

- d'essayer Ubuntu un peu partout (donc potentiellement réparer ce qui ne va pas sur un pc)

- d'installer Ubuntu sur une machine.

C'est sans doute l'outil le plus utile à trimbaler sur soi. *Il ne vous sera d'aucune utilité dans les salles infos, car vous ne pouvez pas booter sur une clef*.


## 4. Un linux portable

La solution précédente est
