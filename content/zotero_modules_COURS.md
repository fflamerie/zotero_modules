
# Approfondissement Zotero : optimiser la gestion de vos PDF, améliorer vos données bibliographiques, et plus encore grâce aux modules complémentaires

L'icône ![zotero][zotero] signale la documentation officielle Zotero, y compris les discussions du forum Zotero : c'est la meilleure source d'information et d'aide!

## Objectifs

* Utiliser les modules complémentaires [ZotFile](http://zotfile.com/), [Zutilo](https://github.com/willsALMANJ/Zutilo) et [DOI Manager](https://github.com/bwiernik/zotero-shortdoi) pour enrichir et optimiser sa bibliothèque Zotero
* Identifier, installer et utiliser d'autres modules complémentaires de Zotero en fonction de ses besoins - ![zotero][zotero] [liste complète des modules complémentaires de Zotero](https://www.zotero.org/support/plugins)


## Sommaire

<!-- MDTOC maxdepth:2 firsth1:0 numbering:0 flatten:0 bullets:1 updateOnSave:0 -->

- [Objectifs](#objectifs)   
- [Sommaire](#sommaire)   
- [Tour de table](#tour-de-table)   
- [I. Installer et configurer un module complémentaire](#i-installer-et-configurer-un-module-complémentaire)   
   - [ZotFile](#zotfile)   
   - [Zutilo](#zutilo)   
   - [DOI Manager](#doi-manager)   
- [II. Optimiser la gestion des PDF avec ZotFile](#ii-optimiser-la-gestion-des-pdf-avec-zotfile)   
   - [Comment gérez-vous vos PDF actuellement?](#comment-gérez-vous-vos-pdf-actuellement)   
   - [Ressources](#ressources)   
   - [1.a Renommer ses fichiers avec ZotFile](#1a-renommer-ses-fichiers-avec-zotfile)   
   - [1.b Déplacer ses fichiers avec ZotFile](#1b-déplacer-ses-fichiers-avec-zotfile)   
   - [Annoter avec Zotero](#annoter-avec-zotero)   
- [III. Améliorer les données bibliographiques avec Zutilo et DOI Manager](#iii-améliorer-les-données-bibliographiques-avec-zutilo-et-doi-manager)   
   - [Zutilo](#zutilo)   
   - [DOI Manager](#doi-manager)   
- [IV. A vous de tester un ou plusieurs modules](#iv-a-vous-de-tester-un-ou-plusieurs-modules)   

<!-- /MDTOC -->

<div style="page-break-after: always;"></div>


## Tour de table

* D'où venez-vous : à quelle unité / institution appartenez-vous?
* Quel est votre domaine de recherche?
* Qu'attendez-vous du stage?


## I. Installer et configurer un module complémentaire

L'installation d'un module complémentaire dans Zotero consiste à charger dans Zotero un fichier d'un format particulier, le format `.xpi`.

Ainsi, pour installer un module complémentaire, il faut procéder selon les étapes suivantes.

* Enregistrer sur son ordinateur le fichier `.xpi` mis à disposition sur le site du module complémentaire que l'on souhaite installer.
* Dans Zotero, aller dans le menu _Outils_  → _Extensions_.
* Cliquer sur la roue dentée et choisir _Install Add-on From File_.
* Sélectionner et charger le fichier `.xpi`.

⚠️ Il faut parfois redémarrer Zotero pour finaliser l'installation.


![gestionnaire_modules_compl](img/zotero_gest_modules_compl.png)


### ZotFile

Sur la page d'accueil du site de ZotFile - http://zotfile.com/ - un clic-droit sur le lien _Download_ > _Enregistrer la cible du lien sous..._ permet de récupérer le fichier `.xpi` de la dernière version de ZotFile.

Une fois ZotFile installé, il peut être configuré à partir du menu _Outils_ de Zotero > _Préférences de Zotfile..._

### Zutilo

Les versions de Zutilo sont disponibles par le biais de la page _Releases_ du dépôt GitHub de ce module. Sur la page https://github.com/wshanks/Zutilo/releases , un clic-droit sur le lien  _zutilo.xpi_ > _Enregistrer la cible du lien sous..._ de la dernière version, présentée en tête de la page, permet de récupérer le fichier `.xpi` pour installer la version la plus récente de Zutilo.

Une fois Zutilo installé, il peut être configuré à partir du menu _Outils_ de Zotero > _Préférences de Zutilo..._

### DOI Manager

DOI Manager est disponible de la même façon que Zutilo, à partir de la page _Releases_ du dépôt GitHub de ce module, soit : https://github.com/bwiernik/zotero-shortdoi/releases.

Une fois Zutilo installé, il peut être configuré à partir du menu _Outils_ de Zotero > _DOI Manager preferences..._


🛠️ Téléchargez et installez ces 3 modules complémentaires.

## II. Optimiser la gestion des PDF avec ZotFile

Voici  les principales caractéristiques de ZotFile.

1. Faciliter la gestion des fichiers joints en les **renommant -> 1.a** et/ou en les **déplaçant -> 1.b** automatiquement.

     * 1.a Renommage automatique et intelligent des fichiers.
     * 1.b Attachement au document Zotero du fichier le plus récemment modifié depuis un répertoire déterminé -> les fichiers sont enregistrés **dans** le répertoire `Zotero\storage`.
     * 1.b Déplacement des fichiers joints dans un répertoire déterminé > les fichiers sont enregistrés **en-dehors** du répertoire `Zotero\storage`.

2. Synchroniser les fichiers PDF avec un iPad ou une tablette.

Avant la version 6.0 de Zotero publiée en mars 2022, ZotFile permettait d'extraire les annotations et le texte surligné des PDF, pour les restituer dans des notes Zotero. Ces fonctionnalités sont désormais intégrées dans Zotero aussi ont-elles été retirées de ZotFile.

Nous allons voir plus en détails les fonctionnalités 1. Je ne suis pas équipée pour une démonstration de la synchronisation avec un iPad ou une tablette, mais je cède bien volontiers la parole à l'un de vous pour un retour d'expérience concernant cette fonctionnalité.

### Comment gérez-vous vos PDF actuellement?

🗳️ Comment gérez-vous les PDF et autres fichiers associés aux documents de votre bibliothèque Zotero (c'est-à-dire vos références bibliographiques)?

1. Ces fichiers sont enregistrés **dans** le répertoire `Zotero\storage`, automatiquement par Zotero ou par un ajout manuel de ma part grâce à la fonction _Ajouter une pièce jointe_>_Joindre une copie enregistrée d'un fichier_.
2. Ces fichiers sont enregistrés **en-dehors** du répertoire `Zotero\storage`et ne sont pas liés aux documents Zotero.
3. Ces fichiers sont enregistrés **en-dehors** du répertoire `Zotero\storage`et je les lie aux documents Zotero grâce à la fonction _Ajouter une pièce jointe_>_Joindre un lien vers un fichier_.
4. Je ne comprends pas la question et/ou les options de réponse.


### Ressources

Billet du blog Zotero francophone : [ZotFile : un outil pour gérer vos PDF](https://zotero.hypotheses.org/2838)

Et son supplément :

Être ou ne pas être dans Zotero : quel choix pour vos PDF et autres fichiers joints ? - [schéma au format .odg](https://github.com/zfrancophone/zfrancophone-blog/blob/master/2019-09-zotfile/zotero_choix_gestion_fichiers.odg) et [schéma au format .pdf](https://github.com/zfrancophone/zfrancophone-blog/blob/master/2019-09-zotfile/zotero_choix_gestion_fichiers.pdf)

### 1.a Renommer ses fichiers avec ZotFile

🛠️ Configurez les préférences de ZotFile pour implémenter les options de renommage suivantes.

* Le nom de fichier est constitué de la concaténation du contenu des champs suivants :
    * nom de l’auteur et première lettre de son prénom,
    * année,
    * titre,
    * type de document.
    * Ces 4 éléments sont séparés par un tiret `-`.
    * Si l'un de ces champs est vide, le tiret `-` est omis.
* 1 seul auteur au maximum est affiché.
* Au maximum 10 caractères du titre sont utilisés.
* Les blancs sont remplacés.
* Les caractères spéciaux (diacritiques) sont enlevés.

📃 Notez vos réponses aux 2 questions suivantes.

* Quel est le format de renommage que vous avez défini? Nous ferons un retour de vive voix pour les options sous forme de cases à cocher.
* Quelles autres options de renommage vous semblerait-il pertinent de définir?

🕰️ Rendez-vous dans **10 minutes**.

💡 Sélectionnez un document dans votre bibliothèque Zotero et cliquez sur _Règles de renommage_ > _Aperçu des règles actuelles de renommage_ > _Mettre à jour_ dans les préférences de ZotFile pour prévisualiser un exemple du schéma que vous avez défini.

<!--corrigé : {%F-}{%y-}{%t-}{%T}-->

### 1.b Déplacer ses fichiers avec ZotFile

#### Comment choisir?

👓 Commentaire et explication de : [Être ou ne pas être dans Zotero : quel choix pour vos PDF et autres fichiers joints ? schéma au format .pdf](https://github.com/zfrancophone/zfrancophone-blog/blob/master/2019-09-zotfile/zotero_choix_gestion_fichiers.pdf)


### Annoter avec Zotero

Les avantages d'intégrer des annotations dans Zotero demeurent, que ces fonctionnalités soient gérées avec ZotFile ou désormais avec Zotero.

* Vos annotations sont **indexées** par le moteur de recherche de Zotero et vous pouvez les interroger au même titre que tout le contenu de votre bibliothèque.
* Vos annotations sont **transférées dans un format texte indépendant de PDF**. Cela vous permet par exemple de les modifier aisément ultérieurement, de les transférer dans un autre texte, etc.
* Grâce à la fonction de **recherche enregistrée** de Zotero, vous pouvez distinguer facilement et automatiquement les documents que vous avez annotés de ceux que vous n'avez pas commentés.
La recherche enregistrée permettant d'afficher toutes vos notes est construite de la façon suivante.

  `Type de document`-- `égal`--`Note`

![zotero][zotero] [Documentation Zotero : Rechercher](https://docs.zotero-fr.org/searching)

Le lecteur de PDF et l'éditeur de notes de Zotero 6 offrent de plus de nombreuses autres fonctionnalités, dont voici un aperçu.

* Ouvrir les PDF dans un lecteur intégré à la fenêtre principale de Zotero, dans une interface à onglets.
* Modifier les informations bibliographiques d’un document tout en visualisant le PDF associé.
* Annoter les PDF avec des surlignages et des annotations d'image et d'extraits de texte, **en intégrant systématiquement les informations de citation**.
* **Ajouter les annotations dans des notes Zotero** : créer automatiquement une note à partir de toutes les annotations d'un PDF, ou ajouter des annotations provenant de différents PDF à une même note.
* **Citer depuis les annotations** :  le nouveau bouton "Add Note" dans le module de traitement de texte insère le contenu d'une note Zotero et les citations associées.

#### Stockage, import et export des annotations de PDF

* Les annotations créées dans le lecteur de PDF de Zotero ne sont pas lisibles directement dans un lecteur de PDF externe. Elles ne sont en effet pas stockées dans le fichier PDF mais dans votre base de données Zotero. Elles peuvent bien sûr être exportées.
* Zotero peut **importer les annotations** effectuées dans un lecteur de PDF externe, comme le faisait ZotFile.

#### Ressources

📺 Vidéo de "La Boîte à outils des  historien·ne·s" concernant le lecteur de PDF de Zotero v6 :

Heimburger, F. (2022, avril 21). Découvrir Zotero 6 - Le lecteur de pdf et la prise de notes en vidéo. La boîte à outils des historien·ne·s. https://boiteaoutils.info/2022/04/decouvrir-zotero-6-le-lecteur-de-pdf-et-la-prise-de-notes-en-video/

📑Mini-tutoriels sur Twitter :

Bilal, M. (2022, août 30). Zotero 101 : A step-by-step guide with visuals [how to take notes and annotate PDFs in Zotero]. Twitter. https://twitter.com/MushtaqBilalPhD/status/1564522758696013824

Bilal, M. (2022, septembre 11). Zotero 101 : A step-by-step guide with visuals [how to make groups and do « collaborative annotations. »]. Twitter. https://twitter.com/MushtaqBilalPhD/status/1568829219383218179

Bilal, M. (2022, octobre 17). Zotero 101 : A step-by-step guide with visuals [how to supercharge your writing using Zotero’s Note Editor]. Twitter. https://twitter.com/MushtaqBilalPhD/status/1581927147685687297


![zotero][zotero] [Documentation Zotero : Le lecteur PDF et l'éditeur de notes de Zotero](https://docs.zotero-fr.org/pdf_reader)

![zotero][zotero] [Base de connaissance Zotero : Pourquoi Zotero stocke-t-il les annotations PDF dans sa base de données plutôt que dans le fichier PDF ?](https://docs.zotero-fr.org/kb/annotations_in_database)


## III. Améliorer les données bibliographiques avec Zutilo et DOI Manager

### Zutilo

Par le biais d'options de menu supplémentaires et de raccourcis clavier, Zutilo ajoute des fonctions non disponibles en standard dans Zotero. Voici quelques-unes des fonctionnalités de Zutilo.

* Copier, coller et retirer des ensembles de marqueurs.
* Créer des liens de "Connexe" entre les documents sélectionnés grâce à un clic-droit avec le bouton de la souris.
* Copier dans le presse-papiers des documents dans plusieurs formats différents.
* Modifier des documents, définir l'emplacement du curseur et masquer différents éléments de l'interface utilisateur Zotero grâce à des raccourcis clavier.

Zutilo s'efforce de réaliser tous vos souhaits en termes de flux de travail Zotero, et de rester à l'écart autrement. Tous les éléments graphiques de Zutilo peuvent être désactivés individuellement, de sorte que les fonctionnalités indésirables n'encombrent pas l'interface utilisateur.

_Traduit de la [présentation de Zutilo - fichier README](https://github.com/wshanks/Zutilo/blob/master/README.md)_


La traduction en français de la documentation est disponible dans le dépôt GitHub de Zutilo.

* Le [fichier COMMANDS-fr](https://github.com/wshanks/Zutilo/blob/master/i18n/fr/readme/docs/COMMANDS.md) explicite chacune des fonctionnalités offertes par ZotFile.
* Le [fichier USAGE-fr](https://github.com/wshanks/Zutilo/blob/master/i18n/fr/readme/docs/USAGE.md) détaille des cas d'usage pour certaines fonctionnalités en particulier.

🛠️ Ouvrez les préférences de Zutilo et le fichier COMMANDS-fr.

📃 En considérant les fonctions **autres que les fonctions des pièces jointes**, notez :

* les **3** fonctionnalités de Zutilo qui vous semblent **les plus utiles**, en faisant précéder cette liste de `+1`,
* les **3** fonctionnalités de Zutilo que **vous ne comprenez pas** et pour lesquelles vous souhaiteriez une démo, en faisant précéder cette liste de `??`.

🕰️ Rendez-vous dans **15 minutes**.

<!-- Exemple1 : Copier + Coller dans les champs vides : Compléter des notices -> chapitres, chapitres 1 et 2 de Santé mondiale. Enjeu stratégique et jeux diplomatiques
Exemple2 : Copier + Remplacer les champs : Rendre conformes des notices -> articles revue d'éco. ind.
Exemple3 : Multiples formats pour copie rapide
Préférences avancées à modifier :
`extensions.zutilo.copyItems_alt_total`  -> nbre de alt souhaités
  Les documents seront copiés dans le presse-papiers en utilisant d'autres convertisseurs d'export.
  Pour sélectionner les convertisseurs utilisés par ces fonctions, les préférences correspondantes `extensions.zutilo.quickcopy_alt1` -> préciser le format
  `extensions.zutilo.quickcopy_alt2` -> préciser le format
  `export.quickCopy.setting` -> afficher la chaîne de caractères du format de sortie en cours de sélection-->

Notez que les 2 fonctionnalités suivantes sont désormais intégrées à Zotero, sous des intitulés différents, mais avec un fonctionnement similaire.

* Créer une notice "Chapitre de livre"  - _fonctionnalité Zotero correspondante : Créer un Chapitre de livre_
* Créer une notice "Livre" - _fonctionnalité Zotero correspondante : Créer un Livre à partir du Chapitre de livre_

### DOI Manager

Voici les principales fonctionnalités de DOI Manager.

* _Get shortDOIs_ : Pour les documents sélectionnés, recherche les DOI courts, remplace les DOI déjà enregistrés le cas échéant, et marque les DOI non valides.
* _Get long DOIs_: Pour les documents sélectionnés, recherche les DOI complets, remplace les DOI déjà enregistrés le cas échéant et marque les DOI non valides
* _Verify and clean DOIs_: Pour les documents sélectionnés, recherche les DOI complets, remplace les DOI déjà enregistrés le cas échéant, vérifie que  les DOI déjà enregistrés sont valides, et marque les DOI non valides.
    * Cette fonction retire aussi les préfixes indésirables (comme doi:, https://doi.org/, or ou un préfixe d'URL d'éditeur) du champ DOI.

_Traduit de la [présentation de DOI Manager - fichier README](https://github.com/bwiernik/zotero-shortdoi/blob/master/README.md)_

💡 La présence de DOI valides dans vos références bibliographiques est non seulement nécessaire pour respecter les consignes de certains styles bibliographiques, mais peut encore vous rendre des services complémentaires.

 * **Accéder facilement à la page de la publication sur le site de son éditeur** : l'un des principaux avantages du DOI est de fournir une page de description permanente pour l'objet qu'il identifie, accessible grâce à un mécanisme de résolution du DOI. Dans Zotero, cliquer sur l'intitulé du champ `DOI` active ce processus et ouvre cette page dans un nouvel onglet de votre navigateur internet.
 * **Améliorer les performances des options de localisation de Zotero** : les performances des moteurs de recherche intégrés à Zotero peuvent être augmentés par le DOI, car ce dernier constitue un critère d'identification (et de recherche) univoque. Voir le billet du blog Zotero francophone : [Les moteurs de recherche intégrés à Zotero](https://zotero.hypotheses.org/3388)


## IV. A vous de tester un ou plusieurs modules

🛠️

Nous allons maintenant tester d'autres modules complémentaires, selon les fonctionnalités supplémentaires que vous voudriez ajouter à Zotero.

Chacun d'entre vous va installer et tester le module de son choix.

Plusieurs personnes peuvent tester le même module.

Vous rédigez en LaTeX ou avec un système qui utilise BibTeX? Je vous recommande [**BetterBibTeX**](https://retorque.re/zotero-better-bibtex/).

Vous souhaitez améliorer encore la gestion de vos pièces jointes, enregistrées dans `Zotero/storage`? Vous pouvez tester [**Zotero Storage Scanner**](https://github.com/retorquere/zotero-storage-scanner)


📃 Notez le module que vous allez tester.

Aucune idée? Consultez ![zotero][zotero] [liste complète des modules complémentaires de Zotero](https://www.zotero.org/support/plugins).

Ou encore testez l'un des modules ci-dessous.

* [**ZoteroPreview**](https://github.com/dcartertod/zotero-plugins) pour ajouter un onglet de prévisualisation de la référence bibliographique mise en forme dans le panneau de droite de Zotero.
* [**Zotero Tag**](https://github.com/windingwind/zotero-tag) pour gérer ses marqueurs : ajout/ retrait selon des règles, modifications par lot, etc.
* [**Zotero PDF Translate**](https://github.com/windingwind/zotero-pdf-translate)  pour traduire des extraits de PDF à partir du lecteur de PDF intégré à Zotero, traduire automatiquement le titre et le résumé d'un document sélectionné dans sa bibliothèque Zotero, etc.
* [**Zotero Style**](https://github.com/MuiseDestiny/zotero-style) (non référencé dans la documentation) pour ajouter des colonnes au panneau central de Zotero et les personnaliser, créer des marqueurs hiérarchisés, attribuer des étoiles de favori à des documents, afficher la progression dans la lecture des PDF, etc.
* [**Zotero Duplicates Merger**](https://github.com/frangoud/ZoteroDuplicatesMerger) (non référencé dans la documentation) pour fusionner par lot des doublons.


Toujours pas d'idée? Testez l'un des modules choisis par un autre participant.

📃 Notez le module que vous allez tester.

🕰️ Rendez-vous dans **20 minutes** pour une mise en commun et un retour d'expérience du module que vous avez testé.

🤔Si le test du module que vous avez choisi initialement tourne court, changez de module, et signalez ce changement.


[zotero]: img/icone_zotero.png


# Crédits

<a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/fr/"><img alt="Licence Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/3.0/fr/88x31.png" /></a><br />Ce document est mis à disposition selon les termes de la <a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/fr/">Licence Creative Commons Attribution -  Partage dans les Mêmes Conditions 3.0 France</a>.

**Auteur**

Frédérique Flamerie
