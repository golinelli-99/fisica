# ⚡ Interazione delle Particelle Cariche con la Materia

_Autore: Marco Pizzichemi_  
📧 **Email:** marco.pizzichemi@unimib.it  

---

## 🔬 1. Interazioni della Radiazione con la Materia

### ⚛️ Principali processi di interazione
Le particelle cariche, i fotoni e i neutroni interagiscono con la materia attraverso diversi meccanismi:

| Tipo di radiazione | Principali processi di interazione |
|--------------------|----------------------------------|
| **Particelle cariche** | Ionizzazione, eccitazione, interazioni nucleari, processi radiativi (es. bremsstrahlung) |
| **Fotoni** | Effetto fotoelettrico, diffusione Compton, produzione di coppie, cascata elettromagnetica |
| **Neutroni** | Diffusione elastica e inelastica, cattura neutronica |

---

## 🌌 2. Necessità della Fisica Quantistica
- La **fisica classica** non è sufficiente per descrivere il comportamento della materia su scala atomica.
- Esempio: gli **elettroni negli atomi** hanno energie di legame di circa **10 eV** e momenti nell'ordine di $p \approx 10^{-24}$ kg·m/s.
- La loro lunghezza d’onda di de Broglie è comparabile alle dimensioni atomiche, quindi il comportamento degli atomi non può essere descritto in termini classici.

---

## 📏 3. Sezione d'Urto e Cammino Libero Medio

### 📌 Definizione di Sezione d'Urto
- La **sezione d'urto** $\sigma$ misura la probabilità di interazione tra una particella incidente e un bersaglio:
  $$
  \sigma = \frac{N}{n S_0 X}
  $$
  dove:
  - $N$ è il numero di particelle che interagiscono,
  - $n$ è la densità dei bersagli,
  - $S_0$ è l'area della superficie incidente,
  - $X$ è lo spessore del bersaglio.

- L’unità di misura della sezione d’urto è il **barn**:  
  $$
  1 \text{ barn} = 10^{-28} \text{ m}^2
  $$

### 📌 Cammino Libero Medio
- Il **cammino libero medio** $\lambda$ è la distanza media percorsa da una particella prima di subire un'interazione:
  $$
  \lambda = \frac{1}{n \sigma}
  $$

---

## ⚡ 4. Interazione delle Particelle Cariche

### 🔋 Meccanismi principali:
1. **Ionizzazione ed eccitazione**: diffusione anelastica con gli elettroni atomici.
2. **Bremsstrahlung**: emissione di radiazione da una carica accelerata.
3. **Scattering multiplo**: collisioni elastiche con i nuclei.
4. **Effetto Cherenkov e radiazione di transizione**: emissione di fotoni.

---

## 🌀 5. Perdita di Energia per Ionizzazione (Formula di Bethe-Bloch)

### 📌 Collisioni anelastiche con elettroni
- Il processo dominante per particelle cariche pesanti è la **ionizzazione**:
  $$
  Pa + \text{atomo} \rightarrow Pa + \text{atomo}^+ + e^-
  $$
- In alternativa, si può verificare **eccitazione** dell’atomo, seguita dall’emissione di un fotone:
  $$
  Pa + \text{atomo} \rightarrow Pa + \text{atomo}^*
  $$
  $$
  \text{atomo}^* \rightarrow \text{atomo} + \gamma
  $$

### 📌 Formula di Bethe-Bloch
- Descrive la perdita media di energia per unità di lunghezza:
  $$
  -\frac{dE}{dx} = \frac{K z^2}{\beta^2} \left[ \ln \frac{2 m_e c^2 \beta^2 \gamma^2 T_{\max}}{I^2} - 2\beta^2 \right]
  $$
  con:
  - $K = 4\pi N_A r_e^2 m_e c^2 = 0.307$ MeV g⁻¹ cm²,
  - $T_{\max}$ energia massima trasferibile in una collisione,
  - $I$ potenziale di eccitazione del materiale.

### 📌 Effetti di Correzione
- **Correzione di bassa energia ($C$)**: tiene conto dell’energia di legame degli elettroni.
- **Correzione ad alta energia ($\delta$)**: effetto di densità, la polarizzazione del materiale riduce la perdita di energia.

---

## 📊 6. Energia Persa e Raggio della Particella

### 📌 Particelle minime ionizzanti (MIP)
- Per $\beta\gamma \approx 3-4$, la perdita di energia è minima: **MIP (Minimum Ionizing Particle)**.

### 📌 Raggio della particella
- La distanza percorsa prima di fermarsi è chiamata **range** $R$:
  $$
  R = \int_0^E \frac{dE}{(dE/dx)}
  $$

### 📌 Picco di Bragg
- **Le particelle cariche lasciano la maggior parte della loro energia alla fine del percorso**.
- Questo è il principio della **terapia adronica per il trattamento dei tumori**. 🎯

---

## ⚛️ 7. Radiazione di Bremsstrahlung

- Una particella accelerata emette radiazione **bremsstrahlung**:
  $$
  P_{\text{rad}} \propto \frac{Z^2}{m^2}
  $$
  - Più importante per elettroni rispetto a particelle pesanti.
  - Determina il **limite di radiazione critica** $E_c$, dove le perdite per bremsstrahlung e ionizzazione sono uguali.

### 📌 Lunghezza di radiazione $X_0$
- Distanza dopo la quale un elettrone perde **1/e** della sua energia per bremsstrahlung.

| Materiale | $X_0$ (cm) |
|-----------|-----------|
| **Piombo** | 0.56 |
| **Ferro** | 1.76 |
| **Aria** | 30050 |

---

## 🎯 8. Scattering Multiplo

- Una particella carica subisce molte piccole deflessioni **(scattering multiplo)**.
- L'angolo medio quadratico è dato da:
  $$
  \theta_{\text{rms}} \approx \frac{13.6 \text{ MeV}}{\beta p} Z \sqrt{\frac{x}{X_0}}
  $$

---

## 🔷 9. Effetto Cherenkov e Radiazione di Transizione

### 📌 Effetto Cherenkov 🚀
- Una particella che si muove **più veloce della luce nel mezzo** emette radiazione Cherenkov.
- La condizione di emissione è:
  $$
  v > \frac{c}{n}
  $$
  con **$n$ indice di rifrazione**.
- L'angolo di emissione è:
  $$
  \cos\theta_C = \frac{c}{n v}
  $$

### 📌 Radiazione di Transizione 🌌
- Quando una particella relativistica attraversa il confine tra due mezzi con **costanti dielettriche diverse**, emette **radiazione X**.

---

## 🔚 Conclusione
Lo studio dell’interazione delle particelle cariche con la materia è fondamentale per applicazioni in **fisica delle particelle**, **fisica medica** (radioterapia e imaging), e **rilevazione di particelle** nei grandi esperimenti. 🚀✨
