# Du hardware libre aux technologies réappropriées

***Elleflâne***

Le concept de hardware est assez nouveau, très large, en perpétuelle
rénovation et radicalement différent de celui du logiciel. Il existe une large
controverse sur ce qu'il est et sur ce qu'il n'est pas, et en l'absence d'une
définition approuvée de tous, chacun l'interprète à sa façon. Par exemple,
pour moi, le hardware va du composant électronique, du condensateur, du
transistor, du led, du circuit intégré, d'un artefact jusqu'au velo-charrue,
de la description d'un processus industriel jusqu'à la fabrication d'une
brique réfractaire, un ordinateur, une imprimante 3D, un mécanisme pour
l'épuration de l'eau écrit en code source ouvert, un processus de recyclage de
plastique, la création d'une fraiseuse CNC, une méthode d'analyse de terres
contaminées grâce à des capteurs ou le code d'un microcontrôleur.

Mais si nous adoptons une vision plus arrêtée, nous pouvons dire que
l'histoire du hardware libre est parallèle à celle de l'informatique. En 1970,
le Homebrew Computer Club [^1] s'est avéré être un hybride composé par le
mouvement radical étudiant, par des entrepreneurs du domaine informatique de
la communauté de Berkeley et par des amateurs de l'électronique. Il est
ironique de voir comment bon nombre de ces garages regorgeant autrefois de
créativité sont aujourd'hui des musées, comme le Bill Hewlett et Dave Packard,
qui ont géré le premier dispositif HP.

Dans les années 90, de la même manière que les programmes de logiciels
pouvaient être interchangeables, les FPGA [^2] permettaient également
l'échange électronique de conceptions libres. L'Open Design Circuits [^3],
lancée par Reinoud Lamberts, est la première communauté Web à avoir créé un
hardware libre dans l'esprit des logiciels libres. Et même s'il n'existait
aucun logiciel libre adéquat pour la conception électronique, ce portail a
impliqué de nombreuses personnes qui ont assis les bases pour une communauté
plus large.

En 2002, le "Challenge to Silicon Valley" [^4], lancée par Kofi Annan, a
introduit plusieurs projets de développement de hardware en mettant en avant
la nécessité de développer des technologies adaptées aux différentes réalités
socioculturelles et économique. Cette ligne de développement des technologies
s'est également associée à la lutte mondiale contre la brèche numérique à
travers les initiatives de ICT4Development. Celles-ci ont été en général le
résultat de partenariats entre l'académie et les organisations du secteur
tertiaire pour implanter des technologies adaptées aux besoins des pays
définis de manière erronée comme "en développement".

Toutefois, aujourd'hui encore, le panorama de la production de hardware est
essentiellement marqué par les limites imposées par les brevets industriels et
la propriété industrielle [^5]. Celles-ci sont l'ensemble de droits que
possède une personne physique ou morale sur une invention. Elles accordent
deux types de droits: le droit à utiliser l'invention, la conception ou le
signe distinctif, et le droit à en interdire l'accès à un tiers. Le droit
d'interdire (*lus prohibendi*) permet au titulaire du droit de demander le
paiement d'une licence, appelée redevance ou royaltie, qui possède des limites
temporelles et territoriales.

## Hardware libre: jusqu'où et de quelle manière?

Toutes les étapes suivantes doivent faire partie de la mise en place de
hardware libre: une conception, un processus de fabrication, des matières
premières, une distribution, un modèle d'activité, un entretien, une mise en
œuvre, une reproduction, une force de travail, un accès à la documentation et
à la technique de fabrication. Partant de ce contexte, si nous tentons de
définir ce qu'est le hardware libre, nous devons comprendre comment les étapes
de production additionnées aux types de résultats tangibles possibles peuvent
être interprétés par des licences libres.

Richard Stallman lui-même [^6], président de la Free Software Foundation [^7]
et créateur de la licence GNU GPL [^8] qui garantit les 4 libertés suivantes
(liberté d'utilisation, d'étude et de modification, de distribution et de
redistribution des versions modifiées), affirme que *"les idées du logiciel
libre peuvent être appliquées aux archives ou aux fichiers nécessaires à leur
conception et à leur spécification (schémas, PCB, etc.), mais non au circuit
physique en soi" [^9].

Il convient également de noter qu'il existe le hardware statique, composé par
les éléments tangibles des systèmes électroniques et le hardware libre
reconfigurable, décrit grâce à un langage de description composé par des
fichiers de texte qui contiennent le code source. De ce fait, les mots
"hardware libre" et "conception de hardware libre" sont deux choses
différentes. La conception et l'objet physique ne peuvent se confondre bien
qu'ils se fondent parfois l'un dans l'autre.

Tous ces facteurs entraînent une confusion lorsqu'il faut définir de quelle
façon le hardware libre l'est vraiment. S'il est certain que chaque composant
et chaque étape de production peuvent s'adapter aux quatre libertés
spécifiques du logiciel libre, il convient également de dire qu'aujourd'hui
aucun projet ne peut englober toute la chaîne depuis le strictement
libre. Nous utilisons donc actuellement le terme de hardware libre/open
hardware sans avoir à appliquer les quatre libertés de manière restreinte dans
tous ses domaines. Il existe de nombreuses initiatives consolidées dans ce
domaine, bien que les modèles d'utilisation et de rapprochement soient
différents selon les motivations sociales, économiques et politiques de chaque
collectif ou communauté derrière leur développement.

Une multitude de licences différentes tentent de clarifier ces questions. Par
exemple, le Free Hardware Design [^10], est un concept qui peut être copié,
distribué, modifié et fabriqué librement. Cela ne veut pas dire que la
conception ne peut être vendue, ou que toute les pratiques de conception du
hardware soient libres de coût. Le Libre Hardware Design est comme le free
hardware design, mais il éclairci le fait que le mot libre se réfère à la
liberté et non au prix. Pour l'Open Source Hardware [^11], toute l'information
de conception est à la disposition du public en général, et elle peut se baser
sur du free hardware design ou sur une conception restreinte d'une certaine
manière. L'Open hardware [^12], une marque enregistrée par l'Open Hardware
Spécification Program, s'avère être une forme limitée de Open Source Hardware,
dans la mesure où la seule exigence est de mettre à disposition une quantité
d'informations restreintes concernant la conception pour pouvoir par exemple
procéder à une réparation. Enfin, en guise de synthèse, Patrick McNamara
définit pour l'Open Hardware les niveaux d'ouverture suivants:

1. Interface ouverte: l'utilisateur dispose de toute la documentation
lui permettant de savoir comment une pièce de hardware libre doit
remplir la fonction pour laquelle elle a été conçue.

2. Conception ouverte: la documentation disponible est suffisamment
détaillée pour qu'un tiers puisse créer un dispositif fonctionnel et
compatible.

3. Mise en œuvre ouverte: met à disposition la liste de tous les
matériaux nécessaires à la construction du dispositif.

Comme les licences spécifiques pour hardware libre sont encore en
développement, le panorama actuel est marqué par une grande variété.  Certains
groupes utilisent la GNU GPL [^13] comme le Free Model Foundry [^14] qui
permet la simulation de modèles, de composants et de vérification, ESA Sparc
[^15] qui développe une CUP pour 32 bits ou Opencores [^16], une communauté
qui développe des IP cores. D'autres groupes utilisent la licence Open Source
initiative du MIT [^17] comme le Free-IP Project [^18] et LART [^19]. Quant à
la licence GNUBook [^20], elle se base sur la licence GPL mais avec des ajouts
qui concernent les droits environnementaux et humains.

Il existe également des groupes qui développent de nouvelles licences comme la
Simputer GPL [^21], la Freedom CPU [^22], l'OpenIPCores [^23], l'OHGPL [^24],
l'Open NDA [^25], l'OpenPPC [^26] (basée sur l'Apple Public Source Licence) et
la Hardware Design Public Licence [^27] du groupe Open Collector [^28]. Parmi
celles-ci, nous distinguons la licence Hardware du Cern OHL [^29] écrite à
l'origine pour les conceptions du CERN (Accélérateur de Particules) logées
dans le Dépôt Open Hardware.

## Modèle d'activité et durabilité dérivées du hardware libre libre

Selon le magazine Wired, une bible du techno-positivisme, l'Open Hardware
devient une "commodity", à savoir une marchandise. Même s'il n'existe pas
encore un modèle clair d'activité, il est sous-entendu qu'il peut répondre à
des niches de marché qui jusqu'alors n'ont pas été couvertes, en appliquant la
logique de la "long tail" ou large queue de distribution de biens et de
services (du style Amazon) à la dimension quasi infinie du
hardware. Concernant la commercialisation, la conception de hardware libre
peut être mise en œuvre par une entreprise et ensuite être commercialisé, la
seule contrainte est de conserver une conception libre.

En 2010, Torrone et Fried [^30] ont compilé 13 exemples de compagnies qui
vendaient du Hardware Open Source et qui facturaient, toutes réunies, 50
millions de dollars. À l'heure actuelle, il existe plus de 200 projets de ce
type et l'on prévoit que la communauté de Hardware Open Source facturera 1000
millions de dollars en 2015. Adafruit [^31], Arduino [^32], Chumby [^33],
Liquidware [^34] et Makerbot [^35] ont respectivement des bénéfices qui
atteignent plus de 1 million de dollars. Tout cela démontre qu'il existe de
réelles possibilités de générer des gains économiques avec des projets basés
sur une activité ouverte et partagée avec la communauté. Ce qui est moins
clair, c'est: Est-il possible d'envisager une réelle politique anticapitaliste
basée sur un projet économique et de redistribution des biens en lien avec des
logiques de durabilité et de décroissance?

Il existe un modèle de durabilité intéressant pour l'Open Hardware qui réside
dans le crowdfunding [^36] et qui consiste à recevoir de petites quantités de
donations/travail d'individus ou groupes pour initier un projet. Huynh et
Stack ont créé par exemple, l'Open Source Hardware Reserve Bank [^37] pour
couvrir les coûts associés aux révisions continues du hardware libre durant le
processus de conception estimés à près de 40% du budget initial nécessaire. Le
projet cherche à réduire les risques pour que les projets de hardware libre
puissent passer à la phase de production. Enfin, ils facilitent également
l'expérimentation en permettant la construction et la distribution de petites
quantités de produits considérés comme "non évolutifs" étant donné "qu'une
mauvaise idée d'activité" est différente "d'une mauvaise idée de hardware
libre".

Le Open Money est un autre exemple. Il permet simplement aux hackers et non à
des investisseurs de capital-risque ou à d'autres compagnies d'investir dans
des projets spécifiques en dupliquant le nombre de pièces produites et en
réduisant leur coût unitaire entre 10 et 30%.  Une communauté peut également
autofinancer ses projets grâce au microcrédit. Open Money [^38] et
Metacurrency [^39] proposent par exemple de nouveaux formats de monnaie et
cherchent à promouvoir l'union de monnaies existantes avec des certificats de
microcrédit.

Enfin, l'Open Design Manifeste [^40] unit deux tendances. D'un côté, les
personnes offrent leur savoir-faire et leur temps à des projets pour le bien
commun, qui ne reçoivent généralement pas de soutien par manque d'intérêt
commercial. De l'autre, il fournit un cadre pour le développement de projets
et de technologies avancées qui pourraient aller au-delà des ressources de
quelque entreprise ou pays que ce soit et impliquer des personnes qui, sans le
mécanisme copyleft, ne pourraient collaborer d'une autre façon.

Voyons maintenant quelles sont les problématiques liées à la durabilité du
hardware libre.

D'une part, l'absence de consensus concernant la propre définition du hardware
libre est extrapolée aux possibles modèles d'activités. Un dispositif ouvert
est différent de ce qui existe et prédomine sur le marché dans la mesure où ce
qui est important ce n'est pas le produit fini (hardware manufacturé), mais
les activités intangibles, l'information relative à la conception du hardware
qui s'ouvre à l'utilisation publique. D'autre part et comme nous l'avons vu
antérieurement, les quatre libertés du logiciel libre ne peuvent être
complétement appliquées au hardware , au vu de leur nature différente.  L'un a
une existence physique et l'autre non. De ce fait, une conception physique est
unique et sa répartition dépend de sa facilité de reproduction.

De plus, il existe une dépendance technologique envers les composants importés
qui peut se traduire par: les chips sont-ils disponibles? De ce fait, il
existe des modèles d'exclusion étant donné que toute personne n'est pas
capable de réaliser un hardware libre, dû aux implications causées par le type
d'infrastructure nécessaire. La personne qui souhaite utiliser le hardware
libre conçu par une autre personne, doit le fabriquer en achetant les
composants nécessaires et en reconstruisant le design. Tout ceci a un
coût. Conséquence logiques, seules quelques entreprises possèdent cette
connaissance, et la gardent jalousement pour que les personnes restent de
simples consommateurs de produits.

## Les modèles de production différenciés

Nous observons deux modèles conventionnels de production/distribution.  D'une
part, le modèle basé sur la fabrication centralisée, avec un même produit
disponible dans de nombreux lieux, permettant d'augmenter le prix final au
consommateur. D'autre part, un système de fabrication distribuée basée sur un
nombre de petits groupes indépendants qui produisent le même design pour le
distribuer localement. Pour que les deux modèles soient durables, les
initiatives de hardware libre ont besoin de plates-formes qui regroupent et
permettent le contact entre les moyens de production et les personnes qui
souhaitent créer.

Par rapport au modèle de production distribuée, nous voyons qu'il existe
actuellement de nombreuses communautés de hardware libre qui cherchent à
développer des alternatives sans objectifs mercantilistes. Ces groupes
cherchent en général à créer de l'autonomie, faciliter la liberté pour toutes
et renverser les effets sociaux, environnementaux et politiques néfastes liées
à la production de hardware propriétaire.

Il existe par exemple différentes rencontres encouragées par les mouvements
sociaux comme le Hackmeeting [^41], le Hardmeeting [^42], le HacktheEarth
[^43], le Extrud\_me [^44], ou encore le OSHW Conference [^45], le Chaos
Communication Congress [^46] ou les rencontres Dorkbot où l'on peut trouver
des personnes qui développent des projets de hardware libre. Le projet OSWASH
[^47] (Open Source Washing machines) représente parfaitement ce que nous
définissons comme la recherche et le développement de technologies appropriées
pour lesquelles le seul hardware qui fait sens est celui qui est libre, celui
qui a été réapproprié au privé et rendu aux biens communs.

Au niveau de l'État espagnol des lieux comme le Medialab Prado [^48], la
Laboral [^49] ou Hangar [^50], parient en général sur le développement du
hardware libre. Ainsi dans Hangar (Barcelone), nous trouvons BeFaco [^51], qui
développe du son avec hardware libre et FABoratory [^52], spécialisé dans la
fabrication d'imprimantes 3D. À Calafou, nous pouvons trouver le HardLab
Pechblenda [^53], un laboratoire de son électronique et biohacking depuis la
perspective transféministe.  Enfin, depuis la XarxaCTiT [^54] (Réseau de
Science, Technique et Technologie) de la Coopérative Intégrale Catalane [^55],
nous développons une plate-forme d'échange de savoirs et de besoins au niveau
local, en créant un réseau d'associés, de producteurs, prosommateurs et
consommateurs de hardware libre et de technologies appropriées.

Dans une vision diamétralement opposée et en pariant sur une stratégie globale
pendant que cet écosystème complet de fabrication distribuée continue à
émerger, Chris Anderson [^56] suggère de fabriquer des projets d'Open Hardware
en Chine en utilisant Alibaba.com [^57]. Cette entreprise créée en 1999 est
devenue une compagnie pesant 12000 millions de dollars avec 45 millions
d'utilisateurs enregistrés et 1,1 million d'employés.  Fabriquer en Chine est
un phénomène connu comme le phénomène Shanzai. À l'origine, ce terme décrivait
*"des bandits qui se révoltaient contre une autorité et qui commettaient des
actes qu'ils jugeaient comme justifiés".*

Le mouvement Shanzai représentait en 2009, 20% des téléphones mobiles vendus
en Chine et 10% des téléphones mobiles vendus dans le monde entier. Certains
fabricants ont tellement de succès qu'ils préfèrent favoriser leurs propres
marques au lieu de fabriquer des produits "pirates". Ce qui est intéressant
dans ces entreprises, c'est qu'en "piratant" des produits de marque, elles ont
établi une culture d'échange d'informations sur ces produits et ont généré du
hardware de conception ouverte, en se donnant du crédit les unes aux autres
quant aux améliorations apportées. C'est la communauté qui établit elle-même
cette politique et qui exclut ceux qui ne la suivent pas. Les Shanzai
comprennent et répondent aux besoins et aux goûts locaux, en établissant et en
maintenant des bases locales de fabrication et de distribution, appelées les
fabrications localisées. Toutefois, les conditions de travail surtout dans la
création de composants électriques sont déplorables et elles supposent un
risque physique pour la santé [^58]. L'on ne peut pas dire non plus qu'elles
cherchent la justice sociale pour ses chaînes de travailleuses. L'Open Source
Hardware Work Licence (en attente d'écriture) doit exiger des conditions de
travail respectueuses des personnes, de leur liberté et de leur entourage.

## Conclusions

Utiliser et créer du hardware libre protège et défend la souveraineté
technologique car cela permet aux personnes d'avoir une certaine indépendance
technologique en évitant qu'aucune ne dépende d'une autre comme fournisseur de
ressources nécessaires pour son développement. La réutilisation et
l'adaptation de conceptions permettent d'innover et d'améliorer, de minimiser
les coûts et les temps de conception, de faciliter le transfert de la
connaissance et d'éviter que s'accentue l'analphabétisme numérique pour des
motifs économiques.

En permettant aux personnes de savoir comment cela fonctionne, comment
entretenir et réparer la technologie dont elles ont besoin, elles peuvent
cesser d'être de simples consommateurs technologiques. Utiliser et créer un
hardware libre, active et entraîne plus de bien-être qu'utiliser un autre type
de hardware même s'il faut passer en premier lieu par on ne sait combien de
déception dans son apprentissage. Outre la propre conviction politique, la
liberté représente la possibilité, la capacité d'apprendre et de construire
son propre monde, cela nous rend moins aliénées et nous éloigne encore plus de
la participation à la structure capitaliste.

L'adéquat et l'inadéquat ne sont pas des attributs en soi d'une
technologie. Leur qualification est le résultat de l'évaluation de ses
caractéristiques par rapport à (1): un état d'organisation de la production et
d'un système économique ; (2) des niveaux de distribution des ressources et
(3) un état de développement du système technologique en utilisation. Nous
analysons la façon dont se désertifie une société à travers la techCnologie:
obsolescence programmée, dépendance technologique et introduction de
technologies inappropriées. Leur dévastation et leur récupération sont quasi
impossibles si elles restent à l'intérieur des puissantes chaînes du système
capitaliste.

Car le monde du hardware libre libre est très complexe, et les liens et abus
qui se réalisent à travers le développement technologique ne semblent pas
respecter les libertés. C'est la raison pour laquelle je mise sur les
Technologies Réappropriées.

Celles-ci sont celles qui s'adaptent le mieux à des situations sociales,
culturelles et économiques. Elles exigent peu de ressources, impliquent un
coût moindre et un impact sur l'environnement très faible. Nous autres, nous
avons besoin d'une technologie réappropriée à l'industrialisation, qui
s'incorpore à nos technologies, nos techniques et notre quotidien, ainsi qu'à
nos traditions ancestrales qui de manière inhérente ont déjà une base
environnementale, durable et holistique. Des Technologies Réappropriées au
progrès, à l'analphabétisme et à l'aliénation, à la science immobile, aux
intérêts du pouvoir, réappropriée car décentralisée, organique, transmutable.

## Bibliographie

Annan, Kofi: Challenge to Silicon Valley. http://news.com.com/2010-1069-964507.html?tag=lh 

Avis de Richard Stallman sur le hardware libre. http://features.linuxtoday.com/news_story.php3?ltsn=1999-06-22-005-05-NW-LF

Canals, Xavier: Wikipedias versus blogs. La création collective et l'accès universel au savoir.. http://www.bubok.com/libros/172033/Wikipedias-versus-blogsCasassas

Chaney, D: “L'industrie de la musique dans l'ère numérique: Participation des consommateurs à la création de valeur.”

Kessner, David: Open-source IP could ignite system-on-chip era. http://www.eetimes.com/story/speakout/OEG20000131S0007

Kessner, David: The economics of Free Core development. http://www.free-ip.com/Economics.htm

Khatib, Jamil: Free chips for all - The status of open hardware designs. http://www-4.ibm.com/software/developer/library/openhw.html?dwzone=opensource

Lessig, Lawrence: Culture libre. http://meta.wikimedia.org/wiki/w:es:Cultura_libre_(libro)

Noubel, Jean-François: Intelligence Collective, la révolution invisible. http://www.adin-noticias.com.ar/libros03.htm

Open Hardware and Free Software. http://www.opencollector.org/Whyfree/whyfree.html

Pomerantz, Gregory: Business Models for Open Source Hardware Design. http://pages.nyu.edu/~gmp216/papers/bmfosh-1.0.html

Rojas, León J. M.: Libéralité du savoir depuis la cession des droits de propriété intellectuelle.

Seaman, Graham: Free Hardware Design - Past, Present, Future. http://www.opencollector.org/Whyfree/freedesign.html

Vilbrandt, Carl, concepteur de GnuBook: Extending the Freedoms of Free and Open Information. http://www.opencollector.org/Whyfree/vilbrandt.html

------------------------------------------------------------------------

**Elleflâne:** Diplômée en ingénierie industrielle de l'Université
Nationale de l'Éducation à Distance, ainsi qu'en ingénierie de Design
industriel de l'université Pompeu Fabra. Elle réalise des
courts-métrages, des poèmes, des BDs, des romans fantastiques, des
contes, et invente des artefacts et autres technologies appropries.
Elleflane a également suivi des ateliers au sein de l'ESA (European
Space Agency).

------------------------------------------------------------------------

[^1]: http://es/wikipedia.org/wiki/homebrew_Computer-Club

[^2]: http://www.webopedia.com/TERM/F/FPGA.html

[^3]: http://www.nationmaster.com/encyclopedia.Challenge-to-Silicon-Valley

[^4]: http://www.opencollector.org/history/OpenDesignCircuits/index.html

[^5]: http://www.oepm.es/es/propiedad_industrial/propiedad_industrial/

[^6]: http:/stallman.org

[^7]: http://www.fsf/org/

[^8]: https://www.gnu.org/licences/licences.es.html

[^9]: http://www.linuxtoday.com/infrastructure/1999062200505NWLF

[^10]: http://www.opencollector.org/Whyfree/freedesign.html

[^11]: http://www.oshwa.org/

[^12]: http://www.openhardware.net/

[^13]: https://www.gnu.org/copyleft/gpl.html

[^14]: http://freemodelfoundry.com/

[^15]: http://www.uv.es/leo/sparc

[^16]: http://opencores.org/

[^17]: http://opensource.org/licenses/MIT

[^18]: http://web.media.mit.edu/~rehmi/freeip.html

[^19]: http://www.debian.org/News/2000/20001123.en.html

[^20]: http://blog.openlibrary.org/tag/gnubook/

[^21]: http://www.simputer.org/simputer/license/

[^22]: http://f-cpu.seul.org/

[^23]: http://opencores.org/

[^24]: http://www.opencollector.org/hardlicense/msg00007.html

[^25]: https://joinup.ec.europa.eu/software/page/open_source_licences_and_complementary_agreements

[^26]: http://www.opencollector.org/hardlicense/hdpl.html

[^27]: http://www.opencollector.org/hardlicense/licenses.html

[^28]: http://www.opencollector.org/hardlicense/hdpl.html

[^29]: http://www.ohwr.org/projects/cernohl/wiki

[^30]: http://www.marketwired.com/press-release/adafruits-limor-fried-phillip-torrone-featured-keynotes-for-make-conference-1649479.htm

[^31]: https://www.adafruit.com/

[^32]: http://www.arduino.cc/

[^33]: http://www.chumby.com/

[^34]: http://www.liquidware.com/

[^35]: https://www.makerbot.com/

[^36]: http://en.wikipedia.org/wiki/Crowdfunding

[^37]: http://p2pfoundation.net/Open_Source_Hardware-Reserve_Bank

[^38]: http://www.openmoney.org/

[^39]: http://metacurrency.org/

[^40]: http://opendesignnow.org/index.php/visual_index/manifestos/

[^41]: http://sindomonio.net/hackmeeting/wiki/2014

[^42]: http://giss.tv/dmmdb/index.php?channel=hardmeeting

[^43]: https://calafou.org/es/contenthackthearth-2013-jornadas-autosuficiencia

[^44]: http://xctit.cooperativa.cat/encuentros/extrud_me-2014/

[^45]: http://2013.oshwa.org/

[^46]: http://www.ccc.de/en/

[^47]: http://www.oswash.org/

[^48]: http://medialab-prado.es/

[^49]: http://www.laboralcentrodearte.org

[^50]: http://hangar.org

[^51]: http://www.befaco.org

[^52]: http://faboratory.org/

[^53]: http://pechblenda.hotglue.me/

[^54]: http://xctit.cooperativa.cat/

[^55]: http://cooperativa.cat/

[^56]: "In the Next Industrial Revolution, Atoms Are the New Bits."

[^57]: http://www.openhardware.net/

[^58]: http://www.publico.es/418911/la-gente-se-sentiria-molesta-si-viera-de-donde-viene-su-iphone
