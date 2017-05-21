# Descentralización y redes sociales 
## Hellekin 

![](media/image7.png)

Aún prácticamente desconocido por el público hace dos décadas, el término «red social» aparece hoy como una innovación de la **Web 2.0** [^1]. No obstante, se trata de un concepto muy anterior al fenómeno de concentración mercantil de los instrumentos que se dedican a las redes sociales. En 1933, el sociólogo Jacob Levy Moreno [^2] introdujo el sociograma, una representación gráfica de las relaciones interpersonales en las que cada nudo es un individuo y cada lazo una relación social.

El término «red social» apareció por primera vez en 1954 en un artículo del profesor John Arundel Barnes [^3] para concluir su investigación sobre las relaciones sociales en un pueblo de pescadores noruegos.

Howard Rheingold [^4], pionero en las comunidades virtuales y cronista visionario de los cambios sociales inducidos por las tecnologías de la información y de la comunicación, subraya cómo: *«Algunas personas confunden las redes sociales, que son la suma de las relaciones humanas, con los servicios en línea para las redes sociales como Facebook y, puede ser, G**+***».Tal confusión establece el servicio como origen de la red social, a pesar de que su rol esté limitado en el mejor de los casos a facilitar su emergencia.

### ¿Red centralizada, descentralizada, distribuida? 

Estos conceptos evolucionaron a partir del artículo de Paul Baran [^5] dedicado a las diferentes topologías de redes de comunicación [^6]. En el siguiente apartado se presentan sus características desde un enfoque más social que técnico.

Se dice de una red que es centralizada cuando su integridad depende de un actor, y que sin él, la red no puede funcionar. Tal arquitectura tiene numerosas ventajas para la integración vertical de los servicios, en particular porque tiene un polo de decisión única, y porque la solución técnica tiende a la uniformidad. Este modelo combina una utilización simplificada, la facilidad de desarrollo y la estabilidad del sistema; sin embargo, impone una posición especial del suministrador de servicio lo que le permite observar a sus usuarios y analizar su proceder.

Propone, entonces, poca o ninguna protección o consideración para el derecho a la privacidad de sus usuarios.

Una red descentralizada no depende de un polo único de decisión, aunque cada miembro de la red no es necesariamente autónomo, y puede depender de la disponibilidad de un servidor que le une al resto de la red; la federación es el modelo típico de la red descentralizada, el correo electrónico o las redes de chat [^7] son por ejemplo sistemas federados descentralizados. Este modelo es perfecto para organizaciones que pueden mantener sus propias infraestructuras de comunicación y prefieren controlar sus comunicaciones. Pero presenta la misma problemática que una red centralizada respeto al rol del intermediario todo-poderoso (en términos de seguridad informática, el «**man in the middle**» [^8]).

Cuando cada nodo de la red descentralizada es autónomo, se habla de red distribuida: es el modelo de red de pares (P2P) como Bittorrent [^9], GNUnet [^10], Tor [^11], I2P [^12], cjdns [^13], o Bitcoin [^14]. Este modelo es el más robusto contra la agresión de un poder centralizado (observación, censura, manipulación), porque no permite ningún ángulo de ataque, ni blanco especial, no dispone de un «punto único de fallo», como pasa con los modelos anteriores. Sin embargo, su realización es mucho más difícil que la de un servicio centralizado, sobre todo por el tema de la heterogeneidad y de la complejidad del campo.

Estas arquitecturas no se oponen necesariamente entre ellas [^15]. La contradicción radica más bien en la decisión de proteger la privacidad de los usuarios o al contrario, establecer su vigilancia. El enfoque dominante actual de los instrumentos para las redes sociales depende radicalmente de la vigilancia de los usuarios, y por consiguiente, busca una arquitectura centralizada y propietaria, favorable a su control.

Tampoco hay que confundir la capacidad de «exportar» datos con su «portabilidad», ni su disponibilidad. La exportación de datos de un servicio o de una aplicación funciona la mayoría de las veces en circuito cerrado. Alienados de su contexto, estos datos exportados solo son un montón de ficheros inertes, ya que es su inscripción en un contexto social lo que les da vida (su conexión con datos parecidos o relativos, los comentarios de otros usuarios, el enriquecimiento de los conocimientos con la conversación incesante crea una interdependencia entre las diversas fuentes).

Así, más allá de un guión técnico, a menudo abstracto e incompleto considerando sólo un aspecto formal de la red, es necesario reconocer los fundamentos y la complejidad de las consecuencias éticas, sociales, políticas y económicas de las tecnologías que dan soporte a la sociabilidad de los individuos y de las colectividades.

### ¿Qué hacer?: Software libre y redes libres 

El Apocalipsis según Snowden (sus revelaciones escandalosas sobre la NSA) confirma lo que dicen, desde hace 30 años, los programadores de software libre [^16]. Para valorar la seguridad de un sistema, es imprescindible que éste pueda ser observado. Un sistema no verificable es por definición un acto de fe con su creador, como ya prevenía con razón Ken Thompson en 1984 [^17]. Un sistema informático del que no se puede estudiar el código fuente no puede ser considerado como seguro [^18]. El software libre [^19], en el sentido dado por la **Free Software Foundation** [^20] y el proyecto GNU [^21], significa que su usuario dispone de cuatro libertades fundamentales: 0) usar el software según su propia voluntad; 1) estudiar el funcionamiento del software (a través de su código fuente); 2) compartir el software libremente e incluso comercializarlo; 3) modificar el software según sus necesidades y distribuir estas modificaciones libremente. Estas cuatro libertades fundamentales permiten al usuario la apropiación libre de los software, es decir, su control; esto favorece la valoración del código entre iguales, como los trabajos científicos. Se trata, entonces, de software eminentemente político, desarrollado en el seno del interés general.

El campo del software libre que propone alternativas para las plataformas propietarias todavía es bastante experimental. Pero su efervescencia demuestra la posibilidad de poder contar con herramientas de gestión de las redes sociales que no sean, ni propietarias, ni liberticidas. Que vengan de la Web, y orientadas hacia una descentralización federada, o que vengan de la red de pares (P2P), apuntando hacia un modelo más distribuido entre nodos autónomos, estas iniciativas se oponen por definición a la vigilancia de los usuarios y fomentan sus libertades.

El proyecto GNU consensus [^22] tiene como objetivo fomentar y coordinar el desarrollo de software libre de carácter social. Considerando que una entidad hostil [^23] participa activamente de la red, el proyecto recomienda que cada nodo de la red pueda protegerse de esta amenaza, y proteger también a sus interlocutores legítimos. En este ámbito, la mayoría de alternativas disponibles procuran poca protección en contra de los atacantes más sofisticados. Sin embargo, permiten una transición necesaria desde las plataformas propietarias, porque estas, por definición se ven comprometidas ya que participan de la vigilancia global. La encriptación sistemática de los datos y la protección de las interacciones sociales de cada uno forman parte de los elementos necesarios para una alternativa fuerte y viable. GNU consensus promueve la adopción a largo plazo de la plataforma de red de pares GNUnet [^24], y su complemento para las redes sociales llamado Secushare [^25], todavía en fase de investigación.

Hasta que sea disponible GNUnet para el público en general, el proyecto también se empeña en identificar las soluciones capaces de facilitar el éxodo de los usuarios de los servicios propietarios hacia las soluciones libres. Es importante destacar que si este proyecto considera GNUnet como la referencia que hay que seguir, no excluye la diversidad de los enfoques. Así, el proyecto promueve también software que facilitan una solución parcial, intentan identificar sus limitaciones y reconocer sus ventajas.

La siguiente sección da una vista parcial de las problemáticas proyectadas y de las posibles soluciones alternativas. El sitio del proyecto GNU consensus ofrece una visión más elaborada y actual. El lector puede también remitirse a la lista colaborativa mantenida por el sitio de Prism Break [^26] que ofrece una correspondencia entre las aplicaciones y servicios propietarios, y las alternativas libres.

### Problemática y alternativas emancipadoras 

**Publicación**: La forma más corriente de publicación personal sigue siendo el blog, y los comentarios forman conversaciones ricas dentro de la «blogosfera»; el wiki también ofrece una forma de publicación colectiva en la que el aspecto social es más discreto. Sin embargo, estas dos formas involucran comunidades más bien especializadas y literarias. Por otra parte, involucran sobre todo las interacciones públicas.

**Exhibición y rumor**: Facebook es el ejemplo más conocido para el intercambio de experiencias sociales. Twitter supo combinar la brevedad de los SMS con la Web para crear uno de los servicios más populares y adictivos de la Web. Google+ ofrece un intermedio entre los dos.

La «monetización» de los beneficios y la apropiación mercantil de los contenidos depende de la voluntad de los usuarios de someterse a la la máquina de vigilancia intercambiando unas ventajas percibidas como una sumisión demasiado abstracta, olvidándose de las consecuencias: exhibicionismo a ultranza, delación trivializada, esclavitud voluntaria, difusión del capital social hacia los circuitos capitalistas superfluos. Las consecuencias de la amplificación de las conversaciones más allá de las simples premisas «¿qué estás haciendo?» Permite la captura de una parte importante de la sociabilidad de las redes hasta tal punto que muchos usuarios de Facebook hoy confunden este servicio con «el Internet».

Los «clones de Twitter» siguen siendo incompatibles en su mayoría con el original, así lo quiere la política de la empresa, pero están trabajado para la interoperatividad: entre ellos están GNU social [^27], Friendica [^28], Pump.io [^29]. Una solución distribuida que usa la misma tecnología que Bitcoin también está en su fase experimental: Twister [^30].

**Conversaciones y organización colectiva:** La mayoría de las soluciones alternativas existentes se presentan bajo la forma de silos incompatibles entre sí. Estas soluciones sobrepasan, sin embargo, el motivo de la logorrea para proponer medios de organización colectiva. Podemos nombrar algunos ejemplos como Elgg [^31] y Lorea [^32], Crabgrass [^33], Drupal [^34], y la Web Independiente [^35], que hace a la vez de pionera en la definición y en la adopción de estándares de la Web Semántica y de resistente a la tendencia centralizadora de los mercaderes.

**Telefonía y videoconferencia:** Skype, desde su compra por Microsoft, ha pasado al rango de colaboradores directos de la NSA. Google Hangouts es accesible sólo por los usuarios de Google. En los dos casos, podremos usar ventajosamente la alternativa Jit.si [^36], o esperar la llegada del Project Tox [^37] .

**Mensajería:** El correo electrónico sigue siendo una de las aplicaciones más difundidas. El uso de GnuPG permite la encriptación de los mensajes pero no protege a la fuente, al destinatario, ni el sujeto del mensaje (el proyecto LEAP [^38] busca la solución a este problema). La dominación de Google en este servicio con Gmail y GoogleGroups merma de forma considerable su aspecto federativo. Mientras esperamos usar soluciones especializadas como Pond [^39], I2P-Bote [^40], o BitMessage, se recomienda usar un servicio de mail autónomo que fomenta la privacidad, tipo Riseup [^41] o Autistici [^42], o montar su propio servidor.

**Compartir vídeos:** La supremacía de Youtube (otra vez Google) en este ámbito deja a sus competidores muy atrás. Dada la enorme infraestructura necesaria para el tratamiento y el envío de ficheros de vídeo, este servicio no tiene muchas alternativas. GNU MediaGoblin [^43] le permite a un sitio gestionar sus medias y soporta los formatos libres de vídeo. Un nuevo proyecto, Wetube, hace la promesa de innovar y reemplazar Youtube por una red distribuida usando un enfoque similar al de Twister que se basa en una cadena de bloques, y ofrece a los participantes la zanahoria de una remuneración correspondiente al ancho de banda compartido.

**Compartir música:** La referencia propietaria sigue siendo SoundCloud. Parece que hay poco interés para crear una alternativa libre a este servicio. GNU MediaGoblin también acepta los ficheros de audio, y podría tener este rol. Los aficionados a la música, pueden usar Bittorrent teniendo cuidado con descargar torrents legales y eliminar de su conexión, con listas de bloqueo (blockslists) los nodos especializados en la caza de internautas o la diseminación de software contaminados.

### Otros ejemplos pertinentes para imaginar futuras aplicaciones e implicaciones. 

**Aplicación estática:** El proyecto UnHosted [^44] propone restablecer la descentralización de las aplicaciones Web separando la ejecución del código con los datos afectados. Estos se quedan bajo el control del usuario, y las aplicaciones se ejecutan en el navegador y no en un servidor.

**Compartir el código:** Github ofrece un contra-ejemplo de servicio propietario social. Su contribución al mundo del software libre nos enseña que es posible encontrar un mercado cuya explotación comercial no pasa ni por el comercio de los datos de los usuarios, ni por ninguna restricción de su libertad. Sin embargo, tiene dos serios competidores, Gitlab y Gitorious, y existe incluso una versión P2P, Gitbucket. ¡El código fuente de Gitlab y de Gitbucket se encuentra en Github! El modelo de Github puede servir de idea para el «comunismo empresarial» propuesto por Dmytri Kleiner [^45] .

**Videojuegos masivos compartidos en línea:** Los MMORPGs [^46] son también lugares de encuentro y de sociabilidad. Si es más fácil de hablar de las cosas de la vida en Second Life, las relaciones sociales existen en World of Warcraft o Minecraft. Solo que estos mundos virtuales generan una economía y una franja de sociedad primermundista que le son propias. Son lugares donde el anonimato no es un problema, sino que es casi una obligación: ¿quién quiere saber que el gran mago Krakotaur pasaba su juventud perforando tarjetas para darle de comer a un ordenador del tamaño del hall de un palacio? Si les apetece, pueden unirse a PlaneShift [^47] o a los universos de desarrollo de CrystalSpace [^48] para imaginar el futuro de los juegos de inmersión libres.

### Conclusiones 

El gran desafío de las redes libres se une al del software libre: aquel de la autonomía y de su perennidad. El apoyo financiero de los desarrollos, por una parte, y el marketing de la soluciones, por la otra, se encuentran en el corazón de las problemáticas que limitan su autonomía. La infraestructura necesaria para la liberación de los ciudadanos internautas debe venir prioritariamente de los mismos usuarios. Puede hacerse autónoma, sólo si sus usuarios la asumen, como asumen otros recursos necesarios para la preservación de la comunidad. El desarrollo sostenible y la disponibilidad de una infraestructura pública y social de comunicación sólo puede crearse si una masa crítica de participantes percibe la soberanía tecnológica como un bien común.

La omnipresencia del todo gratuito esconde capitales colosales invertidos por las empresas para capturar sus auditorios. El todo gratuito es una manera de matar a los competidores: porque en este juego sólo pueden jugar los que ya tienen grandes reservas financieras. Sin embargo, después de las revelaciones de Snowden, exponiendo la extensión de la vigilancia global, podemos ver algunas consecuencias en la evolución de las costumbres de uso de las herramientas de búsqueda [^49] o en el rebrote de atención por parte de algunas instituciones respeto al software libre. Esta tendencia tiene que acompañarse con una posición por parte de los usuarios en sus elecciones tecnológicas, materiales y de software, y en su decisión de apoyar los esfuerzos de desarrollo alternativo.

¡La campaña anual de financiamiento de Wikipedia anuncia que si cada persona leyendo su anuncio contribuyera con sólo tres dolares, ésta se terminaría en dos horas! Es esta realidad del poder de los grandes números que nos hace falta encontrar para alcanzar a materializar una visión democrática de Internet libre y público. Si el ciudadano, aislado como individuo, no tiene gran cantidad de dinero, las campañas de crowdfunding (financiación masiva) permiten recaudar rápidamente los fondos necesarios para un proyecto dado.

El crowdfunding sigue siendo, sin embargo, una forma de prestación de los recursos que pertenece al consumo: el «financiador» es un comprador que paga con antelación el producto que le proponen. Al contrario, una campaña de este tipo debería ser una inversión para reforzar la infraestructura pública generada. Este es el argumento que desarrolla Dmytri Kleiner en el **Manifiesto Telecomunista.** Cada comunidad debería poder gestionar su propia inversión, como ya lo proponía en 2009 el proyecto Lorea.

Está claro que las elecciones de orden tecnológico depende de una élite apta para el análisis técnico, y las innovaciones científicas son permanentes. Pero la elección ética no depende de la capacidad técnica. Si los técnicos conocen la orientación ética de una comunidad, deberían verse capaces de tomarla en cuenta en su análisis. La vigilancia global surgió porque es técnicamente posible, y porque esa elección técnica se realizó sin restricciones de orden ético o legal, con total impunidad.

Software libre, servicios descentralizados, distribuidos, reproducibles y comunitarios, nodos autónomos, participación e inversión son las claves de una infraestructura de comunicación pública, sostenible y sana, no sólo susceptible de preservar la vida privada de los ciudadanos, proteger la libertad de los individuos y de los pueblos en lucha contra regímenes totalitarios, sino también de forjar las bases de la democracia del siglo XXI para enfrentarse juntos, en la pluralidad y en la diversidad de las situaciones individuales y colectivas, a las inmensas problemáticas planetarias.

El porvenir de las redes sociales empieza en su base: es decir, nosotros mismos.

* * * 

**Hellekin,** es el mantenedor oficial del proyecto GNU consenso. Desarrollador en sus tiempos perdidos, activista a tiempo completo, navega por las redes y los continentes en busca de soluciones para el empoderamiento de la raza humana desde sus ideales libertarios. En su base en América Latina, ayuda a construir una comunidad e una infraestructura pública para las redes de comunicaciones electrónicas afín de defender y promover las iniciativas locales y descentralizadas. *GnuPG: 0x386361391CA24A13 hellekin[at]cepheide[dot]org*

* * * 

[^1] La web 2.0 es un concepto mercantil inventado para valorar la aparición de sitios interactivos de carácter social. El «2.0» no representa aquí ninguna característica técnica, pero busca la huella de la obsolescencia de lo que existe, es decir la Web original, red entre iguales y descentralizada.

[^2] https://es.wikipedia.org/wiki/Jacob_Levy_Moreno

[^3] Barnes, John (1954) “**Class and Committees in a Norwegian Island Parish**”, en Human Relations, (7), pp 39-58

[^4] https://es.wikipedia.org/wiki/Howard_Rheingold

[^5] https://fr.wikipedia.org/wiki/Paul_Baran

[^6]Baran, Paul (1962) “**On Distributed Communications Networks**”, presentado en el Primer Congreso de las Ciencias de los Sistemas de Información, organizado por MITRE

[^7] La «charla», ha sido posible por el bajo coste de las comunicaciones numéricas que se obtienen usando los protocolos **Internet Relay Cha**t (IRC) y **eXtensible Messaging Presence Protocol** (XMPP), mucho antes que aparecieran aplicaciones propietarias y limitadas como MSN o Facebook **chat**.

[^8] https://es.wikipedia.org/wiki/Ataque_Man-in-the-middle

[^9] https://es.wikipedia.org/wiki/BitTorrent

[^10] https://es.wikipedia.org/wiki/GNUnet

[^11] https://es.wikipedia.org/wiki/Tor

[^12] https://fr.wikipedia.org/wiki/I2P

[^13] http://cjdns.info

[^14] https://fr.wikipedia.org/wiki/Bitcoin

[^15] Un servicio centralizado usa muchas veces la distribución en su propia estructura para asegurarse su expansibilidad a gran escala.

[^16] La FSF cumple en 2014 treinta años desde su creación.

[^17] Thompson, Ken (1984) “**Reflections on Trusting Trust**”, URL: http://cm.bell-labs.com/who/ken/trust.html (Ver el uso tendencioso de la palabra 'hacker' en su aceptación maliciosa, y como sus reflexiones se aplican hoy a los abusos de los servicios secretos).

[^18] La complicidad de los gigantes del software propietario en la vigilancia global llevada a cabo por la NSA debería hacer de este punto algo indudable.

[^19] Stallman, Richard (1996), “Qu'est-ce que le logiciel libre ?” (¿qué es el software libre?), URL: https://gnu.org/philosophy/free-sw.fr.html

[^20] http://www.fsfla.org/ikiwiki

[^21] https://gnu.org/home.fr.html

[^22] https://gnu.org/consensus

[^23] Forajidos: criminales y spamers, servicios secretos, corporaciones y gobiernos totalitarios...

[^24] https://gnunet.org

[^25] http://secushare.org

[^26] http://prism-break.org/fr

[^27] https://gnu.org/s/social

[^28] http://friendica.com

[^29] http://pump.io

[^30] http://twister.net.co

[^31] http://www.elgg.org

[^32] https://lorea.org

[^33] https://we.riseup.net/crabgrass

[^34] https://drupal.org

[^35] http://indiewebcamp.com

[^36] http://meet.jit.si para el servicio, http://jitsi.org para el software.

[^37] http://tox.im tiene como objetivo el reemplazo de Skype por una solución libre.

[^38] https://leap.se/fr

[^39] https://pond.imperialviolet.org

[^40] https://es.wikipedia.org/wiki/I2P

[^41] https://help.riseup.net/es/email

[^42] http://www.autistici.org/fr/index.html

[^43] https://gnu.org/s/mediagoblin

[^44] https://unhosted.org

[^45] Kleiner, Dmytri (2010), “El manifiesto telecomunista»”, URL: http://telekommunisten.net/the-telekommunist-manifesto

[^46] MMORPG: Massively Multiplayer Online Role Playing Games, o Videojuegos de rol multijugador masivos en línea.

[^47] http://www.planeshift.it

[^48] https://es.wikipedia.org/wiki/Crystal_Space

[^49] StartPage, Ixquick y DuckDuckGo han multiplicado por cinco la afluencia a sus motores de búsqueda después publicarse en diciembre de 2013 diferentes artículos en Der Spiegel y The Guardian.

