### Equivalenza finanziaria
Lo scambio fra prestazioni finanziarie presuppone che tra queste esista equivalenza. Due o più somme di denaro che si susseguono nel tempo, possono essere confrontate con altre sulla base del **principio di equivalenza dei rispettivi flussi di cassa**. Il fattore che li rende equivalenti è il tasso di interesse. Per formalizzare tale principio possiamo dire che due somme possedute in istanti di tempo diversi, producono gli stessi effetti se sono legate dal **fattore di capitalizzazione di un singolo pagamento**:

$$F=P(1+i)^n$$

Notare come la formula inversa risulti essere invece il **fattore di attualizzazione di un singolo pagamento**:

$$P=F(1+i)^{-n}$$

L'equivalenza con prestazioni multiple (più pagamenti) riguarda scambi di denaro (debito/credito) di pari entità che si susseguono più volte nel tempo a intervalli regolari. Questa operazione presuppone che ci siano regolarità nelle quantità scambiate e nell'intervallo di tempo fra un'operazione e l'altra.

#### Serie di pagamenti uguali
- **A** è il pagamento singolo di una serie di pagamenti uguali effettuato alla fine di ogni periodo di interesse
- **A** contraddistingue somme uguali che si susseguono nel tempo ad intervalli regolari (le costanti del nostro mutuo, la somma mansile che accantoniamo a fini previdenziali, ecc.)
- La fine di un periodo di interesse coincide con l'inizio del successivo (P coincide con l'inizio, F coincide con la fine del progetto di investimento)
- **A** si verifica alla fine di ciascun periodo d'interesse considerato

#### Prestazioni Multiple
Per il calcolo dell'equivalenza con prestazioni multiple ci rifaremo ad una famiglia di fattori esposti qui di seguito:

- **Fattore di capitalizzazione composta di una serie di pagamenti uguali**
$$F=A\frac{(1+i)^n-1}{i}$$
- **Fattore di ammortamento di una serie di pagamenti uguali**
$$A=F\frac{i}{(1+i)^n-1}$$
- **Fattore di attualizzazione di una serie di pagamenti uguali**
$$P=A\frac{(1+i)^n-1}{i(1+i)^n}$$
- **Fattore di recupero del capitale**
$$A=P\frac{i(1+i)^n}{(1+i)^n-1}$$

### Il Capital Budgeting
Il **capital budgeting** è una metodologia con cui il management stabilisce l'allocazione ottimale delle risorse finanziarie. Si tratta di valutare se i progetti di investimento di lungo periodo di un'azienda valgono il costo iniziale richiesto. Tali progetti possono essere di lungo o breve periodo ma in entrambe i casi l'obiettivo primario del capital budgeting è sempre quello di creare valore per gli azionisti.
Nel capital budgeting i progetti si classificano come:

- **Indipendenti**: se la sua realizzazione non dipende da quella di altri progetti alternativi. Di conseguenza tutti i progetti indipendenti che rispettano i criteri del capital budgeting dovrebbero essere accettati e portati avanti.

- **Alternativi**: se non possono essere accettati tutti contemporaneamente, ad esempio per ragioni di budget. Per questo vengono anche detti mutuamente esclusivi.

### Criteri basati sul rendimento contabile
Tali criteri decisionali derivano da misure contabili di rendimento, alcuni basati sulla nozione di reddito dal punto di vista degli azionisti (ROE), mentre altri considerano il reddito dal punto di vista degli investitori (ROI).

$$ROI=\frac{Reddito\ Operativo\ (EBIT)}{Valore\ contabile\ del\ capitale\ investito\ nel\ progetto}$$

$$ROE=\frac{Utile\ Netto}{Valore\ contabile\ dell'investimento\ azionario\ nel\ progetto}$$

Le componenti di questo metodo riflettono i valori contabili delle imposte, non i valori di mercato o dei flussi cassa. Entrambi possono essere considerati al lordo o al netto di un'imposta. Se il progetto ha una durata pluriennale, per entrambi bisogna considerare i valori medi del periodo.

### Tempo di recupero
Il **tempo di recupero**, anche detto *pay-back period* o *PBP*, è un metodo che basa la valutazione di un progetto sul numero di anni necessari affinché il flusso di cassa cumulativo previsto eguagli l'esborso iniziale.
Secondo la regola del tempo di recupero è opportuno effettuare solo operazioni che "recuperano" nell'arco di tempo desiderato. Il tempo di recupero del capitale, pur non fornendo indicazioni nell'intero ciclo di vita dell'investimento, fornisce un metodo rapido per conoscere dopo quanto tempo possiamo rientrare in possesso del capitale investito. Dal punto di vista operativo, si deve individuare il numero di anni $t=n_{payback}$ in cui per la prima volta le entrate eguagliano le uscite.

$$\sum_{t=0}^{n_{payback}} F_t = 0$$ 

#### Punti di debolezza
- Non considera i flussi conseguiti nei periodi successivi a PBP.
- Non considera il valore finanziario del tempo.
- Non considera l'ammontare di capitale investito.
- È un indicatore di rischio, non di rendimento.
- La definizione del *cutoff period* può essere fissata in maniera del tutto arbitraria.
- Spinge i manager a perseguire politiche di breve periodo ma non di massimizzazione del valore nel lungo periodo. 
- È idoneo per un investimento "tradizionale" caratterizzato da un investimento iniziale elevato e nessun reinvestimento successivo.

#### Punti di forza
- Presenta una buona facilità di calcolo, uso e comunicazione
- Considera i flussi cassa.
- È idoneo per un investimento "tradizionale" caratterizzato da un investimento iniziale elevato e nessun reinvestimento successivo.

### Tempo di recupero attualizzato
Il **tempo di recupero attualizzato** è un metodo che basa la valutazione di un progetto sul numero di anni necessari affinché il flusso di cassa cumulativo **attualizzato** previsto equivalga all'esborso iniziale. Rispetto al tempo di recupero classico, considera il valore temporale del denaro:

$$\sum_{t=0}^{n_{payback}} F_t(1+i)^{-t}-F_0 = 0$$ 

### Il valore attuale netto
Il **valore attuale netto** rappresenta il contributo netto al valore economico dell'azienda ed esprime la differenza fra il valore attuale dei flussi monetari annui ed il valore dell'investimento. Il principale vantaggio del VAN è che riconosce il valore temporale del denaro e dipende unicamente dai flussi di cassa previsti dal progetto e dal costo opportunità del capitale.

$$VAN = \sum_{t=0}^n\frac{F_t}{(1+i)^t}$$

Dove:

- $F_t$ flusso di cassa iniziale ($t = 0$) e futuri generati al tempo $t$
- $n$ periodo di vita utile
- $i$ costo opportunità del capitale

#### Il costo opportunità del capitale
Il **costo opportunità del capitale** rappresenta il premio che gli investitori richiedono per accettare la posticipazione del ricavo, ovvero la remunerazione a cui si rinuncia investendo nel progetto piuttosto che nel mercato azionario.

#### Il periodo di vita utile
Il **periodo di vita utile** rappresenta l'orizzonte temporale del progetto che coincide generalmente con la vita economica utile del progetto.

#### Criterio di accettazione
Se il VAN > 0 allora ci troviamo in una situazione di **creazione del valore**, ne consegue che il progetto va accettato poiché l'analisi del progetto di investimento ha rilevato che i benefici futuri, valorizzati oggi, sono superiori ai costi dell'investimento.

Se il VAN < 0 allora ci troviamo in una situazione di **distruzione del valore**, ne consegue che il progetto va rifiutato poiché l'investimento ha un costo superiore rispetto ai benefici futuri.

### Equivalente annuo
L'**equivalente annuo**, in inglese *Annual Equivalent (AE)*, attraverso il segno ed il valore assunto, consente di stabilire quanto si potrà guadagnare annualmente dal progetto, su quale rendimento annuo fare affidamento. Fornisce le **stesse indicazioni del VAN** da cui deriva direttamente (è dato dal prodotto tra VAN e il fattore di recupero del capitale):

$$AE = VAN\frac{i(1+i)^t}{(1+i)^t-1}$$

Se l'$AE$ è $=0$ non si guadagna ne si perde, se è $>0$ si guadagna e l'investimento è pertanto accettabile, se è $<0$ si perde e l'investimento è pertanto inaccettabile. È utile se si stanno confrontando investimenti che hanno vita utile diversa, altrimenti è equivalente al confronto dei VAN dei rispettivi progetti.

### Tasso interno di rendimento
Il **tasso interno di rendimento (T.I.R.)**, in inglese *Internal Rate of Return (I.R.R.)*, è definito come quel tasso di interesse che rende identici i valori dei flussi positivi e negativi di un progetto. Il TIR esprime il rendimento effettivo di un progetto oltre il quale l'iniziativa non sarebbe economica, anche detto costo massimo della raccolta. Teoricamente è quel tasso di interesse che rende pari a zero il VAN:

$$\sum_{t=0}^n\frac{F_t}{(1+TIR)^n} = 0$$

Una volta calcolato il TIR lo si confronta con il costo opportunità del capitale e se è maggiore di quest'ultimo si accetta il progetto. Nel caso di più progetti mutualmente esclusivi, tutti a TIR maggiore del costo opportunità del capitale, si sceglie quello con il TIR più alto.

#### 1° Trappola del TIR - Prestare o prendere a prestito?
Con alcuni flussi cassa il VAN aumenta all'aumentare del tasso di sconto. Ciò è contrario alla relazione normalmente esistente fra VAN e tasso di sconto. Vediamo il seguente esempio:

|Progetto| $F_0$ | $F_1$ | TIR |VAN (10%)|
|--------|-------|-------|-----|---------|
|    A   |- 1.000|+ 1.500|+ 50%|  + 364  |
|    B   |+ 1.000|- 1.500|+ 50%|  - 364  |

Basandoci sul TIR potremmo concludere che i progetti siano ugualmente vantaggiosi, tuttavia nel caso A dove paghiamo inizialmente 1000€ stiamo prestando del denaro a un tasso del 50%;
nel secondo invece dove riceviamo inizialmente 1000€, lo stiamo prendendo in prestito ad un tasso del 50%. Quando prestiamo denaro, vogliamo un alto tasso di rendimento, mentre, quando lo prendiamo in prestito, il tasso di rendimento deve essere basso. 

#### 2° Trappola del TIR
Alcuni flussi di cassa possono generare VAN pari a 0 in corrispondenza di due tassi diversi di sconto. Il flusso di cassa che segue genera VAN pari a 0 sia al -50% che al 15,2%:

| $F_0$ |$F_1$|$F_2$|$F_3$|$F_4$|$F_5$|$F_6$|
|-------|-----|-----|-----|-----|-----|-----|
|- 1.000|+ 800|+ 150|+ 150|+ 150|+ 150|- 150|

Per la *regola dei segni* di Cartesio, vi sono tante soluzione quanti sono i cambiamenti di segno del polinomio. Il caso dei tassi di rendimento multipli si verifica quando il progetto prevede un'uscita di cassa finale.

Il TIR può inoltre risultare inesistente se il progetto prevede VAN positivo per qualsiasi tasso di attualizzazione, come nel seguente esempio:

|Progetto| $F_0$ | $F_1$ | $F_0$ | TIR |VAN (10%)|
|--------|-------|-------|-------|-----|---------|
|    C   |+ 1.000|- 3.000|+ 2.500| N/A |  + 339  |

#### 3° Trappola del TIR - Progetti mutuamente esclusivi

In questo caso occorre calcolare il tasso interno di rendimento dei flussi incrementali. 

|Progetto|  $F_0$ |  $F_1$ | TIR | VAN (10%)|
|--------|--------|--------|-----|----------|
|  F-E   |- 10.000|- 15.000| 50% |  + 3636  |

Poiché il TIR dell'investimento incrementale è maggiore del costo opportunità del capitale (50%>10%), viene scelto il progetto F. Se ci fossimo basati solo sul TIR avremmo scelto il progetto E. L'errore deriva dal fatto che il tir non tiene conto dell'entità dell'operazione.

#### 4° Trappola del TIR - Costo opportunità variabile nel tempo
Se i tassi d'interesse vanno nel tempo, nel calcolo del TIR si assume per semplicità che i tassi di sconto rimangano stabili durante il periodo di svolgimento dell'operazione. Questa soluzione è un'approssimazione che potrebbe in alcuni casi portare ad errore.

### Razionamento del capitale e indice di redditività
In presenza di risorse limitate, l'**indice di redditività**, in inglese *profitability index (PI)*, fornisce uno strumento per scegliere tra differenti alternative e combinazioni di progetti.
In ipotesi di razionamento del capitale, occorre individuare un metodo che selzioni il pacchetto di progetti caratterizzato dal più alto valore attuale netto.
$$PI=\frac{VAN}{Investimento}$$
L'indice di redditività medio ponderato più elevato può indicare quale investimento scegliere.