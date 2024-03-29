# CMrules

## Table of Contents
* [PERIODI DI GIOCO](https://github.com/Cmod777/CMrules#periodi-di-gioco)
* [VINCITE](https://github.com/Cmod777/CMrules#vincite)
* [MONTEPREMI](https://github.com/Cmod777/CMrules#montepremi)
* [penalità](https://github.com/Cmod777/CMrules#penalit%C3%A0)
* [RITIRARE UNA SCOMMESSA](https://github.com/Cmod777/CMrules#ritirare-una-scommessa)
* [ESEMPIO DI GIOCO](https://github.com/Cmod777/CMrules#esempio-di-gioco)
* [Sezione CEX](https://github.com/Cmod777/CMrules#sezione-cex)
---- [LISTA CEX GIOCATI](https://github.com/Cmod777/CMrules#lista-cex-giocati) 
* [Sezione COIN](https://github.com/Cmod777/CMrules#sezione-coin)
---- [LISTA COIN GIOCATE](https://github.com/Cmod777/CMrules#lista-coin-giocate)
* [SEZIONE CRYPTO-GURU](https://github.com/Cmod777/CMrules#sezione-crypto-guru)
* [PIAZZARE BET](https://github.com/Cmod777/CMrules#piazzare-bet)
* [LIMITI](https://github.com/Cmod777/CMrules#limiti)
* [EXTRA](https://github.com/Cmod777/CMrules#extra)
* [RIEPILOGO DELLE VINCITE](https://github.com/Cmod777/CMrules#riepilogo-delle-vincite)
* [note](https://github.com/Cmod777/CMrules#note)

***
### PERIODI DI GIOCO
(A.1) Periodo di gioco: il gioco e la possibilitá di effettuare #bet iniziano il giorno 1 del mese e finiscono il 15mo giorno dell'ultimo mese. (es: periodo gennaio-marzo, si gioca da gennaio al 15 di marzo) 
(A.2) Periodo di stop: non si possono prendere ordini per gli ultimi 15 giorni del periodo (es: dal 15 a fine marzo)
(A.3) Periodo di controllo: i controlli necessari vengono fatti nei 7 giorni dopo il periodo di stop. Per la sezione COIN i controlli dei prezzi si fanno l'ultimo giorno utile (il settimo).
(A.4) Assegnazione dei premi: i premi si assegnano gli ultimi giorni dell'ultimo mese del periodo di gioco
(A.5) Ritirare una scommessa: si puó ritirare una scommessa fino al massimo due mesi prima della fine del periodo di gioco. (Vedi relativa penalitá)
[TORNA A HOME](https://github.com/Cmod777/CMrules#cmrules)
***
### VINCITE
(B.1) Vincita esatta: raggiugimento dell'obbiettivo (1), il primo utente che piazza #bet viene considerato valido per la vincita del 100% di quota del montepremi relativo. (B.1a) Se c'é una vincita per l'obbiettivo (1) allora il primo in assoluto che ha i requisiti validi vince il 100% di tutto il montepremi della sezione. (B.1b) Non ci possono essere due utenti entrambi vincitori per il tipo (1)
(B.2) Vincita parziale: raggiungimento dell'obbiettivo (2), tutti gli utenti che piazzano #bet vengono considerati validi per la vincita del 70% del montepremi della sezione. (B.2a) Questo tipo di vincita puó essere assegnata solo se non c'é nemmeno un vincitore per il tipo (1). (B.2b) In caso di vincita di tipo (2) si procede cosi: montepremi della sezione -30% > risultato del 70% del totale diviso in parti uguali per tutti i vincitori di tipo (2) 
(B.3) Per entrambi i premi si applicano le penalitá, in caso di penalitá verrá detratta la quota (20%) ai soli vincitori con penalitá, i restanti riscuoteranno la loro quota regolare. 
(B.4) Nessuna vincita: sondaggio per decidere assegnazione del montepremi. 
(B.5) Vincita anticipata: in caso di vincita di tipo (1) prima della scadenza del gioco sarà assegnato il premio del X% del montepremi relativo al vincitore valido e la COIN o il CEX perdente saranno delistati dal gioco. (B.5a) Si potrà proseguire con le altre COIN o CEX e relative #bet fino a scadenza naturale del periodo di gioco. (B.5b) Il montepremi relativo sará l'equivalente della rimanenza del precedente piú tutte le scommesse successive.
(B.6) Per vincite anticipate entro il primo mese di inzio sará assegnato il 50% del montepremi accumulato, per quelle fino al secondo mese il 75%, oltre il secondo mese e prima della scadenza l'85%.
[TORNA A HOME](https://github.com/Cmod777/CMrules#cmrules)
***
### MONTEPREMI
(C.1) Il montepremi é diviso in due sezioni: CEX&COIN e GURU e le due vincite sono indipendenti tra loro. Lo stesso giocatore puó vincerle entrambe.
(C.2) Il premio CEX&COIN viene assegnato cosi: 
100% al primo che ottiene una vincita valida con obbiettivo (1) 
Oppure se non c'é nessun vincitore né per le scommesse CEX né per quelle COIN per il tipo (1) si prosegue cosi:
70% del totale del montepremi CEX&COIN suddiviso in parti uguali tra tutti i vincitori con obbiettivo (2)
[TORNA A HOME](https://github.com/Cmod777/CMrules#cmrules)
***
### Penalità:
Ci sono vari tipi di penalità:
* (D.1) PENALITA' DI GIOCO: "HOT TOPIC" Quando un admin, a sua totale discrezione, ritiene che un giocatore stia piazzando un #bet facile o comodo (argomento di discussione acceso, recenti avvenimenti che portano in risalto il COIN o CEX che si vuole puntare) può lanciare il comando appropriato e applicare una penalità al giocatore. (D.1a) Tale penalità avvierà un sondaggio anonimo della durata di 10 min circa tra i giocatori che decideranno, tra le opzioni possibili, come procedere. (D.1b) Il giocatore potrà decidere se accettare la penalità e proseguire o annullare la puntata per quel turno di gioco.
(D..1c) Il questionario proposto comprende queste opzioni: A) riduci bet max al giocatore di -1 | B) aumenta la puntata del 50% | C) annulla la puntata al giocatore
* (D.2) PENALITA' DI VINCITA: Se la vincita é avvenuta conseguentemente ad aver ripiazzato la scommessa almeno una volta per giocatore [se il giocatore aveva piazzato #bet per X, ritira la scommessa e piazza #bet per Y e poi Y vince (sia tipo 1 che tipo 2)] allora a qualsiasi premio debba riscuotere verrá detratto il 20% della sua parte di vincita. 
[TORNA A HOME](https://github.com/Cmod777/CMrules#cmrules)
***
### RITIRARE UNA SCOMMESSA:
(E.1) Chiunque voglia ritirare una #bet piazzata potrá farlo ottenendo un rimborso del 70% di quanto pagato. (E.1a) É possibile ritirare una scommessa fino a 2 mesi prima della fine del periodo di gioco. (es: se il periodo di gioco é di 3 mesi e inizia a gennaio allora il limite massimo per ritirare una scommessa é l'ultimo giorno utile di gennaio). (E.1b) Il rimborso viene fatto il prima possibile, idealmente immediatamente alla richiesta. (E.1c) In caso di ritiro di una scommessa, e successiva nuova bet, verrà considerata bet ri-piazzata anche se sono presenti altre bet da consumare. (E.1d) Le giocate massime restano uguali ma, se si decide di ripuntare una scommessa con giocate rimanenti ancora valide, la nuova giocata verrà considerata come ri-piazzata con relativa penalità in caso di vincita. (si suggerisce di terminare le puntate residue prima di ripiazzarne una)
[TORNA A HOME](https://github.com/Cmod777/CMrules#cmrules)
***
### ESEMPIO DI GIOCO:
Periodo 4 mesi gennaio-aprile
Si gioca dal 1 gennaio al 15 aprile
Fino all'ultimo di febbraio si possono ritirare e piazzare nuove scommesse.
Dal 16 aprile si iniziano i controlli.
Gli ultimi 3 giorni di aprile si assegnano i premi.
Caso A) due persone candidate alla vincita esatta, il primo che ha giocato vince il 100% del montepremi.
Caso B) nessuna vincita esatta, cinque candidati per vincita parziale. Si prende il 70% del montepremi e si divide per cinque. Il vincitore due ha vinto a seguito di una rigiocata. I vincitori 1 3 4 5 prendono a testa un quinto del 70% del montepremi, il vincitore 2 prende un quinto meno la penalitá del 20% della sua quota. 
Caso C) nessuna vincita esatta né parziale. Se il montepremi é inferiore ai 1.000.000 sats allora si assegna integralmente in base al risultato del sondaggio, se superiore allora la quota extra dei 1M sats si tiene in aggiunta al prossimo giro di gioco. 
[TORNA A HOME](https://github.com/Cmod777/CMrules#cmrules)
***
### Sezione CEX:
- (G.1) il cex o la società maggiore del gruppo (es: binance vale sia per binance.us, binance.it ecc) dichiara ufficialmente bancarotta, insolvenza, fallimento. L'acquisizione o assorbimento in altra azienda non conta come sopravvivenza del cex, viene considerato ugualmente fallito.
- (G.2) il cex non viene piu utilizzato, i volumi di scambio giornaliero si stabilizzano a:
1) 250.000 usd - VINCITA ESATTA
2) 1.000.000 usd - VINCITA PARZIALE

(G.3) I volumi di scambio vengono calcolati sulla base delle informazioni riportate da https://coinmarketcap.com/rankings/exchanges/ CMC viene utilizzato per determinare i volumi al calcolo per assegnare i premi.

(G.4) Per la preparazione della tabella di gioco: vengono riportati i primi 50 CEX presenti al link https://coinmarketcap.com/rankings/exchanges/ (al momento di preparazione della tabella / i dati riportati nel link possono cambiare nel tempo, la tabella resta uguale per tutto il periodo di gioco). (G.4a) I dati vengono confronttati con quelli indicati nella lista https://www.coingecko.com/it/cambi . (G.4b) Vengono confermati solo i CEX che compaiono in entrambe le liste (considerando Coingecko fino alla massima posizione del 60imo posto / se un cex presente su cmc non è presente nei primi 60 posti della lista coingecko, viene eliminato dal turno di gioco ). (G.4c) La lista viene aggiornata ad ogni turno di gioco e non è modificabile se non aggiungendo CEX extra (vedi sezione) con votazione degli utenti. (G.4d) Se la tabella di gioco presenta degli spazi vuoti vuol dire che i cex riportati da cmc non erano presenti nei primi 60 di coingecko, i posti rimanenti restano vacanti fino al prossimo turno di gioco. Tutte le aggiunte di cex fatte dai giocatori andranno inserite nella sezione "extra" della tabella.
e viene tollerato uno scarto + o - del 20% quindi:
* dai 200.000 usd ai 300.000 usd
* dai 800.000 usd ai 1.200.000 usd
(G.5) Ogni giorno (nel periodo di calcolo) vengono presi i valori di riferimento (scartando le migliaia) e a fine del periodo viene fatta una media matematica. 
[TORNA A HOME](https://github.com/Cmod777/CMrules#cmrules) - [LISTA CEX GIOCATI](https://github.com/Cmod777/CMrules#lista-cex-giocati)
***
### Sezione COIN:
- (H.1) La coin viene considerata fallita quando perde almeno il X% del suo valore dal momento di inizio del periodo di gioco. All'inizio del gioco viene riportata la coin listata e il suo prezzo di quotazione preso da https://coinmarketcap.com/ , dal periodo indicato fino al periodo di fine verrá verificato il prezzo di quotazione finale.
1) perdita di almeno il 90% - VINCITA ESATTA
2) perdita compresa tra il meno 75% e il 90% - VINCITA PARZIALE 
(H.2) Nel periodo di controllo si procede cosi: l'ultimo giorno utile (circa 3 giorni prima della scadenza del gioco) si controllano i prezzi finali delle coin e il controvalore perso in % rispetto a quanto riportato a inizio gioco.
[TORNA A HOME](https://github.com/Cmod777/CMrules#cmrules) - [LISTA COIN GIOCATE](https://github.com/Cmod777/CMrules#lista-coin-giocate)
***
### Sezione CRYPTO-GURU:
Per la sezione GURU il gioco si svolge in questo modo: 
* (K.1) il giocatore deve indovinare quale crypto guru shillerà per primo il prossimo progetto scam entro la fine del periodo di gioco (puó essere una coin, un cex, un dex, uno smart-contract ecc...) Per essere considerato scam si devono verificare le seguenti condizioni: COIN: almeno una perdita del 75% dall'inizio del periodo di gioco, CEX: fallimento o insolvenza dell'exchange, DEX o SMART-CONTRACT: hack o perdita di fondi dovute all'utilizzo del codice, altro non espressamente previsto viene valutato caso per caso.
* (K.2) si gioca sulla sponsorizzazione di un progetto scam, non sulla moneta o sull'exchange.
* (K.3) il giocatore dovrá fornire prove a dimostrazione della vincita da reclamare. Le prove possono essere screenshot o video reperiti dalle pagine social pubbliche del guru stesso. (Non sono concessi in nessun modo screen provenienti da gruppi privati e/o conversazioni personali intrattenute con la persona su cui si scommette) Le prove devono contenere la data di pubblicazione visibile, sono valide anche prove da post poi cancellati dal guru.
* (K.4) a paritá di vincitori potrá reclamare il montepremi relativo (sezione GURU) solo il primo giocatore che porterá prove a suo vantaggio. (K.4a) Fará fede la chat pubblica del gruppo. I messaggi cancellati non potranno essere usati a proprio vantaggio: il giocatore che invia un messaggio di prova (screen o video) e poi lo cancella non potrá usarlo a proprio vantaggio, il messaggio cancellato non sará conteggiato come prova valida.
* (K.5) si puó giocare solo sui crypto influencer italiani, o che fanno contenuti in lingua italiana.
* (K.6) per giocare nella sezione GURU si usa il comando di base per piazzare una scommessa, seguito dal nome del GURU su cui si gioca.
(K.7) La lista dei GURU su cui é possibile giocare é disponibile nel gruppo dedicato, hanno tutti pari quotazione.
(K.8) I guru da listare come extra hanno quotazione 50k e possono essere listati a condizione che siano richiesti da almeno 3 giocatori. 
(K.9) Il montepremi della sezione GURU é considerato a parte rispetto a quello della sezione CEX&COIN.
(K.10) Ogni giocatore ha a disposizione lo stesso numero di puntate della sezione CEX&COIN (7) con massimo due ri-puntate [LIMITI](https://github.com/Cmod777/CMrules#limiti). (K.10a) Si applicano le stesse penalitá in caso di ritiro e successiva scommessa [RITIRARE UNA SCOMMESSA](https://github.com/Cmod777/CMrules#ritirare-una-scommessa), si applicano le stesse condizioni di penalitá per vittoria anticipata [VINCITE](https://github.com/Cmod777/CMrules#vincite). (K.10b) Si applicano le stesse penalitá in caso di vittoria derivante da una scommessa ri-piazzata [penalità](https://github.com/Cmod777/CMrules#penalit%C3%A0).
(K.11) Non si applicano penalitá di gioco alla sezione GURU. Vince solo chi, tra i giocatori, comunica per primo e fornisce prove valide per riscattare la sua vincita. (K.11a) In caso di vittoria, il vincitore incassa il premio e le puntate per la sezione GURU sono sospese fino a nuovo turno di gioco: un solo vincitore per turno di gioco.
(K.12) Il montepremi non incassato (in caso di vincita anticipata o in caso di nessun vincitore) viene sommato al prossimo turno di gioco della sezione GURU. [TORNA A HOME](https://github.com/Cmod777/CMrules#cmrules)
***
### PIAZZARE BET:
(L.1) La modalitá di candidatura a una scommessa va fatta nel modo indicato, il pagamento della invoice va fatto come richiesto. La scommessa risulta valida quando viene pagata e non quando viene piazzata. (L.1a) Con la stessa logica si ritiene valido per la vincita esatta solo il primo che ha saldato se piu di uno possono essere parimerito per la vincita esatta. 
[TORNA A HOME](https://github.com/Cmod777/CMrules#cmrules)
***
### LIMITI:
(M.1) Sono concesse massimo sette #bet a utente, comprese quelle ritirate e poi ripiazzate. Sono concesse al massimo due rigiocate a utente. (Max 7 di cui max 2 rigiocate). (M.1a) Attenzione: se un giocatore ha ancora bet residue ma decide di ritirarne una già fatta, la successiva sarà considerata come "rigiocata" con relativa penalità di vincita. Suggeriamo di terminare le bet a disposizione prima di rigiocarne una già fatta.
[TORNA A HOME](https://github.com/Cmod777/CMrules#cmrules)
***
### EXTRA:
(N.1) Possono essere listate CEX&COIN non comprese nell'elenco iniziale a patto che, con sondaggio anonimo, si raggiunga almeno il 40% di voti tra i partecipanti. (N.1a) Devono votare almeno il 40% per considerare il sondaggio valido, in caso di validitá si aggiunge se vince a maggioranza dei votanti al SI.
[TORNA A HOME](https://github.com/Cmod777/CMrules#cmrules)
***

### RIEPILOGO DELLE VINCITE:
* M= montepremi
* V= vincitore/i
* P= premio assegnato
* pen = penalitá
* re-bet = scommessa ripiazzata 

(O.1) Puoi vincere il montepremi intero se:
-sei il primo, tra i giocatori che scommettono sulla stessa cosa, ad effettuare una VINCITA ESATTA
P= 100%M (solo a scadenza)

(O.2) Puoi vincere il montepremi parziale se:
-sei il primo, tra i giocatori che scommettono sulla stessa cosa, ad effettuare una VINCITA ESATTA ma la vincita é anticipata rispetto la fine del gioco
* P= 50%M -pen (1 mese) re-bet
* P= 75%M -pen (2 mese) limite re-bet
* P= 85%M -pen (oltre il secondo mese) no re-bet

-effettui una vincita parziale alla scadenza del gioco
* P= 70%M / V (eventuali V -pen)

-effettui una vincita ESATTA o PARZIALE a seguito di un scommessa ripiazzata (piu tentativi) re-bet 
* P= -20% della quota spettante

[TORNA A HOME](https://github.com/Cmod777/CMrules#cmrules)

 ***
### LISTA CEX GIOCATI:
| CEX | BET (bet uguali fino a indicazione differente)| turno 1 | 
|:--------------|:-------------:|:--------------:|
BINANCE*|15.000 sats|
COINBASE|-|
KRAKEN|-|
KUCOIN|-|
BITFINEX|-|
GEMINI|-|null 20.1.23|
COINCHECK|-|
BITSTAMP|-|
BYBIT|-|
OKX|-|
BITHUMB|20.000 sats|
BITFLYER|-|
BITGET|-|
GATE dot IO|-|
MEXC|-|
CRYPTO dot COM|-|
LBANK|-|
HUOBI GLOBAL|-|
BKEX|-|
BITMART|-|
PHEMEX|25.000 sats|
XT dot COM|-|
BTCEX|-|
BITMEX|-|
COINONE|-|
BIGONE|-|
POLONIEX|-|
BINGX|-|
P2B|-|
OKCOIN|-|
WHITEBIT|30.000 sats|
COINSBIT|-|
BITTREX|-|
BTCTURK pro|-|
DIGIFINEX|-|
COINEX|-|
BITBANK|-|
BITSO|-|
-|-|
-|-|
-|35.000 sats|
-|-|
-|-|
-|-|
-|-|
-|-|
-|-|
-|-|
-|-|
-|-|
-- EXTRA --|50.000 sats|
BLOCKFI|-|
YOUNG PLATFORM|-|
-|-|

1* comprende anche Binance.us, Binance.tr (cex inteso come principale, non sono considerati i sottogruppi)

(P.1) (se il cex contiene l'indicazione "null" in tabella è escluso dalle prossime votazioni nel turno - le bet precedenti il "null" sono valide, non ne vengono accettate altre fino alla fine del turno di gioco)

(P.2) La tabella comprende 50 posizioni massime (+quelle extra scelte dai giocatori). Da una posizione all'altra viene aggiunto un extra di 5k sats. (P.2a) Alla prima posizione viene assegnato un punteggio di 10k. Nel caso in cui non ci fosse possibilità di inserire nemmeno un CEX nell'ultimo scaglione allora la prima posizione inizierà con 15k, nel caso in cui non ci fosse possibilità di inserire nemmeno un CEX nel penultimo scaglione allora la prima posizione inizierà con 20k ecc... Nel caso in cui si potesse riempire solo il primo scaglione allora esso partirà con una quotazione di 30k.
[TORNA A HOME](https://github.com/Cmod777/CMrules#cmrules)
 ***
### LISTA COIN GIOCATE:
| COIN | PREZZO DI PARTENZA A INIZIO TURNO DI GIOCO | PREZZO TARGET MINIMO PER LA VITTORIA | 
|:--------------|:-------------:|:--------------:|
| bet 10.000 sats | turno 1 | VINCITA PARZIALE tra -75% e -89% / VINCITA ESATTA oltre il -90% |
BTC / bitcoin |15.442,69€|Parziale: 3.860,67€	- Esatta: 1.544,27€|
ETH / ethereum|1.117,01€|Parziale: 279,25€	- Esatta: 111,70€|
USDT / tether|0,99€|Parziale: 0,25€	- Esatta: 0,10€|
BNB / bnb|229,31€|Parziale: 57,33€	- Esatta: 22,93€|
USDC / usdc coin|1,00€|Parziale: 0,25€	- Esatta: 0.10€|
BUSD / binance usd|0,93€|Parziale: 0,23€	- Esatta: 0,09€|
XRP / xrp|0,32€|Parziale: 0,08€	- Esatta: 0.03€|
DOGE / dogecoin|0,06€|Parziale: 0,02€	- Esatta: 0,006€|
ADA / cardano|0,23€|Parziale: 0,06€	- Esatta: 0,02€|
MATIC / polygon|0,71€|Parziale: 0,18€	- Esatta: 0,07€|

| COIN | PREZZO DI PARTENZA A INIZIO TURNO DI GIOCO | PREZZO TARGET MINIMO PER LA VITTORIA | 
|:--------------|:-------------:|:--------------:|
| bet 15.000 sats | turno 1 | VINCITA PARZIALE tra -75% e -89% / VINCITA ESATTA oltre il -90% |
DOT / polkadot|4,05€|Parziale: 1,01€	- Esatta: 0,40€|
DAI / dai|0,93€|Parziale: 0,23€	- Esatta: 0,09€|
SOL / solana|9,23€|Parziale: 2,31€	- Esatta: 0,92€|
SHIB / shiba inu|0,000007€|Parziale: 0,0000017€	- Esatta: 0,0000007€|
TRX / tron|0,05€|Parziale: 0,01€	- Esatta: 0,005€|
UNI / uniswap|4,78€|Parziale: 1,19€	- Esatta: 0,48€|
LTC / litecoin|63,63€|Parziale: 15,91€	- Esatta: 6,36€|
AVAX / avalanche|10,22€|Parziale: 2,55€	- Esatta: 1,02€|
WBTC / wrapped bitcoin|15.407,84€|Parziale: 3.851,96€	- Esatta: 1.540,78€|
LEO / unus sed leo|3,31€|Parziale: 0,83€	- Esatta: 0,33€|

| COIN | PREZZO DI PARTENZA A INIZIO TURNO DI GIOCO | PREZZO TARGET MINIMO PER LA VITTORIA | 
|:--------------|:-------------:|:--------------:|
| bet 20.000 sats | turno 1 | VINCITA PARZIALE tra -75% e -89% / VINCITA ESATTA oltre il -90% |
LINK / chainlin|5,17€|Parziale: 1,29€	- Esatta: 0,52€|
ATOM / cosmos|8,73€|Parziale: 2,18€	- Esatta: 0,87€|
ETC / eth classic|14,69€|Parziale: 3,67€	- Esatta: 1,47€|
XRM / monero|135,94€|Parziale: 33,98€	- Esatta: 13,59€|
XLM / stellar|0,06€|Parziale: 0,02€	- Esatta: 0,006€|
BCH / bitcoin cash|91,27€|Parziale: 22,82€	- Esatta: 9,13€|
TON / toncoin|1,98€|Parziale: 0,50€	- Esatta: 0,20€|
ALGO / algorand|0,16€|Parziale: 0,04€	- Esatta: 0,016€|
CRO / cronos|0,05€|Parziale: 0,012€	- Esatta: 0,005€|
NEAR / near protocol|1,19€|Parziale: 0,30€	- Esatta: 0,12€|

| COIN | PREZZO DI PARTENZA A INIZIO TURNO DI GIOCO | PREZZO TARGET MINIMO PER LA VITTORIA | 
|:--------------|:-------------:|:--------------:|
| bet 25.000 sats | turno 1 | VINCITA PARZIALE tra -75% e -89% / VINCITA ESATTA oltre il -90% |
FIL / filecoin|2,78€|Parziale: 0,69€	- Esatta: 0,29€|
VET / vechain|0,01€|Parziale: 0,0025€	- Esatta: 0,001€|
QNT / quant|99,98€|Parziale: 24,99€	- Esatta: 9,99€|
FLOW / flow|0,61€|Parziale: 0,15€	- Esatta: 0,06€|
CHZ / chiliz|0,09€|Parziale: 0,022€	- Esatta: 0,009€|
LUNC / terra classic|0,000013€|Parziale: 0,0000032€	- Esatta: 0,0000013€|
ICP / internet computer|3,82€|Parziale: 0,95€	- Esatta: 0,38€|
OKB / okb|24,39€|Parziale: 6,10€	- Esatta: 2,44€|
EGLD / elrond|30,89€|Parziale: 7,72€	- Esatta: 3,09€|
HBAR / hedera|0,03€|Parziale: 0,02€	- Esatta: 0,003€|

| COIN | PREZZO DI PARTENZA A INIZIO TURNO DI GIOCO | PREZZO TARGET MINIMO PER LA VITTORIA | 
|:--------------|:-------------:|:--------------:|
| bet 30.000 sats | turno 1 | VINCITA PARZIALE tra -75% e -89% / VINCITA ESATTA oltre il -90% |
XCN / chain|0,01€|Parziale: 0,0025€	- Esatta: 0,001€|
EOS / eos|0,80€|Parziale: 0,2€	- Esatta: 0,08€|
TWT / trust wallet token|1,32€|Parziale: 0,33€	- Esatta: 0,13€|
USDP / pax dollar|0,92€|Parziale: 0,69€	- Esatta: 0,092€|
XTZ / tezos|0,66€|Parziale: 0,16€	- Esatta: 0,06€|
APE / apecoin|3,38€|Parziale: 0,84€	- Esatta: 0,33€|
SAND / sandbox|0,36€|Parziale: 0,09€	- Esatta: 0,036€|
THETA / theta network|0,68€|Parziale: 0,17€	- Esatta: 0,068€|
TUSD / trueusd|0,93€|Parziale: 0,23€	- Esatta: 0,09€|
AAVE / aave|48,99€|Parziale: 12,25€	- Esatta: 4,89€|

| COIN | PREZZO DI PARTENZA A INIZIO TURNO DI GIOCO | PREZZO TARGET MINIMO PER LA VITTORIA | 
|:--------------|:-------------:|:--------------:|
| bet 35.000 sats | turno 1 | VINCITA PARZIALE tra -75% e -89% / VINCITA ESATTA oltre il -90% |
MANA / decentraland|0,27€|Parziale: 0,067€	- Esatta: 0,027€|
GUSD / gemini dollar|0,92€|Parziale: 0,23€	- Esatta: 0,09€|
KCS / kucoin token|6,03€|Parziale: 1,51€	- Esatta: 0,60€|
BSV / bitcoin SV|38,56€|Parziale: 9,64€	- Esatta: 3,85€|
HT / huobi token|4,74€|Parziale: 1,18€	- Esatta: 0,47€|
USDD / usdd|0,91€|Parziale: 0,23€	- Esatta: 0,09€|
AXS / axie infinity|5,65€|Parziale: 1,41€	- Esatta: 0,56€|
MKR / maker|489,42€|Parziale: 122,35€	- Esatta: 48,94€|
BIT / bitdao|0,31€|Parziale: 0,08€	- Esatta: 0,03€|
ZEC / zcash|35,50€|Parziale: 8,87€	- Esatta: 3,55€|

| COIN | PREZZO DI PARTENZA A INIZIO TURNO DI GIOCO | PREZZO TARGET MINIMO PER LA VITTORIA | 
|:--------------|:-------------:|:--------------:|
| bet 50.000 sats | turno 1 | VINCITA PARZIALE tra -75% e -89% / VINCITA ESATTA oltre il -90% |
EXTRA / coin|0.00€|Parziale: 0.00€	- Esatta: 0.00€|
EXTRA / coin|0.00€|Parziale: 0.00€	- Esatta: 0.00€|

(Q.1) La tabella comprende una lista di 60 posizioni, tutte le aggiunte EXTRA verranno inserite dopo votazione dei giocatori con quotazione 50k sats. Da uno scaglione al successivo c'è un incremento di 5k sats, la tabella parte con la prima posizione quotata 10k.
Cifre di riferimento: 2 oltre la virgola. Se presenti più zeri viene preso il primo numero disponibile diverso da uno (se 1 viene preso anche quello a seguire)

[TORNA A HOME](https://github.com/Cmod777/CMrules#cmrules)
***
### NOTE
* (R.1) Si prega di rispettare il metodo indicato per il pagamento, esso tiene conto delle info aggiuntive contenute nella invoice che serviranno a indicare il corretto vincitore
* (R.2) Non sono accettati come validi saldi di invoice effettuati in altra maniera oltre a quella indicata
* (R.3) Per la generazione delle invoice viene utilizzato il wallet Phoenix Mobile e/o Muun, le fee di gestione dei canali sono dedotte dal totale del montepremi (la gestione dei canali è a carico di tutti)
* (R.4) Ulteriori modifiche saranno comunicate in questa pagina e/o sui gruppi chat
* (R.5) In tutti i casi di vincita, il giocatore può decidere di devolvere in beneficenza la propria quota. Verrà effettuato un pagamento a suo nome verso il servizio scelto. Puntate doppie o multiple (il giocatore punta più volte sulla stessa bet) vengono considerate come singole ai fini della vincita, consumano però le bet a disposizione di ognuno.
* (R.6) Attenzione: i pagamenti vanno effettuati nella modalità indicata dagli admin. (R.6a) Tutti i pagamenti effettuati in modalità diversa da quella indicata vanno considerati come persi. (R.6b) Ricordiamo che le transazioni bitcoin sonno irreversibili, ognuno è responsabile per la propria transazione errata. (R.6c) Il metodo di pagamento che viene indicato dagli admin serve a rintracciare in modo univoco e senza errori una bet correttamente piazzata e pagata (si fa riferimento all'orario del pagamento e alle note indicate nella invoice che servono a indicare chi ha effettuato il pagamento)
* (R.7) Attenzione: al termine del periodo di gioco e prima della distribuzione dei premi verrà stilata una lista provvisioria dei possibili vincitori. (R.7a) Tutti i membri del gruppo hanno tempo 24 ore per controllare che non manchino vincitori o che non ci siano errori, trascorso quel periodo la lista sarà considerata definitiva e si procederà a pagare i vincitori li indicati. (R.7b) Non saranno ritenute valide lamentele oltre alla data prevista, 24 ore sono sufficienti per controllare che non ci siano errori o dimenticanze. 
[TORNA A HOME](https://github.com/Cmod777/CMrules#cmrules)
