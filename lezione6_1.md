# Lezione di Elettromagnetismo: Autoinduzione e Circuiti Induttivi

![Circuito con induttore](frame_0.jpg)

## Introduzione 🌟

Nella lezione di oggi, approfondiamo il concetto di autoinduzione nei circuiti elettrici, un fenomeno che si verifica quando un circuito genera spontaneamente una forza elettromotrice a causa della variazione del campo magnetico al suo interno. Questo è simile all'induzione elettromagnetica che avviene tra due circuiti distinti, ma accade all'interno dello stesso circuito.

## Induzione Elettromagnetica tra Circuiti

### Fenomeno dell'Induzione

Quando due spire di filo sono poste una accanto all'altra, una variazione di corrente in una delle spire genera un campo magnetico variabile, che induce una corrente nell'altra spira. Questa corrente indotta, $I'$, dipende dalla forza elettromotrice, che è la derivata del flusso del campo magnetico.

### Legge di Lenz

La legge di Lenz ci dice che la corrente indotta si oppone alla variazione del campo magnetico che l'ha generata. Questo principio vale non solo tra spire distinte, ma anche all'interno della stessa spira. L'autoinduzione si verifica quando il campo magnetico generato da una spira induce una forza elettromotrice al suo interno.

## Autoinduzione nei Circuiti

### Forza Elettromotrice Indotta

Nel caso di autoinduzione, la forza elettromotrice aggiuntiva è proporzionale alla variazione del campo magnetico nel tempo. Dato che il campo magnetico è proporzionale all'intensità della corrente, la forza elettromotrice sarà proporzionale alla variazione della corrente nel tempo:

$$
\mathcal{E} = -L \frac{di}{dt}
$$

Dove $L$ è l'induttanza del circuito, una costante di proporzionalità che dipende dalla geometria del circuito.

### Unità di Misura

- **Induttanza ($L$):** misurata in Henry (H), dove $1\, \text{H} = 1\, \text{V}\cdot\text{s}/\text{A}$.
- **Flusso Magnetico:** misurato in Weber (Wb), dove $1\, \text{Wb} = 1\, \text{T}\cdot\text{m}^2$.

## Costruzione di un Induttore

![Solenoide](frame_1.jpg)

### Solenoide

Un solenoide è un esempio classico di induttore, costituito da molte spire di filo avvolte strettamente. Quando la corrente scorre attraverso queste spire, genera un forte campo magnetico, che a sua volta induce una forza elettromotrice significativa.

### Geometria e Induttanza

La forma e la disposizione delle spire influenzano l'induttanza. Un filo diritto avrà un'induttanza minore rispetto a un solenoide compatto.

## Energia Accumulata in un Induttore

L'energia accumulata in un induttore è data dall'integrale della potenza nel tempo, che può essere espressa come:

$$
W = \frac{1}{2} L I^2
$$

Questa energia è immagazzinata sotto forma di campo magnetico all'interno del solenoide.

## Analisi di un Circuito Induttivo

### Circuito RL

Un circuito RL semplice consiste in una resistenza (R) e un induttore (L) collegati in serie. Quando il circuito viene chiuso, la corrente inizia a fluire e l'induttore si oppone inizialmente al cambiamento di corrente a causa della sua autoinduzione.

![Circuito RL](frame_10.jpg)

### Equazione Differenziale

L'equazione del circuito RL è:

$$
\mathcal{E} = R I + L \frac{di}{dt}
$$

Questa è una equazione differenziale, simile a quella vista nei circuiti RC, ma qui la soluzione riguarda l'intensità di corrente nel tempo.

### Comportamento della Corrente

All'inizio, la corrente è zero e aumenta esponenzialmente fino a raggiungere un valore stazionario $I_0$. Il tempo caratteristico di questa crescita è $\tau = \frac{L}{R}$.

## Filtraggio delle Frequenze

### Circuiti RL e RC

- **Circuito RC:** Comportamento di filtro passa-alto, che consente il passaggio di segnali ad alta frequenza.
- **Circuito RL:** Comportamento di filtro passa-basso, che consente il passaggio di segnali a bassa frequenza.

![Filtri](frame_11.jpg)

### Applicazioni

I circuiti RLC combinati possono essere utilizzati per costruire filtri passa-banda, che permettono il passaggio solo di un intervallo specifico di frequenze, come nei sintonizzatori radio.

![RLC Circuito](frame_12.jpg)

## Conclusioni

Abbiamo esplorato il fenomeno dell'autoinduzione nei circuiti elettrici e il ruolo degli induttori come componenti chiave nei circuiti di filtraggio delle frequenze. Comprendere come la geometria e le proprietà dei materiali influenzano l'induttanza ci permette di progettare circuiti più efficienti e sintonizzati per applicazioni specifiche.