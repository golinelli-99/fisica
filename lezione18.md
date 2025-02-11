---
title: "Rivelatori di Particelle"
author: "Appunti di Fisica Avanzata"
date: "2025"
---

# 📡 Rivelatori di Particelle

## 📌 Proprietà Generali

### 🔬 Come rileviamo la radiazione?
Per rilevare una particella ionizzante, il rivelatore deve soddisfare le seguenti condizioni:

- **Nessuna particella → Nessun segnale**  
- **Particella ionizzante → Segnale rilevabile**  

L'interazione di una particella con il rivelatore porta solitamente alla generazione di carica elettrica nel volume attivo del rivelatore.

### 🛠️ Tipologie di generazione di carica
- **Diretta** (es. ionizzazione nei gas)
- **Indiretta** (es. scintillatori accoppiati a PMT)

L'interazione ha generalmente una durata molto breve:
- **Nanosecondi** nei gas
- **Picosecondi** nei solidi

La carica generata viene raccolta sugli elettrodi per formare un segnale elettrico.  
- **Particelle cariche** → Interazioni continue con piccole perdite di energia.  
- **Particelle neutre** → Poche interazioni, ma più distanti tra loro.  

### 📏 Cosa vogliamo misurare?
Un rivelatore può fornire diverse informazioni sulle particelle:
- **Traiettoria** → Risoluzione spaziale
- **Energia** → Risoluzione energetica
- **Posizione** → Risoluzione spaziale
- **Tempo** → Risoluzione temporale
- **Tipo di particella** → Risposta differente a seconda della particella incidente

---

## 🏗️ Esempio: Rivelatori a gas
Quando una particella attraversa un volume di gas:
1. Ionizza il gas, creando coppie elettrone-ione.
2. Un campo elettrico fa migrare le cariche verso gli elettrodi.
3. Il movimento delle cariche altera il campo elettrico e modifica il potenziale sugli elettrodi.

L'energia immagazzinata nel condensatore cambia secondo la relazione:

$$ \Delta E = 2 V_0 \Delta V $$

Dove \( C \) è la capacità del condensatore.

L'energia persa dalla particella è proporzionale al numero di coppie elettrone-ione prodotte lungo il cammino della particella.

---

## ⚡ Modalità di funzionamento
Tre modalità generali di funzionamento dei rivelatori di radiazioni:

1. **Modo a impulsi** 📊  
   - Conta ogni particella individualmente  
   - Migliore sensibilità  
   - Permette l'analisi dettagliata del segnale  

2. **Modo a corrente** 🔋  
   - Integra molte interazioni nel tempo  
   - Utile per alte frequenze di eventi  

3. **Modo MSV (Mean Square Voltage)** 📡  
   - Variante del modo a corrente  
   - Aumenta la risposta relativa agli eventi di ampiezza maggiore  

Il **modo a impulsi** è il più utilizzato, perché fornisce la massima sensibilità.

---

## 🔎 Risoluzione Energetica
La capacità di un rivelatore di separare energie vicine è definita dalla **risoluzione energetica**, espressa come:

$$ R = \frac{\text{FWHM}}{H_0} $$

Dove:
- **FWHM** è la larghezza a metà altezza della distribuzione degli impulsi
- **H₀** è la posizione del massimo

I valori tipici sono:
- **1%** per rivelatori a semiconduttore
- **5-10%** per scintillatori accoppiati a PMT

---

## ⏳ Tempo morto e rateo di conteggio
Il **tempo morto** (τ) è il tempo minimo tra due eventi per essere registrati separatamente.

Due modelli:
- **Non-paralizzabile** 🕒 → Il conteggio massimo è \( 1/ \tau \)
- **Paralizzabile** ⏳ → Se la frequenza degli eventi è troppo alta, il rivelatore può perdere eventi.

Alti ratei di interazione possono causare una **saturazione** della risposta del rivelatore.

---

## 🏆 Tipologie di Rivelatori
Tre categorie principali di rivelatori moderni:

1. **Rivelatori a gas** 💨  
   - Es. camere a ionizzazione, contatori Geiger
   - Sensibilità elevata per particelle cariche  

2. **Rivelatori a semiconduttore** 🔬  
   - Alta risoluzione energetica  
   - Esempi: rivelatori al silicio, germanio  

3. **Scintillatori** ✨  
   - Producono luce proporzionale all'energia della particella  
   - Accoppiati a PMT o fotodiodi  

Altri metodi storici includono le **camere a bolle, camere a nebbia** e **emulsioni nucleari**, ancora usate per dosimetria e radiografie industriali.

---

📌 **Conclusione:** I rivelatori di particelle sono strumenti fondamentali per la fisica delle radiazioni. Ogni tecnologia ha vantaggi specifici in termini di sensibilità, risoluzione energetica e velocità di risposta. La scelta del rivelatore dipende dal tipo di particelle da misurare e dal contesto sperimentale. 🎯
