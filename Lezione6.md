# Lezione di Elettromagnetismo

## Introduzione

Buongiorno a tutti! 😊 Oggi apriamo un nuovo capitolo riguardante l'induzione di corrente dovuta al campo magnetico. Questo fenomeno rappresenta un'altra connessione tra il campo magnetico e il circuito elettrico, osservata sperimentalmente.

## Fenomeno dell'Induzione di Corrente

### Esperimento di Osservazione

- **Descrizione dell'esperimento**: 
  - Se prendiamo un anello di filo conduttore e avviciniamo un magnete permanente nelle vicinanze, si osserva una corrente che fluisce nel circuito.
  - Anche se il circuito è passivo e non c'è forza elettromotrice, il movimento del magnete induce una corrente.

### Variazioni del Campo Magnetico

- **Movimento del magnete**: 
  - Avvicinando o allontanando il magnete dal circuito, o ruotandolo, si genera una corrente.
  - Questo fenomeno è dovuto al cambiamento del campo magnetico che genera una forza elettromotrice nel circuito.

## Collegamento tra Campo Magnetico ed Elettrico

- **Induzione Elettromagnetica**: 
  - Un cambiamento nel campo magnetico genera un campo elettrico.
  - La scoperta di Maxwell: un cambiamento nel campo elettrico genera un campo magnetico, il che consente la propagazione delle onde elettromagnetiche.

## Misurazione del Cambiamento nel Campo Magnetico

### Definizione del Flusso Magnetico

- **Concetto di flusso magnetico**: 
  - È la misura di quanto il campo magnetico attraversa una superficie.
  - Si calcola tramite l'integrale del prodotto scalare tra il campo magnetico $\mathbf{B}$ e un elemento di superficie $\mathrm{d}\mathbf{S}$.

\[
\Phi_B = \int_S \mathbf{B} \cdot \mathrm{d}\mathbf{S}
\]

### Legge di Faraday-Neumann-Lenz

- **Formula della forza elettromotrice indotta**:

\[
\mathcal{E} = -\frac{\mathrm{d}\Phi_B}{\mathrm{d}t}
\]

- **Interpretazione**: 
  - La corrente indotta si oppone alla variazione del flusso magnetico.

## Esempio Pratico

### Calcolo della Corrente Indotta

- **Dati dell'esempio**:
  - Area del loop: $0.1 \, \text{m}^2$
  - Resistenza: $10 \, \Omega$
  - Campo magnetico iniziale: $0.2 \, \text{T}$
  - Tempo di variazione: $10^{-4} \, \text{s}$

- **Calcolo della variazione del flusso**:

\[
\frac{\mathrm{d}\Phi_B}{\mathrm{d}t} = A \cdot \frac{\mathrm{d}B}{\mathrm{d}t} = 0.1 \, \text{m}^2 \cdot \frac{0.2 \, \text{T}}{10^{-4} \, \text{s}} = 200 \, \text{V}
\]

- **Calcolo della corrente**:

\[
I = \frac{\mathcal{E}}{R} = \frac{200 \, \text{V}}{10 \, \Omega} = 20 \, \text{A}
\]

### Direzione della Corrente

- **Regola della mano destra**: 
  - La corrente fluisce in modo da generare un campo magnetico che si oppone alla diminuzione del campo originale.

## Applicazioni Pratiche

### Trasformatore Elettrico

- **Funzionamento**:
  - Basato sull'induzione elettromagnetica.
  - Un'asta metallica con avvolgimenti di filo genera un campo magnetico variabile, inducendo una forza elettromotrice in un secondo avvolgimento.

## Equazioni di Maxwell

### Descrizione delle Equazioni

1. **Legge di Gauss per il campo elettrico**:

\[
\oint_S \mathbf{E} \cdot \mathrm{d}\mathbf{A} = \frac{Q_{\text{int}}}{\varepsilon_0}
\]

2. **Legge di Gauss per il campo magnetico**:

\[
\oint_S \mathbf{B} \cdot \mathrm{d}\mathbf{A} = 0
\]

3. **Legge di Faraday**:

\[
\oint_C \mathbf{E} \cdot \mathrm{d}\mathbf{l} = -\frac{\mathrm{d}}{\mathrm{d}t} \int_S \mathbf{B} \cdot \mathrm{d}\mathbf{A}
\]

4. **Legge di Ampère-Maxwell**:

\[
\oint_C \mathbf{B} \cdot \mathrm{d}\mathbf{l} = \mu_0 I_{\text{int}} + \mu_0 \varepsilon_0 \frac{\mathrm{d}}{\mathrm{d}t} \int_S \mathbf{E} \cdot \mathrm{d}\mathbf{A}
\]

## Comportamento dei Materiali nei Campi Magnetici

### Tipi di Materiali Magnetici

1. **Diamagnetici**: 
   - Riduzione del campo magnetico interno.
2. **Paramagnetici**: 
   - Aumento lieve del campo magnetico interno.
3. **Ferromagnetici**: 
   - Aumento significativo del campo magnetico interno.

### Permeabilità Magnetica

- **Definizione**:
  - Relazione tra il campo magnetico in materia $B$ e in vuoto $B_0$:

\[
B = \mu \cdot B_0
\]

- **Coefficienti**:
  - **Diamagnetici**: $\mu < 1$
  - **Paramagnetici**: $\mu > 1$
  - **Ferromagnetici**: $\mu \gg 1$

## Conclusione

Prendiamo una pausa e riprenderemo alle 12:00. Grazie per l'attenzione e ci vediamo più tardi! 📚