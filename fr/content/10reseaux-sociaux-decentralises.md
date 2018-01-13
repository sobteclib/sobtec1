# Décentralisation et réseaux sociaux

***Hellekin***

![](media/descentralised-soc-net.png)

Encore largement inconnu du public il y a deux décennies, le terme de « réseau
social » apparaît aujourd'hui comme une innovation du *Web
2.0* [^1]. Toutefois il s'agit d'un concept
bien antérieur au phénomène de concentration mercantile des instruments dédiés
aux réseaux sociaux. En 1933, le sociologue Jacob Levy
Moreno [^2] introduisit le sociogramme, une
représentation graphique des relations interpersonnelles où chaque nœud est un
individu et chaque lien une relation sociale. Le terme de « réseau social »
apparut pour la première fois en 1954 dans un article du professeur John
Arundel Barnes [^3], concluant son étude des
relations sociales dans un village de pêcheurs Norvégiens.

Howard Rheingold [^4], pionnier des
communautés virtuelles et chroniqueur visionnaire des changements sociaux liés
à l'évolution des technologies de l'information et de la communication
souligne comment « *certaines personnes confondent les réseaux sociaux, qui
sont l’agrégat des relations humaines, avec les services en ligne pour les
réseaux sociaux tels Facebook et, sans doute, G+ *». Une telle confusion
établit le service comme origine du réseau social, même si son rôle se limite
au-mieux à en faciliter l'émergence.

### Réseau centralisé, décentralisé, distribué ?

Ces concepts ont évolués depuis l'article de Paul
Baran [^5] consacré aux diverses topologies
de réseaux de communication [^6]. Les
caractérisations suivantes en offrent une vue plus sociale que technique.

On dit qu'un réseau est centralisé lorsque son intégrité dépend d'un acteur
sans lequel le réseau ne fonctionne pas. Une telle architecture offre de
nombreux avantages pour l'intégration verticale des services, notamment en
raison du pôle de décision unique et de l'uniformité de la solution
technique. Ce modèle combine simplicité d'utilisation, facilité de
développement et stabilité du système; en revanche il impose une position
unique du prestataire de service lui permettant d'observer ses utilisateurs et
analyser leur comportement. Il offre donc peu ou prou de protection ou de
considération pour le droit à la privauté de ses utilisateurs.

Un réseau décentralisé ne dépend pas d'un pôle unique de décision, mais chaque
membre du réseau n'est pas nécessairement autonome, et peut dépendre de la
disponibilité d'un serveur qui le relie au reste du réseau; la fédération est
le modèle typique du réseau décentralisé, tels le courrier électronique ou les
réseaux de *chat [^7]*. Ce modèle est parfait
pour des organisations qui peuvent maintenir leur propres infrastructures de
communication et préfèrent contrôler leurs communications. Mais il présente la
même problématique qu'un réseau centralisé concernant le rôle de
l'intermédiaire-tout-puissant (en termes de sécurité informatique, le « *man
in the middle* »).

Lorsque chaque nœud du réseau décentralisé est autonome, on parle de réseau
distribué: c'est le modèle de pair-à-pair (P2P) comme
Bittorrent [^8],
GNUnet [^9],
Tor [^10],
I2P [^11],
cjdns [^12] ou
Bitcoin [^13]. Ce modèle est le plus robuste
face à l'agression d'un pouvoir centralisé (observation, censure,
manipulation), car il n'offre pas de prise directe ni de cible particulière,
il ne dispose pas de « point unique de défaillance » contrairement aux modèles
sus-cités. En revanche sa réalisation est bien plus difficile qu'un service
centralisé, notamment en raison de l'hétérogénéité et la complexité de
l'environnement.

Ces architectures ne sont cependant pas forcément
opposées [^14]. La contradiction entre elles
réside plutôt dans la décision de protéger la privauté des utilisateurs ou au
contraire établir leur surveillance. L'approche dominant actuellement les
instruments pour les réseaux sociaux dépend radicalement de la surveillance
des utilisateurs et par conséquent recherche une architecture centralisée et
propriétaire, favorable à leur contrôle.

Il ne faut pas non-plus confondre la capacité « d'exporter » des données avec
leur « portabilité » ni leur disponibilité. L'exportation de données d'un
service ou d'une application fonctionne le plus souvent en cercle
fermé. Aliénées de leur contexte, ces données exportées ne sont plus qu'un tas
de fichiers inertes car c'est leur inscription au sein d'un contexte social
qui leur donne vie (leur connexion avec des données similaires ou relatives,
les commentaires d'autres utilisateurs, l'enrichissement des connaissances par
la conversation incessante génèrent une interdépendance entre des sources
diverses.)

Ainsi, au-delà d'un découpage technique souvent abstrait et incomplet
considérant seulement un aspect formel du réseau, il convient de reconnaître
les fondements et la complexité des conséquences éthiques, sociales,
politiques et économiques des technologies qui supportent la sociabilité des
individus et des collectivités.

### Que faire?: **Logiciel libre et réseaux libres**

L'Apocalypse selon Snowden (ses révélations fracassantes sur la NSA) confirme
ce que les programmeurs de logiciel libre martèlent depuis 30
ans [^15]. Pour considérer la sûreté d'un
système il est impératif que celui-ci soit observable. Un système
non-vérifiable est en effet par définition un simple acte de foi en son
créateur comme prévenait déjà très justement Ken Thompson en
1984 [^16]. Un système informatique dont on
ne peut pas étudier le code source ne peut donc pas être considéré comme
sécurisé [^17].

Le logiciel libre [^18], au sens donné par
la *Free Software Foundation [^19]* et le
projet GNU [^20], signifie que son
utilisateur dispose de quatre libertés fondamentales: 0) utiliser le logiciel
selon sa propre volonté ; 1) étudier le fonctionnement du logiciel (à travers
son code source) ; 2) partager le logiciel librement, y compris le
commercialiser ; 3) modifier le logiciel selon ses propres besoins et
distribuer ces modifications librement. Ces quatre libertés fondamentales
permettent à l'utilisateur l'appropriation libre des logiciels, c'est-à-dire
leur contrôle ; cela favorise ainsi l'évaluation du code entre pairs, au même
titre que les travaux scientifiques. Il s'agit donc de logiciel éminemment
politique, développé dans le sens de l'intérêt général.

Le champ du logiciel libre offrant des alternatives aux plate-formes
propriétaires reste encore largement expérimental. Mais son effervescence
montre la viabilité de pouvoir compter sur des outils de gestion des réseaux
sociaux qui ne soient ni propriétaires ni liberticides. Qu'elles soient
héritées du Web, et orientées vers une décentralisation fédérée, ou bien
héritées du pair-à-pair (P2P), visant un modèle plus distribué entre nœuds
autonomes, ces initiatives s'opposent par définition à la surveillance des
utilisateurs et encouragent leur liberté.

Le projet GNU consensus [^21] vise à
favoriser et coordonner le développement de logiciel libre à caractère
social. Considérant qu'une entité
hostile [^22] participe activement au
réseau, le projet recommande que chaque nœud du réseau puisse se prémunir
contre cette menace, et protéger également ses correspondants légitimes. Dans
ce cadre, la plupart des alternatives actuellement disponibles offrent peu de
protection contre les attaquants les plus sophistiqués. Cependant, elles
permettent une transition nécessaire depuis les plate-formes propriétaires qui
elles, sont compromises par définition, puisqu'elles participent de la
surveillance globale.

Le chiffrement systématique des données et la protection du graphe social (les
interactions sociales de chacun) forment partie des éléments nécessaires à une
alternative solide et viable. GNU consensus promeut l'adoption à long terme de
la plate-forme de pair-à-pair GNUnet [^23],
et son complément pour les réseaux sociaux nommée
Secushare [^24], encore en phase de
recherche.

En attendant la disponibilité de GNUnet pour le grand public, le projet
s'attache aussi à identifier les solutions susceptibles de faciliter l'exode
des usagers de services propriétaires vers des solutions libres.  Il faut
noter que si ce projet considère GNUnet comme la référence vers laquelle
tendre, il n'exclut pas la diversité des approches. Ainsi, le projet promeut
également des logiciels qui offrent une solution partielle et tente
d'identifier leurs limitations et reconnaître leurs avantages.

La section suivante offre une vue partielle des problématiques envisagées et
des solutions alternatives possibles. Le site du projet GNU consensus offre
une vue plus élaborée et actuelle. Le lecteur peut également se référer à la
liste collaborative maintenue sur le site de Prism
Break [^25] qui offre une correspondance
entre les applications et services propriétaires et les alternatives libres
correspondantes.

### Problématiques et alternatives émancipatrices

**Publication** La forme la plus courante de publication personnelle reste le
blog, et les commentaires tissent des conversations riches au sein de
la « blogosphère » ; le wiki offre également une forme de publication
collective dont l'aspect social est plus discret. Cependant ces deux formes
concernent des communautés plutôt spécialisées et littéraires. D'autre part
elles concernent principalement des interactions publiques.

**Exhibition et rumeur** Facebook est l'exemple le plus connu pour le partage
de ses expériences sociales. Twitter a su combiner la brièveté des SMS avec le
Web pour créer l'un des services les plus populaires et addictifs du
Web. Google+ offre un intermédiaire entre les deux...

La « monétisation » des profils et l'appropriation mercantile des contenus
dépend de la propension des utilisateurs à s'exposer eux-mêmes à la machine de
surveillance en troquant un avantage perçu contre une soumission trop
abstraite, oublieux des conséquences: exhibitionnisme à outrance, délation
banalisée, mise en esclavage volontaire, diversion du capital social vers des
circuits capitalistes superflus. Les conséquences de l'amplification des
conversations au-delà des simples prémisses du « que fais-tu en ce moment ? »
permet la capture d'une grande part de la sociabilité des réseaux à tel point
que nombre des utilisateurs de Facebook confondent aujourd'hui le service avec
« l'Internet ».

Les « clones de Twitter » restent largement incompatibles avec l'original
selon la volonté politique de l'entreprise, mais travaillent à
l'interopérabilité: parmi eux on trouve GNU
social [^26],
Friendica [^27],
Pump.io [^28]. Une solution distribuée
utilisant la même technologie que Bitcoin est également en phase
expérimentale: Twister. [^29]

**Conversation et organisation collective** La plupart des solutions
alternatives existantes se présentent sous forme de silos incompatibles entre
eux. Ces solutions dépassent cependant le motif de la logorrhée pour proposer
des moyens d'organisation collective. On peut citer parmi elles
Elgg [^30] et
Lorea [^31],
Crabgrass [^32],
Drupal [^33], et le Web
Indépendant [^34] qui fait figure à la fois
de pionnier dans la définition et l'adoption des standards du Web Sémantique
et de résistant à la tendance centralisatrice des marchands.

**Téléphonie et vidéoconférence** Skype est passé, depuis son rachat par
Microsoft, dans l'escarcelle des collaborateurs directs de la NSA.  Google
Hangouts n'est accessible qu'aux utilisateurs de Google. Dans les deux cas, on
pourra utiliser avantageusement l'alternative de
Jit.si [^35], ou attendre l'arrivée du
Project Tox [^36].

**Messagerie** Le courrier électronique reste l'une des applications les plus
répandues. L'usage de GnuPG permet de chiffrer les messages mais ne protège
pas la source, le destinataire, ni le sujet du message (le projet
LEAP [^37] cherche à solutionner cet
aspect.) La domination de Google sur ce service avec Gmail et GoogleGroups
réduit considérablement son aspect fédératif. En attendant d'utiliser des
solutions spécialisées comme Pond [^38],
I2P-Bote [^39], ou BitMessage, il est
recommandé d'utiliser un service de courriel autonome favorisant la privauté,
tel Riseup [^40] ou
Autistici [^41], ou monter son propre
serveur.

**Partage de vidéos** La suprématie de Youtube (encore Google) en la matière
laisse tout ses concurrents loin derrière. Étant donné l'énorme infrastructure
nécessaire pour le traitement et l'envoi de fichiers vidéos, ce service n'a
que peu d'alternatives.
GNU MediaGoblin [^42] permet à un site de
gérer ses médias et supporte les formats libres de vidéo. Un nouveau projet,
Wetube, promet d'innover et remplacer Youtube par un réseau distribué
utilisant une approche similaire à Twister basée sur une chaîne de blocs, et
offrir aux participants la carotte d'une rémunération correspondant à la bande
passante partagée.

**Partage de musique** La référence propriétaire reste SoundCloud. Il semble y
avoir peu d'intérêt pour fournir une alternative libre à ce service. GNU
MediaGoblin supporte aussi les fichiers audios et pourrait tenir ce rôle. Les
amateurs de musique, eux, peuvent utiliser Bittorrent en faisant attention de
télécharger des torrents légaux et d'éliminer de leurs connexions les nœuds
spécialisés dans la chasse aux internautes ou la dissémination de pourriciel
grâce à des listes de blocage (*blocklists*).

### Autres exemples pertinents pour imaginer de futures applications et implications

**Applications statiques** Le projet
UnHosted [^43] propose de renouer avec la
décentralisation des applications Web en séparant l’exécution du code des
données affectées. Celles-ci restent sous le contrôle de l'utilisateur, et les
applications sont exécutées dans le navigateur et non sur un serveur.

**Partage de code** Github offre un contre-exemple de service propriétaire
social. Sa contribution au monde du logiciel libre montre qu'il est possible
de trouver une niche dont l'exploitation commerciale ne passe ni par la
commercialisation des données des utilisateurs ni par aucune restriction à
leur liberté. Il dispose cependant de deux concurrents sérieux, Gitlab et
Gitorious, et il existe même une version P2P, Gitbucket. Le code source de
Gitlab et Gitbucket est disponible sur Github ! Le modèle de Github peut
servir d'inspiration pour « le communisme entrepreneurial » proposé par Dmytri
Kleiner [^44].

**Jeux vidéos en ligne massivement partagés** Les
MMORPGs [^45] sont aussi des lieux de
rencontre et de sociabilité. S'il est plus simple de converser des choses de
la vie sur Second Life, les relations sociales fleurissent sur World of
Warcraft ou MineCraft. Il reste que ces mondes virtuels génèrent une économie
et une frange de société premier-monde qui leur sont propres. Ce sont des
lieux où l'anonymat n'est pas un problème, mais presque une obligation: qui
veut savoir que le grand mage Krakotaur passait sa jeunesse à perforer des
cartes pour le donner à manger à un ordinateur de la taille d'un hall de
palace ? Si le cœur vous en dit, vous pouvez toujours rejoindre
PlaneShift [^46] ou les univers de
développement de CrystalSpace [^47] pour
imaginer l'avenir des jeux immersifs libres.

### Conclusions

Le grand défi des réseaux libres rejoint celui du logiciel libre: celui de
l'autonomie et de sa pérennité. Le soutien financier des développements d'une
part, et le marketing des solutions d'autre part se trouvent au cœur des
problématiques qui limitent leur autonomie.  L'infrastructure nécessaire à la
libération des citoyens internautes doit prioritairement venir des
utilisateurs eux-mêmes. Elle peut devenir autonome pour autant que ses
utilisateurs la prennent en charge, comme ils prennent en charge d'autres
ressources nécessaires à la préservation de la communauté. Le développement
durable et la disponibilité d'une infrastructure publique et sociale de
communication ne peut émerger que si la souveraineté technologique est perçue
comme un bien commun par une masse critique de participants.

L'omniprésence du tout-gratuit cache les capitaux colossaux investis par les
entreprises pour capturer leurs audiences. Le tout-gratuit est une manière de
tuer la compétition dans l'œuf: car seuls peuvent participer à ce jeu ceux qui
disposent déjà de larges réserves financières.  Pourtant, après les
révélations de Snowden exposant l'étendue de la surveillance globale, on peut
voir certaines conséquences dans l'évolution des habitudes d'usage des outils
de recherche [^48] ou dans le renouveau
d'attention portée par certaines institutions aux alternatives logicielles
libres. Cette tendance doit s'accompagner d'une prise de position de la part
des utilisateurs eux-mêmes dans leurs choix technologiques, matériels et
logiciels, et dans leur décision de supporter les efforts de développements
alternatifs.

La campagne annuelle de financement de Wikipedia annonce que si chaque
personne lisant son annonce contribuait seulement trois dollars, elle serait
terminée en deux heures ! C'est cette réalisation de la puissance des grands
nombres qu'il nous faut rencontrer pour achever une vision démocratique de
l'Internet libre et public. Si le citoyen pris dans son isolement d'individu
ne dispose généralement pas de larges sommes, des campagnes de *crowdfunding*
(financement par la foule) permettent de capitaliser instantanément les fonds
nécessaires à une entreprise donnée.

Le *crowdfunding* reste cependant une forme d'allocation des ressources qui
appartient à la consommation: le « financeur » est un fait un acheteur qui
paie par avance le produit qui lui est proposé. Au contraire, une telle
campagne devrait être un investissement afin de renforcer l'infrastructure
publique générée. C'est l'argument développé par Dmytri Kleiner dans le
Manifeste Télécommuniste. Chaque communauté devrait pouvoir gérer son propre
investissement, comme le proposait déjà en 2009 le projet Lorea.

Certes les choix des technologies à supporter dépend d'une élite apte à
l'analyse technique, et les innovations scientifiques sont permanentes. Mais
le choix éthique ne dépend pas de la compétence technique. Si les techniciens
connaissent l'orientation éthique d'une communauté, ils devraient être
capables de la prendre en compte dans leur analyse. La surveillance globale
est apparue parce qu'elle est techniquement possible, et parce que ce choix
technique s'est effectué sans restriction éthique ni légale, en toute
impunité.

Logiciel libre, services décentralisés, distribués, reproductibles et
communautaires, nœuds autonomes, participation et investissement sont les clés
d'une infrastructure de communication publique, durable et saine, susceptible
non-seulement de préserver la vie privée des citoyens, protéger la liberté des
individus et des peuples en lutte contre des régimes totalitaires, sinon
également de fournir les bases de la démocratie du XXI^ème^ siècle pour
adresser ensemble, dans la pluralité et la diversité des situations
individuelles et collectives, les immenses problématiques planétaires
auxquelles nous sommes tous confrontés. L'avenir des réseaux sociaux commence
à leur source: c'est-à-dire nous-mêmes.

------------------------------------------------------------------------

**Hellekin:** Responsable officiel du projet GNU consensus. Développeur à
temps perdu, activiste à temps plein, il navigue sur les réseaux et les
continents à la recherche de solutions pour l'émancipation et le bien-être de
l'espèce humaine suivant ses idéaux libertaires. Depuis sa base en Amérique
Latine, il contribue à forger une infrastructure publique et communautaire des
réseaux de communication électroniques pour défendre et valoriser les
initiatives locales et décentralisées.  GnuPG: 0x386361391CA24A13

------------------------------------------------------------------------

[^10]: https://fr.wikipedia.org/wiki/Tor_!%28r%C3%A9seau%29

[^11]: https://fr.wikipedia.org/wiki/I2P

[^12]: http://cjdns.info/

[^13]: https://fr.wikipedia.org/wiki/Bitcoin

[^14]: Un service centralisé fait souvent usage de la distribution au sein de sa propre infrastructure pour en assurer l'extensibilité à grande échelle.

[^15]: La FSF fête en 2014 le trentième anniversaire de sa création.

[^16]: Thompson, Ken (1984) “*Reflections on Trusting Trust*”, URL: http://cm.bell-labs.com/who/ken/trust.html (Noter l'usage tendencieux du terme 'hacker' dans son acception maligne, et comment ces réflexions s'appliquent aujourd'hui aux abus des agences de renseignement.)

[^17]: La complicité des géants du logiciel propriétaire dans la surveillance globale effectuée par la NSA devrait rendre ce point tout à fait indubitable.

[^18]: Stallman, Richard (1996), “Qu'est-ce que le logiciel libre ?”, URL: https://gnu.org/philosophy/free-sw.fr.html

[^19]: http://www.fsffrance.org/

[^1]:Le Web 2.0 est un concept marchand inventé pour qualifier l'apparition de sites interactifs à caractère social. Le « 2.0 » ne représente ici aucun caractère technique, mais recherche l'empreinte de l'obsolescence de l'existant, c'est-à-dire le Web original, pair-à-pair et décentralisé.

[^20]: https://gnu.org/home.fr.html

[^21]: https://gnu.org/consensus

[^22]: Hors-la-loi: criminels et spameurs, agences de renseignement, corporations et gouvernements totalitaires, etc.

[^23]: https://gnunet.org/

[^24]: http://secushare.org/

[^25]: http://prism-break.org/fr/

[^26]: https://gnu.org/s/social/

[^27]: http://friendica.com/

[^28]: http://pump.io/

[^29]: http://twister.net.co/

[^2]: https://fr.wikipedia.org/wiki/Jacob_Levy_Moreno

[^30]: http://www.elgg.org/

[^31]: https://lorea.org/

[^32]: https://we.riseup.net/crabgrass

[^33]: https://drupal.org/

[^34]: http://indiewebcamp.com/

[^35]: http://jit.si/ pour le service, et http://jitsi.org/ pour le logiciel.

[^36]: http://tox.im/ vise le remplacement de Skype par une solution libre.

[^37]: https://leap.se/fr

[^38]: https://pond.imperialviolet.org/

[^39]: https://fr.wikipedia.org/wiki/I2P#Optionnelles

[^3]: Barnes, John (1954) “*Class and Committees in a Norwegian Island Parish*”, dans Human Relations, (7), pp 39-58.

[^40]: https://help.riseup.net/fr/email

[^41]: http://www.autistici.org/fr/

[^42]: https://gnu.org/s/mediagoblin

[^43]: https://unhosted.org/

[^44]: Kleiner, Dmytri (2010), “Le manifeste télécommuniste”, URL: http://telekommunisten.net/the-telekommunist-manifesto/ • http://translatedby.com/you/the-telekommunist-manifesto/into-fr/trans/

[^45]: MMORPG: Massively Multiplayer Online Role Playing Games, ou jeux massivement multi-joueurs en ligne.

[^46]: http://www.planeshift.it/

[^47]: https://fr.wikipedia.org/wiki/Crystal_Space

[^48]: StartPage, Ixquick et DuckDuckGo ont vu multipliée par 5 l'affluence à leurs moteurs de recherche suite aux différents articles parus notamment dans Der Spiegel et The Guardian en décembre 2013.

[^4]: https://fr.wikipedia.org/wiki/Howard_Rheingold

[^5]: https://fr.wikipedia.org/wiki/Paul_Baran

[^6]: Baran, Paul (1962) “*On Distributed Communications Networks*”, présenté lors du premier congrès des sciences des systèmes d'information, organisé par MITRE

[^7]: Le « bavardage », rendu possible par le faible coût des communications numériques se pratique par exemple grâce aux protocoles *Internet Relay Chat* (IRC) et *eXtensible Messaging Presence Protocol* (XMPP), bien avant l'apparition d'applications propriétaires et restreintes comme MSN ou Facebook *chat*.

[^8]: https://fr.wikipedia.org/wiki/BitTorrent_%28protocole%29

[^9]: https://fr.wikipedia.org/wiki/GNUnet

