# DW-V3-P2
## Stylisez le HTML 
### Figma
Maquette haute fidélité: https://www.figma.com/file/EGLtVGfH0H7S4068Fl5EOO/Maquette-desktop-Riding-Cities?type=design&node-id=2-43&mode=design&t=YP02HueIqPgi5DHz-0
### Détails
#### Scénario


 
Vous rejoignez l’agence Webonzaï pour un stage en tant que développeur junior.

Romain, votre maître de stage et CTO, est en déplacement professionnel la semaine de votre arrivée.

 

Pour vous permettre d’avancer sans lui, il vous confie par e-mail votre première mission : mettre à jour la page Internet de Riding Cities, une association sportive qui promeut le skate en région.

 

De : Romain

À : Moi

Objet : Première mission : mise à jour de la page Riding Cities

Hello ! 

On est ravis de pouvoir te compter parmi nous ! 

Pour anticiper mon absence, j’ai résumé ta première mission en une vidéo. Ça te permettra d’avancer sans moi. Je te laisse la visionner avec attention, en prenant des notes : 


Je joins en bas de l’e-mail les fichiers de travail que je montre dans la vidéo, et qui te seront nécessaires pour effectuer la mission. 


Tu trouveras donc en pièces jointes : la page du site existant de Riding Cities, le code du site existant et la maquette réalisée par notre graphiste.


Tu as toutes les informations pour avancer. On se programme une réunion pour parler du résultat !


Bon démarrage !


Romain

Pièces jointes :

Page et code existants du site Riding Cities 
Maquette du résultat attendu
 

Avant de commencer, vous prenez des notes :  


Client : Riding Cities, association de skate
Mission : actualiser la page Internet de Riding Cities de la façon suivante :

Créer une nouvelle section, “Les membres fondateurs”, avec les noms et photos des créateurs de l’association.
Modifier la section comprenant le bouton “Télécharger le planning de cours” pour ajouter un titre et deux boutons permettant de télécharger deux plannings de cours différents (un pour les enfants et un pour les adultes).
Informations sur le code :

Il n’y a que du code HTML à développer.
Le code existant contient des lignes qui pourront être réutilisées et adaptées pour obtenir le résultat de la maquette.
Le code CSS est déjà en place : je devrai copier-coller les classes CSS déjà écrites pour ordonner et mettre en forme les éléments comme sur la maquette.
 

Vous vous mettez sans tarder au travail !

 

#### Étapes
##### Étape 2 : Créez la section des membres
Ici, le but est de produire une nouvelle section, intitulée “Les membres fondateurs”, contenant du texte et des images en colonnes. Pour y arriver, vous allez vous inspirer de la section “La mission de l’asso” déjà existante. Pour cela, voici les différentes actions à prendre :

###### Action 1 : Prenez connaissance des documents 
Avant tout, consultez la page existante ainsi que le code qui la compose. Une première analyse du code permettra de comprendre le fonctionnement de celui-ci. 
Ensuite, observez la maquette. Elle représente ce à quoi devra ressembler la nouvelle page de l’association après les modifications demandées. 

###### Action 2 : Copiez le code existant pour le réutiliser
En partant du code déjà en place, vous pourrez reprendre certaines lignes de code et les adapter pour obtenir un résultat correspondant aux maquettes.
Vous devez ajouter une section, et il en existe déjà une codée sur le site. Il semble donc intéressant de repartir de ce bout de code pour mettre en place la nouvelle section.

Copiez et collez la balise “section” de la partie “La mission de l’asso”.
Ressource utile : le chapitre “Créez votre première page web en HTML” du cours HTML-CSS, sur lequel vous pourrez vous appuyer également pour l’étape suivante. 

 
###### Action 3 : Modifiez le code HTML
À ce stade, vous avez deux sections identiques l’une au-dessus de l’autre.
Vous allez devoir faire évoluer celle du dessous pour qu’elle corresponde à la section attendue sur la maquette : “Les membres fondateurs”.


Pour cela, observez les différences entre les deux sections, et modifiez le code où c’est nécessaire.

Les colonnes : actuellement, cette nouvelle balise “section” contient 4 colonnes. La section “Les membres fondateurs”, elle, ne doit en contenir que 3.
Il faut donc en supprimer une pour n’avoir plus que 3 colonnes, comme sur la maquette.
Les textes : il existe des balises contenant du texte, mais le texte de la nouvelle section est différent.
Remplacez les textes à l’intérieur des balises en reprenant les textes de la maquette.
Les images : la section “La mission de l’asso” ne contient pas d’images, mais pour la section “Les membres fondateurs”, vous devez faire apparaître des photos.
Récupérez les images dans le dossier correspondant.
Ajoutez les images dans les colonnes.
Veillez à bien renseigner les attributs “src” (il est important de renseigner un chemin relatif ) et “alt” (à vous de trouver quelque chose de pertinent).
 
###### Action 4 : Utilisez les classes CSS présentes dans le code pour mettre en forme la section
À présent, le contenu de la section correspond à la maquette, mais la mise en forme en est encore éloignée. C’est là qu’interviennent les classes CSS.

Dans cette étape, vous allez modifier le code HTML pour lui ajouter du style. Vous ne devez pas modifier le fichier style.css, mais uniquement le fichier index.html. C'est-à-dire, utiliser les classes CSS déjà écrites et les appliquer dans le HTML, sans modifier ou ajouter de code CSS.

Les textes : il va falloir maintenant modifier la couleur et l’alignement des textes pour qu’ils correspondent à la maquette. Des classes CSS sont disponibles dans le code pour faire cela :
trouvez la classe correspondante ;
appliquez-la sur le texte.
La couleur de fond : Vous devrez changer la couleur du fond. De nouveau, une classe CSS disponible dans le code permet ce changement :
trouvez la classe correspondante ;
appliquez-la au fond de la section.
Ressource utile : le chapitre Intégrez le CSS dans la page HTML du cours HTML-CSS, sur lequel vous pourrez également vous appuyer pour la suite.

##### Étape 3 : Faites évoluer la session
Suite à la création de la section “Les membres fondateurs” en dessous de “La mission de l’asso”, la section contenant le bouton de téléchargement se trouve désormais en bas de la page. Vous devrez faire plusieurs changements pour obtenir le résultat présenté sur la maquette. Pour cela, réalisez les actions suivantes : 

 
###### Action 1 : Ajoutez un titre et une couleur de fond à la section
Ajoutez le titre “Découvrez nos cours”. Pour cela, prenez exemple sur les titres déjà en place.
Ajoutez la couleur de fond grise sur la section à l’aide d’une classe CSS déjà en place.
Ressource utile : le chapitre Créez votre première page web en HTML du cours HTML-CSS, sur lequel vous pourrez vous appuyer également pour l’action 3.

 
###### Action 2 : Modifiez le bouton de téléchargement
Pour l’instant, vous allez vous concentrer sur le bouton existant, et le transformer pour obtenir quelque chose qui se rapproche du premier bouton visible sur la maquette.

La forme et la couleur du bouton : vous remarquerez que la forme du bouton “Télécharger le planning de cours” est différente des boutons qu’on voit sur la maquette. 
Ajoutez les classes CSS nécessaires pour obtenir un bouton arrondi, à la couleur correspondant à la maquette.
L’effet au survol : sur la maquette, le deuxième bouton montre l’effet désiré au survol, c’est-à-dire l’effet voulu lorsqu’on place le curseur de la souris sur le bouton.
Ajoutez la classe CSS nécessaire pour obtenir un effet sur le bouton lors du survol de la souris. 
 
###### Action 3 : Ajoutez le deuxième bouton de téléchargement et placez les boutons tel que sur la maquette
Pour cela, copiez et collez la balise du bouton déjà en place.
À ce stade, les deux boutons doivent se retrouver l’un à côté de l’autre. Pour mettre ces deux boutons en colonne :

Modifiez la classe qui est appliquée sur la balise “div” contenant les deux boutons.
Enfin, finalisez la modification des boutons :

Modifiez le contenu texte des deux boutons, conformément à la maquette.
Appliquez la bonne couleur sur chacun des deux boutons, en modifiant une des classes appliquées sur le bouton. 
 
###### Action 4 : Rattachez les bons documents aux boutons de téléchargement
Les boutons de téléchargement doivent mener vers les plannings de cours pour enfants et pour adultes. Consultez les brochures présentes dans le dossier “Documents”.

Vous devrez ensuite remplir l’attribut “href” des boutons pour permettre de cibler les bons documents. 
Ressource utile : le chapitre Créez des liens du cours HTML-CSS.

Le site de Riding Cities doit désormais correspondre à la maquette.

 

Félicitations, vous avez finalisé votre mission ! 