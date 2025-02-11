# 📖 Ottica - Fondamenti Avanzati

_Autore: Marco Pizzichemi_  
📧 **Email:** marco.pizzichemi@unimib.it  

---

## 📌 1. Onde e Luce

### 🌊 Definizione di onda
- Un'onda è una perturbazione che si propaga **senza trasporto di materia**.
- Esempio: gettando un sasso in un lago, si formano **onde circolari** che si propagano senza che l'acqua si sposti significativamente.

### ⚡ Luce come onda
- **Onde luminose** possono viaggiare nel vuoto.
- Il disturbo si manifesta come una variazione nei **campi elettrico e magnetico**.
- La luce può essere trattata con le stesse proprietà delle onde sonore o delle vibrazioni nei solidi.

### 🔄 Parametri fondamentali delle onde
- **Velocità dell'onda**: ogni onda si propaga con velocità finita.
- **Lunghezza d'onda** $\lambda$ [m]: periodicità nello spazio.
- **Frequenza** $\nu$ [Hz]: periodicità nel tempo.
  - **Periodo** $T = \frac{1}{\nu}$
- **Relazione fondamentale delle onde**:
  $$
  v = \lambda \nu
  $$

### 📈 Equazione dell'onda
- **Ampiezza**: massimo spostamento dal punto di equilibrio.
- **Fase**: l'argomento della funzione seno, determina il punto nel ciclo dell'onda.
- **Equazione generale per un'onda monodimensionale**:
  $$
  y(x,t) = A \sin(kx - \omega t + \phi)
  $$
  con:
  - **Numero d'onda** $k = \frac{2\pi}{\lambda}$
  - **Frequenza angolare** $\omega = 2\pi \nu$

---

## 🌟 2. La Luce: Dualità Onda-Particella

### ⚖️ La doppia natura della luce
- **Prima del XIX secolo**: Newton considerava la luce un flusso di particelle.
- **1678 - Huygens**: propose una teoria ondulatoria della luce.
- **1801 - Young**: dimostrò l'interferenza della luce (esperimento della doppia fenditura).
- **1873 - Maxwell**: formulò l'elettromagnetismo, spiegando la luce come onda elettromagnetica.
- **XX secolo**: alcuni fenomeni (es. effetto fotoelettrico) dimostrarono che la luce si comporta anche come **particella**.

### 📡 Spettro elettromagnetico
- **Lo spettro elettromagnetico** comprende tutte le radiazioni in funzione della loro lunghezza d’onda.
- Relazione tra lunghezza d’onda e frequenza:
  $$
  c = \lambda \nu
  $$
  con **c = \(3 \times 10^8\) m/s** (velocità della luce nel vuoto).

| Tipo di onda | Lunghezza d'onda (m) | Applicazioni |
|-------------|----------------------|--------------|
| **Onde radio** | $10^4 - 0.1$ | Comunicazioni, radio 📻 |
| **Microonde** | $0.3 - 10^{-4}$ | Radar, telecomunicazioni 📡 |
| **Infrarossi** | $10^{-3} - 7 \times 10^{-7}$ | Termografia, telecomandi 🔥 |
| **Visibile** | $7 \times 10^{-7} - 4 \times 10^{-7}$ | Luce percepibile dall'occhio umano 👀 |
| **Ultravioletti** | $4 \times 10^{-7} - 6 \times 10^{-10}$ | Abbronzatura, sterilizzazione ☀️ |
| **Raggi X** | $10^{-8} - 10^{-12}$ | Diagnostica medica, astronomia 🔍 |
| **Raggi γ** | $10^{-10} - 10^{-14}$ | Radioattività, fisica nucleare ⚛️ |

---

## 🔎 3. Ottica Geometrica

### 🪞 Riflessione e Legge della Riflessione
- Quando un raggio di luce incontra una superficie riflettente, viene **riflesso**.
- **Legge della riflessione**:
  $$
  \theta_i = \theta_r
  $$
  dove:
  - $\theta_i$ è l'angolo di incidenza
  - $\theta_r$ è l'angolo di riflessione

### 🔄 Rifrazione e Legge di Snell
- Se un raggio di luce passa da un mezzo con indice di rifrazione $n_1$ a un altro con $n_2$, cambia direzione secondo la **Legge di Snell**:
  $$
  n_1 \sin\theta_1 = n_2 \sin\theta_2
  $$
- **Indice di rifrazione**:
  $$
  n = \frac{c}{v}
  $$
  con $v$ la velocità della luce nel mezzo.

### 🌈 Dispersione e Rifrazione Totale
- L'indice di rifrazione dipende dalla **lunghezza d’onda** → **la luce si scompone nei suoi colori** (es. prisma e arcobaleno 🌈).
- Se l’angolo di incidenza supera un certo valore **($\theta_c$ angolo critico)**, la luce subisce **riflessione totale interna**.

---

## 🔭 4. Specchi e Lenti

### 📌 Equazione degli specchi
- Relazione tra distanza dell’oggetto, distanza dell’immagine e lunghezza focale:
  $$
  \frac{1}{p} + \frac{1}{q} = \frac{1}{f}
  $$
  con:
  - $p$ = distanza dell'oggetto
  - $q$ = distanza dell'immagine
  - $f$ = lunghezza focale

### 📌 Equazione delle lenti sottili
- Per una lente con curvature $R_1$ e $R_2$:
  $$
  \frac{1}{f} = (n - 1) \left( \frac{1}{R_1} - \frac{1}{R_2} \right)
  $$

---

## 🎭 5. Interferenza e Diffrazione

### 🌊 Esperimento della doppia fenditura
- **Onde coerenti e monocromatiche** danno interferenza costruttiva e distruttiva.
- **Massimi di interferenza**:
  $$
  d \sin\theta = m\lambda
  $$
- **Minimi di interferenza**:
  $$
  d \sin\theta = \left(m + \frac{1}{2} \right) \lambda
  $$

### 📡 Reticolo di diffrazione
- Un reticolo di diffrazione con $N$ fenditure produce massimi di diffrazione in posizioni date da:
  $$
  d \sin\theta = m\lambda
  $$

---

## ☀️ 6. Polarizzazione della Luce

### 🔄 Malus' Law
- L’intensità della luce che passa attraverso un polarizzatore è:
  $$
  I = I_0 \cos^2\theta
  $$
  con $\theta$ angolo tra l’asse del polarizzatore e il vettore campo elettrico.

### 🔵 Angolo di Brewster
- Quando un raggio di luce colpisce una superficie con un **angolo particolare** ($\theta_B$), il raggio riflesso è **completamente polarizzato**.
- **Formula dell'angolo di Brewster**:
  $$
  \tan\theta_B = \frac{n_2}{n_1}
  $$

---

## 📌 Conclusioni
L’ottica è una branca della fisica fondamentale, con applicazioni che vanno dalle telecomunicazioni alla diagnostica medica, fino all’astrofisica e alla tecnologia laser. 🔬✨
