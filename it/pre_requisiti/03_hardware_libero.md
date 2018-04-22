# Sull'hardware libero e il riappropriarsi della tecnologia

*Elle Flâne*

![3dprinter](../../es/content/media/free-hw.png)	

Il concetto di hardware è abbastanza nuovo, molto ampio, in continuo cambiamento e spesso in direzione diametralmente opposta al software. E' in atto una discussione sulla natura dell'hardware, su cosa sia e non sia: in assenza di una definizione comune ognuno lo interpreta a modo proprio. Ad esempio, per me, l'hardware comprende un componente elettronico, un condensatore, un transistor, un LED, un circuito integrato, un dispositivo quale un moto-aratro, la descrizione di un processo industriale, come la fabbricazione di un mattone refrattario, un computer, una stampante 3D, un meccanismo per la purificazione dell'acqua scritto in codice sorgente aperto, un processo per il riciclo della plastica, l'assemblaggio di una fresatrice CNC, un metodo di analisi dei suoli inquinati mediante sensori o il codice di un microcontrollore. 

Ma se diamo una occhiata più da vicino, si può dire che la storia dell'Hardware Libero corra parallela a quella dei computer. Nel 1970, l'Homebrew Computer Club[^1] fu un'entità ibrida composta dal movimento studentesco radicale, imprenditori della comunità informatica dell'università di Berkeley e hobbysti. 
E' buffo come molti di quei garage, prima pieni di creatività, siano ora musei, ad esempio quello di Bill Hewlett e Dave Packard, dove è stato sviluppato il primo dispositivo HP. Negli anni '90, nello stesso modo in cui si condivideva il software, l'FPGA [^2] consentiva lo scambio digitale di disegni liberi. La Open Design Circuits [^3] lanciata da Reinoud Lamberts, è il primo sito web di una comunità di progettisti hardware con lo spirito del software libero. E nonostante non ci fosse ancora un software libero adeguato per la progettazione elettronica, questo portale coinvolse molte persone ponendo le basi per una comunità più ampia. Nel 2002, l'iniziativa "Challenge to Silicon Valley" [^4] promossa da Kofi Annan ha lanciato diversi progetti di sviluppo di hardware libero e reso più visibile la necessità di sviluppare tecnologie adeguate a differenti realtà socioculturali e economiche. Quella linea di sviluppo tecnologico si è quindi legata alla lotta contro il digital divide attraverso iniziative come ICT4Development. Si trattava generalmente di collaborazioni tra università e terzo settore, per creare tecnologie adatte ai bisogni di paesi erroneamente definiti "in via di sviluppo". Tuttavia, oggi le prospettive di produzione hardware sono fortemente limitate da brevetti e proprietà industriale [^5]: l'insieme di diritti che una persona fisica o giuridica detiene per un'invenzione. Sono essenzialmente due: il diritto di utilizzare l'invenzione, il progetto o logo, e il diritto di vietare a terzi di farlo. Il divieto (*Ius prohibendi*) consente al titolare di richiedere il pagamento di una licenza, denominata royalty, o di canoni, con limitazioni temporali e territoriali.


### Hardware Libero: Fin a che punto e come?

Va tenuto presente che l'hardware libero richiede quasi tutte le seguenti componeti: un disegno, un processo di produzione, alcune materie prime, la distribuzione, il modello di business, di manutenzione, di replicabilità, la forza lavoro, l'accesso alla documentazione e alla tecnica di produzione. Partendo da questo contesto, se cerchiamo una definire dobbiamo considerare tutte le tappe del processo produttivo correlate a tutti i possibili soggetti sottoposti a licenze libere.
Lo stesso Richard Stallman [^6], presidente della Free Software Foundation [^7] e creatore della GNU GPL [^8] ( garante delle quattro libertà: di utilizzo, studio e modifica, distribuzione e redistribuzione delle versioni modificate), afferma che "l'idea di software libero può essere applicata ai file o agli archivi necessari per la progettazione e le specifiche (schemi, PC, ecc), ma non al circuito fisico in sé" [^9]. 
Esite inoltre un hardware "statico", composto di elementi materiali o elettronici tangibili, e un hardware "riconfigurabile" attraverso un linguaggio di programmazione, con codice sorgente scritto in unfile di testo. Pertanto, le parole "hardware" e "progettazione hardware" sono due cose diverse. Il disegno e l'oggetto fisico non possono essere confusi, anche se a volte si fondono.
Tutti questi fattori rendeno complesso descrivere che cosa sia l'hardware libero. E' vero che i singoli componenti e le fasi di produzione possono essere adatte alle quattro libertà del software libero, ma attualmente nessun progetto riesce a coprire l'intera catena con passaggi rigorosamente liberi. Dunque per ora utilizziamo il termine hardware libero/aperto, ma senza dover applicare le quattro libertà per tutta la sfera produttiva. Esistono molte iniziative consolidate in questo campo, anche se i modelli di utilizzo e approccio sono diversi a seconda delle motivazioni sociali, economici e politiche di ogni gruppo o comunità.
Esitono dunque una miriade di licenze, che cercano di chiarire questi problemi. Ad esempio, il Free Hardware Design [^10] copre disegni che possono essere copiati, distribuiti, modificati e prodotti liberamente. Ciò non implica che il progetto non possa essere venduto, o che ogni genere di progettazione hardware sia gratuita. Il Libre Hardware Design è uguale al Free Hardware Design, ma chiarisce che la parola "libre" si riferisce alla libertà, non al prezzo. L' Open Source Hardware [^11] mette tutte le informazioni per la progettazione a disposizione del pubblico in generale, e può essere basato su hardware con design libero, o limitato in qualche modo. L'Open Hardware [^12], un marchio registrato della Open Hardware Specification Program, è una forma limitata di Open Source Hardware, l'unico requisito è fornire una quantità limitata di informazioni di progettazione utili per le riparazioni. Infine, in un tentativo di sintesi, Patrick McNamara ha definito per l'Open Hardware in base al livello di "apertura":


1. Interfaccia aperta: l'utente ha tutta la documentazione che illustra come un pezzo di hardware svolga la funzione per cui è stato progettato.

2. Design aperto: la documentazione disponibile è sufficientemente dettagliata affinchè una terza parte possa creare un dispositivo funzionale e compatibile.

3. Fabbricazione aperta: disponibile l'elenco di tutti i materiali necessari per la costruzione del dispositivo.

Nello scenario attuale dell'hardware libero esiste una grande varietà di licenze.
Ci sono gruppi che usano la GNU GPL [^13] come la Free Model Foundry [^14] per la simulazione di modelli, componenti e testing; ESA Sparc [^15] che ha creato un CUP per 32bits o Opencores [^16], una comunità che sviluppa IP core.
Altri gruppi usano la licenza Open Source Initiative del MIT [^17] come il Free-IP Project [^18] e LART [^19]; per quanto riguarda la licenza GNUBook [^20], è basata sulla licenza GPL ma con aggiunte riguardanti i diritti ambientali e umani.
Esistono anche gruppi che sviluppano nuove licenze, come la Simputer GPL [^21], Freedom CPU [^22], OpenIPCores [^23], la OHGPL [^24], The Open NDA [^25], la OpenPPC [^26] (basata sulla Apple Public Source License) e la Hardware Design Public License [^27] del gruppo Open Collector [^28]. Distinguiamo tra le altre la Licenza Hardware del CERN OHL [^29] scritta originalmente per la progettazione del CERN (l'acceleratore di particelle) elecato nel Repository Open Hardware.

### Modelli di business e sostenibilità derivati dall'open hardware

Secondo Wired, la Bibbia del tecnopositivismo, l'Open Hardware sta diventando una “commodity”, ovvero una merce. Anche se non esiste ancora un modello di business chiaro, si capisce che può servire mercati di nicchia che non sono stati finora coperti, applicando la logica della "long tail", coda lunga o distribuzione di beni e servizi hardware (il modello Amazon) dalle dimensioni pressoché infinite. Per quanto riguarda la commercializzazione, la progettazione con hardware libero può essere realizzata da una società per promuovere il proprio mercato, l'unica premessa è mantenere il progetto libero.
Nel 2010, Torrone e Fried [^30] hanno raccolto 13 esempi di aziende che vendono Hardware Open Source fatturando in totale 50 milioni di dollari. Attualmente ci sono più di 200 progetti di questo tipo e si prevede che la comunità di Open Source Hardware fatturerà miliardi nel 2015. Adafruit [^31], Arduino [^32], Chumby [^33], Liquidware [^34] e Makerbot [^35] hanno entrate pari a più di un milione di dollari ciascuno. Tutto questo dimostra che ci sono quindi le possibilità per generare reali guadagni economici con progetti che basano le loro attività sul rendere noto e condividere il design con la comunità.

Ora, ciò che è meno chiaro: è possibile esercitare una vera politica anticapitalista sulla base di un progetto economico e di ri-distribuzione delle attività legate ad una logica di sostenibilità e decrescita?
Un modello interessante per l'open hardware risiede nel crowdfunding [^36], cioé nel raccogliere piccole quantità di individui o gruppi per avviare un progetto. Huynh e Stack hanno creato, ad esempio, la Open Source Hardware Reserve Bank [^37] per coprire i costi connessi alle revisioni hardware in corso durante un progetto: si stima sia il 40% del bilancio iniziale necessario. L'idea è ridurre i rischi per i progetti di hardware libero prima di passare alla fase di produzione. Inoltre facilitano la sperimentazione consentendo la costruzione e la distribuzione di piccole quantità di prodotti considerati "non scalabili", perché "una pessima idea di business" non è la stessa cosa che "una brutta idea hardware".

Un altro esempio è l'Open Source Hardware Reserve Bank che permette solo ad hacker, non a chi fa investimenti di capitali di rischio o di altre società, di investire in progetti specifici per raddoppiare il numero di pezzi prodotti e riducendo il costo unitario dal 10 al 30% circa. 
Da notare anche che una comunità può anche autofinanziare i propri progetti attraverso il microcredito. Open money [^38] e Metacurrency [^39] propongono nuove forme di valuta, e cercano di promuovere il legame tra monete esistenti e certificati di microcredito.

E infine, l'Open Design Manifesto [^40] che unisce le due tendenze. Da un lato, le persone applicano le loro competenze e il tempo in progetti per il bene comune, di solito inesistenti a causa della mancanza di interesse commerciale. E fornisce inoltre un quadro di riferimento per lo sviluppo di progetti e tecnologie avanzate che potrebbero essere al di là delle risorse di qualsiasi azienda o paese, coinvolgendo persone che senza il meccanismo del copyleft non si sentirebbe motivata a collaborare. 

Analizziamo ora alcune problematiche relative alla sostenibilità dell'hardware libero.

Da un lato, la mancanza di consenso sulla definizione di hardware libero è applicata anche ai possibili modelli di business. Un dispositivo aperto è diverso da ciò che esiste e domina il mercato e la cosa importante non è il prodotto finito (hardware prodotto), ma le attività immateriali, le informazioni riguardanti la progettazione dell'hardware, che si apre al pubblico utilizzo. Inoltre, come si è visto in precedenza nell'hardware libero non si possono applicare direttamente le quattro libertà del software libero, data la sua natura diversa, uno ha una esistenza fisica, materiale, l'altro no. Pertanto, un progetto fisico è unico e la condivisione dipende dalla facilità di riproduzione.

Esiste anche una dipendenza tecnologica dai componenti importati, che può essere tradotta come: "I chip sono disponibili?"
Questo è un modello di esclusione imposto e a volte non è possibile realizzare l'hardware a causa delle implicazioni nella creazione di tutte le infrastrutture necessarie. Chi vuole ricreare l'hardware progettato da altri, deve procurarsi i componenti necessari e ricostruire lo schema. Tutto questo ha un costo. Di conseguenza poche aziende sono in possesso di queste conoscenze e le conservano gelosamente, in modo che le persone rimangano mere consumatrici del prodotto.


### Modelli di produzione differenziati

Abbiamo osservato due modelli convenzionali di produzione/distribuzione. Da un lato, il modello di produzione centralizzato con lo stesso prodotto disponibile in molti luoghi, con prezzo maggiorato per chi lo compra. Dall'altra parte, un sistema di produzione distribuito basato su un numero di piccoli gruppi indipendenti che producono lo stesso progetto distribuito localmente. Per diventare sostenibili, in entrambi i modelli, le iniziative di hardware libero necessitano di piattaforme per facilitare l'incontro tra i mezzi di produzione e coloro che desiderano usarli.
Per quanto riguarda il modello distribuito, al momento non ci sono molte comunità che cercano di sviluppare hardware libero alternativo senza obiettivi capitalistici. Questi gruppi dovrebbero cercare di creare autonomia, facilitando l'accesso a chiunque, per invertire gli effetti sociali, ambientali e politici negativi legati alla produzione di hardware proprietario.

Per esempio, ci sono vari incontri promossi dai movimenti sociali, come Hackmeeting [^41], Hardmeeting [^42], HacktheEarth [^43], Extrud_me [^44], o anche come la Conferenza OSHW [^45], la Chaos Computer Conference [^46] o incontri Dorkbot dove incontrare le persone che sviluppano hardware libero. Il progetto OSWASH [^47] (Lavatrici Open Source) rappresenta perfettamente quello che intediamo per ricerca e sviluppo di tecnologie utili, per le quali l'unico hardware sensato è libero: frutto di una riappropriazione da licenze proprietarie, e tornato ad essere aperto.
In Spagna esistono luoghi pseudo istituzionali come Medialab Prado [^48], La Laboral [^49] o Hangar [^50], spesso concentrati sullo sviluppo di hardware libero.Ad Hangar (Barcellona), troviamo BeFaco [^51], che sviluppa strumenti per suonare con hardware libero e FABoratory [^52], specializzato nella produzione di stampanti 3d. In Calafou, c'è la HardLab Petchblenda [^53] un laboratorio di suoni, elettronica e biohacking, visto dall'ottica transfemminista. Infine la XarxaCTiT [^54] (Network of Science, Engineering and Technology) della Cooperativa Integral Catalana [^55] sta sviluppando una piattaforma per lo scambio di conoscenze ed esigenze a livello locale, promuovendo una rete che coinvolga chi produce e chi consuma hardware libero e tecnologie liberate.

In una visione diametralmente opposta e concentrandosi su una strategia globale, mentre non esiste un completo ecosistema di produzione distribuita, Chris Anderson [^56] suggerisce la produzione di progetti open hardware in Cina utilizzando Alibaba.com [^57]. Questa società creata nel 1999, è diventata una società da 12 miliardi di dollari con 45 milioni di utenti registrati e 1,1 milioni di dipendenti. La produzione in Cina è un fenomeno noto come Shanzai. In origine questo termine, definiva "banditi che si sono ribellati all'autorità e impegnati in atti per loro pienamente legittimi."
Il movimento Shanzai nel 2009 produceva il 20% dei telefoni cellulari venduti in Cina, e il 10% a livello mondiale. Tra i produttori c'è chi ha tale successo da preferire promuovere i propri marchi, piuttosto di contraffare quelli altrui. La cosa interessante di queste aziende è che "piratare" prodotti di marca ha creato una cultura di condivisione delle informazioni, volte alla promozione di design aperti, migliorando i prodotti esitenti. E' la comunità stessa che ha formulato questa politica, e esclude quelli che non la seguono. Lo Shanzai capisce e risponde alle esigenze e ai gusti locali, stabilendo e mantenenendo basi di produzione e distribuzione locali, chiamate per l'appunto fabbriche locali. Tuttavia le condizioni di lavoro, in particolare nella creazione di componenti elettrici, sono deplorevoli e rappresentano un rischio per il fisico e la salute [^58] e certo non rivolte alla ricerca di giustizia sociale per i propri lavoratori. La Open Source Hardware Work Licence (ancora da scrivere) dovrebbe integrare come un requisito fondamentale le condizioni rispettose del lavoro delle persone, la loro libertà e il loro ambiente.


### Conclusioni

Utilizzare e creare hardware libero difende e promuove la sovranità tecnologica perché permette l'indipendenza tecnologica delle persone, evitando di dipendere da altri fornitori di risorse per lo sviluppo. Il riutilizzo e l'adattamento dei progetti può innovare e migliorare, ridurre i costi e tempi di progettazione, facilitare il trasferimento di conoscenze e prevenire l'analfabetismo digitale casuato da motivi economici.
Le persone possono smettere di essere semplici consumatrici tecnologiche, essendo libere di conoscere il funzionamento, la manutenzione e la riparazione degli oggetti tecnologici di cui hanno bisogno. Utilizzare e creare hardware libero coinvolge e genera maggiore ricchezza rispetto ad altri paradigmi produttivi, anche se la curva di apprendimento può comportare qualche delusione iniziale. 
Al di là delle proprie convinzioni politiche, libertà significa possibilità, capacità di imparare a costruire il proprio mondo, senza alienarci e prendere parte alle strutture del capitale.
Ció che è appropriato o inappropriato non è un attributo della tecnologia stessa.  Il tuo giudizio sarà influenzato da: 
* (1) l'organizzazione della produzione e del sistema economico
* (2) i livelli e la distribuzione del reddito
* (3) lo stato di sviluppo del sistema della tecnologia in uso
* 
Pensiamo all'equivalmente della desertificazione, ma attraverso la tecnologia: l'obsolescenza programmata, la dipendenza tecnologica e l'introduzione di strumenti inappropriati. La distruzione e ricostruzione su altre basi di questo sistema, sono quasi impossibili se si rimane incatenate al sistema capitalista.

Il mondo dell'hardware libero è molto complesso, le restrizioni e gli abusi insiti nello sviluppo tecnologico non sembrano rispettare la libertà: per questo sono attratta dall'idea di riappropriazione delle tecnologie.
Quest'ultime devono rispondere meglio alle situazioni ambientali, culturali ed economiche. Richiedere poche risorse, costi minori e basso impatto ambientale. Abbiamo bisogno di una vera e propria reindustrializzazione, che comprenda le nostre tecnologie, le tecniche e gli strumenti di uso comune fino alle tradizioni più ancestrali, che di per sé già hanno una base ambientale, sostenibile e olistica. Tecnologia strappata al cieco progresso, all'analfabetismo e alienazione, alla scienza inamovibile, agli interessi del potere; frutto di una riappropiazione perché decentrata, organica, trasmutabile. 

------

*Elle Flâne*

Ingegnera Industriale per la UNED Universidad Nacional a Distancia; Ingegnera Tecnica in Design Industriale dell'Università Elisava Pompeu Fabra; realizza cortometraggi, poesie, quadri, fumetti, novelle fantastiche, invenzioni, +, ++, +++. Sta studiando alla ESA European Space Agency. *elle_flane [at] riseup [dot] net*


---- 

* [**Hardware Libre** https://cooperativa.ecoxarxes.cat/file/view/246449/esbozo-de-articulo-hardware-libre](https://cooperativa.ecoxarxes.cat/file/view/246449/esbozo-de-articulo-hardware-libre) di Elle Flâne

* [**Tecnologías Re-apropiadas** https://cooperativa.ecoxarxes.cat/file/view/246450/esbozo-de-articulo-tecnologias-apropiadas](https://cooperativa.ecoxarxes.cat/file/view/246450/esbozo-de-articulo-tecnologias-apropiadas) di Elle Flâne

* [**Mi conocimiento es plástico** https://cooperativa.ecoxarxes.cat/file/view/247274/esbozo-articulos-plastico-impresoras3d](https://cooperativa.ecoxarxes.cat/file/view/247274/esbozo-articulos-plastico-impresoras3d) di Elle Flâne  

-   [Opinione di Richard Stallman sull'hardware libero http://features.linuxtoday.com/news_story.php3?ltsn=1999-06-22-005-05-NW-LF](http://features.linuxtoday.com/news_story.php3?ltsn=1999-06-22-005-05-NW-LF)

-   [Free Hardware Design - Past, Present, Future http://www.opencollector.org/Whyfree/freedesign.html](http://www.opencollector.org/Whyfree/freedesign.html) di Graham Seaman

-   [The economics of Free Core development http://www.free-ip.com/Economics.htm](http://www.free-ip.com/Economics.htm) di David Kessner

-   [Open-source IP could ignite system-on-chip era http://www.eetimes.com/story/speakout/OEG20000131S0007](http://www.eetimes.com/story/speakout/OEG20000131S0007) di David Kessner

-   [Business Models for Open Source Hardware Design http://pages.nyu.edu/\~gmp216/papers/bmfosh-1.0.html](http://pages.nyu.edu/\~gmp216/papers/bmfosh-1.0.html) di Gregory Pomerantz

-   [Free chips for all - The status of open hardware designs http://www4.ibm.com/software/developer/library/openhw.html?dwzone=opensource](http://www4.ibm.com/software/developer/library/openhw.html?dwzone=opensource) di Jamil Khatib

-   [Open Hardware and Free Software http://www.opencollector.org/Whyfree/whyfree.html](http://www.opencollector.org/Whyfree/whyfree.html)

-   [Extending the Freedoms of Free and Open Information http://www.opencollector.org/Whyfree/vilbrandt.html](http://www.opencollector.org/Whyfree/vilbrandt.html) di Carl Vilbrandt, progettista di GnuBook.

-   [Challenge to Silicon Valley http://news.com.com/2010-1069-964507.html?tag=lh](http://news.com.com/2010-1069-964507.html?tag=lh) di Kofi Annan

-   ”Liberalidad del conocimiento desde la cesión de derechos de propiedad intelectual” di J. M. León Rojas

-   [Inteligencia Colectiva, la revolución invisible http://www.adin-noticias.com.ar/libros03.htm](http://www.adin-noticias.com.ar/libros03.htm) di Jean-François Noubel

-   [Wikipedias versus blogs: La creación colectiva y el acceso universal al conocimiento http://www.bubok.com/libros/172033/Wikipedias-versus-blogs](http://www.bubok.com/libros/172033/Wikipedias-versus-blogs) di Xavier Casas Canals

-   ”Cultura libera” di Lawrence Lessig

-   “La industria de la música en la era digital: Participación de los consumidores en la creación de valor” di D. Chaney


###### NOTE

[^1]: https://es.wikipedia.org/wiki/Homebrew_Computer_Club

[^2]: http://www.webopedia.com/TERM/F/FPGA.html

[^3]: http://www.nationmaster.com/encyclopedia/Challenge-to-Silicon-Valley

[^4]: http://www.opencollector.org/history/OpenDesignCircuits/index.html

[^5]: http://www.oepm.es/es/propiedad_industrial/propiedad_industrial/

[^6]: http://stallman.org/

[^7]: http://www.fsf.org/

[^8]: https://www.gnu.org/licenses/licenses.es.html

[^9]: http://www.linuxtoday.com/infrastructure/1999062200505NWLF

[^10]: http://www.opencollector.org/Whyfree/freedesign.html

[^11]: http://www.oshwa.org/

[^12]: http://www.openhardware.net

[^13]: https://www.gnu.org/copyleft/gpl.html

[^14]: http://www.freemodelfoundry.com/

[^15]: http://www.uv.es/leo/sparc/

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

[^34]: http://www.liquidware.com

[^35]: https://www.makerbot.com/

[^36]: http://en.wikipedia.org/wiki/Crowdfunding

[^37]: http://p2pfoundation.net/Open_Source_Hardware_Reserve_Bank

[^38]: http://www.openmoney.org/

[^39]: http://metacurrency.org/

[^40]:  http://opendesignnow.org/index.php/visual_index/manifestos

[^41]: http://sindominio.net/hackmeeting/wiki/2014

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

[^56]: “In the Next Industrial Revolution, Atoms Are the New Bits”

[^57]: http://www.openhardware.net/

[^58]: http://www.publico.es/418911/la-gente-se-sentiria-molesta-si-viera-de-donde-viene-su-iphone

<p align="center"><img src="../../end0.png"></p>
