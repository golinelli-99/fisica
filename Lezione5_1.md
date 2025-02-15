# Effetti dei Campi Magnetici sui Correnti Elettrici

## Introduzione

In questa lezione, esploreremo l'effetto dei campi magnetici generati dai correnti elettrici e viceversa. 🌪️ Cominciamo con un filo attraversato da una corrente elettrica $I$. Qual è l'intensità e la direzione del campo magnetico generato dal flusso di corrente all'interno del filo?

## Momento magnetico per un atomo
Se consideriamo un atomo avente un solo elettrone che ruota attorno al nucleo, possiamo intenderlo come una corrente in un filo circolare generata da un solo elettrone. 

$$
i = \frac{q e}{T} = \frac{q e}{\frac{2\pi r}{v}} = \frac{q e v}{2\pi r}
$$

Essendo che $\mu = I \cdot A$ possiamo riscriverlo come $\mu = q e \left( \frac{v r}{2} \right) \cdot \frac{m_e}{m_e}$, se consideriamo il momento angolare che è definito come $L = m v r$ allora diviene:

$$
\vec{\mu} = \frac{q e}{2m} \cdot L_e
$$


## Legge di Biot-Savart

### Concetti Fondamentali

La legge di Biot-Savart descrive il campo magnetico generato da un elemento di corrente. Supponiamo di avere un pezzo di filo di lunghezza $\Delta L$ con una corrente $I$ che lo attraversa. Vogliamo determinare il campo magnetico $\Delta B$ generato in un punto nello spazio.

- **Intensità del Campo Magnetico**: Proporzionale alla corrente $I$ e alla lunghezza $\Delta L$ del filo.
- **Distanza**: Il campo magnetico diminuisce con l'aumentare della distanza dal filo.

### Equazione

L'equazione della legge di Biot-Savart è:

$$
\Delta B \propto \frac{I \Delta L}{r^2} 
$$

Dove \(r\) è la distanza tra il filo e il punto di interesse. È necessaria una costante di proporzionalità \(K'\), che ha un valore specifico:

$$
K' = \frac{\mu_0}{4\pi} 
$$

### Applicazioni della Legge

Questa espressione si interpreta come un contributo infinitesimale al campo magnetico da un piccolo pezzo di filo. I calcoli devono essere eseguiti per determinare il campo totale per fili molto lunghi o circolari.

## Esempi Pratici

### Filo Infinitamente Lungo

Immagina un filo infinitamente lungo con corrente $I$. Qual è l'effetto del campo magnetico in un punto dato?

- **Campo Magnetico**: Proporzionale alla corrente e inversamente proporzionale alla distanza $r$.
- **Direzione**: Determinata dalla regola della mano destra.

### Loop di Filo Singolo

Calcoliamo il campo magnetico al centro di un loop singolo di filo con corrente.

$$
B = \frac{2\pi K' I}{R} 
$$

- **Direzione**: Il campo punta fuori dal piano del loop.

### Solenoide

Un solenoide è un insieme di loop avvolti in serie. Il campo magnetico all'interno di un solenoide è uniforme e parallelo all'asse del cilindro.

$$
B = \mu_0 n I 
$$

Dove $n$ è la densità di avvolgimenti per unità di lunghezza.

## Interazioni tra Fili

### Forza tra Fili Paralleli

Due fili paralleli con correnti $I_1$ e $I_2$ esercitano una forza l'uno sull'altro:

$$
F = 2 K' \frac{I_1 I_2}{r} \Delta L 
$$

- **Forza Attrattiva**: Se le correnti sono nella stessa direzione.
- **Forza Repulsiva**: Se le correnti sono in direzioni opposte.

Questa interazione è stata storicamente utilizzata per definire l'unità di corrente elettrica, l'ampere.

## Conclusioni

I campi magnetici generati da correnti elettriche sono fondamentali per comprendere molte applicazioni pratiche, dai motori elettrici ai dispositivi di misurazione. 🧲 La legge di Biot-Savart ci fornisce un potente strumento per calcolare questi campi in vari scenari.
