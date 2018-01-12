# Cryptomonnaies

***Jorge Timón***

*"Si vous demandez à un économiste ce qu'est l'argent", il est probable qu'il
ne vous réponde pas en employant une définition mais en énumérant les trois
fonctions attribuées traditionnellement à l'argent. À savoir : un moyen
d'échange, une unité de valeur, un stock de valeur"*. Pour citer Bernard
Lietaer [^1] et en laissant de côté si le "bon" argent, si celui-ci existe,
doit remplir toutes ces fonctions ou si cela est même possible, les opinions
sur ce qu'il est exactement sont relativement divergentes.

Certains le considèrent comme un actif économique comme tout autre actif,
alors que d'autres nient que c'est un vrai capital (puisqu'il n'est pas
directement un moyen de production) et qu'il n'est pas non plus un bien de
consommation puisqu'il ne disparaît pas lorsqu'il circule de main en
main. Certains le considèrent comme un accord social (implicite ou imposé
explicitement par un état) et d'autres simplement une technologie pour
l'échange de biens et de services.

Si nous nous questionnons sur son histoire, une explication communément
acceptée relève du fait que l'or s'est hissé en tant que monnaie puisque c'est
le matériau le plus facilement commercialisable lors de troc.  L'anthropologue
David Graeber [^2] nie l'existence de preuves et voit les économies
d'offrandes [^3]/dons et monnaies basées sur des crédits mutuels [^4] comme
les origines plus probables du commerce.

Les réformistes monétaires [^5] voient dans la structure de l'argent la racine
de nombreux problèmes de nos sociétés. De fait, aujourd'hui les monnaies
complémentaires/locales/sociales en circulation sont plus nombreuses que les
monnaies officielles [^6]. Déjà en pleine crise de 1929, le maire de la ville
tyrolienne de Wörgl [^7] a décidé de mettre en pratique la théorie de la libre
monnaie de Sylvio Gesell [^8]. Malgré son succès, la banque centrale
autrichienne a interrompu l'expérience et a interdit que les communes voisines
copient le modèle.

Pour sa part, le mouvement Cypherpunk [^9] créé dans les années 80, plaide en
faveur de l'usage étendu de la cryptographie comme outil d'échange social et
politique. En 1990, David Chaum lançait Digicash [^10], un système centralisé
d'argent électronique qui permettait des transactions plus anonymes et plus
sûres. En 1997, Adam Black proposait Hashcash [^11], un système basé sur la
preuve de travail pour limiter le spam (courriers indésirables) et les
attaques par déni de service (DoS). En 2009, une identité méconnue sous le
pseudonyme de Satoshi Nakamoto publiait Bitcoin [^12], la première
crypto-monnaie complètement décentralisée, en utilisant une chaîne de blocs
avec preuve de travail, dont nous parlerons plus en détail.

Depuis son apparition, de nombreuses autres crypto-monnaies ou inspirées de
celle sont apparues, mais il est important de souligner qu'elles ne sont pas
toutes des monnaies p2p [^13] décentralisées. Certaines ont été créées pour
rajouter quelques fonctionnalités [^14], par différences idéologiques envers
la question de l'économie [^15], pour tenter de solutionner des problèmes
techniques [^16] ; toutefois la majorité se limite à de petits échanges sans
importance ou sont créée par pur désir spéculatif ou de fraude [^17]. Ceci
étant, une exigence indispensable pour être une monnaie p2p, est que le
système se base sur du logiciel libre [^18], dans le cas contraire il serait
sous le seul contrôle de ses développeurs, et les personnes et les
utilisateurs ne pourraient avoir confiance en lui.

## Principaux agents

Hackers et autres enthousiastes
:   Au départ, les seuls qui utilisaient Bitcoin étaient les informaticiens,
    les enthousiastes de la cryptographie ou du logiciel libre. Une pratique
    habituelle a été par exemple celle de collecter des primes pour payer des
    programmeurs, généralement pour qu'ils mettent en œuvrent un développement
    sous logiciel libre en rapport avec les propres monnaies. Les adeptes de
    l'école autrichienne [^19] (le courant économique dominant de la
    communauté des monnaies p2p) et les anarchistes capitalistes [^20] sont
    d'autres groupes qui ont été rapidement attirés par les similitudes entre
    l'or en tant qu'argent et le Bitcoin.

Les "mineurs"
:   Ceux-ci mettent leur matériel à disposition du réseau p2p et réalisent la
    preuve de travail (Proof of Work - POW) sur laquelle se base la sécurité
    de la majorité de ces crypto-monnaies. Même si certains mineurs sont
    arrivés à amasser une fortune dû en partie à la chance et aux grandes
    fluctuations à la hausse dans le prix des monnaies, le minage s'est
    converti en une activité très compétitive, complexe et risquée où il est
    relativement facile de perdre de l'argent, que ce soit à cause des coûts
    de l'électricité ou à cause de l'incapacité de récupérer l'investissement
    initial.

Entreprises, coopératives, collectifs spécialisés
:   De nombreuses entreprises ont été créées autour de ces technologies pour
    couvrir des niches de marché comme par exemple : des marchés pour échanger
    des crypto-monnaies entre elles ou contre des monnaies officielles, des
    entreprises qui gèrent des paiements en éliminant les risques de
    volatilité pour les commerçants, les portefeuilles Web, les publicités
    pour Bitcoin, les micro dons, etc. Il convient de noter que bons nombres
    d'entre elles sont seulement des adaptations de modèles d'activité qui
    existaient déjà autour des monnaies p2p. Mais de nombreuses autres
    apportent également de l'innovation dans un secteur aussi régulé et
    contrôlé par les cartels comme le cartel financier.

Spéculateurs
:   Certaines personnes sont chargées de l'arbitrage entre les différents
    marchés existants et en réalité elles peuvent remplir une fonction
    importante. Toutefois, le type le plus fréquent de spéculateur est celui
    qui se consacre à amasser des monnaies p2p dans l'espoir de voir leur
    valeur augmenter. Et comme si le Bitcoin n'était pas suffisamment volatil
    en soi, ces spéculateurs jouissent maintenant d'une grande variété de
    nouvelles monnaies avec des marchés plus petits (et donc, en général, plus
    volatils), dans lesquels on peut prendre des risques jusqu'à l'extrême.

Producteurs et commerçants
:   Ceux-ci peuvent fidéliser ou obtenir des clients supplémentaires en
    acceptant des crypto-monnaies. Ils courent des risques découlant de la
    fluctuation du prix des monnaies (même s'il existe des services pour les
    annuler), mais ils jouissent de commissions moins chère et d'une
    irréversibilité des transactions. En comparaison, une grande partie des
    commissions sur les cartes de crédit ou sur des services comme Paypal, est
    justifiée par le haut niveau de fraude dû au fait que les paiements
    peuvent être annulés ultérieurement.

Citoyenneté et organisations sans but lucratif
:   Recevoir des dons en monnaie p2p a toujours été extrêmement simple, il
    suffit de taper une adresse ou un code QR sur une page Web ou sur une
    pancarte [^21]. Certaines organisations sans but lucratif, pionnières dans
    l'acceptation des Bitcoin ont reçu d'importantes sommes, lesquelles petit
    à petit ont pris de la valeur avec l'évaluation ultérieure de la monnaie.
    D'autre part, les organisations du secteur tertiaire développent également
    des projets et sont en train d'expérimenter sur ce terrain. Par exemple,
    90 % de la création de Devcoin [^22] sont destinés à des projets de
    connaissance libre, même si la prise de décision est décentralisée. Ou
    encore Freicon qui reverse 80 % de la somme initiale émise en trois ans à
    la fondation Freicoin pour que celle-ci la distribue en utilisant des
    méthodes expérimentales de distribution acceptées et développées au
    préalable par la communauté. À l'heure actuelle, il n'existe qu'un
    programme d'émission qui consiste en une plate-forme de crowdfunding [^23]
    pour des organisations et des projets sans but lucratif [^24] : toute
    personne peut vous faire des dons de freicoins, et la fondation apporte un
    supplément de 10 %, sans avoir à choisir directement la somme remise à
    chacune d'elles. Toute personne peut auditer la chaîne de blocs de
    transactions pour vérifier que la répartition a été réalisée de manière
    adéquate.

## Censurés et bloqués

L'autre avantage fondamental réside dans l'impossibilité de censurer.  D'une
part, les paiements peuvent venir de n'importe quelle partie du monde. Seul
Paypal bloque plus de 60 pays et de nombreuses compagnies de cartes ont des
restrictions similaires. Des organisations comme Wikileaks ont également été
bloquées par Visa, MasterCard et Paypal, lesquels les ont empêchées de
recevoir des dons en monnaie officielle mais n'ont rien pu faire contre les
dons en monnaie p2p.

Paradoxalement, plus un pays est pauvre, plus les commissions et les intérêts
auxquels il doit faire face sont importants. Il est fréquent que le total des
commissions payées par un pays à des entités financières étrangères dépasse le
total des aides qu'il reçoit. Les immigrants qui envoient de l'argent dans
leur pays paient également des commissions honteuses supérieures à 10 %, très
peu compétitives par rapport aux commissions fixes marquées par des monnaies
p2p (souvent inférieures à un centime d'euro). De plus, dans de nombreux pays,
une grande partie de la population adulte n'a accès à aucun type de service
financier, ni à aucun compte courant. Au Kenya, 31 % du produit intérieur brut
est transféré grâce à des téléphones mobiles via le système m-pesa [^25]. Un
exemple d'entreprise ayant un lien avec les monnaies p2p [^26].

## Problématiques et limites

Macroéconomie
:   Nous résumerons très succinctement les principales positions autour de la
    "qualité" des crypto-monnaies en tant qu'argent au sens
    macroéconomique. L'école autrichienne accepte souvent une somme fixe
    d'argent maximal ou de création prévisible. Les néo-keynésiens [^27], plus
    nombreux et influents, ne trouvent pas leur place parmi les
    crypto-monnaies puisqu'ils pensent que l'économie "a parfois besoin de
    plus d'argent".  Il existe un autre courant plus minoritaire et ignoré,
    celui initié par Sylvio Gesell, selon lequel le problème n'est pas le
    manque d'argent mais sa stagnation. Lorsque les rendements de capitaux et
    les intérêts sont bas, les épargnants cessent tout simplement d'investir
    et de prêter de l'argent.  Freicoin [^28] par exemple applique une
    commission d'oxydation [^29] pour éviter sa stagnation et supprimer
    l'avantage du prêteur pour pouvoir négocier l'intérêt plus à la hausse.

Le problème de l'émission
:   Bien qu'il soit nécessaire de compenser les mineurs pour la sécurité
    qu'ils fournissent, cette compensation devrait, à l'avenir, être
    suffisante grâce aux commissions par transaction. En général, la
    distribution initiale des crypto-monnaies est un thème sujet à controverse
    sur lequel des expériences continueront à être menées, et qui nous font
    également réfléchir à la création de la monnaie officielle en
    soi. Certains pensent [^30] que ce ne sont pas aux banques commerciales et
    centrales de s'en charger mais bien à l'état [^31].

Matériel informatique spécialisé
:   Autre sujet abordé, celui des circuits intégrés pour applications
    spécifiques (ASIC) [^32]. Il s'agit d'un matériel spécialisé dans une
    tâche concrète, dans ce cas, le minage. L'argument contre les ASIC est
    souvent celui de la centralisation, certaines personnes ayant peur d'un
    monopole ou d'une grande concentration dans sa production et/ou dans sa
    distribution. Mais, même s'il est possible d'échapper à ces circuits pour
    toujours, certaines personnes ne pensent pas que ce soit un sujet à éviter
    [^33], et argumentent leur position par le fait que cette centralisation
    existait lorsque la forme la plus efficace de miner résidait dans
    l'utilisation des GPU (cartes graphiques), puisque le marché est
    pratiquement contrôlé par deux compagnies et dans la pratique la majorité
    des mineurs achetaient à la même compagnie (ATI).

Pool et centralisation
:   Les pools sont un groupe organisé de mineurs qui parient conjointement
    pour se partager la récompense des blocs qu'ils arrivent à obtenir en
    dépendant de la puissance de calcul que chacun a apporté. Le problème
    réside dans le fait que seul l'opérateur de la pool valide le bloc dans
    lequel les autres participants ont contribué à l'aveugle. L'opérateur
    pourrait abuser de ce pouvoir pour attaquer le système sans que ses
    mineurs ne s'en rendent compte et il pourrait également les tromper.

Privacité
:   On peut lire de nombreux commentaires sur Internet sur la façon dont le
    supposé anonymat de Bitcoin fait d'elle la monnaie préférée des
    criminels. Mais la réalité est que tout au long de son histoire, toutes
    les transactions ont été publiques et toutes personne peut télécharger la
    chaîne de blocs pour les voir s'éloigner de l'idéal type de la monnaie
    anonyme.  Le système n'est pas non plus conçu pour une surveillance
    orwellienne des finances, étant donné que toute personne peut créer un
    numéro de clé ou recevoir des paiements et ne pas avoir son nom
    directement associé aux adresses (pseudonyme). À moins que, bien sûr, le
    propriétaire en informe les personnes qui le souhaitent ou qu'il le publie
    sur Internet (ou si les connexions sur Internet sont surveillées
    [^34]). Certains projets comme Coinjoin [^35] ou darkwallet [^36] servent
    à améliorer la privacité des utilisateurs sans modifier le protocole de
    base de Bitcoin. D'autres projets comme Zérocoin [^37] optent pour le
    modifier (créer une nouvelle crypto-monnaie) pour offrir plus d'anonymat,
    même si cela peut supposer moins d'efficacité ou d'autres effets non
    désirés.

Scalabilité
:   L'un des défis les plus importants auxquels doivent faire face les
    monnaies à long terme résident en leur capacité [^38] à croître selon le
    nombre de transactions traitées. VISA, par exemple, traite une moyenne de
    2000 transactions par seconde (temps) et pourrait traiter jusqu'à 10 000
    temps. À titre de comparaison, Bitcoin peut seulement traiter jusqu'à 7
    temps, même si certaines de ses limites imposées par ce maximum sont
    artificielles. Il existe un compromis délicat entre scalabilité et
    centralisation, car avec de nombreuses transactions, le nombre de
    personnes pouvant effectuer des noeuds complets (en contraste avec des
    clients légers [^39]) sera moins important.

## Conclusions

Il est probable qu'à court et moyen terme les cryptomonnaies soient de plus en
plus volatiles. De même que toute personne peut gagner de l'argent rapidement
en spéculant sur sa valeur, celle-ci peut également le perdre. De ce fait, il
n'est pas prudent de spéculer avec de grandes sommes d'argent. De plus, il
convient d'apporter une attention particulière aux nouvelles crypto-monnaies,
car souvent il s'agit de projets avec de petites communautés qui ne peuvent
fournir au logiciel qu'une maintenance.

Les organisations et les projets sans but lucratif ne courent toutefois aucun
risque en acceptant des dons effectués avec ces monnaies. C'est quelque chose
de relativement simple à faire et cela peut leur rapporter une source
additionnelle de revenus. Pour les free-lance, cela peut représenter un outil
très utile pour pouvoir travailler dans n'importe quelle partie du monde, mais
comme tout autre commerçant ou producteur, celui-ci est responsable de les
échanger rapidement contre des monnaies officielles et/ou contre un
pourcentage suffisant pour ne pas subir les risques associés à leur
volatilité.

Quel que soit le destin de chaque monnaie, indépendamment les unes des autres,
la technologie offre des avantages suffisants pour espérer que certaines
d'entre elles (ou d'autres à venir) trouvent leur place dans la société pour
exister à long terme. Dans un certain sens, leur potentiel de rupture pour
l'industrie monétaire et financière est comparable à celle que les
technologies p2p comme *bittorent* [^40] ont causé à l'industrie du
copyright. Toutefois, il est improbable, dû à certaines limites, que ces
monnaies soient les seules monnaies, il est plus réaliste de penser qu'elle
cohabiteront avec les monnaies officielles et la tendance également croissante
d'autres types de monnaies complémentaires (locales, sociales, entre marché
B2B [^41], etc.).

------------------------------------------------------------------------

**Jorge Timón:** Ingénieur en logiciels avec 4 années d'expérience au sein de
Indra où il a travaillé sur d'importants projets internationaux incluant la
mise en place de logiciels pour plusieurs compagnies d'assurance. Il a
contribué au design du Protocole Ripple v0.6 (pre-Ripple Labs) créé par Ryan
Fugger. Il est par ailleurs à l'initiative de Freicoin et a participé à son
design. Il est le principal développeur du site internet de la Fondation
Freicoin. Enfin, il a été l'un des intervenants lors de la II Conférence
Internationale sur les Systèmes de Monnaies Complémentaires et le Bitcoin de
2013, entre autres.

------------------------------------------------------------------------

[^1]: http://en.wikipedia.org/wiki/Bernard_Lietaer

[^2]: http://en.wikipedia.org/wiki/Debt:_The_First_5000_Years

[^3]: http://en.wikipedia.org/wiki/Gift_economy

[^4]: http://en.wikipedia.org/wiki/Mutual_credit

[^5]: http://en.wikipedia.org/wiki/Monetary_reform

[^6]: http://www.complementarycurrency.org/ccDatabase/

[^7]: http://en.wikipedia.org/wiki/Worgl#The_W.C3.B6rgl_Eperiment

[^8]: http://en.wikipedia.org/wiki/Silvio_Gesell

[^9]: http://en.wikipedia.org/wiki/Cypherpunk

[^10]: http://en.wikipedia.org/wiki/DigiCash

[^11]: http://en.wikipedia.org/wiki/Hashcash

[^12]: http://en.wikipedia.org/wiki/Bitcoin

[^13]: http://en.wikipedia.org/wiki/Peer-to-peer

[^14]: http://dot-bit.org

[^15]: http://freico.in/

[^16]: http://peercoin.net/

[^17]: https://bitcointalk.org/index.php?topic=361813.0 contient la vidéo explicative suivante: http://www.youtube.com/watch?v=xcaltexImW0

[^18]: http://en.wikipedia.org/wiki/Free_software

[^19]: http://en.wikipedia.org/wiki/Austrian_School

[^20]: http://en.wikipedia.org/wiki/Anarcho-capitalism

[^21]: http://lifeboeat.com/blog/2013/12/a-college-kid-made-over-24000-yesterday-just-by-waving-this-sign-on-espn

[^22]: http://devcoin.org

[^23]: http://en.wikipedia.org/wiki/Crowdfunding

[^24]: http://foundation.freicoin.org/#/donations

[^25]: http://en.wikipedia.org/wiki/M-Pesa

[^26]: http://kipochi.com/blog/kipochi-launches-first-bitcoin-wallet-in-africa-with-m-pesa-integration

[^27]: http://en.wikipedia.org/wiki/Neo-Keynesian_economics

[^28]: http://freico.in/

[^29]: http://en.wikipedia.org/wiki/Demurrage_(currency)

[^30]: http://www.positivemoney.org/

[^31]: https://es.wikipedia.org/wiki/Se%C3%B1oreaje

[^32]: http://en.wikipedia.org/wiki/Application-specific_integrated_circuit

[^33]: http://www.coindesk.com/bitcoin-developer-jeff-garzik-on-altcoins-asics-and-bitcoin-usability/

[^34]: http://en.wikipedia.org/wiki/Global_surveillance_disclosures_(2013%E2%80%93present

[^35]: https://bitcointalk.org/index.php?topic=279249.0

[^36]: https://darkwallet.unsystem.net/

[^37]: http://zerocoin.org/

[^38]: http://en.wikipedia.org/wiki/Scalability_https://en.bitcoin.it/wiki/Scalability

[^39]: https://en.bitcoin.it/wiki/Thin_Client_Security

[^40]: http://en.wikipedia.org/wiki/BitTorrent

[^41]: https://fr.wikipedia.org/wiki/Business_to_business_%28Internet%29
