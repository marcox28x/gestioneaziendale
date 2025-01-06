Le scorte sono materiali temporaneamente inutilizzati nell'attesa di poter essere usati o venduti in un punto della catena logistica

## Perché si generano le scorte?
- **Fronteggiare consumi imprevedibili:** le scorte consentono di affrontare variazioni nei consumi che non possono essere previste con precisione
- **Supportare il sistema produttivo e distributivo:** una disponibilità di materie prime, semilavorati e prodotti finiti permette di disaccoppiare i diversi stadi del processo produttivo e distributivo, che spesso operano a ritmi differenti.
- **realizzare economie di acquisto e produzione:** la presenza di costi fissi di spedizione e attrezzaggio rende conveniente accumulare scorte per ottimizzare tali operazioni
- **Assorbire fluttuazioni stagionali:** le scorte aiutano a gestire variazioni stagionali negli acquisti o nelle vendite.
- **Speculazione sui valori unitari dei materiali:** accumulare scorte può essere vantaggioso in periodi di forti variazioni nei prezzi delle materie prime o dei prodotti.

# Variabilità
---
Il ruolo delle scorte in ultima analisi è quello di ridurre la variabilità endogena ed esogena a cui il sistema impresa è sottoposto.

## variabilità endogena
Si lega agli elementi interni dell'impresa, dunque problemi:
- di movimentazione interna
- di logistica
- presenza di colli di bottiglia
- errori nella programmazione della produzione
- guasti imporvvisi
cioè problemi relativi alle fasi che si sviluppano attorno al processo di trasformazione.

## variabilità esogena
Si lega agli elementi esterni all'impresa, dunque:
- imprevedibilità dei mercati
- affidabilità delle forniture
- sicurezza negli acquisti
per ottenere garanzia di fluidità e uniformità del processo di trasformazione con la variabilità del mercato.

# scorte come problema
---
Le scorte:
- rappresentano un investimento finanziario oneroso
- perdono valore per obsolescenza e deperimento
- occupano spazio
- generano costi per la loro gestione, movimentazione, trasporto

Pertanto, è opportuno prevenire ad un dimensionamento delle scorte che rappresenti il giusto equilibrio tra il livello di servizio garantito e i costi sostenuti, secondo un classico trade-off.

# Obiettivi della gestione dei materiali
---
- **efficacia**: garantire la disponibilità dei materiali ai diversi stadi del processo produttivo e distributivo, misurata come livello di servizio erogato in termini di quantità, tempi e mix.
- efficienza finanziaria: misurata dall'investimento in mezzi finanziari.
- efficienza economica: misurata dall'entità di risorse connesse con il governo delle scorte.

# Due domande chiave nella gestione materiali
---
- **Quanto ordinare**: di un determinato materiale, considerando gli obiettivi di costo e livello di servizio.
- **Quando effettuare tale ordine**: per assicurare la puntuale alimentazione dei processi produttivi e distriutivi ed eludere ogni rischio di insoddisfazione della domanda interna ed esterna.

# Complessità della gestione dei materiali
---
La complessità della gestione dei materiali è in funzione della presenza o meno dei vincoli:
- **Articolazione gamma prodotti** (ampiezza e profondità di gamma): 
	- L'**ampiezza** si riferisce al numero di differenti prodotti messi in vendita: iphone, watch, ipad...
	- La **profondità** si riferisce al numero di varianti di ogni prodotto della linea: versione da 128GB, 38-45mm...
- **Articolazione della struttura di prodotto** (ampiezza e profondità delle distinte base):
	La distinta Base o Bill of Materials è semplicemente la ricetta nell'assemblaggio del prodotto. Se la diba è ampia, significa che hai molto da gestire per singolo livello. Se è profonda, la pianificazione richiede più livelli di lavorazione da seguire.

- articolazione dei processi (fabbricazione, assemblaggio, distribuzione)

- articolazione della distribuzione (numero e dispersione geografica punti vendita/clienti, livelli di intermediazione)

- articolazione della fornitura (numero e dispersione geografica dei fornitori, tempi, qualità, affidabilità, flessibilità di mix e volumi)

- flessibilità della manodopera (polivalenza e polifunzionalità, flessibilità agli orari, orientamento ai processi).

# Classificazione Delle Scorte
---
Materiali di acquisto stoccati a magazzino distinti in:
- Materie Prime: oggetto di almento una trasformazione interna
- Componenti: destinati ad essere impiegati direttamente nel processo produttivo
- Materiali in corso di lavorazione distinti in:
	- WIP: se presenti all'interno di reparti produttivi
	- conto lavoro: se una parte del processo produttivo viene affidato ad un fornitore esterno,
- **Prodotti Finiti**: materiali ottenuti in uscita dal processo produttivo stoccati nel magazzino centrale, o presenti nei magazzini periferii della rete distributiva multilivello o nei punti vendita
- **Parti di ricambio o spare parts**: materiali di acquisto o produzione stoccati a magazzino centrale, o presenti nei magazzini periferici della rete distributiva multilivello o nei punti vendita.

# Tipologie Di Materiali nello schema di flusso produttivo e logistico
---
Le materie prime acquistate dai fornitori sono pronte a passare alla fase di fabbricazione dove vengono trasformate in componenti. Le componenti passano poi per una fase di preassemblaggio per diventare sotto-assiemi, e, successivamente, ad una di assemblaggio finale. I prodotti finiti sono quindi pronti ad essere distribuiti nei magazzini centrali o periferici dove verrano in fine consegnati al cliente.


# Lotto Economico
---
EOQ sta per Economic Order Quantity ed è un modello utilizzato per determinare la quanità ottimale da ordinare di un prodotto, in modo da minimizzare i costi totali di gestione delle scorte.

In particolare aiuta a bilanciare due tipi di costi:
- costi di emissione: sono legati all'emissione dell'ordine, come le spese di trasporto, gestione dell'ordine o preparazione dell'macchinario. In somma questi costi si riducono se si fanno ordini più grandi.
- costi di giacenza delle scorte: sono legati al magazzino, come lo spazio di stoccaggio, il deterioramento, il rischio di obsolescenza e il capitale immobilizzato. Generalmente questi costi aumentano se si fanno ordini più grandi.

## Costi di emissione
---
### materiali d'acquisto
##### $$
\text{costo di ordinazione} = \text{costi amministrativi}
$$

### materiali di produzione interna
##### $$ \text{costo di ordinazione} = \text{costi di preparazione} + \text{costi di attrezzaggio} $$

## costi di mantenimento (o di giacenza)
---
##### $$ \text{costi dei mezzi finanziari immobilizzati nelle scorte} $$

## Ipotesi
---
Il modello regge su di alcune ipotesi:
- gli articoli hanno domanda nota e costante nel tempo
- il valore unitario degli articoli è noto, costante nel tempo e indipendente dal numero di unità acquistate o prodotte
- i costi di mantenimento delle scorte sono proporzionali al valore dell'articolo e al tempo di permanenza in magazzino
- le quantità ordinate vengono versate a magazzino in un unica soluzione
- non esistono vincoli per quanto concerne la capacità del magazzino, la quantità da ordinare, il capitale richiesto per acquistare o produtte la merce
- non sono consentite rotture di stock (stockout), tutta la domanda viene cioè soddisfatta senza far attendere i clienti

### Notazione
---
- $Q$: Lotto economico \[pezzi]
- $D$: Domanda annuale \[pezzi $/$ periodo]
- $k$: Costo preparazione ordine \[€]
- $i$: Tasso di costo
- $v$: Valore d'acquisto \[€ $/$ pezzo]
- $C_g$: Costi di giacenza \[€]  $$
C_g = \frac{Q}{2} \cdot v \cdot i
$$
- $C_e$: Costi di emissione dell'ordine \[€] 
$$
C_e = \frac{D}{Q} \cdot k 
$$

## Determinazione del Lotto Economico
---
I costi totali d'acquisto sono dati da:
$$
\text{CT} = C_g + C_e
$$

L'EOQ equivale al minimo dei costi totali, pertanto
$$
\text{EOQ} := \frac{d\text{CT}}{dQ} = 0
$$

$$
\text{EOQ} = \sqrt{\frac{2 \cdot D \cdot k}{v \cdot i}}
$$

# Classi Di Scorte
---
- **Scorte cicliche (Cycle Stock)**:
	- Si hanno quando gli ordini sono più grandi di quanto realmente necessario a soddisfare le richieste immediate dei clienti
	- Generalmente sono la conseguenza dei vantaggi delle economie di scala.
- **Scorte di disaccoppiamento (Decoupling stock):**
	- Per rendere indipendenti i diversi stadi della catena produttiva e logistica. 
	- Alcune cause sono:
		- Per impiegare differenti criteri di aggregazione degli ordini (stesso modello di colore diverso).
		- Diversa velocità di funzionamento di due fasi operative consecutive.
		- Bottleneck.
- **Scorte di transito (Transit stock):**
	- Le varie fasi del processo produttivo e distributivo non sono fisicamente adiacenti
	- Possono essere ridotte:
		- migliorando i collegamenti tra le varie fasi
		- modificando le caratteristiche della struttura del sistema produttivo - distributivo.
- **Scorte di sicurezza (Safety stock):**
	- Sono indotte dalla necessità di fronteggiare l'incertezza della domanda a valle o dei rifornimenti a monte.
- **Scorte Stagionali (Seasonal stock):**
	- Riguardano i prodotti che rappresentano una domanda fortemente stagionale (panettone, pandoro, giacche invernali...)
- **Scorte speculative (Speculation stock):**
	- Sono legate ad aspettative di aumento dei costi di approvvigionamento dei materiali.
	- Si cerca in pratica di minimizzare gli effetti negativi dovuti alle oscillazioni dei prezzi.

# Costi delle scorte di materiali
---
Si dividono in:
1) Costi di ordinazione o emissione dell'ordine:
	- per materiali  di acquisto:
$$
\text{costi di ordinazione} = \text{costi amministrativi} + \text{costi di trasporto}
$$
	- per materiali di produzione:
$$
\text{costi di ordinazione} = \text{costi di preparazione} + \text{costi di attrezzaggio}
$$
2) Costi di mantenimento
3) Costi di stock-out


# Livello di servizio
---
Il livello di servizio è un valore che descrive sinteticamente la capacità dell'organizzazione di soddisfare le richieste dei clienti nelle quantità, nei tempi e nel mix desiderati.

Poiché un livello di servizio pari a $1$ ha generalmente costi improponibili, l'obiettivo è quello di garantire un livello di servizio adeguato ai costi più bassi possibili.

Esistono numerosi metodi pe misurare il livello di servizio $LS$.
quantità:
$$LS_\text{quantità} = \frac{Q_\text{consegnate}}{Q_\text{ordinate}} $$

puntualità
$$LS_\text{puntualità} = \frac{t_\text{ConsegnaEffettiva}}{t_\text{ConsegnaPromesso}} $$

ordini:
$$LS_\text{ordini} = \frac{N_\text{OrdiniEvasi}}{N_\text{OrdiniRicevuti}} $$

rapidità:
$$LS_\text{rapidità} = \frac{t_\text{consegna}}{t_\text{ConsegnaMigliorConcorrente}} $$

mix:
$$LS_\text{mix} = \frac{N_\text{RigheOrdineEvase}}{N_\text{RigheOrdineRicevute}} = \text{FillRate}$$


# Analisi di Pareto
---
La maggior parte degli effetti è dovuta ad un numero ristretto di cause.

Sfruttando queste osservazioni è possibile analizzare un insieme di dati in modo da determinare le poche variabili che influenzano in modo significativo i risultati finali di un determinato fenomeno.

Questa analisi viene spesso utilizzata per:
- Una classificazione economica di scorte, fornitori o clienti.
- Interventi di manutenzione preventiva
- La ricerca di attività di riduzione dei tempi di set-up

Sotto il profilo economico le valutazioni possono essere mirate alla conoscenza di:
- quali sono i prodotti più redditizi di una gamma produttiva.
- quali sono i prodotti che comportano oneri maggiori per il loro mantenimento a scorta.
- qual'è l'importanza di diversi clienti o fornitori, ecc..

In merito ai materiali messi a scorta, l'analisi ABC consente una suddivisione degli articoli di magazzio in tre categorie, in modo da permettere di valutare in modo selezionato il loro impatto, definendo quali sono gli articoli critici su cui focalizzare l'attenzione.

L'analisi ABC può riguardare l'insieme di tutti gli articoli in magazzino oppure un loro sottoinsieme; infine può essere semplice o incrociata, intendendo che la suddivisione del gruppo di articoli sotto osservazione porta a individuare rispettivamente tre o nove classi.

## ABC semplice

