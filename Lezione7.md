# 📡 Onde Elettromagnetiche

**Autore**: Marco Pizzichemi  
📧 *marco.pizzichemi@unimib.it*  

---

## ⚡ 1. Induttanza

Un circuito con corrente genera un **campo magnetico** \( B \) nello spazio, che a sua volta induce una forza elettromotrice (EMF) secondo la **Legge di Faraday**:

> 📌 Quando la corrente cambia, cambia anche il campo magnetico e si genera un'EMF auto-indotta.

La **induttanza** (\( L \)) misura questa proprietà ed è definita in **Henry** \([H]\).

---

## 🔄 2. Circuiti LC

### 🔹 Comportamento iniziale  
Un circuito LC è composto da un **induttore** (\(L\)) e un **condensatore** (\(C\)), entrambi in grado di immagazzinare energia.  

Quando colleghiamo un condensatore carico a un induttore:
1. **Inizialmente** tutta l'energia è nel condensatore (\( E \) immagazzinata nel campo elettrico).
2. Il condensatore funge da generatore di EMF.
3. La corrente inizia a fluire nel circuito.
4. L'induttore **si oppone** al cambiamento di corrente.
5. Con il tempo, l'induttore accumula energia nel suo **campo magnetico**.
6. **Alternanza**: l'energia si scambia tra il condensatore e l'induttore ciclicamente.

🌀 Questo porta a un **comportamento oscillatorio** del circuito.

### 🔹 Evoluzione temporale  

L'energia totale del circuito è conservata:

$$
U_{\text{tot}} = U_C + U_L
$$

La soluzione dell'equazione differenziale descrive una **corrente oscillante**:

$$
i(t) = I_0 \cos(\omega t + \phi)
$$

Dove la **frequenza angolare** è:

$$
\omega = \frac{1}{\sqrt{LC}}
$$

📌 Maggiore sono \( L \) e \( C \), minore sarà la frequenza delle oscillazioni.

---

## 🔥 3. Circuiti RLC e Smorzamento

### 🔹 Resistenza e dissipazione  
I circuiti reali hanno sempre una resistenza \( R \), che dissipa energia sotto forma di calore.

L'equazione differenziale per un **circuito RLC senza generatore** (seconda legge di Kirchhoff):

$$
L \frac{d^2 q}{dt^2} + R \frac{dq}{dt} + \frac{q}{C} = 0
$$

📌 **Comportamento in funzione di \( R \)**:
- **Sotto-smorzato (\( \alpha < \omega_0 \))**: Oscillazioni con ampiezza decrescente.
- **Criticamente smorzato (\( \alpha = \omega_0 \))**: Ritorno a zero nel minor tempo possibile, senza oscillazioni.
- **Sovra-smorzato (\( \alpha > \omega_0 \))**: Ritorno lento senza oscillazioni.

Dove:

$$
\alpha = \frac{R}{2L}, \quad \omega_0 = \frac{1}{\sqrt{LC}}
$$

📌 **Nota**: La resistenza influenza anche la larghezza della banda passante nel comportamento in frequenza del circuito.

---

## 🔄 4. Circuiti in Corrente Alternata (AC)

Se aggiungiamo una **sorgente di tensione alternata** (AC), l'EMF applicata è:

$$
V(t) = V_0 \cos(\omega t)
$$

La risposta del circuito dipende dalla **frequenza** del generatore:
- **Risonanza** si ha quando la frequenza del generatore coincide con:

  $$
  \omega_{\text{risonanza}} = \frac{1}{\sqrt{LC}}
  $$

- Alla **risonanza**, la corrente nel circuito è massima.
- Il circuito RLC può agire come **filtro selettivo di frequenze**, principio base delle **radio** 📻.

---

## 🌊 5. Onde Elettromagnetiche

### 🔹 Propagazione nel vuoto  
Dalle equazioni di Maxwell, sappiamo che i campi **elettrico** (\( E \)) e **magnetico** (\( B \)) possono propagarsi nello spazio come **onde elettromagnetiche**.

📌 **Caratteristiche principali**:
- \( \mathbf{E} \) e \( \mathbf{B} \) sono **ortogonali tra loro** e **alla direzione di propagazione**.
- Sono **onde trasversali** 🚀.
- Il **campo elettrico** e **campo magnetico** oscillano in fase.

La forma di un'onda piana in direzione \( x \):

$$
E(x,t) = E_0 \cos(kx - \omega t)
$$

Dove:
- \( k = \frac{2\pi}{\lambda} \) è il numero d'onda.
- \( \omega = 2\pi f \) è la frequenza angolare.

### 🔹 Velocità della luce  
La velocità delle onde elettromagnetiche nel vuoto è data da:

$$
c = \frac{1}{\sqrt{\mu_0 \varepsilon_0}} \approx 3 \times 10^8 \text{ m/s}
$$

📌 **Scoperta storica**: Maxwell previde che la luce fosse un'onda elettromagnetica, e le misure di velocità di Fizeau lo confermarono.

---

## ⚡ 6. Energia e il Vettore di Poynting

Le onde elettromagnetiche **trasportano energia**.

📌 L'energia trasportata in un'onda EM è descritta dal **vettore di Poynting**:

$$
\mathbf{S} = \mathbf{E} \times \mathbf{B}
$$

- La direzione di \( \mathbf{S} \) indica **dove si propaga l'energia**.
- Il **modulo** di \( \mathbf{S} \) dà la potenza trasportata per unità di area.

L'**intensità media** dell'energia trasportata da un'onda piana è:

$$
\langle S \rangle = \frac{1}{2} c \varepsilon_0 E_0^2
$$

📌 Questo è il motivo per cui le **antenne trasmettono e ricevono onde EM**: il vettore di Poynting descrive il flusso di energia dalla sorgente al ricevitore 📡.

---

## 🎯 Conclusioni

📌 **Punti chiave**:
- I **circuiti LC** generano oscillazioni elettriche e magnetiche.
- L'aggiunta di **resistenza** introduce **smorzamento**.
- I **circuiti RLC con generatore AC** permettono la selezione delle frequenze (principio delle radio 📻).
- Le **onde elettromagnetiche** si propagano concatenando variazioni di \( E \) e \( B \).
- Il **vettore di Poynting** descrive il trasporto di energia nelle onde EM.

🚀 **Applicazioni**:
- **Radio, radar, trasmissioni TV**.
- **Comunicazioni wireless e fibra ottica**.
- **Microonde e segnali satellitari**.

📖 **Buono studio! 🔥**
