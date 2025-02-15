# Introduzione al Campo Elettromagnetico 🌟

In questa lezione, esploreremo il concetto di magnetismo e come i campi magnetici interagiscono con i materiali e le correnti elettriche. Discuteremo i fondamenti del magnetismo, le leggi che governano il comportamento dei campi magnetici e il loro effetto su particelle cariche.

## Magnetismo e Forze Magnetiche

### Caratteristiche dei Magneti Permanenti 🧲

I magneti permanenti sono materiali che possiedono un campo magnetico intrinseco. Questi magneti si comportano come se contenessero due cariche interne, una positiva e una negativa, che si manifestano come poli nord e sud. Quando due magneti si avvicinano, poli simili si respingono mentre poli opposti si attraggono. Questa interazione avviene senza contatto diretto, simile a come funziona un campo elettrico.

### Linee di Campo Magnetico

Quando si rappresenta un magnete, le linee di campo magnetico escono dal polo nord e entrano nel polo sud. Queste linee possono essere visualizzate utilizzando una bussola, che si orienta secondo la direzione del campo magnetico.

> **Nota:** Le linee di campo magnetico non si intersecano mai e sono sempre chiuse, a differenza delle linee di campo elettrico.

## Origine dei Campi Magnetici

### Correnti Elettriche e Campi Magnetici 🔄

Un campo magnetico può essere generato da una corrente elettrica che scorre attraverso un filo. Le linee di campo magnetico generate da un filo elettrico sono circolari e la loro direzione può essere determinata usando la **regola della mano destra**. Se la corrente scorre verso l'alto, le linee di campo ruotano in senso antiorario e viceversa.

> **Nota aggiuntiva:** Un solenoide, ovvero un filo avvolto a spirale, genera un campo magnetico simile a quello di un magnete permanente.

### Correnti Microscopiche e Momento Magnetico

All'interno dei materiali, i campi magnetici possono essere generati da piccole correnti elettriche dovute al movimento degli elettroni intorno ai nuclei. Questo spiega perché i magneti permanenti non possono essere divisi in monopoli magnetici isolati: i poli magnetici sono sempre accoppiati.

> **Curiosità:** Il **momento magnetico** degli elettroni è una delle cause principali del magnetismo nei materiali ferromagnetici.

## Misurazione del Campo Magnetico

### Unità di Misura: Tesla

Il campo magnetico è misurato in **Tesla (T)**. Per avere un'idea delle scale:

- Il **campo magnetico terrestre** è dell'ordine di $10^{-4}$ Tesla.
- I **magneti per risonanza magnetica (MRI)** raggiungono i $10^{-1}$ Tesla o più.
- Il **campo magnetico del Sole** può arrivare a diversi Tesla nelle macchie solari.

## Effetti del Campo Magnetico

### Forza su Particelle Cariche

Una particella carica in movimento in un campo magnetico subisce una forza che è **perpendicolare** sia alla velocità della particella che al campo magnetico. La forza è data dalla legge di Lorentz:

$$
\vec{F} = q (\vec{v} \times \vec{B})
$$

dove:

- $q$ è la carica della particella,
- $\vec{v}$ è la velocità della particella,
- $\vec{B}$ è il campo magnetico.

Essendo la forza perpendicolare rispetto alla direzione del moto, essa non produce lavoro e, per la seconda legge di Newton, se non c'è lavoro, non c'è accelerazione. Pertanto, la velocità della particella non cambia, cambia solo la sua direzione.
La direzione della forza segue la **regola della mano destra**.

### Movimento Circolare e Forza Centripeta

Se una particella si muove **perpendicolarmente** al campo magnetico, il suo percorso diventa **circolare** con un raggio dato da:

$$
r = \frac{m v}{q B}
$$

dove:

-  $m$ è la massa della particella,
- $v$ è la velocità,
- $B$ è l'intensità del campo magnetico.

Se la velocità ha una componente parallela al campo, il movimento risultante sarà a **spirale**.

## Interazione tra Circuiti e Campi Magnetici

### Particella all'interno di una campo magnetico ed elettrico

Se inserisco una particella all'interno sia di un campo magnetico che di un campo elettrico in modo che la forza risultante sulla particella sia 0, posso selezionarne la velocità:


$\vec{F} = q \vec{v} \times \vec{B} + q \vec{E}$ dove $\vec{F}=0$ \
$q\vec{v}\times\vec{B} = q\vec{E}$ \
$\vec{E} = \vec{v}\times\vec{B}$ \
$v = \frac{E}{B}$


### Forza su un Filo Conduttore

Un filo che trasporta una corrente elettrica in un campo magnetico subisce una forza per unità di lunghezza data da:

$$
\vec{F} = I (\vec{L} \times \vec{B})
$$

dove:

- $I$ è l'intensità della corrente,
- $\vec{L}$ è il vettore lunghezza del filo.

Su un circuito chiuso invece si generano una coppia di forze uguali ed opposte, che generano un **momento torcente $\tau$** dato da:

$$
\tau = \vec{r} \times \vec{F}
$$

$$
\begin{cases}
\vec{\tau}_1 = \frac{\ell}{2} \cdot i \cdot \ell \cdot B \\
\vec{\tau}_2 = \frac{\ell}{2} \cdot i \cdot \ell \cdot B
\end{cases}
$$

$$
\vec{\tau} = \vec{\tau}_1 + \vec{\tau}_2 = \ell^2 i B = i \cdot A \cdot B = i A \hat{m} \times \vec{B}
$$

> **Nota:** Questo principio è alla base del **motore elettrico**, dove un campo magnetico esercita una forza su un filo percorso da corrente, generando movimento.

### Momento di Dipolo Magnetico

Un circuito chiuso in un campo magnetico può essere descritto da un **momento di dipolo magnetico** $\vec{\mu}$, che è dato da:

$$
\vec{\mu} = I \vec{A}
$$

dove $\vec{A}$ è l'area del circuito. La coppia torcente su un circuito in un campo magnetico è data da:

$$
\vec{\tau} = \vec{\mu} \times \vec{B}
$$

Se $\vec{\mu}$ è parallelo a $\vec{B}$ e quindi $\vec{\tau} = 0$ allora ho due casi possibili di equilibrio:

$$
\begin{cases}
\vec{\mu} \parallel \vec{B} & \text{equilibrio stabile} \\
-\vec{\mu} \parallel \vec{B} & \text{equilibrio instabile}
\end{cases}
$$

