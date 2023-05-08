#Rapprt de stage 




## Introduction
Du 17 avril au 9 juin 2023 (8 semaines), j'ai pour but d'accomplir mon stage dans l'entreprise CIRCL qui se situe au 122 Rue Adolphe Fischer, 1521 Gare Luxembourg. Au cours de ce stage dans
le domaine de l'informatique, plus précisément dans celui qui est plus orienté réseau, j'ai pu m'impliquer dans un grand projet d'envergure internationale qu'est MISP.
CIRCL est une entreprise spécialisée dans la sécurité informatique et est une organisation récemment créée (2012), mais qui a su faire les bons choix pour se faire un nom et une réelle place
en tant qu'acteur majeur de la sécurité informatique au Luxembourg. Elle n'est pas simplement reconnue au niveau national mais bien au-delà grâce à ses projets, son dévouement et son efficacité. 
Ayant pour tuteur Alexandre Dulaunoy, j'ai pu bénéficier des meilleures explications et de l'accompagnement possible pour le bon déroulement de ce début de stage.

Cela fait un mois que nous avons commencé notre stage obligatoire de deux mois en entreprise, dans le cadre de notre deuxième année de formation de Bachelor Universitaire de Technologie.
Cette expérience est, à mon sens, essentielle lors de notre cursus scolaire, car elle nous permet d'expérimenter le monde du travail dans le domaine que nous avons choisi d'étudier.
En tant que promotion ayant suivi au lycée la filière générale ou technologique, nous n'avons pas eu, contrairement à la filière professionnelle, l'occasion d'avoir une expérience professionnelle
en lien direct avec nos études. Cette expérience est donc extrêmement importante et enrichissante pour nous, car elle est notre première véritable expérience, d'autant plus intéressante avec l'ajout
d'un sujet que nous devons accomplir au cours de cette période.L'objectif à l'issue de mon stage serait de mener à bien mon sujet de stage que j'ai choisi. Ce sujet a pour but d'améliorer
la virtualisation et l'orchestration de l'infrastructure de formation et cela consisterait globalement à la mise à jour de plusieurs fichiers datant maintenant de plusieurs années. Tout en prenant
en compte que la modification de ces fichiers peut engendrer d'autres erreurs ailleurs, c'est donc un travail pointilleux et assez complexe à réaliser.
Ce sujet est bien sûr délivré par l'organisme d'accueil, afin que ces derniers puissent nous aider dans le cas où nous rencontrerions des problèmes, car dans la plupart des cas, l'entreprise dans
laquelle l'étudiant décide de faire son stage possède soit un service informatique, soit au moins une personne ayant des connaissances en informatique. Du fait que ce sujet soit délivré par l'organisme
nous accueillant, il y aura des outils que nous n'avons pas spécialement utilisés lors de nos cours, mais dont nous aurons besoin. C'est pourquoi l'attribution du sujet par l'entreprise est essentielle
au bon déroulement de cette expérience. 

Néanmoins, le choix de ce stage et plus précisément de ce sujet de stage est une réelle opportunité pour moi, ayant pour réelle ambition de m'orienter dans un domaine qui m'intéresse énormément  qui
n'est autre que la cybersécurité. Travailler avec des personnes qui pratiquent un métier dans cette spécialité de l'informatique est réellement enthousiasmant et faire un projet directement lié à mon
choix d'étude future l'est encore plus.

Afin de vous expliquer au mieux ce début de stage dans une entreprise informatique, je vais vous présenter en détail tout ce que j'ai fait depuis mon arrivée en vous présentant tout d'abord l'intitulé
de mon sujet, les outils utiliées et entrez dans e vive du sujet en montrant ce que j'ai fait en divisant cette grand partie en deux, l'une portant sur les recherches et la seconde sur les
manipulation que j'ai faites et je finirai enfin par une courte conclusion donnant mon avis sur mon stage.


# Sujet de stage 

Afin de mener à bien l'explication détaillée de mon projet, je vais tout d'abord vous présenter l'intitulé de mon stage ainsi que ce qui m'a été initialement demandé lors de la préparation de celui-ci.
Je vais ensuite poursuivre en vous présentant les outils qui m'ont été mis à disposition ainsi que les logiciels que l'on m'a demandé d'utiliser afin de mener à terme mon projet.
Enfin, je finirais en vous présentant ce que j'ai pu faire durant ce premier mois et ce qu'il me reste à faire.

## Intitulé du sujet de stage 

L'intitulé du sujet de stage est le suivant : "MSc Student Internship Position - Improvement of Virtualisation and Orchestration of Training Infrastructure",ce qui se traduit par "Poste de stage pour
étudiant(e) en master - Amélioration de la virtualisation et de l'orchestration de l'infrastructure de formation". Comme vous l'aurez remarqué, le sujet n'est pas réellement adapté à mon niveau
actuel d'études. Cependant, lors de mon choix de sujet de stage, celui-ci semblait se rapprocher le plus de ce que je voulais entreprendre dans mes études futures. Cela pourrait également constituer
un réel défi pour moi, en me poussant à me surpasser et à découvrir davantage de choses.

Pour réussir ce travail, j'ai donc un certain nombre de tâches et de maîtrises à acquérir. Tout d'abord, je dois être en mesure de maîtriser le SCM (Source Control Management) Git. Ensuite, je dois être
en mesure de procéder au déploiement et à l'installation de l'infrastructure threat intel MISP en VM afin de contribuer activement à ce même projet open source. Enfin, je dois acquérir des compétences
en Bash et en Unix scripting.

Ayant eu la chance de manipuler Git lors de mes heures d'enseignement et d'avoir des bases en Bash et en Unix scripting en première année de mon cursus en BUT informatique, je dispose de certaines
compétences sur lesquelles m'appuyer, même si mes compétences en Bash sont encore très limitées.


## Outils et logiciel mis à disposition

Bien évidemment, au vu de mon sujet de stage, je ne serai pas amené à utiliser des switchs ou des routeurs ou ce genre de chose que l'on a pu pratiquer de nombreuses fois en travaux pratiques de
réseaux avancés, par exemple, mais à manipuler exclusivement grâce à un ordinateur comme en cours de virtualisation, par exemple. De ce fait, un ordinateur portable sur lequel je travaille sous
Ubuntu 22.04 est le seul outil matériel qui m'a été fourni. En termes de logiciel, j'ai été amené à utiliser principalement Vagrant, VirtualBox et Virtualbox.
J'ai par ailleurs utilisé d'autres choses suite aux conseils avisés de mon tuteur, tels que HedgeDoc qui me permet de mettre en page chaque jour les tâches accomplies, en donnant la possibilité par
la même occasion à mes collègues de voir mon avancée et d'apporter des modifications à ce que j'ai fait. Mais ce n'est en revanche pas le seul outil de collaboration utilisé. On m'a proposé d'utiliser
Element afin d'échanger avec chacune des personnes présentes ou avec elles toutes en même temps, afin d'avoir des réponses rapides.
Du fait qu'il n'y a pas beaucoup de nouveaux outils matériels et/ou logiciels, instinctivement, une personne peut penser que l'apprentissage de l'utilisation de ces équipements n'est pas si compliqué,
mais c'est uniquement lorsque l'on entre dans le vif du sujet que nous mesurons la difficulté, chose que nous allons analyser directement au point suivant.



## Ce que j'ai fait 

Pour mener à accomplissement mon projet j'ai décider de m'imposer dès le début de mon stage un chronologie dans mon lélaboration de mon travail. J'ai pue remarquer lorsque j'était en plein 
apprentissage dans mon établissement scolaire que lorsque nous entamions un nouveau "chapitre", j'avais tendances à me précipiter et ne prenais pas réelement le temps de comprendre correctement 
les outils que j'allais être amenée à utiliser, ce qui me vallais de très vite me perdre dans ce que je faisait et de me diciper et m'amener la plupart du temps à rester bloquer et à par conséquent à 
ne plus être aussi productive que je pensais l'être.
C'est pourquoi j'ai pris l'initiative pour mon stage de repartie sur des bases solides sans aucune précipitation, et pour ce faire j'ai tout d'abord décider de me consacrée une période de recherche 
les tout les dispositifs que j'allais etre amener à utiliser, seulement après avoir jugée que j'avais une comprehension assez "complète" de ce que je devais faire et utiliser, je pourrais passez la 
phase pratique à la réalisation de ce projet. Je vais ainsi segmenter l'explication du travail que je entrepris durant ce premier mois en 3 grand point. Je vais tout d'abors vous informer sur les 
recherches que j'ai entrepris et pourquoi, je vais ensuite vous présenter tout ce que j'ai pue faire lors de la phase pratique dans laquel je suis actuellement  et je finirais par vous présenter très
rapidement ou je me situerais dans l'avancer de mon projet ainsi que ce que je compte pour ce deuxième mois.

### Recherches 

Pour débuter correctement mon stage, j'ai tout d'abord tenu à me documenter un maximum tout d'abors sur les logiciel que je devrais utiliser, à savoir Vagrant et Virtualbox. Ces deux logiciel m'était 
jusqu'au début de mon stage totalement inconnu du fait que je n'ai jamais ,ni lors de mon apprentissage ni lors des projet semestrielle (SAE), été amener à les utiliser ou ne serais-ce à en prendre 
connaissance.J'ai ete amener lors de mes cours de système de sécurité reseaux et de virtualisation à travailler sur des machine virtuelles mais ai remarquer que ce que je faisait et ce que je fait 
actuellement pour mon sujet n'est pas enormement simmilaire, pour cause lorsque je travailler sur machines virtuelles lors de mes cours je travailler tout d'abords sur VMWare et non sur Virtualbox et 
j'avais une interface graphique ce qui n'est ici pas le cas. Pour me documenter correctement j'ai donc décider de tout d'aboord de lire un maximum d'article sur ces duecx logiciel afin d'en savoir le
plus possible, j'ai aussi consulté different forum informatique qui évoquer le sujet et pour vagrant ai biensur lu la "Vagrant Documentation" et j'ai enfin regarder de nombreuses vidéo pour essayer de
perfectionner au mieux mes connaissances.
Pour continuer j'ai entames mes recherches sur le projet MISP car étant dans l'optique a l'issue de mon projet de contribuer à ce grand projet avec la modification du dossier misp-vagrant, j'ai décider
d'en apprendre plus à ce sujet. Pour me document sur ce point j'ai tout d'abord comme énoncer précedement consulter de nombreux articles, ai directement consulté la docuementation MISP et enfin, ai
regarder quelques video sur le sujet, mais contrairement au point précédent j'ai ici aussi pris connaisance du code de ce projet.Bien que le code de projet soit assez colossale il m'a semblais tout de
même necessaiee d'en prendre connaissances afin d'en savoir le plus possible.
Pour poursuivre mes recherches j'ai decider de me pencher sur le bash et Unix scripting afin de m'améliorer dans ce language de programation, j'ai pour ce faire lu plusieurs articles et ai lus 
brievement quelques livre dont "beginning shell scripting" conseillé et fournis par mon tuteur de stage.
Enfin pour finir la partie concernant les recherches effectuer j'ai decider d'analyse de manière détailler l'intitulé de mon sujet en recherchant les mots qui me paraissais "clés" afin d'avoir une
meilleurs compréhension de ce qui m'était demander.


 

### Phases pratiques

Après m'etre correctemrnt documenter, il est maintenant temps de passer à la manipulation. En ce qui concerne mon sujet la première étape de ma phase de manipulation est le changement des fichiers de 
code présent dans le dossier misp-vagrant. Conformément aux propos précédents, j'ai commencé à utiliser VirtualBox à l'aide de Vagrant, puis ai continué par la modification des fichiers présents dans 
msip-Vagrant. Nous entrons maintenant dans le vif du sujet. Comme je vous l'ai expliqué au préalable, MISP est une plateforme de partage de connaissances au sujet des attaques et menaces informatiques,
misp-Vagrant lui va fournir une configuration pré-définie au déploiement de MISP et contribue à cette communauté en signalant des bugs tout en proposant des améliorations.
Les fichiers aux-quels je dois procéder à la modification dans le cadre de mon projet date aujourd'hui de plusieurs années déjà, l'évolution ces dernière années n'a fait que s'intensifier et plus 
partculièrement en informtique qui est un univers de connaissance en continuelle expension et avec toutes les avancées que l'on a faites, les nouvelles versions de tous les outils utilisés, les
fichiers que l'on a actuellement ennotre possession présentent un certain nombre d'erreurs. Je dois donc au cours de ces deux mois de stage sera de faire les modifications nécessaires afin qu'il n'y ait
plus d'erreurs, cela implique le changement, par exemple, des versions des outils installés. Si cela consistait simplement à changer les versions installées de différents outils, cela irait assez vite,
mais nous devons prendre en compte que la mise à jour de ces fichiers peut impacter d'autres fichiers qui y sont liés, et là est la complexité de ce projet. Il faut faire en sorte que tout concorde 
parfaitement.

Revenons aux compétences que je dois acquérir ou développer. Nous avons stipulé l'utilisation du bash et Unix scripting, mais je n'en ai pourtant toujours pas parlé depuis la description de ce que j'ai
pu faire depuis le début. Pourtant, c'est l'une des compétences que je suis amenée actuellement à utiliser le plus. Les fichiers présents dans le dossier MISP-Vagrant que je dois principalement modifier
sont exclusivement programmés en bash, et n'étant pas une experte dans ce langage de programmation, je me suis bien documentée et ai un peu lu quelques livres afin de consolider des connaissances.
Nous le savons, avoir des connaissances est très utile, mais savoir les utiliser correctement est mieux.

C'est donc après cela que les nombreux tests ont réellement commencé (même si bien évidemment des tests ont été préalablement faits afin de commencer à manipuler). J'ai tout d'abord commencé par
localiser les erreurs afin d'essayer de les neutraliser une à une. J'ai très vite compris qu'essayer d'éliminer les erreurs une à une sans prendre en compte le reste du code était une mauvaise idée,
car tout est lié, ce qui engendre que la simple modification d'une partie de code ne prenant pas en compte le reste du code engendre encore de nouvelles erreurs. Le travail est donc très minutieux et
complexe, ce qui explique que la modification des fichiers est l'étape qui prend le plus de temps.


Je dois essentiellment procéder à la modification de deuc fichiers, Vagrantfile, et bootstrap.sh. J'ai donc dans le fichier Vagrantfile tenterde  changer l'image afin d'avoir la version 20.04 de 
Ubuntu, chose j'ai réussi.Si vous êtes connaisseur au sujet des versions d'Ubuntu vous devez savoir que la dernière version est la 22.04 et cela semblerais plus logique d'installer la dernière version
mais comme je l'avais précédement stipulée il faut que les modification s'adapte au autres fichier dans le projet misp et la version 20.04 d'ubuntu est la plus préférable dans ce cas ci.
Passons maintenant à la modification du fichier bootstrap.sh ce fichier est bien plus long que le fichier Vagrantfile et necessite bien plus de modification car c'est à partir de ce fichier que la
configuartion est faite avec l'installation des outils leur lancement, leur configuartion et tout ce qui leur ai liée. J'ai donc essayer tout d'abors de compendre à quoi servais chaque bout de code et
ai commencer mes test en tenatnt de modifier tout ce qui se trouve dans cette liste 
- Modification de la version de python initialement installer avec essaie de l'intsallation de la version 3.4 , 3.5 , 3.6 , 3.7 et 3.8
- Modification du code permettant l'installation des modules de MISP 
- Modification du code permettant l'installtion de Mitre's STIX
- Modification du code permettant la configuartion de php par défaut
- Modification du code permettant la récuperation de CakePHP ainsi que du code le permettant pour MISP 



### Avancée et programme 
En ce qui concerne mon avancée je me situerais selon mon avis personnelle à la moitier de l'accomplissement de mon projet, car le fait de prendre connaissance de ces outils, de la manière de
programmner afin d'avoir toujours moins d'erreus et pour moi la phase la plus compliquer que je serais amener à faire lors de mon travail car elle demande une bonne maitrise et une bonne connaisance 
du code ainsi que des outils 
Après cette longue et difficile partie, nous pourrons passer à la documentation du code afin d'expliquer les modifications apportées et pourquoi elles ont été faites. Après avoir commenté l'ensemble de
ces fichiers, je pourrai enfin intégrer mon projet au grand projet open source MISP, et à ce moment-là, je  pourrais considérer que le projet est fini et surtout réussi.
En somme je ne pourrais pas dire que l'organisation que j'ai décider de mener pour le bon déroulement de mon stage est la meilleurs mais je peut dire qu'elle est la plus adaptée à mon cas et celle qui
me premtrra je l'espere de réussir mon projet dans de bonnes conditions 




# CONCLUSION

Mon ressenti après ce premier mois de stage et pour ma part très positive et ceux pour plusieurrs raison. Tout d'abors cela m'a permis découvrir le monde du travail dans le domaine dans lequel 
je fait mes etudes et ayant déja par le passée fait des jobs étudiant, j'ai resentis une réel différences entre ces deux monde. Le fait de travailer dans un domaine dans lesquels nous avons cummuler
un certaun nombre de connaissance que l'ont peut ainsi utiliser a bon ecscient est extremement gratifiant et encourangeant. Le fait d'apprendre de nouveaux logiciel et de participer à l'élaboration
projets "réel" dans le sens ou l'entreprise qui m'acceuil souhaite un résultat est un challenge qui me pousse par conséquent à me surpasser même si cela peut etre compliquer. Enfin tout cela est
appuyer par le fait que j'ai eu la chance de me retrouver au miilieu d'une équipe très agréable avec des collègues qui n'hésite pas de temps en temps à venir voir ce que je fait et en me proposant 
leur aide si besoin, de plus une partie des ces personne ne parle ps francais mais exclusivement anglais ce qui pousse donc par moment à améliorer mon anglais tout en ayant de l'aide à la réalisation
de mon travail. C'est pourquoi je peut conclure que ce premier mois de stage en entreprise se passe très bien pour ma part. 



























