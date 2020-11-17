# How to stream

L'idée de ce document n'est pas de faire de vous des pros-streamers mais de tout faire pour avoir un meilleur confort et une meilleur qualité possible pour tous.

Il y a une très bonne vidéo faite par un YouTuber/streamer Twitch Belge ici: [Streamer Comme un Pro en 20 Minutes Max !](https://www.youtube.com/watch?v=nEXEe-1o5hA) C'est assez similaire à ce que je vous dis ici, j'y ai juste rajouté mes quelques ajouts. Notamment pour les explications de qualité, il le fait mieux que moi, j'ai essayé de faire ce que j'ai pu. Mais on va essayer de limiter a du 720p car il me semble que aucune des chaînes n'est partenaire Twitch et du coup, les viewers seront obligé de visionner en source, si vous mettez du 1080/60 images par secondes, beaucoup de gens ne pourrons pas visionnez le live, ce serait dommage.

# Configuration

## Configuration minimal

* Une bonne connexion, en étant un peut réaliste et proposer une qualité acceptable, ce serait du 480p avec un upload de 3 Mbps environ (si vous avez cette vitesse, normalement, vous pourrez streamer sans perdre des images (avoir des "freeze" et "lag")). Voici un site qui vous permettra de vous donnez une idée de la vitesse de votre connexion: [testmy.net](https://testmy.net/upload) Il suffit de cliquer sur **Test My Upload Speed**
  
  Voici un screenshot d'un test que j'ai fais chez moi, on peut voir que j'ai presque 14Mbps en upload ce qui devrait largement suffire. J'ai fait ce test en WiFi, il est probable que si j'avais branché un câble, j'aurais pu avoir un meilleur score.
  
  <img title="" src=".\Picture\2020-11-11-firefox - score.png" alt="" width="747">
  Malheureusement, ma connexion n'est pas toujours aussi bonne, il arrive qu'elle ai ce qu'on appel des "drop" de temps en temps, elle devient beaucoup moins bonne, voir même ce coupe pendant un certain temps. Si vous savez que vous avez une connexion comme ça, ce serait bien d'avoir une potentiel alternative (quelqu'un qui pourrait reprendre le stream ou trouver quelqu'un d'autre pour streamer par exemple).
  
  Mais l'overlay que l'on va vous passer est basé sur du 720p, vous pourrez tout de même l'utilisez, il faudra juste "downscale" votre image

* Un pc pas trop mauvais.
  
  * GPU compatible DirectX 10.1 (la plus part sauf si vous avez un vraiment vieux pc)
  
  * Processeur: un i7, Intel i5 3th gen (7*** ou +) ou i3 8th gen (8*** ou +) ou Ryzen 3 ou + (un processeur avec 4 cœur, c'est pas mal). Pour donner un exemple, j'ai fait des test sur un portable avec un i5 de 5th génération, j'ai eu des soucis, on a du changer de pc (en tout cas avec streamlab obs, qui est l'outils qui correspond le + à ce qu'on a besoin pour cet événement)
  
  * Ram: 4G
    
    Pour connaître la configuration actuelle de votre PC, il faut aller dans le gestionnaire des tâche <kbd>Ctrl</kbd>+<kbd>Maj</kbd>+<kbd>Esc/Echap</kbd> ce qui vous amène dans le gestionnaire des tâches, il faut cliquer sur "Plus de détails" en bas à gauche, ensuite aller dans l'onglet performance.
    
    <img title="" src=".\Picture\2020-11-14 14_59_08-Task Manager.png" alt="" width="742">
    
    On peut voir que j'ai une carte graphique avec du DirectX 12, j'ai 7,7GB de RAM (8, mais il ne reconnaît pas toute la RAM) et pour le Processeur, il faut aller voir dans la partie CPU:
    
    <img src=".\Picture\2020-11-14 15_06_35-Task Manager.png" title="" alt="" width="742">
  
  J'ai un i5-5300U donc un i5 de 5th gen (5éme génération)
  
  Mon ordinateur est en théorie capable de streamer, et je l'ai déjà fait. Mais ça n'a pas toujours très bien fonctionné.

## Configuration confort

* Pour la connexion, si on passe à une meilleur qualité vidéo, il faudra monter l'upload possible: 6.5Mbps pour du 720p/30 images par secondes (HD)
  
  <img title="" src=".\Picture\2020-11-14 14_41_27-Task Manager.png" alt="" width="428" data-align="inline">
  
  Ici, j'ai lancé un stream en 720p avec 30 images par secondes, j'étais sur eduroam avec pas grand monde de connecté, donc ça fonctionnait plutôt bien, mais comme on peut le voir, streamlab OBS hésite pas prendre pas mal de bande passante.

* Pour ce qui est du PC, il peut rester comme ça, si vous comptez pas jouer dessus (la config cité plus haut risque d'être pas mal monopolisé par streamlab). Si vous souhaitez jouer, ça dépendra des jeux, c'est vraiment au cas par cas, il faut aller voir la configuration minimal du jeux et ce dire qu'il ne faut pas être limite au niveau du processeur et de la RAM.

* Pour le confort, avoir un 2éme écrans,c'est vraiment bien, pour avoir un retour, le chat, le discord sur le 2éme écrans et sur l'écrans principal, ce qui est streamer (le jeux, une page web, un document text, ...). Une alternative possible à ça, c'est d'avoir l'application twitch sur son téléphone, cela permet de voir si tout ce passe bien sur le stream facilement.

## Bon à savoir

Si c'est un ordinateur portable, pensez bien à le garder tout le temps branché, effectivement, un ordinateur portable débranché ce mets en mode économie d'énergie et perd de la puissance. Par ailleurs, un pc fixe avec les même composant qu'un PC portable va mieux s'en sortir, donc essayer d'utiliser un PC fixe dans la mesure du possible.

Essayer d'être le plus proche possible et avec le moins de mur entre la box et vous (un mur, c'est déjà beaucoup), si vous êtes en WiFi; ou encore mieux, essayé d'avoir un câble même temporaire branché sur votre ordinateur.

Essayer de vous isoler un minimum pour pas que votre micro capte trop de bruits parasite.
Si possible, avoir un maximum de lumière qui vous éclaire si vous souhaitez vous filmez, toutes les caméras on un meilleur rendu s'il y a plus de lumière sur ce qu'elles films.
Faite au moins un test en condition réel avant de lancer le stream pour voir si tout va bien.

# Les outils

## Les indispensables

### [Streamlab OBS](https://streamlabs.com/streamlabs-obs)

Ce logiciel vous permettra de streamer sur twitch, il ne fonctionne que sous windows malheureusement (impossible de l'utiliser sous Mac ou Linux, il y a des alternative a streamlab OBS qui fonctionne sous Mac et Linux mais elles ne sont pas présenté ici car trop complexe et trop de diversité). Il est disponible en téléchargement ici: [Streamlab OBS](https://streamlabs.com/streamlabs-obs) 

#### How to streamlab

Il y a plusieurs étapes à faire:

1. Installer Streamlab OBS

2. Faire une première configuration et la tester avec un écrans noir

3. Si ça marche, importer l'overlay

4. Rajouter votre touche perso (Logo de votre cercle, scène supplémentaire éventuel, jeux éventuel ...)

5. C'est partit

##### Premier lancement de streamlab OBS:

Lorsque vous lancez Streamlab pour la première fois, vous allez arriver sur cet écrans:

<img title="" src=".\Picture\2020-11-13 22_32_57-Streamlabs OBS.png" alt="" width="747">

Cliquer sur le logo de twitch (le logo mauve à gauche), cela vous ouvrira une fenêtre comme celle-ci:

<img src=".\Picture\2020-11-13 22_34_24-Log In - Twitch.png" title="" alt="" width="420">

Elle vous sert à vous connectez à la chaîne de votre cercle, moi j'ai utilisé mon second compte. Une fois Votre nom d'utilisateur et votre mot de passe, vous allez recevoir un mail tel que celui-ci:

<img src=".\Picture\2020-11-14 16_40_47-(175) Roundcube Webmail __ Boîte de réception.png" title="" alt="" width="537">

Il faut copier le nombre avec 6 chiffres (ici 581824) dans la fenêtre qui c'est ouverte sur streamlab après avoir cliqué sur Log in. Cette fenêtre-ci: 

<img src=".\Picture\2020-11-13 22_35_06-Twitch - Authorize Application.png" title="" alt="" width="371">

Après cela, vous aurez cette fenêtre:

<img title="" src=".\Picture\2020-11-13 22_35_17-Twitch - Authorize Application.png" alt="" width="347">

Streamlab demande a pouvoir accéder à pas mal d'options et de fonctionnalité du compte Twitch de votre cercle, ce qui est normal car avec Streamlab on sait gérer énormément de choses de la chaîne.

Ensuite, streamlab vous proposera de soit l'utiliser gratuitement, soit de payer un abonnement, nous n'avons absolument pas besoin de l'abonnement ici, vous pouvez utiliser la version gratuite

<img title="" src=".\Picture\2020-11-13 22_35_32-Streamlabs OBS.png" alt="" width="747">

Il nous reste 4 petites étapes:

Il va d'abord nous proposer d'importer les paramètres et Overlay d'OBS, ce que nous ne voulons pas, vous pouvez cliquez sur "Start Fresh"

<img title="" src=".\Picture\2020-11-13 22_42_48-Streamlabs OBS.png" alt="" width="747">

Ici, il va nous proposer de choisir un micro et une caméra par défaut:

<img title="" src=".\Picture\2020-11-13 22_45_32-Streamlabs OBS.png" alt="" width="747">

Il sera possible de modifier ça plus tard si besoin (ou d'en rajouter éventuellement)

Encore une étape que l'on peut passer; il nous propose d'importer un Overlay tout fait, mais nous allons vous en passer un que vous importerez plus tard; donc, vous pouvez cliquer sur skip:

<img title="" src=".\Picture\2020-11-13 23_04_54-Streamlabs OBS.png" alt="" width="747">

Et pour finir, une étape assez importante (mais qu'il est également possible de faire plus tard) essayer de vous mettre au maximum dans les conditions dans lesquelles vous allez streamer (ordinateur branché, câble réseau branché si possible, pas de jeux qui tourne à côté ect) car nous allons lancé une configuration automatique:

<img title="" src=".\Picture\2020-11-13 23_05_30-Streamlabs OBS.png" alt="" width="747">

Après avoir cliqué sur Start, il va faire des tests sur votre ordinateur pour voir quels paramètres vont le mieux.

##### L'interface:

* En haut, nous avons le retour du Live en direct, il est également possible de bouger les sources qui serons dessus

* Au milieux, il y a le "Mini Feed" vous n'en aurez probablement pas besoin (ce sont les annonces des follows (les gens pourrons le vous follow), des abonnements, des dons via twitchs, ect (les abonnements et dons via twitch ne sont pas possible tant que la chaine n'est pas passé au grade Affiliate, ce qui n'est pas simple à avoir))

* En bas, il y a 3 sections très importantes (on y reviendra plus tard):
  
  * La premières, c'est la liste des scènes
  * La seconde, la liste des sources dans la scène sélectionnée
  * La troisième, un "mixer" qui permet de modifier le son de chaque entrées et d'avoir un retour visuel sur le son (avec les barres vertes, puis jaune puis rouge horizontales)

<img title="" src=".\Picture\2020-11-14 22_04_53.png" alt="" width="747">

Je vous conseils de cliquer sur le bouton des statistiques, ce qui va ouvrir la fenêtre suivante:
<img title="" src=".\Picture\2020-11-16 00_49_15-Performance Metrics.png" alt="" width="550">
Sur laquelle vous pourrez cliquer sur les stats pour les ajouter en bas dans streamlab et pouvoir regarder d'un coup d'œil à quel point votre ordinateur et votre connexions souffres et s'ils s'en sortent.
<img title="" src=".\Picture\2020-11-16 00_51_50-Streamlabs OBS.png" alt="" width="747">


La je vous montre les statistique avec mon ordinateur qui stream, on peut voir qu'il s'en sort pas trop mal (en même temps, je venais de lancer le stream avec un écrans noir), il n'y a pas d'images qui ont disparue (Drop frame), le CPU est à 17% d'utilisation (généralement, sur mon PC, ça monte facilement à 40% ou plus), j'ai 30 FPS, c'est ce que j'ai mis dans les paramètres, donc ça correspond bien et j'utilise 6000kb/s ce que j'ai également mis dans les paramètres. Par ailleurs, dans la petite fenêtre dédié aux performance, il est indiqué que la qualité du stream est bonne (YES !).

##### Les paramètres plus avancé de streamlab

<img title="" src=".\Picture\2020-11-15 23_27_46.png" alt="" width="747">

Les cinq paramètres les plus intéressant, selon moi sont General, (stream), Output, Audio, Video et Scene Collections

###### General

Il est possible de remettre les paramètres par défauts, de relancer un paramétrage automatique (Auto Optimize), de sélectionner la langue si vous avez vraiment du mal avec l'Anglais, de désactiver l'accélération Hardware si votre ordinateur à un soucis avec ce paramètre (mais laissez-le activé dans la mesure du possible) + plein d'autres paramètres un peut four-tout.

###### Stream

Je passe rapidement sur cet onglet car il vous permet de vous reconnectez a votre chaîne twitch si vous avez eu un soucis. (ce qui j'espère ne va pas arriver)

###### Output

Il est possible de modifier comment streamlab envoie le flux vidéo (uniquement l'image) vers twitch (ou votre ordinateur car il est également possible d'enregistrer sur votre ordinateur avec streamlab). Normalement, l'optimisation automatique à déjà mis ses paramètres au mieux pour vous.

Mais si vous devez modifier quelque chose, je vous mets les explications de Basile: Pour l’encodeur, la meilleure qualité est donnée avec l’encodeur logiciel x264, mais il consomme énormément de puissance de processeur. Sinon, il existe aussi l’encodeur matériel, qui utilisera l’encodeur de la carte graphique ou de la partie graphique du processeur, moins qualitatif mais soulage le processeur. Il y a plusieurs encodeurs en fonction de votre machine. L’encodeur Intel QSV qui correspond à la partie graphique du processeur (de même pour AMD mais je ne connais pas son nom). L’encodeur NVENC des cartes graphiques Nvidia (et New NVENC pour les cartes graphiques de série 2000 et 3000) et une option similaire pour les cartes AMD.
Deuxième paramètre important est le Bitrate, ça correspond au débit de connexion que vous allouez au stream, plus c’est haut, au mieux sera la qualité (n’allez pas au dessus de 6000 sinon Twitch va vous bannir). Je vous conseille de laisser au moins 0.5 voire 1 Mbit/s pour vos jeux, navigateur etc., n’allouez pas 100% de votre connexion au stream. Si au **Test My Upload Speed** vous avez 5 Mbits/s, ça veut dire que vous pouvez théoriquement monter à 5000 kbits/s mais c’est mieux de mettre 4000 voir grand max 4200. L’audio peut rester à 160. En dessous de 128 kbits/s le son sera de très mauvaise qualité.

###### Audio

La partie qui devrait vous intéressez ce trouve dans le 2éme encadré 
<img title="" src=".\Picture\2020-11-15 23_46_35-Settings.png" alt="" width="747">

Il est possible d'assigner une source différente à une entrée spécifique. Ainsi, dans la source "Desktop Audio Device 1", j'ai mes Haut-parleur, donc tout le son que mes haut-parleurs ferons comme son seront renvoyé vers la source "Desktop Audio 1" (on peut voir cette source dans le mixer sur l'interface principale en bas à droite). La source "Desktop Audio Device 2" donc tout ce que j'entends dans mon casque (c'est un casque Bluetooth) seras renvoyé vers cette source.

Les Desktop Audio Device, ce sont les sources audio que vous entendez (donc les sortie audio, Haut-parleurs, casques, ect), les Mic/Auxiliary Device ce sont les micros (donc les entrées).

Ainsi, dans la configuration actuelle, je n'ai sélectionné que le micro s'appelant "Microphone Array" qui est le micro de mon portable, ce qui est dommage car mon casque a un micro intégré pas mauvais, je pourrais l'utiliser, dans la configuration actuel, je ne pourrais pas l'utiliser. Donc si je souhaite l'utiliser, il faut que je remplace le micro de mon pc portable par celui de mon casque ou bien que je rajoute mon casque dans sur le micro 2 si je souhaite switcher entre les deux micros différents durant le live (via le mixer audio).
L'option Default est l'entrée ou la sortie audio par défaut de Windows, donc, c'est pour pouvoir gérer le son du stream directement depuis windows.

###### Video

Pour la section vidéo, je vais vous demandez de mettre l'option "Base (Canvas) Resolution" à 1280x720 car nous allons vous passer un Overlay avec cette définition.

L'option Output, c'est pour sélectionner la qualité vidéo que vous allez pouvoir streamer. Vous remarquerez que si vous avez sélectionner 1280x720 pour le Canvas, vous ne pourrez pas sélectionner une meilleur qualité. Mais il est préférable de ne pas avoir une trop grosse qualité car sinon les gens qui ont une mauvaise connexion ne pourrons pas regarder votre stream. C'est pour ça qu'il a été décidé que les cercles streamerons au mieux du 1280x720. L'option Downscale Filter permet de dire à streamlab comment passer de la résolution de base (du Canvas) à la résolution du stream (l'output) normalement, vous ne devriez pas toucher à cette option. FPS Type n'as pas beaucoup d'importance (c'est la manière pour sélectionner les FPS, laisser sur Common FPS Values). Malheureusement, si vous streamer à une qualité différente que 1280x720, comme bous vous donnons un canvas de cette qualtié, votre ordinateur va devoir faire la conversion, ce qui lui demandera plus d'énergie (et donc plus de puissance).

Pour les FPS:

Les FPS (frame per seconde) c'est le nombre d'images par seconde que vous allez envoyer à Twitch. Ainsi, 1FPS, ce ne seras clairement pas assez, ça ferait une image par seconde, mais si vous ne streamer pas quelque chose qui bouge beaucoup, 30 FPS devraient être suffisant.

La valeur des FPS, personnellement, je mets 30 FPS car ce que j'ai streamer jusqu'ici c'était des conférences et je n'avais pas besoin de beaucoup de FPS (dites vous que au plus les FPS sont important, au plus ce sera lourd pour votre ordinateur).

Ne dépasser pas 60 FPS, ça n'a pas beaucoup de sens.

###### Scene Collections

C'est ici que vous allez pouvoir importer l'Overlay que nous allons vous donner (en cliquant sur le bouton Import Overlay File)

###### Les autres options

* Hotkeys: permet de mettre des raccourcis clavier sur différentes actions de streamlab

* Advanced: Il y a quelques options que vous pouvez aller voir (le reste, je vous conseil de pas toucher). Comme:
  
  * La possibilité d'utiliser le GPU (la carte graphique) pour créer les images, à modifier si vous avez un problème (mais normalement, vous ne devriez pas à avoir à modifier ça)
  
  * La possibilité d'avoir un delay sur le stream si vous souhaitez

* Notifications: pas grand chose a dire (je sais pas à quel moment il y a des notif, vous devriez pas en avoir, je pense)

* Appearance: il y a pas beaucoup de modifications que vous pouvez faire

* Remote Control: Si vous souhaitez utiliser votre gsm pour controler streamlab (j'ai jamais essayé)

* Virtual Webcam: si vous souhaitez utiliser vos scènes streamlab comme si c'était une caméra dans d'autres logiciels (je pense pas que vous en aurez besoin)

* Game Overlay: permet de voir le chat ou autre par dessus votre jeux (jamais testé)

* Prime: pour donner des sous à streamlab (en gros)

##### Les scènes

Une scène est un ensemble de sources agencées d'une certaine manière pour pouvoir être streamer. Lorsque vous sélectionner une scène, la preview du stream change ainsi que la liste des sources. C'est normal, puisqu'une scène c'est ce qui va être envoyé à Twitch, c'est donc ce qui sera visible sur votre stream.

Si vous souhaitez rajouter des scènes, vous pouvez, mais normalement, j'espère que vous aurez tous ce qu'il vous faut comme scène dans le fichier Overlay que nous allons vous passer.

##### Les sources

C'est ici qu'il y aura toute les sources pour la scène sélectionnée.
Si vous voulez rajouter des choses sur votre stream (comme votre logo de cercle ou autre), il vous faudra rajouter une source pour chaque "objet" que vous souhaitez rajouter.

##### Le mixer

C'est ici que vous avez vos sources audio et que vous allez pouvoir les gérer et avoir un retour visuel sur celles qui fonctionnent et comment elles fonctionnent.
Si vous avez une source audio qui va souvent proche du rouge, c'est qu'elle est probablement un peut forte, si elle va franchement dans le rouge, elle est certainement trop forte, il faudrait la diminuer. Si vous souhaitez une musique d'ambiance, il faudrait qu'elle reste à plus ou moins un tiers du vert. Pour la voix ou le son principale, le mieux, c'est que les barres restent à la fin du vert (entre vert et début du jaune).

##### Passer en direct

Pour passer en direct, il faut cliquer sur le bouton vert tout en bas à droite.
Cette fenêtre devrait s'ouvrir:
<img title="" src=".\Picture\2020-11-16 00_44_46-Streamlabs OBS.png" alt="" width="600">

Vous pouvez y mettre le titre du stream, le jeux (si vous souhaitez) et un ou plusieurs Tags (si vous le souhaitez) et ensuite cliquer sur Confirme & Go Live, et quelques secondes plus tard ce sera partit, vous serez en live.

### [Discord](https://discord.com/)

Ce logiciel vous permettra de discuter entre vous, au sein de votre cercle et avec les autres cercles. Il est possible d'utiliser discord en ligne, ou de le télécharger sur votre ordinateur (il est disponible pour tout les système d'éxploitation, mais sous Linux il à quelques soucis) ou votre gsm. Je conseil fortement de le télécharger sur les ordinateurs qui vont être utilisé pour streamer.

#### How to discord

Une fois que vous avez rejoins le discord via le liens qui vous à été donné et que vous vous êtes connecté avec votre compte, vous devriez arriver sur une fenêtre de ce type. A gauche, il y a tous les "channel" ce sont des espaces de discussions; il y en a des écrits avec un "#" et des vocaux avec un petit haut-parleur (dans les channels vocaux, il y a egalement moyen de partager sa caméra ou son écrans). On peut voir que actuellement, je suis dans le channel discussion pour tous le monde (je suis dans la partie "🙈 For Everyone"). Pour changer de channel, il suffit de cliquer dessus. Une fois dans un salon vocal, vous pouvez couper votre micro en bas a gauche (le miens est actuellement coupé)
<img title="" src=".\Picture\2020-11-17 11_45_11-Streamlabs OBS.png" alt="" width="600">

## Les plus

### [Snaz](https://github.com/JimmyAppelt/Snaz)

Snaz est un petit logiciel pour faire un timer que vous pourrez rajouter a votre stream si vous le souhaitez.
