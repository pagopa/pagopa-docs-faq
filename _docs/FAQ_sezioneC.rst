
+---------------+
| |pagoPA_logo| |
+---------------+

**Gruppo C - Domande frequenti sull'adesione degli Enti Creditori**
===================================================================

..

C1: Quali sono le procedure da seguire per aderire a pagoPA?
------------------------------------------------------------
L’adesione a pagoPA avviene con procedure e modalità coerenti con le Linee Guida emanate da AgID. L’iter è differenziato per
tipologia di soggetto aderente (Ente Creditore o Prestatore di Servizi di Pagamento) e può avvenire per entrambe le tipologie in modalità diretta
oppure in modalità indiretta, ossia in tale ultimo caso tramite Intermediari o Partner tecnologici. La documentazione per l’adesione è disponibile
sul sito www.pagopa.gov.it di pagoPA, suddivisa per Enti Creditori e per Prestatori di Servizi di Pagamento.

*Parole chiave: PA*


C2: Che problemi hanno i soggetti obbligati che non aderiscono a pagoPA?
------------------------------------------------------------------------
Le PA che non hanno ancora attivato tale sistema presentano difformità nel modo di incassare le somme dovute. Alcune di loro richiedono che
i pagamenti siano effettuati con il modello F24, molto più complesso sia nella fase di compilazione che nella fase di pagamento, con frequenti
rischi di errori. I pagamenti effettuati con F24, inoltre, sono incassati dallo Stato che solo successivamente li riversa alle Pubbliche
Amministrazioni (i tempi di riversamento previsti anche di 15 giorni), rendendo più lungo e macchinoso il processo di incasso.
Le Pubbliche Amministrazioni indicano spesso modalità di pagamento diverse per diverse tipologie di servizi: ad esempio, il bonifico, il MAV
(Mediante Avviso), il RAV (Ruoli Mediante Avviso), versamenti presso il tesoriere o presso altri specifici soggetti riscossori. Ne consegue che è
sempre più necessario standardizzare gli incassi per fornire a cittadini e imprese un'unica modalità di pagamento omogenea riconosciuta a livello
nazionale anche se questo può comportare, inizialmente, un fisiologico periodo di adattamento.
Senza il sistema pagoPA, infine, gli Enti Creditori non possono rilasciare al cittadino una quietanza "liberatoria" di pagamento, con il rischio di
comunicare dopo mesi o addirittura anni, eventuali somme ancora dovute a saldo del pagamento già eseguito.

*Parole chiave: PA, obbligatorietà*


C3: Quali accorgimenti e indicazioni è necessario tenere in considerazione per la generazione del codice IUV?
-------------------------------------------------------------------------------------------------------------
Il codice IUV è un elemento strutturale dell’intero sistema pagoPA, non solo per la sua capacità di richiamane l’IBAN di accredito
selezionato dall’Ente Creditore per quella specifica operazione di pagamento, ma soprattutto perché consente all’utente di eseguire il pagamento
 presso i PSP aderenti al Nodo (c.d. modello 3: pagamenti attivati presso il PSP) e altresì consente all’Ente Creditore di eseguire una riconciliazione
 immediata, analitica e automatica. Pertanto, è essenziale che un Ente Creditore lavori nel migliore dei modi nella generazione dello IUV per beneficiare
 in proprio e permettere ai PSP e agli utenti di beneficiare di tutte le funzionalità del sistema pagoPA. Ciò detto, si ricorda  che per:

- il modello 1 (pagamento attivato presso l'Ente Creditore con reindizzamento on-line) e per il modello 2 (pagamento attivato presso l'Ente Creditore con autorizzazione gestita dal PSP) lo IUV può essere rappresentato da una stringa
alfanumerica lunga sino ad un massimo di 35 caratteri alfanumerici tutti liberi, fermo restando l’uso consigliato dello standard ISO 11649;

- il modello 3 (pagamento presso il PSP), lo IUV è ricompreso all'interno del Codice Avviso, per un massimo di 18 caratteri numerici, secondo uno dei due
seguenti schemi:

    - “0” + 2 caratteri numerici + IUV di massimo 15 caratteri numerici;

    - “1” + IUV di massimo 17 caratteri numerici.

Fermo restando quanto appena detto in merito ai caratteri dello IUV, si rappresenta la necessità di tenere nella debita considerazione il fatto che, se si
consente ad un utente di accedere al sito dell’Ente Creditore secondo il Modello 1 o 2 e di stampare l’avviso di pagamento senza eseguire on line la
relativa operazione di pagamento, tale avviso non potrà essere pagato secondo il Modello 3 presso il PSP, laddove il codice IUV sia composto da un
numero di caratteri non compatibile con quelli previsti per il modello 3.

*Parole chiave: PA*


C4: Sono una PA, per aderire a pagoPA il mio tesoriere o cassiere deve essere aderente a sua volta?
---------------------------------------------------------------------------------------------------
L’adesione a pagoPA non è connessa con il servizio di tesoreria e cassa. In sede di adesione l’Ente dovrà indicare gli IBAN dei conti
correnti bancari e/o postali che intende accreditare attraverso le funzionalità di pagoPA. Tali conti correnti potranno essere accreditati a
prescindere che il relativo Prestatore di Servizi di Pagamento sia o meno aderente a pagoPA. Laddove il tesoriere o cassiere dell’Ente sia aderente
a pagoPA questi potrà supportare l’Ente nell’adesione potendosi, se del caso, configurare come Intermediario Tecnologico dell’Ente (cfr. Linee
Guida). Si ricorda che ogni Ente è lasciato libero di individuare le modalità di approvvigionamento di beni e servizi, ivi inclusi quelli di
intermediazione tecnologica per l’adesione a pagoPA, sempre nel rispetto della normativa di riferimento, ivi incluso quella del Codice degli Appalti
e degli Acquisti sulla piattaforma gestita da CONSIP S.p.A.

*Parole chiave: PSP*


C5: L’adesione a pagoPA da parte di un soggetto a cui una PA ha affidato la riscossione delle entrate ha effetto sulla stessa PA appaltante?
--------------------------------------------------------------------------------------------------------------------------------------------
Il Sistema pagoPA è disponibile anche ai soggetti iscritti nell’albo di cui all’articolo 53, comma 1, del D.Lgs. n. 446/1997 che consente
alle PA di affidare a terzi le attività di accertamento, liquidazione e riscossione delle entrate. In merito, si puntualizza che: i) i soggetti
iscritti nell’albo già indicato, ove aderenti al sistema pagoPA, risulteranno beneficiari delle operazioni di pagamento elettroniche eseguite
attraverso pagoPA; e ii) l’attività di riversamento da parte del concessionario in favore della PA appaltante sarà eseguita fuori dal sistema pagoPA
ovvero nelle modalità stabilite nel contratto tra il concessionario e la stessa PA appaltante. Fatta la precisazione appena esposta, appare
necessario puntualizzare che l’adesione al sistema pagoPA eseguita da parte di un soggetto a cui la PA ha affidato, ex D.Lgs. n.446/1997, l’attività
di riscossione delle entrate, non comporta l’adesione a pagoPA da parte anche della PA appaltante.

*Parole chiave: PA, obbligatorietà*


C6: Un’Ente Creditore può utilizzare anche altre modalità di pagamento elettronico, oltre ai servizi di pagamento offerti da pagoPA?
------------------------------------------------------------------------------------------------------------------------------------
Il sistema pagoPA rappresenta il sistema nazionale dei pagamenti elettronici in favore delle Pubbliche Amministrazioni e di altri soggetti
che erogano servizi pubblici tenuti per legge all’adesione. Come previsto al paragrafo 5 delle Linee Guida, gli Enti Creditori obbligati ad aderire a pagoPA
possono affiancare al sistema esclusivamente i seguenti metodi di pagamento:

  a) "Delega unica F24" (c.d. modello F24) fino alla sua integrazione con il Sistema pagoPA;

  b) Sepa Direct Debit (SDD) fino alla sua integrazione con il Sistema pagoPA;

  c) eventuali altri servizi di pagamento non ancora integrati con il Sistema pagoPA e che non risultino sostituibili con quelli erogati tramite pagoPA
     poiché una specifica previsione di legge ne impone la messa a disposizione dell’utenza per l’esecuzione del pagamento;

  d) per cassa, presso il soggetto che per tale ente svolge il servizio di tesoreria o di cassa.

Inoltre si segnala che l’articolo 65, comma 2, del Decreto legislativo 13 dicembre 2017, n. 217 stabilisce «L’obbligo per i prestatori di servizi di
pagamento abilitati di utilizzare esclusivamente la piattaforma di cui all’articolo 5, comma 2, del decreto legislativo n. 82 del 2005 per i pagamenti
verso le pubbliche amministrazioni decorre dal 30 giugno 2020». Pertanto, a decorrere da tale data, i prestatori abilitati a offrire servizi di
pagamento ai sensi della PSD2 non potranno in alcun modo eseguire servizi di pagamento che non transitino per il Nodo dei Pagamenti-SPC e che abbiano
come beneficiario un soggetto pubblico obbligato all’adesione allo stesso sistema, ad eccezione dei soli servizi di cui alle lettere a), b), c) e d)
appena indicati.

Infine, si evidenzia che, ai sensi dell’articolo 2, punto 39, del Decreto legislativo 15 dicembre 2017, n. 218 per il recepimento in Italia della PSD2,
è stabilito che «Gli articoli 36, 37 e 38 del decreto legislativo 27 gennaio 2010, n. 11 sono abrogati dalla data di entrata in vigore del presente decreto,
ad eccezione del comma 6 dell'articolo 37 che è abrogato a decorrere dal 1° gennaio 2019». Pertanto, dovendo le Pubbliche Amministrazioni applicare quanto
stabilito in materia di pagamenti dalla PSD2 a partire dal 1° gennaio 2019, appare opportuno rappresentare che, per la sola componente degli incassi,
l’adesione al Sistema pagoPA garantisce, altresì, il pieno rispetto della direttiva europea, come recepita a livello nazionale.

*Parole chiave: PA, obbligatorietà, PSP*


C7: Un Ente Creditore può censire sul sistema pagoPA degli IBAN inerenti dei conti correnti a lui non intestati?
----------------------------------------------------------------------------------------------------------------
In via generale, sul Sistema pagoPA, ogni Ente Creditore è chiamato per la gestione degli incassi inerenti i servizi da esso erogati a
censire almeno un IBAN di un conto corrente a lui intestato.
Per tale attività di censimento e aggiornamento dei conti correnti, il singolo Ente Creditore nomina il proprio Referente dei Pagamenti, che si
assume ogni responsabilità per quanto comunicato, in nome e per conto dell’Ente Creditore di riferimento, sul Portale pagoPA.

Fatta la precisazione appena esposta, si rappresenta che, tenute nella debita considerazione il ruolo e le funzioni del Referente dei Pagamenti, PagoPA S.p.A.
consente, previo invio tramite Pec (presidio@pec.pagopa.it) della `specifica
dichiarazione <https://github.com/italia/lg-pagopa-docs/blob/master/documentazione_tecnica_collegata/faq/c7_dichiarazione_ente_per_censimento_iban_tramite_altro_ec_1_0.doc>`__ e previa verifica della fattibilità da parte della stessa PagoPA S.p.A., a un Ente Creditore di censire anche IBAN inerenti dei conti correnti a lui non intestati.

Tali IBAN devono però essere di soggetti terzi che, comunque, hanno un rapporto in essere con l’Ente Creditore per l’erogazione di specifici servizi e,
al contempo, abbiano in essere, altresì, un collegamento telematico che, ancorché fuori dal Sistema pagoPA, consenta al soggetto terzo di ricevere i
flussi informativi scambiati sul Sistema pagoPA.

A titolo esemplificativo, si segnala che rappresentano casi di fattibilità le seguenti fattispecie:

  - Ente Creditore che, in qualità di riscossore iscritto nell’albo di cui all’articolo 53, comma 1, del D.Lgs. n. 446/1997, voglia, in esecuzione dell’articolo 2 bis del D.L. 193/2016, censire sul Sistema pagoPA gli IBAN dei singoli enti per i quali svolge il servizio di riscossione;

  - Ente Creditore che voglia censire sul Sistema pagoPA gli IBAN delle società da esso controllate;

  - Ente Creditore che, in qualità di Unione di Comuni, voglia censire sul Sistema pagoPA gli IBAN degli Enti che lo compongono;

  - Ente Creditore che eroghi in proprio un servizio il cui incasso, per legge, è di spettanza di un'altra amministrazione.

*Parole chiave: PA*


C8: Perché nell’avviso di pagamento che mi è arrivato non trovo il bollettino postale? Perché nell’avviso di pagamento non trovo più il bollettino MAV/RAV?
-----------------------------------------------------------------------------------------------------------------------------------------------------------
Non tutti gli Enti Creditori possono ricevere pagamenti con bollettino postale, in quanto non tutti dispongono di un conto corrente postale, né
sono obbligati a disporne (vedi FAQ B6). Inoltre, aderendo a pagoPA, l’Ente Creditore non può utilizzare strumenti di avviso bancari.

*Parole chiave: bollettino, PSP, PA*


C9: Un Ente Creditore è obbligato ad allegare all’avviso analogico il bollettino postale?
-----------------------------------------------------------------------------------------
No. Gli Enti Creditori hanno la facoltà ma non l’obbligo di possedere un conto corrente postale (vedi FAQ B6). Un Ente Creditore per
incassare qualsiasi tipo di pagamento, ove abbia però in essere un rapporto di conto corrente postale è obbligato ad utilizzare tale conto sul
sistema pagoPA, unitamente al conto corrente bancario nella sua disponibilità, con ogni facoltà di censire sul Sistema anche più di un conto
corrente bancario e/o postale.

*Parole chiave: bollettino*


C10: Chi può svolgere il ruolo di Intermediario tecnologico?
------------------------------------------------------------
Come previsto dal modello di funzionamento, sia gli Enti Creditori, sia i Prestatori di Servizi di Pagamento, per aderire a pagoPA,
possono beneficiare dell’attività di interfaccia con il Nodo dei Pagamenti-SPC già posta in essere da altri soggetti aderenti (c.d. Intermediari
tecnologici). L’Intermediario tecnologico è il soggetto che risulta destinatario dei flussi informativi in nome e per conto dell’aderente e deve
essere indicato da quest'ultimo nella modulistica predisposta per la formalizzazione dell’adesione al Nodo dei Pagamenti-SPC. Pertanto, potranno
svolgere il ruolo di Intermediario tecnologico solo soggetti già aderenti al Nodo dei Pagamenti-SPC, in quanto Pubbliche Amministrazioni, società
partecipate o gestori di servizi pubblici o Prestatori di servizio di Pagamento (vedi anche FAQ C12).

*Parole chiave: PA*


C11: Il sistema pagoPA, il SUAP e il portale “impresainungiorno.gov.it”: quali facilitazioni per i Comuni?
----------------------------------------------------------------------------------------------------------
Premesso che il portale “impresainungiorno.gov.it” è stato validamente integrato con le funzionalità di pagamento elettronico del sistema pagoPA:

  - i Comuni che hanno in essere una collaborazione con la Camera di Commercio per lo svolgimento delle funzioni del SUAP attraverso
    “impresainungiorno.gov.it” e che già ricevevano tramite tale portale pagamenti in loro favore, risultano di conseguenza già in regola con l’adesione
    al sistema “pagoPA” per quanto concerne i servizi alle imprese erogati attraverso il SUAP e, ancorché risulteranno già inseriti nell’elenco degli
    Enti aderenti al sistema pagoPA, dovranno in seguito provvedere ad IMPLEMENTARE l’adesione a mezzo l’invio ad AgID di una lettera di adesione per i
    Servizi diversi da quelli erogati tramite il portale “impresainungiorno.gov.it”;

  - i Comuni che hanno in essere una collaborazione con la Camera di Commercio per lo svolgimento delle funzioni del SUAP attraverso
    “impresainungiorno.gov.it” ma che non hanno mai abilitato il sistema di pagamento tramite tale portale, non potranno beneficiare delle facilitazione
    di cui al punto a) che precede ma potranno comunque affidare a InfoCamere il ruolo di intermediario tecnologico; a tale riguardo, tali Comuni
    potranno aderire al sistema “pagoPA” a mezzo dell’invio della lettera di adesione a PagoPA S.p.A. - tramite Portale delle Adesioni - e indicare InfoCamere come Intermediario tecnologico.
    Nel contempo, i Comuni in questione dovranno prendere contatto con InfoCamere per pianificare il piano di attivazione dei servizi e la messa in
    produzione del sistema “pagoPA” per i servizi del SUAP erogati tramite il portale “impresainungiorno.gov.it”.

Ciò detto, si puntualizza che - a prescindere dalle facilitazioni di cui alle lettre a) e b) che precedono - sarà onere di ogni Comune provvedere
all’adesione al sistema “pagoPA” per il pagamento dei restanti sevizi, ossia di quelli erogati all’infuori del portale “impresainungiorno.gov.it”.


C12: Che differenza c’è tra Intermediario tecnologico e Partner tecnologico?
----------------------------------------------------------------------------
Un Ente Creditore, sia esso una Pubblica Amministrazione o un Gestore di pubblici servizi, nell’adesione al Nodo dei pagamenti-SPC ha tre possibilità:

  1. aderire direttamente, senza alcun Intermediario tecnologico e/o Partner tecnologico;

  2. aderire indirettamente, delegando le attività tecniche ad un Intermediario tecnologico;

  3. aderire indirettamente, delegando le attività tecniche ad un Partner tecnologico.

Le tre soluzioni possono anche coesistere tra di loro, potendo il singolo Ente Creditore in autonomia decidere, i) se; ii) a chi; e iii) a quanti
affidare la gestione e/o l’interconnessione dei propri servizi con il Nodo dei Pagamenti-SPC ai fini delle relative funzionalità di pagamento.

Fatta la precisazione appena esposta, si rappresenta che è denominato Intermediario tecnologico un soggetto pubblico che rende disponibile, in sussidiarietà, il servizio di intermediazione 
ad altre pubbliche amministrazioni (ad esempio, una Regione che intermedia gli Enti del proprio territorio).

Si definisce invece Partner tecnologico qualsiasi altro soggetto che eroga a favore di un Ente Creditore aderente i servizi IT necessari a consentire l'interfaccia tecnica con pagoPA. 

PagoPA espone sul proprio sito istituzionale il modello dei Servizi IT connessi all’intermediazione tecnologica e le informazioni relative all'elenco degli Intermediari e Partner tecnologici, 
unitamente a ulteriori informazioni accessorie relative alle proprie basi dati, e pubblica sul proprio sito istituzionale l’elenco di tali soggetti.



C13: Un Ente Creditore è obbligato a mettere a disposizione tutti i modelli di pagamento previsti?
--------------------------------------------------------------------------------------------------
I soggetti sottoposti all’ambito applicativo del CAD hanno l’obbligo di mettere a disposizione degli utenti i pagamenti elettronici
attraverso l’infrastruttura del Nodo dei Pagamenti-SPC. Tale obbligo è declinato e tecnicamente dettagliato nelle Linee Guida e nei relativi
allegati tecnici, ove sono descritti i diversi modelli di pagamento. Pertanto, i soggetti obbligati ad aderire al Nodo dei Pagamenti-SPC sono
altresì chiamati ad implementare tutti i modelli di pagamento previsti, salvo che l’Ente Creditore verifichi che il processo di erogazione di tutti
i servizi da esso erogati sia integralmente dematerializzato. In tale specifico caso, l’Ente può non implementare il modello di pagamento attivato
presso il PSP (c.d. “modello 3”).

*Parole chiave: obbligatorietà*


C14: Presso l’Ente è già attivo un sistema di pagamento on line, è possibile utilizzare il logo “pagoPA”?
---------------------------------------------------------------------------------------------------------
L’adesione al Sistema pagoPA è obbligatoria a prescindere dal fatto che l’Ente abbia già delle modalità elettroniche di pagamento
messe a disposizione della propria utenza. La realizzazione, infatti, di un sistema nazionale centralizzato (pagoPA), risponde al più ampio
obiettivo di cui all’articolo 15, comma 5 bis, del D.L. n. 179/2012, di razionalizzazione e contenimento della spesa pubblica in materia
informatica, nonché a quello di garantire omogeneità nell’offerta all’utenza ed elevati livelli di sicurezza. Ciò premesso, si precisa che ogni
piattaforma di pagamento on line già realizzata e/o in uso da parte di un Ente o di un gestore di pubblico servizio può essere mantenuta in essere
purché integrata con il Nodo dei Pagamenti-SPC per lo scambio dei relativi flussi secondo quanto descritto nelle Linee Guida. Il logo “pagoPA”
identificativo dell’adesione al Sistema pagoPA, viene rilasciato solo ai soggetti che hanno espletato tutte le formalità previste dalla
procedura di adesione (la documentazione è disponibile sul sito di pagoPA suddivisa per Enti Creditori e per Prestatori di Servizi di Pagamento).
Attraverso tale logo, infatti, l’utenza potrà comprendere immediatamente se un soggetto pubblico - in qualità di beneficiario – oppure un soggetto
privato - in qualità di prestatore di servizi di pagamento - è aderente al Sistema pagoPA.



C15: Quali sono i soggetti che devono o possono aderire a pagoPA?
-----------------------------------------------------------------
Ai sensi dell’articolo 15, comma 5bis, del D.L. 179/2012 e dell’articolo 2 del CAD l’adesione a pagoPA resta facoltativa solo per le
società a controllo pubblico quotate e per i Prestatori di Servizi di Pagamento.

*Parole chiave: obbligatorietà*


C16: Un Ente locale può scegliere di mettere a disposizione degli utenti solo le modalità di pagamento offerte dal sistema pagoPA?
----------------------------------------------------------------------------------------------------------------------------------
Il Sistema pagoPA rappresenta il sistema nazionale dei pagamenti elettronici in favore delle Pubbliche Amministrazioni e degli altri
soggetti obbligati all’adesione al Sistema.
Pertanto, i soggetti sottoposti all’adesione all’infrastruttura del Nodo dei Pagamenti-SPC, per incassare quanto di propria spettanza, devono
mettere a disposizione dell’utenza le modalità di pagamento offerte dal Sistema pagoPA che possono essere affiancate dal servizio di pagamento per
cassa, presso l’Ente e/o il soggetto che per tale Ente svolge il servizio di tesoriere e cassa.

Ricordato quanto appena esposto, un Ente locale può, in via autonoma, nel rispetto della normativa attualmente vigente, secondo le proprie scelte
gestionali e di autonomia contabile, escludere completamente i versamenti per cassa, al fine di eliminare l’uso del contante e/o di digitalizzare
integralmente la gestione degli incassi.
In considerazione di quanto appena precisato, risulta opportuno ricordare che il Sistema pagoPA, articolandosi sui 3 diversi modelli di pagamento
elettronico (c.d. modello 1, 2 e 3) descritti nelle Linee Guida dell’AgID, prevede per il pagatore la possibilità di scegliere tra un’interazione
on-line o un’interazione allo sportello del PSP o della PA.

*Parole chiave: PA*


C17: Le Associazioni volontarie tra Enti pubblici locali, sono obbligate ad aderire al Sistema pagoPA?
------------------------------------------------------------------------------------------------------
Sì. Né il CAD, né il D.L. n. 179/2012 prevedono alcun tipo di eccezione e/o deroga a riguardo. Infatti, qualunque Ente che riceva
pagamenti in suo favore da soggetti privati o da soggetti pubblici che non possano eseguire il pagamento tramite un’operazione di girofondi presso
la tesoreria della Banca d’Italia, devono dare attuazione all’obbligo di legge di adesione al Sistema pagoPA.

*Parole chiave: obbligatorietà*


C18: Le società a controllo pubblico che non ricevono pagamenti da cittadini o imprese sono obbligate ad aderire a pagoPA?
--------------------------------------------------------------------------------------------------------------------------
Sì, ogni soggetto obbligato dalla normativa ad aderire a pagoPA resta obbligato all’adesione anche se non riceve pagamenti da cittadini e
imprese, ma solo da soggetti pubblici. Pertanto, le società a controllo pubblico o i gestori di pubblici servizi e ogni altro soggetto obbligato che
non abbia l’obbligo di eseguire operazioni di pagamento verso altre pubbliche amministrazioni tramite girofondi, per la gestione delle proprie
entrate, deve aderire a pagoPA.
Infatti, né il nuovo art. 5 del CAD, né il comma 5bis dell’art. 15 del D.L. 179/2012 specificano che pagoPA riguarda esclusivamente i rapporti con
cittadini o le imprese. Pertanto, tutti i pagamenti in favore di soggetti obbligati all’adesione a pagoPA, devono avvenire tramite pagoPA.

*Parole chiave: obbligatorietà*


C19: Gli ordini professionali sono obbligati ad aderire a pagoPA?
-----------------------------------------------------------------
Per potere validamente rispondere a tale quesito, appare doveroso premettere che nel nostro ordinamento può creare qualche dubbio
interpretativo individuare la natura giuridica degli ordini professionali.
Infatti, se da un lato gli Ordini sono riconosciuti dal legislatore come veri e propri enti pubblici non economici, in quanto idonei ad adottare
atti incidenti sulla sfera giuridica altrui, dall’altro, essi continuano ad essere conformati come enti esponenziali di ciascuna delle categorie
professionali interessate, e quindi come organizzazioni proprie di determinati appartenenti all’ordinamento giuridico generale.

Pertanto, in generale, è necessario effettuare una valutazione caso per caso, facendo prevalere i profili privatistici ovvero quelli pubblicistici a
seconda della ratio della normativa per la quale ci si chiede se debba o meno essere applicata agli ordini professionali.
Nel caso specifico dell’applicazione dell’articolo 5 del CAD e, dunque, dell’adesione al Sistema pagoPA, appare opportuno ricordare che tale
obbligo, ai sensi dell’art. 2, comma 2, del CAD riguarda anche gli enti pubblici non economici e, addirittura, i gestori di pubblici servizi e le
società a controllo pubblico non quotate.

Precisato quanto appena esposto, si rappresenta che gli ordini professionali sono, quindi, obbligati ad aderire al Sistema pagoPA per consentire ai
loro pagatori di beneficiare delle funzionalità di pagamento elettronico offerte dal sistema.

*Parole chiave: obbligatorietà*


C20: Se un Ente decide di delegare l’incasso di tutti i pagamenti in suo favore ad un soggetto riscossore, che a sua volta ha aderito al sistema pagoPA, quale formula di esenzione può essere richiamata?
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Avendo l’Ente delegato tutti i servizi, rientra nella fattispecie di cui al punto 1 della lettera di esenzione, ma è necessario che venga
soddisfatta anche la fattispecie di cui al punto 4 della stessa lettera, ossia che non riceva istanze/documenti con marca da bollo poiché, in caso
positivo, dovrà aderire a pagoPA per mettere a disposizione dell’utente il servizio di acquisto e pagamento del bollo digitale.

*Parole chiave: PA*


C21: Gli Enti di previdenza sono obbligati ad aderire a pagoPA?
---------------------------------------------------------------

Ricordato che il CAD è stato dapprima modificato dal D.Lgs. n. 179/2016 (G.U. n. 214 del 13.9.2016) e successivamente corretto dal D. Lgs.
n. 217/2017 (G.U. n. 9 del 12.01.2018), si segnala che l’attuale articolo 2, comma 2, del CAD, oltre alle Pubbliche Amministrazioni, ha introdotto
nel perimetro soggettivo del CAD anche le società a controllo pubblico, nonché i gestori di pubblici servizi.

Pertanto, le Pubbliche Amministrazioni, le società a controllo pubblico e i gestori di pubblici servizi sono obbligati ad aderire al Sistema pagoPA
per consentire alla loro utenza di eseguire pagamenti elettronici in modalità uniforme nei loro confronti.

Fermo quanto già esposto, appare doveroso ricordare che nel nostro ordinamento, ancorché possa creare qualche dubbio interpretativo individuare la
natura giuridica degli enti di previdenza, nel caso specifico, dell’adesione al Sistema pagoPA, appare opportuno ricordare che tale obbligo riguarda
anche gli Enti inclusi nell’elenco di cui all’art. 1, comma 2, della L. n. 196/2009 e, addirittura, i soggetti privati gestori di pubblici servizi.

Nella fattispecie, essendo gli Enti nazionali di previdenza e di assistenza sociale, sia inclusi nell’elenco di cui all’art. 1, comma 2, della l. n.
196/2009, sia soggetti privati gestori di pubblici servizi, ai sensi dell’articolo 2, comma 2, rispettivamente, lettera c) e b), risultano obbligati
ad aderire al Sistema pagoPA.

*Parole chiave: obbligatorietà*


C22: I trasferimenti di fondi tra enti pubblici che vengono effettuati tramite i conti di tesoreria in Banca d’Italia sono esclusi dal Sistema pagoPA?
------------------------------------------------------------------------------------------------------------------------------------------------------

Il sistema pagoPA non modifica, né altera, l'applicazione della normativa di finanza pubblica, incluso l’art.  44  della  legge n. 526/1982 
che impone agli enti titolari di fondi presso conti correnti o contabilità speciali presso le Tesorerie dello Stato di eseguire operazioni di girofondi 
a valere su tali conti correnti o contabilità speciali intestati agli enti destinatari dei pagamenti.

Ogni altra forma di incasso deve essere gestita sulla Piattaforma pagoPA.

Si rinvia anche alle FAQ C17 e C18.


*Parole chiave: girofondi*


C23:  Come deve eseguire un Ente Creditore l’attività di riversamento ad altro ente?
------------------------------------------------------------------------------------

L’attività di incasso posta in essere da un Ente Creditore può comportare la necessità in capo a tale stesso ente di dovere riconoscere, in tutto o in parte, quanto incassato ad altro soggetto, quale soggetto avente una competenza finale all’incasso di tali somme.
In altri termini, un Ente Creditore può essere chiamato a riversare, in tutto o in parte, i fondi incassati ad altro soggetto.

Sul sistema pagoPA i pagamenti eseguiti online attraverso il c.d. modello 1 gestiscono il carrello multi-beneficiario, cioè l’importo totale della transazione può essere accreditato su diversi IBAN anche intestati, se del caso, a distinti soggetti beneficiari.
Viceversa, i pagamenti eseguiti presso il PSP attraverso un avviso di pagamento (c.d. modello 3) necessariamente sono destinati a un solo beneficiario.

Fatta la precisazione fin qui esposta, un Ente Creditore potrà scegliere tra due opzioni:

* 1. incassare integralmente attraverso la PIattaforma pagoPA e continuare ad eseguire l’attività di riversamento ad altro ente, al di fuori del sistema pagoPA; 

oppure

* 2. eseguire un accredito immediato e automatico della quota di competenza di altro ente per i soli pagamenti online attraverso il c.d. modello 1 e ridurre/circoscrivere l'attività di riversamento ad altro ente da eseguire al di fuori del sistema pagoPA solo per i pagamenti eseguiti presso il PSP attraverso il c.d. modello 3.

Infine, per completezza, si segnala che affinchè l’Ente Creditore possa censire uno o più IBAN intestati ad altri enti beneficiari - in tutto o in parte - dell’incasso, non è necessario che tali stessi enti beneficiari siano a loro volta aderenti alla piattaforma pagoPA, ma è sufficiente che abbiano sottoscritto la specifica dichiarazione di cui alla FAQ C7. 


*Parole chiave: riversamento*



.. |pagoPA_logo| image:: media/logo-pagopa-small-trasp.png
