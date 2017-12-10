# Sull'hardware libero e il riappropriarsi della tecnologia

*Elle Flâne*

![3dprinter](../../es/content/media/free-hw.png)	

Il concetto di hardware è abbastanza nuovo, molto ampio, in continuo rinnovamento e diametralmente diverso dal software. Vi è una vasta polemica su ciò che è e non é, quindi grazie all'assenza di una definizione concordata chiunque lo interpreta un po' a modo suo. Ad esempio, per me, l'hardware comprende un componente elettronico, un condensatore, un transistor, un LED, un circuito integrato, un dispositivo quale un moto-aratro, la descrizione di un processo industriale, come la fabbricazione di un mattone refrattario, un computer, una stampante 3D, un meccanismo per la purificazione dell'acqua scritto in codice sorgente aperto, un processo per il riciclo della plastica, l'assemblaggio di una fresatrice CNC, un metodo di analisi dei suoli inquinati mediante sensori o il codice di un microcontrollore. 

Ma se diamo una occhiata più da vicino, si può dire che la storia dell'Hardware Libero corre parallela a quella dei computer. Nel 1970, l'Homebrew Computer Club[^1] si è rivelato essere un ibrido composto dal movimento studentesco radicale, imprenditori della comunità informatica dell'università di Berkeley e hobbysti elettronici. 
Appare un po' ironico vedere come molti di quei garage, prima pieni di creatività, sono ora musei, come quello di Bill Hewlett e Dave Packard, dove è stato sviluppato il primo dispositivo HP. Negli anni '90, nello stesso modo in cui i software venivano scambiati, l'FPGA [^2] consentiva anche lo scambio elettronico di disegni liberi. La Open Design Circuits [^3] lanciata da Reinoud Lamberts, è il primo sito web di una comunità di progettisti di hardware con lo spirito del software libero. E nonostante non ci fosse ancora un software libero adeguato per la progettazione elettronica, questo portale coinvolse molte persone ponendo le basi per una comunità più ampia. Nel 2002, l'iniziativa "Challenge to Silicon Valley" [^4] promossa da Kofi Annan ha lanciato diversi progetti di sviluppo di hardware libero e reso più visibile la necessità di sviluppare tecnologie varie adeguate a realtà socioculturali ed economiche diverse. Quella linea di sviluppo della tecnologia si è anche miscelata con la lotta globale contro il divario digitale attraverso iniziative come ICT4Development. Queste erano generalmente il risultato di collaborazioni tra università e il terzo settore per creare tecnologie adattate alle esigenze dei paesi erroneamente definiti "in via di sviluppo". Tuttavia, oggi le prospettive di produzione hardware sono principalmente caratterizzate dalle limitazioni imposte da brevetti industriali e proprietà industriale [^5]. Questi sono l'insieme di diritti che una persona fisica o giuridica pone sopra un'invenzione. Questi forniscono due tipi di diritti: il diritto di utilizzare l'invenzione, disegno o segno distintivo, e il diritto di vietare a terzi di farlo. Il diritto di vietare (*Ius prohibendi*) consente al titolare il diritto di richiedere il pagamento di una licenza, denominata royalty, o di canoni, avendo limiti temporali e territoriali.

### Hardware Libero: Fin dove e in che modo?

Va tenuto presente che l'hardware libero richiede quasi tutte le seguenti parti: un disegno, un processo di produzione, alcune materie prime, la distribuzione, il modello di business, di manutenzione, distribuzione, replicabilità, la forza lavoro, l'accesso alla documentazione e alla tecnica di produzione. Partendo da questo contesto, se cerchiamo di definire ciò che è hardware libero abbiamo bisogno di vedere tutte le tappe di produzione sommate a tutti i tipi di risultati tangibili possibili che possano essere interpretati da licenze libere.
Lo stesso Richard Stallman [^6], presidente della Free Software Foundation [^7] e creatore della GNU GPL [^8] che garantisce le seguenti quattro libertà (la libertà di utilizzo, studio e modifica, la distribuzione e la redistribuzione delle versioni modificate), afferma anche che "le idee di software libero possono essere applicati ai file o agli archivi necessari per la progettazione e le specifiche (schemi, PCB, ecc), ma non al circuito fisico in sé" [^9]. 
Va segnalato anche che c'è un hardware "statico", comprendente gli elementi di sistemi materiali o elettronici tangibili, e un hardware "riconfigurabile", composto da un linguaggio di descrizione hardware scritto in un file di testo che contiene il codice sorgente. Pertanto, le parole "hardware" e "progettazione hardware" sono due cose diverse. Il disegno e l'oggetto fisico non possono essere confusi anche se a volte si fondono reciprocamente.
Tutti questi fattori creano confusione quando si cerca di descrivere che cos'è l'hardware libero. Se è vero che ogni componente e le fasi di produzione possono essere adatte alle quattro libertà specificate dal software libero, va detto che attualmente nessun progetto riesce a coprire l'intera catena con passaggi rigorosamente liberi. Così ora usiamo il termine hardware libero/aperto, senza dover attuare le quattro libertà strettamente in tutte le aree. Ci sono molte iniziative consolidate in questo campo, anche se i modelli di utilizzo ed approccio sono diversi a seconda delle motivazioni sociali, economici e politiche di ogni gruppo o di comunità dietro il suo sviluppo.
Di conseguenza, v'è una moltitudine di diverse licenze che cercano di chiarire questi aspetti. Ad esempio, il Free Hardware Design [^10] è un disegno che può essere copiato, distribuito, modificato, e prodotto liberamente. Ciò non implica che il progetto non possa essere venduto, o che qualsiasi pratica di progettazione hardware sia gratuita. Il Libre Hardware Design è uguale al Free Hardware Design, ma chiarisce che la parola "libre" si riferisce alla libertà, non al prezzo. L' Open Source Hardware [^11] mette tutte le informazioni di progettazione a disposizione del pubblico in generale, e può essere basato su hardware con design libero, o limitato in qualche modo. L'Open Hardware [^12], un marchio registrato della Open Hardware Specification Program, è una forma limitata di Open Source Hardware in quanto l'unico requisito è quello di fornire una quantità limitata di informazioni di progettazione per effettuare riparazioni. Infine, in un tentativo di sintesi, Patrick McNamara ha definito per l'Open Hardware i seguenti livelli di apertura:


1. Interfaccia aperta: l'utente ha tutta la documentazione che spiega come un pezzo di hardware svolge la funzione per cui è stato progettato.

2. Design aperto: la documentazione disponibile è sufficientemente dettagliata affinchè una terza parte possa creare un dispositivo funzionale e compatibile.

3. Fabbricazione aperta: disponibile l'elenco di tutti i materiali necessari per la costruzione del dispositivo.

Nello scenario attuale delle licenze, rispetto all'hardware libero ne esistono una grande varietà.
Ci sono gruppi che usano la GNU GPL [^13] come la Free Model Foundry [^14] per la simulazione di modelli, componenti e testing; ESA Sparc [^15] che ha creato un CUP per 32bits o Opencores [^16], una comunità che sviluppa IP core.
Altri gruppi usano la licenza Open Source Initiative del MIT [^17] come il Free-IP Project [^18] e LART [^19]; per quanto riguarda la licenza GNUBook [^20], è basata sulla licenza GPL ma con aggiunte riguardanti i diritti ambientali ed umani.
Esistono anche gruppi che sviluppano nuove licenze, come la Simputer GPL [^21], Freedom CPU [^22], OpenIPCores [^23], la OHGPL [^24], The Open NDA [^25], la OpenPPC [^26] (basata sulla Apple Public Source License) e la Hardware Design Public License [^27] del gruppo Open Collector [^28]. Distinguiamo tra le altre la Licenza Hardware del CERN OHL [^29] scritta originalmente per la progettazione del CERN (l'acceleratore di particelle) elecato nel Repository Open Hardware.

### Modelli di business e sostenibilità derivati dall'open hardware

Secondo Wired, la Bibbia del tecnopositivismo, l'Open Hardware sta diventando una “commodity”, ovvero una merce. Anche se non esiste ancora un modello di business chiaro, si capisce che può servire mercati di nicchia che non sono stati finora coperti, applicando la logica della "long tail", coda lunga o distribuzione di beni e servizi hardware (il modello Amazon) dalle dimensioni pressoché infinite. Per quanto riguarda la commercializzazione, la progettazione in hardware libero può essere implementata da una società per promuovere il suo stesso mercato, la cui unica premessa è quella di mantenere il progetto libero.
Nel 2010, Torrone e Fried [^30] hanno raccolto 13 esempi di aziende che vendono Hardware Open Source fatturando tra tutti 50 milioni di dollari. Attualmente ci sono più di 200 progetti di questo tipo e si prevede che la comunità di Open Source Hardware fatturerà miliardi nel 2015. Adafruit [^31], Arduino [^32], Chumby [^33], Liquidware [^34] e Makerbot [^35] hanno entrate pari a più di un milione di dollari ciascuno. Tutto questo dimostra che ci sono quindi le possibilità per generare reali guadagni economici con progetti che basano le loro attività sul rendere noto e condividere il design con la comunità.

Ora, ciò che è meno chiaro: E' possibile esercitare una vera politica anticapitalista sulla base di un progetto economico e di ri-distribuzione delle attività legate ad una logica di sostenibilità e decrescita?
Un modello interessante per l'open hardware risiede nel crowdfunding [^36], cioé nel raccogliere piccole quantità di individui o gruppi per avviare un progetto. Huynh e Stack hanno creato, ad esempio, la Open Source Hardware Reserve Bank [^37] per coprire i costi connessi alle revisioni hardware in corso durante un progetto, stimate quasi il 40% del bilancio iniziale necessario. Il progetto mira a ridurre i rischi per i progetti di hardware libero prima di passare alla fase di produzione. Inoltre facilitano la sperimentazione consentendo la costruzione e la distribuzione di piccole quantità di prodotti considerati "non scalabili", perché "una pessima idea di business" non è la stessa cosa che "una brutta idea hardware".

Un altro esempio è l'Open Source Hardware Reserve Bank che permette solo ad hacker, non a chi fa investimenti di capitali di rischio o di altre società, di investire in progetti specifici per raddoppiare il numero di pezzi prodotti e riducendo il costo unitario dal 10 al 30% circa. 
Da notare anche che una comunità può anche autofinanziare i suoi progetti attraverso il microcredito. Open money [^38] e Metacurrency [^39] propongono nuove forme di valuta, e cercano di promuovere il legame di monete esistenti con certificati di microcredito.

E infine, l'Open Design Manifesto [^40] che unisce le due tendenze. Da un lato, le persone applicano le loro competenze e il tempo in progetti per il bene comune che di solito non esistono a causa della mancanza di interesse commerciale. D'altra parte, fornisce un quadro di riferimento per lo sviluppo di progetti e tecnologie avanzate che potrebbero essere al di là delle risorse di qualsiasi azienda o paese e coinvolge la gente che senza il meccanismo del copyleft non si sentirebbe motivata a collaborare. Vediamo ora che esistono problemi per quanto riguarda la sostenibilità dell'hardware libero.

Da un lato, la mancanza di consenso sulla definizione di hardware libero è applicata anche ai possibili modelli di business. Un dispositivo aperto è diverso da ciò che esiste e domina il mercato e la cosa importante non è il prodotto finito (hardware prodotto), ma le attività immateriali, le informazioni riguardanti la progettazione dell'hardware che si apre all'uso pubblico. Inoltre, come si è visto in precedenza nell'hardware libero non si possono applicare direttamente le quattro libertà del software libero, data la sua natura diversa, uno ha una esistenza fisica, materiale, l'altro no. Pertanto, un progetto fisico è unico e la condivisione dipende dalla facilità di riproduzione.

Esiste anche una dipendenza tecnologica dai componenti importati, che può essere tradotta come: "I chip sono disponibili?"
Questo è un modello di esclusione imposto e a volte non è possibile realizzare l'hardware a causa delle implicazioni nella creazione di tutte le infrastrutture necessarie. Chi vuole ricreare l'hardware che un'altra persona ha progettato, si deve fare acquistare i componenti necessari e ricostruire lo schema. Tutto questo ha un costo. Di conseguenza poche aziende sono in possesso di queste conoscenze e le conservano gelosamente in modo che le persone rimangano mere consumatrici del prodotto.


### Modelli di produzione differenziati

Abbiamo osservato due modelli convenzionali di produzione / distribuzione. Da un lato, il modello di produzione centralizzato con lo stesso prodotto disponibile in molti luoghi, con prezzo maggiorato per il consumatore. Dall'altra parte, un sistema di produzione distribuito basato su un numero di piccoli gruppi indipendenti che producono lo stesso design distribuito localmente. Per diventare sostenibile in entrambi i modelli, le iniziative di hardware libero hanno bisogno di piattaforme che mettano insieme e facilitino il contatto tra i mezzi di produzione e coloro che vogliono creare.
Per quanto riguarda il modello di produzione distribuita, vediamo che al momento non ci sono molte comunità che cercano di sviluppare hardware libero alternativo senza obiettivi capitalistici. Questi gruppi di solito dovrebbero cercare di creare autonomia, facilitando l'accesso a tutti e invertire gli effetti sociali, ambientali e politici avversi legati alla produzione di hardware proprietario.

Per esempio, ci sono vari incontri promossi dai movimenti sociali, come Hackmeeting [^41], Hardmeeting [^42], HacktheEarth [^43], Extrud_me [^44], o anche come la Conferenza OSHW [^45], la Chaos Computer Conference [^46] o incontri Dorkbot dove si possono trovare le persone che sviluppano progetti di hardware libero. Il progetto OSWASH [^47] (Lavatrici Open Source) rappresenta perfettamente quello che noi definiamo come ricerca e sviluppo di tecnologie appropriate per i quali l'unico hardware che abbia un senso è libero, che è stato ri-appropriato ovvero ripreso da licenze proprietario ed è tornato ad essere aperto.
In Spagna esistono posti a livello statale come Medialab Prado [^48], La Laboral [^49] o Hangar [^50], spesso concentrati sullo sviluppo di hardware libero. Così a Hangar (Barcellona), troviamo BeFaco [^51], che sviluppa strumenti per suonare con hardware libero e FABoratory [^52], specializzato nella produzione di sampanti 3d. In Calafou, possiamo di trovare la HardLab Petchblenda [^53] un laboratorio di suoni, elettronica e biohacking dal punto di vista transfeminista. Infine, dal XarxaCTiT [^54] (Network of Science, Engineering and Technology) della Cooperativa Integral Catalana [^55] stiamo sviluppando una piattaforma per lo scambio di conoscenze ed esigenze a livello locale, promuovendo una rete di partner, produttori, prosumer e di consumatori di hardware libero e tecnologie riappropriate.

In una visione diametralmente opposta e concentrandosi su una strategia globale, mentre non esiste un completo ecosistema di produzione distribuita, Chris Anderson [^56] suggerisce la produzione di progetti open hardware in Cina utilizzando Alibaba.com [^57]. Questa società creata nel 1999, è diventata una società da 12 miliardi di dollari con 45 milioni di utenti registrati e 1,1 milioni di dipendenti. La produzione in Cina è un fenomeno noto come Shanzai. In origine questo termine, definiva "banditi che si sono ribellati all'autorità e impegnati in atti che per loro sono visti come giustificati."
Il movimento Shanzai nel 2009 ha rappresentato il 20% dei telefoni cellulari venduti in Cina, e il 10% dei telefoni venduti nel mondo. Alcuni produttori hanno tanto successo che preferiscono promuovere i propri marchi, piuttosto che produrre prodotti di "pirateria". La cosa interessante di queste aziende è che "piratare" prodotti di marca ha creato una cultura di condivisione delle informazioni su questi prodotti e ha generato materiale di design aperto, dando credito reciprocamente in quanto ne hanno apportato miglioramenti. E' la comunità che ha auto-formulato questa politica ed esclude quelli che non la seguono. Lo Shanzai capisce e risponde alle esigenze e ai gusti locali, stabilendo e mantenenendo basi di produzione locale e della distribuzione, chiamate fabbriche locali. Tuttavia le condizioni di lavoro, in particolare nella creazione di componenti elettrici, sono deplorevoli e rappresentano un rischio per il fisico e la salute [^58] e non possono essere votati a cercare la giustizia sociale per i propri lavoratori. La Open Source Hardware Work Licence (ancora da scrivere) dovrebbe integrare come un requisito fondamentale le condizioni rispettose del lavoro delle persone, la loro libertà e il loro ambiente.


**Conclusioni**

Utilizzare e creare hardware libero protegge e difende la sovranità tecnologica perché permette l'indipendenza tecnologica per le persone evitando ogni dipenza da un altro fornitore di risorse per il proprio sviluppo. Il riutilizzo e l'adattamento del design può innovare e migliorare, ridurre i costi e tempi di progettazione, facilitare il trasferimento di conoscenze e prevenire l'analfabetismo digitale per motivi economici.
Le persone possono smettere di essere semplici consumatori tecnologici, consentendo loro di sapere come funziona, come mantenere e riparare la tecnologia di cui hanno bisogno. Utilizzare e creare hardware libero coinvolge, e genera più ricchezza rispetto all'utilizzo di altro hardware, anche se spesso si deve prima passare attraverso un paio di delusioni durante l'apprendimento. 
Al di là della propria convinzione politica, la libertà rappresenta la possibilità, la capacità di imparare a costruire il proprio mondo, che non ci aliena da noi stessi e ci allontana invece dal partecipare alla struttura capitalistica.
Ció che è appropriato o inappropriato non è un attributo della tecnologia stessa. 
Il tuo giudizio è il risultato della valutazione delle sue caratteristiche in relazione alla: (1) organizzazione dello Stato della produzione e del sistema economico; (2) i livelli e la distribuzione del reddito, e (3) lo stato di sviluppo del sistema della tecnologia in uso.
Analizziamo cosa può significare  in una società la desertificazione attraverso la tecnologia: l'obsolescenza programmata, la dipendenza tecnologica e l'introduzione di tecnologie inappropriate. La sua devastazione e recupero sono quasi impossibili se rimangono all'interno delle catene pesanti del sistema capitalista.

Poichè il mondo dell'hardware libero è molto complesso, e gli obblighi e gli abusi che ci sono attraverso lo sviluppo tecnologico non sembrano rispettare le libertà, sono attratta dalla riappropriazione delle tecnologie.
Queste sono quelle che meglio rispondono alle situazioni ambientali, culturali ed economiche. Esse richiedono poche risorse, significano costi minori e basso impatto ambientale. Abbiamo bisogno di una vera e propria reindustrializzazione, che includa le nostre tecnologie, le tecniche e la tecnologia di tutti i giorni così come le nostre tradizioni ancestrali, che di per sé già hanno una base ambientale, sostenibile e olistica. Tecnologia riappropriata dal cieco progresso, dall'analfabetismo e dall'alienazione, dalla scienza inamovibile, dagli interessi del potere; ri-appropriata perché decentrata, organica, trasmutabile. 


____

Opinione di Richard Stallman sull'hardware libero.
Free Hardware Design - Past, Present, Future; di Graham Seaman
The economics of Free Core development; di David Kessner
Open-source IP could ignite system-on-chip era; di David Kessner
Business Models for Open Source Hardware Design; di Gregory Pomerantz
Free chips for all - The status of open hardware designs; di Jamil Khatib
Open Hardware and Free Software Extending the Freedoms of Free and Open Information; di Carl Vilbrandt, progettista di GnuBook.
Challenge to Silicon Valley; di Kofi Annan 
Liberalidad del conocimiento desde la cesión de derechos de propiedad intelectual León Rojas, J. M. 
Inteligencia Colectiva, la revolución invisible; di Jean-François Noubel Wikipedias versus blogs. La creación colectiva y el acceso universal al conocimiento. Casassas Canals, Xavier. 
Cultura libre; di Lawrence Lessig, 
“La industria de la música en la era digital: Participación de los consumidores en la creación de valor.”; di Chaney, D 


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
