# Introduzione ai Circuiti Elettrici 🚀

Benvenuti alla lezione di oggi sui circuiti elettrici! Esploreremo i concetti fondamentali di corrente, potenziale e circuiti elettrici semplici. Sentitevi liberi di fare domande e, se preferite non essere registrati, fatemelo sapere. Iniziamo!

---

## ⚡ Corrente Elettrica e Convenzioni

### 📌 Definizione di Corrente Elettrica
La corrente elettrica è il flusso di carica elettrica, tipicamente confinato all'interno di circuiti composti da materiali conduttori, come i fili. Questo flusso richiede materiali conduttori e permette diverse configurazioni e modelli di circuiti elettrici.

### 🔄 Tipi di Circuiti
<br>
<br>
<img align="right" width="200" src="DC.png" alt="Descrizione">
<p> 
   
1. **Corrente Continua (DC):**  
   - La corrente scorre costantemente in una direzione.  
   - Un generatore fornisce la corrente dal polo positivo a quello negativo, secondo la convenzione di flusso da positivo a negativo.  
</p>
<br>
<br>
<img align="right" width="200" src="AC.png" alt="Descrizione">
<p> 
   
2. **Corrente Alternata (AC):**  
   - La corrente cambia direzione periodicamente.  
   - Il generatore in un circuito AC non mantiene una polarità fissa, permettendo alla corrente di alternarsi.  

</p>
<br>
<br>

### 📏 Intensità di Corrente
L’intensità di corrente $I$ è definita come il tasso di flusso della carica attraverso una sezione trasversale del filo:

$$
I = \frac{dQ}{dt}
$$

dove $Q$ è la carica e $t$ è il tempo.

---

## 🔍 Vista Microscopica del Flusso di Corrente
<img align="right" width="300" src="tubo.png" alt="Descrizione">
<p> 
   
### ⚛️ Portatori di Carica
- Il flusso di corrente è dovuto ai portatori di carica, tipicamente elettroni nei conduttori.
- La velocità di deriva media di questi portatori di carica è molto piccola.

### 🧮 Rappresentazione Matematica
La corrente può essere espressa come:

$$
\frac{dq}{dt} = e \cdot \frac{N}{dt} = e n \frac{V}{dt} = e n \frac{A ds}{dt} = I
$$

$$
I = n \cdot A \cdot v_d \cdot e
$$
</p> 

dove:
- N è il numero dei portatori di carica
- $n$ è la densità dei portatori di carica,
- $A$ è l'area della sezione trasversale del filo,
- $v_d$ è la velocità di deriva,
- $e$ è la carica elementare.

---

## 🔌 Resistenza e Legge di Ohm

### 📏 Conduttori Ohmici
La relazione tra tensione $V$ e corrente $I$ è lineare:

$$
V = I \cdot R
$$

dove $R$ è la resistenza. In base ai suoi valori si distinguono in:




### 🏗️ Fattori che Influenzano la Resistenza
La resistenza dipende dalla resistività del materiale $\rho$, dalla lunghezza $L$ e dall'area della sezione trasversale $A$:

$$
R = \rho \cdot \frac{L}{A}
$$

| **Resistività (ρ) [Ω·m]**       | **Categoria**        | **Esempi**       |
|-------------------------------|----------------------|-----------------|
| 1-2 × 10⁻⁸                    | Conduttori          | Metalli         |
| 0,6 - 2300                     | Semiconduttori      | Silicio         |
| 10¹⁰ - 10¹⁴                   | Isolanti            | Vetro           |
| 0,15                           | Conduttori ionici   | Fluidi corporei |

### 🔥 Dissipazione di Potenza
La potenza è definita come $P=V \cdot I$.

Se in un circuito abbiamo un generatore di corrente, esso produce una **forza elettromotrice (EMF)** che non è altro che il potenziale applicato al circuito. (questa tensione V = EMF viene mantenuta dalla batteria in modo costante fino a quando non si scarica).

Avreemo quindi che $P=V \cdot I = EMF \cdot I$


La potenza $P$ dissipata in un resistore sarà data da:

$$
P = I^2 \cdot R = \frac{V^2}{R}
$$

---

## 🔄 Tecniche di Analisi dei Circuiti
<img align="right" width="300" src="serieparal.png" alt="Descrizione">
<p> 
   
### 🔗 Circuiti in Serie e in Parallelo
1. **Circuiti in Serie:**  

$$
   R_{\text{totale}} = R_1 + R_2 + \dots + R_n
$$

   - La stessa corrente scorre attraverso ogni componente.

2. **Circuiti in Parallelo:**  

$$
   \frac{1}{R_{\text{totale}}} = \frac{1}{R_1} + \frac{1}{R_2} + \dots + \frac{1}{R_n}
$$

   - La stessa tensione è applicata a ogni componente.
</p>
<br><br>

### ⚖️ Leggi di Kirchhoff
<img align="right" width="400" src="kirchoff.png" alt="Descrizione">
<p> 
   
1. **Legge delle Tensioni di Kirchhoff (KVL):**  
   - La somma delle correnti entranti in un nodo è uguale alla somma delle correnti uscenti.

2. **Legge delle Correnti di Kirchhoff (KCL):**  
    - La somma di tutte le tensioni in un circuito chiuso è zero.

</p>
<br>
<br>

## 🔋 Condensatori e Accumulo di Energia
<img align="right" width="400" src="RC.png" alt="Descrizione">
<p> 
   
### ⚡ Condensatori nei Circuiti
- I condensatori immagazzinano energia in un campo elettrico tra due piastre.
- La carica $Q$ su un condensatore è data da:

$$
  Q = C \cdot V
$$

dove $C$ è la capacità.

### 🔄 Carica e Scarica di un Condensatore
- **Carica:** La tensione su un condensatore aumenta man mano che accumula carica.
- **Scarica:** L’energia immagazzinata viene rilasciata, causando una diminuzione della tensione.
   

</p>

### ⏳ Costante di Tempo
- La costante di tempo $\tau$ per un circuito resistivo-capacitivo (RC) è:

$$
  \tau = R \cdot C
$$

Indica la velocità con cui un condensatore si carica o si scarica.

---

## 🌟 Concetti Avanzati e Applicazioni

### 🎛️ Circuiti AC e Filtri
- I condensatori possono essere utilizzati per filtrare segnali, permettendo il passaggio solo di determinate frequenze.
- **Filtri passa-alto** permettono il passaggio dei segnali ad alta frequenza, bloccando quelli a bassa frequenza.

