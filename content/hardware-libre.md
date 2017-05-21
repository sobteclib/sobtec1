# Hardware libre: Del Hardware Libre a las Tecnologías Re-Apropriadas
## Elle Flâne 

![](media/free-hw.png)

El concepto de Hardware es bastante nuevo, muy amplio, en continua renovación y radicalmente diferente del software. Existe una amplia controversia sobre lo que es y lo que no es hardware y al no existir una definición consensuada, cada uno lo interpreta a su manera. Por ejemplo, para mi, el Hardware incluye desde un componente electrónico, un condensador, un transistor, un led, un circuito integrado, un artefacto como una bici-arado, la descripción de un proceso industrial como es la fabricación de un ladrillo refractario, una computadora, una impresora 3D, un mecanismo para depuración de agua escrito en código fuente abierto, un proceso de reciclaje de plástico, la creación de una fresadora CNC, un método de análisis de tierras contaminadas mediante sensores o el código de un microcontrolador.

Si adoptamos una visión más cerrada, se puede decir que la historia del Hardware Libre transcurre paralela a la de la informática. En 1970, el Homebrew Computer Club [^1] resulto ser un híbrido compuesto por el movimiento radical estudiantil, empresarios del área de computación de la comunidad de Berkeley y aficionados a hobbies electrónicos. Ahora resulta irónico ver como muchos de esos garajes cargados de creatividad son ahora museos, como el Bill Hewlett y Dave Packard, dónde se gestó el primer dispositivo HP.

En los años 90, de la misma manera que los programas de software podían ser intercambiados, los FPGA [^2] permitían el intercambio electrónico de diseños libres. La Open Design Circuits [^3], lanzada por Reinoud Lamberts, es la primera web de una comunidad de diseño de hardware con el espíritu del software libre. Aunque no existiese aún un software libre adecuado para el diseño electrónico, ese portal involucró a muchas personas sentando las base para una comunidad más amplia.

En el 2002, el ***“Challenge to Silicon Valley”*** [^4] lanzando por Kofi Annan, inició varios proyectos de desarrollo de hardware libre, haciendo más visible la necesidad de desarrollar tecnologías apropiadas para realidades socioculturales y económicas variadas. Esa linea de desarrollo de tecnologías se confundió con la lucha global contra la brecha digital a través de las iniciativas de ICT4Development. Estas fueron en general el resultado de partenariados entre la academia y organizaciones del tercer sector para implementar tecnologías adaptadas a las necesidades de los países definidos erróneamente como “en desarrollo”.

No obstante, hoy en día el panorama de la producción de hardware sigue mayormente marcado por las limitaciones impuestas por las patentes industriales y la propiedad industrial [^5] . Estas son el conjunto de derechos que posee una persona física o jurídica sobre una invención. Otorgan dos tipos de derechos: el derecho a utilizar la invención, diseño o signo distintivo, y el derecho a prohibir que un tercero lo haga. El derecho de prohibir **(***Ius prohibendi***)** permite al titular del derecho solicitar el pago de una licencia, llamada regalía o *royalty*, que posee límites temporales y territoriales.

### Hardware Libre: ¿Hasta donde y de que manera? 

Crear en hardware libre requiere casi todos los procesos: un diseño, un proceso de manufactura, unas materias primas, una distribución, un modelo de negocio, un mantenimiento, una implementación, una replicabilidad, una fuerza de trabajo, un acceso a la documentación y a la técnica de fabricación. Partiendo de este contexto, si intentamos definir lo que es hardware libre tenemos que ver como las etapas de producción sumadas a los tipos de resultados tangibles posibles, pueden ser interpretados por licencias libres.

El mismo Richard Stallman [^6], presidente de la Free Software Foundation [^7] y creador de la licencia GNU GPL [^8] garantiza las siguientes 4 libertades (libertad de uso, de estudio y modificación, distribución, y redistribución de las versiones modificadas), afirma que *«las ideas del software libre se pueden aplicar a los archivos o ficheros necesarios para su diseño y especificación (esquemas, PCB, etc), pero no al circuito físico en si*» [^9].

Existe también el hardware estático, compuesto por los elementos materiales o tangibles de los sistemas electrónicos y el hardware reconfigurable, descrito mediante un lenguaje de descripción de hardware compuesto por archivos de texto que contienen el código fuente. Por ello, las palabras "hardware" y "diseño de hardware" son dos cosas distintas.

El diseño y el objeto físico no pueden confundirse aunque se fundan a veces con el otro.

Todos estos factores generan confusión a la hora de tipificar de qué manera el hardware es realmente libre. Es cierto que cada componente y etapa de producción puede adecuarse a las cuatro libertades especificadas por el software libre, pero en la actualidad ningún proyecto consigue abarcar toda la cadena desde lo estrictamente libre. Por lo que actualmente utilizamos el término de hardware libre/open hardware, sin tener que aplicar las cuatro libertades de forma restringida en todos sus ámbitos. Existen muchas iniciativas consolidadas en este campo, aunque los modelos de uso y acercamiento son distintos según las motivaciones sociales, económicas y políticas de cada colectivo o comunidad detrás de su desarrollo.

Como resultante, existe una multitud de licencias diferentes intentando clarificar estas cuestiones. Por ejemplo, el Free Hardware Design [^10], es un diseño que puede ser copiado, distribuido, modificado, y fabricado libremente. No implica que el diseño no pueda ser vendido, o que cualquier práctica de hardware del diseño este libre de coste. El Libre Hardware Design, es igual al free hardware design, pero aclara que la palabra libre, se refiere a la libertad y no al precio. Para el Open Source Hardware [^11], toda la información del diseño está a disposición del público en general, y puede basarse en un free hardware design, o en un diseño restringido de alguna manera.

El Open Hardware [^12], una marca registrada por el Open Hardware Specification Program, resulta una forma limitada de Open Source Hardware ya que el único requisito es poner a disposición una cantidad de información limitada sobre el diseño para poder por ejemplo hacer una reparación. Finalmente en un intento de síntesis, Patrick McNamara define para el Open Hardware los siguientes niveles de apertura:

1.  Interfaz abierta: el usuario dispone de toda la documentación que explica cómo hacer que una pieza de hardware cumpla la función para la cual fue diseñada.

2.  Diseño abierto: la documentación disponible es suficientemente detallada como para que un tercero pueda crear un dispositivo funcional y compatible.

<!-- -->

2.  Implementación abierta: disponible la lista de todos los materiales necesarios para la construcción del dispositivo y proceso de manufactura

Las licencias específicas para hardware libre todavía se encuentran en desarrollo, existe un panorama actual con gran variedad. Hay grupos que usan la GNU GPL [^13] como el Free Model Foundry [^14] para simulación de modelos, componentes y verificación, ESA Sparc [^15] desarrollan una CPU para 32bits, Opencores [^16], comunidad que desarrolla IP cores. Otros grupos usan la licencia Open Source Initiative del MIT [^17] como el Free-IP Project [^18] y LART [^19]. En cuanto a la licencia GNUBook [^20] se basa en la licencia GPL pero con adiciones referentes a los derechos ambientales y humanos.

Existen grupos que desarrollan nuevas licencias como la Simputer GPL [^21], Freedom CPU [^22], OpenIPCores [^23], la OHGPL [^24], The Open NDA [^25], la OpenPPC [^26] (basada en la Apple Public Source License) y la Hardware Design Public License [^27] del grupo Open Collector [^28]. Destacamos entre ellas la Licencia Hardware del Cern OHL [^29], escrita originalmente para diseños del CERN (Acelerador de Partículas) alojados en el Repositorio Open Hardware.

### Modelos de negocio y sostenibilidad derivadas del hardware libre 

Según Wired, la biblia del tecnopositivismo, el Open Hardware se está convirtiendo en una *commodity*, o sea una mercancía. Aunque no exista aún un modelo claro de negocio, se sobreentiende que puede atender nichos de mercado que hasta ahora no han sido cubiertos, aplicando la lógica de la *long tail* o larga cola de distribución de bienes y servicios (al estilo Amazon) a la dimensión casi infinita del hardware. Respecto a la comercialización, el diseño de hardware libre puede ser implementado por una empresa para posteriormente comercializar con él, la única premisa es mantener el diseño libre, pero no las otras partes, fabricación, materias primas, manufactura.

En 2010, Torrone y Fried [^30] recopilaron 13 ejemplos de compañías que vendían Hardware Open Source facturando entre todas 50 millones de dólares. Actualmente existen más de 200 proyectos de este tipo y se prevé que la comunidad de Hardware Open Source facturará mil millones de dólares en 2015. Adafruit [^31] , Arduino [^32] , Chumby [^33] , Liquidware [^34] y Makerbot [^35] tienen ganancias, por separado, que ascienden a más de un millón de dólares. Todo ello muestra que existen por lo tanto posibilidades reales de generar ganancias económicas en proyectos que basan su actividad en dar a conocer y compartir con la comunidad. Ahora lo que no queda tan claro es si: ¿Es posible una política anticapitalista real basada en un proyecto económico y de re-distribución de los bienes unido a unas lógicas de sostenibilidad y decrecimiento?

Un modelo de sostenibilidad interesante para el Open Hardware radica en el *crowdfunding* [^36] que consiste en recolectar pequeñas cantidades de individuos o grupos para empezar un proyecto. Huynh y Stack han creado por ejemplo, el Open Source Hardware Reserve Bank [^37] para cubrir los costes asociados a las continuas revisiones del hardware durante el proceso de diseño estimados en casi el 40% del presupuesto inicial necesitado. El proyecto busca reducir los riesgos para que los proyectos de hardware libre puedan pasar a la fase de producción. También facilitan la experimentación permitiendo la construcción y distribución de pequeñas cantidades de productos considerados "no escalables", ya que "una mala idea de negocios" no es lo mismo que “una mala idea de hardware”.

El Open Source Hardware Reserve Bank, que permite solo a hackers, y no a inversores capital de riesgo u otras compañías, invertir en proyectos específicos duplicando el número de piezas producidas y reduciendo su coste unitario alrededor de un 10 – 30%., destacando que una comunidad también puede auto-financiar sus proyectos a través del microcrédito. Open Money [^38] y Metacurrency [^39], proponen nuevos formatos de moneda, y buscan promover la unión de monedas existentes con certificados de microcrédito.

Finalmente, el Open Design Manifiesto [^40] une dos tendencias. Por un lado, la gente aplica sus habilidades y tiempo a proyectos para el bien común que no se suelen apoyar por falta de interés comercial. Por otro lado, proporciona un marco para el desarrollo de proyectos y tecnologías avanzadas que podrían estar más allá de los recursos de cualquier empresa o país e involucra a personas que, sin el mecanismo copyleft, no podrían colaborar de otra forma.

Veamos ahora qué problemáticas se dan en relación a la sostenibilidad del hardware libre. Por una parte, la falta de consenso respecto a la propia definición de free hardware se extrapola a los posibles modelos de negocios. Un dispositivo abierto es diferente a lo que existe y predomina en el mercado ya que lo importante no es el producto acabado (hardware manufacturado) sino los activos intangibles, la información referente al diseño del hardware que se abre al uso público. Por otra parte, y como hemos visto anteriormente en el hardware libre no se pueden aplicar actualmente y de forma directa las cuatro libertades del software libre, dada su naturaleza diferente, uno tiene existencia física, el otro no. Por lo tanto, un diseño físico es único y su compartición depende de la facilidad de reproducción.

Existe además una dependencia tecnológica por los componentes importados que se puede traducir por: ¿Están disponibles los chips?. Se da por lo tanto modelos de exclusión, ya que no cualquiera puede realizar hardware, debido a las implicaciones que con lleva crear toda la infraestructura necesaria. La persona que quiera usar el hardware que otra haya diseñado, lo tiene que fabricar, comprando los componentes necesarios y reconstruyendo el diseño. Todo esto tiene un coste. Como resultado lógico el conocimiento lo poseen pocas empresas, y estas lo retienen celosamente para que las personas sigan siendo simples consumidoras del producto.

### Modelos de producción diferenciados 

Observamos dos modelos convencionales de producción/ distribución. Por una parte, el modelo basado en la manufactura centralizada, con un mismo producto disponible en muchos lugares, permitiendo aumentar el precio al consumidor. Por otra parte, un sistema de manufactura distribuido basado en un número de grupos pequeños independientes que producen el mismo diseño para distribuirlo localmente. Para volverse sostenible en ambos modelos, las iniciativas de hardware libre necesitan plataformas que aglutinen y faciliten el contacto entre los medios de producción y las personas que quieran crear.

En relación al modelo de producción distribuida, vemos que existen actualmente muchas comunidades de hardware libre que buscan desarrollar alternativas sin objetivos mercantilistas. Estos grupos buscan en general crear autonomía, facilitar la libertad para todas y revertir los efectos sociales, ambientales y políticos nefastos ligados a la producción de hardware propietario.

Existen distintos encuentros promovidos desde los movimientos sociales como el Hackmeeting [^41] ,Hardmeeting [^42] , HacktheEarth [^43] , Extrud_me [^44] , o aún como el OSHW Conference [^45] , el Chaos Communication Congress [^46] o los encuentros Dorkbot donde se puede encontrar gente desarrollando proyectos de Hardware libre. El proyecto OSWASH [^47] (Open Source Washing machines) representa a la perfección lo que definimos como investigación y desarrollo de tecnologías apropiadas para las cuales el único hardware que hace sentido es el libre, el que ha sido re-apropriado a lo privativo y devuelto a los comunes.

A nivel del Estado español lugares como el Medialab Prado [^48] , LaLaboral [^49] o Hangar [^50], apuestan por el desarrollo de Hardware Libre. Así en Hangar (Barcelona), encontramos a BeFaco [^51], desarrollando sonido en hardware libre y FABoratory [^52], especializado en fabricación de impresoras 3D. En Calafou, podemos encontrar el HardLab Pechblenda [^53], un laboratorio de sonido, electrónica y biohacking desde una perspectiva transfeminista. Finalmente, desde la XarxaCTiT [^54] (Red de Ciencia, Técnica y Tecnología) de la Cooperativa Integral Catalana [^55] desarrollamos un plataforma de intercambio de saberes y necesidades a nivel local, fomentando una red de socios, productores, prosumidores y consumidores de hardware libre y tecnologías re-apropriadas.

En una visión diametralmente opuesta y apostando por una estrategia global mientras no exista ese ecosistema completo de manufactura distribuida, Chris Anderson [^56] sugiere manufacturar proyectos de Open Hardware en China usando Alibaba.com [^57]. Esta empresa creada en 1999, se ha convertido en una compañía de 12 mil millones de dólares con 45 millones de usuarios registrados y 1.1 millones de empleados. Fabricar en China es un fenómeno conocido como *Shanzai*. Originalmente ese termino, describía «***bandidos que se rebelaban a una autoridad y cometían actos que ellos veían como justificados***»***. ***

El movimiento Shanzai representaba en 2009 el 20% de los teléfonos móviles vendidos en China, y el 10% de los móviles vendidos en todo el mundo. Algunos fabricantes son tan exitosos que prefieren potenciar sus propias marcas en vez de producir productos “piratas”. Lo interesante de estas empresas es que "pirateando" productos de marca han establecido una cultura de compartir información acerca de esos productos y han generado material de diseño abierto, dándose crédito las unas a las otras en cuanto a las mejoras aportadas. Es la comunidad quien auto-formula esta política y excluye a quienes no la siguen. Las Shanzai entienden y responden a las necesidades y gustos locales, estableciendo y manteniendo bases locales de manufactura y distribución, llamadas manufacturas situadas.

Sin embargo las condiciones de trabajo sobretodo en la creación de componentes eléctricos son deplorables y suponen un riesgo físico a la salud [^58], así como no pueden ser tildadas de buscar la justicia social para sus plantillas de trabajadoras. La Open Source Hardware Work Licence (todavía por escribir) debe integrar como requisito unas condiciones de trabajo respetuosas con las personas, sus libertades y su entorno.

### Conclusiones 

Usar y crear hardware libre protege y defiende la soberanía tecnológica porque permite independencia tecnológica para las personas evitando que ninguna dependa de otra como proveedora de recursos necesarios para su desarrollo. La reutilización y adaptación de diseños permite innovar y mejorar, ahorrar costes y tiempos de diseños, facilitar la transferencia del conocimiento y evitar que se acentúe el analfabetismo digital por motivos económicos.

Las personas dejan de ser meros consumidores tecnológicos, al permitirles saber como funciona, como mantener y reparar la tecnología que necesitan. Usar y crear hardware libre, engancha, y genera más bienestar que usar otro tipo de hardware, aunque primero haya que pasar por unos cuantos disgustos en su aprendizaje. Más allá de la propia convicción política, la libertad representa la posibilidad, la capacidad de aprender y construir tu propio mundo, esto nos aliena menos de nosotras mismas y nos aleja más de participar dentro de la estructura capitalista.

Lo adecuado o inadecuado no es un atributo en sí de una tecnología. Su calificación es el resultado de evaluar sus características en relación al (1): Estado de organización de la producción y sistema económico; (2) Niveles y distribución de los ingresos y (3) Estado de desarrollo del sistema tecnológico en uso.

Sin la Soberanía Tecnológica, analizamos como se desertiza una sociedad a través de la tecnología: obsolescencia programada, dependencia tecnológica e introducción de tecnologías inadecuadas. Su devastación y su recuperación son casi imposibles si permanecen dentro de las fuertes cadenas del sistema capitalista. El mundo del hardware libre es muy complejo, y las ataduras y abusos que se realizan a través del desarrollo tecnológico no parecen respetar las libertades, por eso apuesto/apostamos por **Tecnologías Re-Apropiadas**.

Estas tecnologías son las que mejor se adecuan a situaciones medioambientales, culturales y económicas concretas. Son las que responden a necesidades básicas y reales, y no a cavilaciones . Requieren pocos recursos, significan menos costo y bajo impacto en el ambiente. Nosotras necesitamos una Tecnología re-apropiada a la industrialización, que incorpore a nuestras tecnologías, técnicas y cotidianidad, nuestras tradiciones ancestrales que inherentemente tienen una base medioambiental, sostenible y holística. Tecnologías re-apropiadas al progreso, al analfabetismo y a la alienación, a la ciencia inmóvil, a los intereses del poder, re-apropiada porque es descentralizada, orgánica, transmutable. **Re-apropiadas** porque son las **“Tecnologías más apropiadas para Todas (sin desapropiar a otras)” **

* * * 

**Elle Flâne,** Inventora, poeta, roadmanager, fantasiadora, hiper-agitadora, comisaria arte, ingeniera de Materiales, ingeniera Industrial, ingeniera Técnica en Diseño Industrial. Estuvo cursando talleres en la ESA European Space Agency. **elle_flane[at]riseup[dot]net**

* * * 

-   **[Hardware Libre](https://cooperativa.ecoxarxes.cat/file/view/246449/esbozo-de-articulo-hardware-libre)** por Elle Flâne

-   **[Tecnologías Re-apropiadas](https://cooperativa.ecoxarxes.cat/file/view/246450/esbozo-de-articulo-tecnologias-apropiadas)** por Elle Flâne

-   **[Mi conocimiento es plástico](https://cooperativa.ecoxarxes.cat/file/view/247274/esbozo-articulos-plastico-impresoras3d)** por Elle Flâne

-   [Opinión de Richard Stallman sobre el hardware libre]http://features.linuxtoday.com/news_story.php3?ltsn=1999-06-22-005-05-NW-LF

-   [Free Hardware Design - Past, Present, Future](http://www.opencollector.org/Whyfree/freedesign.html) por Graham Seaman

-   [The economics of Free Core development](http://www.free-ip.com/Economics.htm) por David Kessner

-   [Open-source IP could ignite system-on-chip era](http://www.eetimes.com/story/speakout/OEG20000131S0007) por David Kessner

-   [Business Models for Open Source Hardware Design](http://pages.nyu.edu/\~gmp216/papers/bmfosh-1.0.html) por Gregory Pomerantz

-   [Free chips for all - The status of open hardware designs](http://www4.ibm.com/software/developer/library/openhw.html?dwzone=opensource) por Jamil Khatib

-   [Open Hardware and Free Software](http://www.opencollector.org/Whyfree/whyfree.html)

-   [Extending the Freedoms of Free and Open Information](http://www.opencollector.org/Whyfree/vilbrandt.html) por Carl Vilbrandt, diseñador de GnuBook.

-   [Challenge to Silicon Valley](http://news.com.com/2010-1069-964507.html?tag=lh) por Kofi Annan

-   *Liberalidad del conocimiento desde la cesión de derechos de propiedad intelectual* por J. M. León Rojas

-   [Inteligencia Colectiva, la revolución invisible](http://www.adin-noticias.com.ar/libros03.htm) por Jean-François Noubel

-   [Wikipedias versus blogs: La creación colectiva y el acceso universal al conocimiento](http://www.bubok.com/libros/172033/Wikipedias-versus-blogs) por Xavier Casas Canals

-   [Cultura libre](http://meta.wikimedia.org/wiki/w:es:Cultura_libre_(libro)) por Lawrence Lessig

-   “La industria de la música en la era digital: Participación de los consumidores en la creación de valor.” por D. Chaney

[^1] https://es.wikipedia.org/wiki/Homebrew_Computer_Club

[^2] http://www.webopedia.com/TERM/F/FPGA.html

[^3] http://www.nationmaster.com/encyclopedia/Challenge-to-Silicon-Valley)

[^4] http://www.opencollector.org/history/OpenDesignCircuits/index.html)

[^5] http://www.oepm.es/es/propiedad_industrial/propiedad_industrial

[^6] http://stallman.org

[^7] http://www.fsf.org

[^8] https://www.gnu.org/licenses/licenses.es.html

[^9] http://www.linuxtoday.com/infrastructure/1999062200505NWLF

[^10] http://www.opencollector.org/Whyfree/freedesign.html

[^11] http://www.oshwa.org/

[^12] http://www.openhardware.net/

[^13] https://www.gnu.org/copyleft/gpl.html

[^14] http://www.freemodelfoundry.com/

[^15] http://www.uv.es/leo/sparc/

[^16] http://opencores.org/

[^17] http://opensource.org/licenses/MIT

[^18] http://web.media.mit.edu/\\\~rehmi/freeip.html

[^19] http://www.debian.org/News/2000/20001123.en.html

[^20] http://blog.openlibrary.org/tag/gnubook/

[^21] http://www.simputer.org/simputer/license/

[^22] http://f-cpu.seul.org/

[^23] http://opencores.org

[^24] http://www.opencollector.org/hardlicense/msg00007.html

[^25] https://joinup.ec.europa.eu/software/page/open_source_licences_and_complementary_agreements

[^26] http://www.opencollector.org/hardlicense/hdpl.html

[^27] http://www.opencollector.org/hardlicense/licenses.html

[^28] http://www.opencollector.org/hardlicense/hdpl.html

[^29] http://www.ohwr.org/projects/cernohl/wiki

[^30] http://www.marketwired.com/press-release/adafruits-limor-fried-phillip-torrone-featured-keynotes-for-make-conference-1649479.htm

[^31] https://www.adafruit.com

[^32] http://www.arduino.cc

[^33] http://www.chumby.com

[^34] http://www.liquidware.com

[^35] https://www.makerbot.com

[^36] http://en.wikipedia.org/wiki/Crowdfunding

[^37] http://p2pfoundation.net/Open_Source_Hardware_Reserve_Bank

[^38] http://www.openmoney.org

[^39] http://metacurrency.org

[^40] http://opendesignnow.org/index.php/visual_index/manifestos

[^41] http://sindominio.net/hackmeeting/wiki/2014

[^42] http://giss.tv/dmmdb/index.php?channel=hardmeeting

[^43] https://calafou.org/es/contenthackthearth-2013-jornadas-autosuficiencia

[^44] http://xctit.cooperativa.cat/encuentros/extrud_me-2014

[^45] http://2013.oshwa.org

[^46] http://www.ccc.de/en

[^47] http://www.oswash.org/

[^48] http://medialab-prado.es

[^49] http://www.laboralcentrodearte.org

[^50] http://hangar.org

[^51] http://www.befaco.org

[^52] http://faboratory.org

[^53] http://pechblenda.hotglue.me

[^54] http://xctit.cooperativa.cat

[^55] http://cooperativa.cat/

[^56] "In the Next Industrial Revolution, Atoms Are the New Bits."

[^57] http://www.openhardware.net/

[^58] http://www.publico.es/418911/la-gente-se-sentiria-molesta-si-viera-de-donde-viene-su-iphone
