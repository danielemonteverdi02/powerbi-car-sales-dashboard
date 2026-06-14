# 🚗 Analisi delle Vendite Automobilistiche

## 📋 Descrizione del progetto

Dashboard interattiva sviluppata in **Power BI** per l'analisi delle vendite automobilistiche. Il progetto permette di monitorare KPI commerciali, analizzare l'andamento delle vendite nel tempo e approfondire le singole transazioni tramite funzionalità di **drill-through**.

La dashboard è composta da due pagine:

- **Overview**: panoramica generale delle performance aziendali.
- **Vendite**: dettaglio delle singole transazioni.

---

## 🎯 Obiettivi

- Monitorare l'andamento delle vendite.
- Analizzare i ricavi generati.
- Valutare le performance delle aziende automobilistiche.
- Analizzare le vendite per carrozzeria, colore e concessionario.
- Esplorare le transazioni a livello dettagliato.

---

## 🛠️ Tecnologie utilizzate

- Power BI Desktop
- Power Query
- DAX
- Data Modeling
- Drill-Through
- Slicer e filtri interattivi

---

## 📊 KPI principali

### Vendite Totali
Numero complessivo di automobili vendute.

### Guadagno Totale
Ricavo complessivo generato dalle vendite.

### Prezzo Medio Auto
Prezzo medio delle automobili vendute.

Per ogni KPI viene mostrata anche la variazione percentuale rispetto all'anno precedente.

---

## 📈 Visualizzazioni

### Pagina Overview

- Guadagno totale per mese (grafico a linee)
- Performance delle aziende (tabella)
- Guadagno per tipologia di carrozzeria (grafico a ciambella)
- Guadagno per città del concessionario (grafico a barre)
- Vendite per colore dell'automobile (grafico a colonne)

### Pagina Vendite

Tabella dettagliata delle transazioni contenente:

- ID vendita
- Data
- Azienda
- Modello
- Carrozzeria
- Cambio
- Motore
- Colore
- Prezzo
- Città del concessionario
- Sesso del cliente

---

## 🔍 Filtri disponibili

L'utente può filtrare dinamicamente l'intera dashboard tramite:

- Anno
- Cambio
- Concessionario
- Motore

Tutti i visual vengono aggiornati automaticamente in base alle selezioni effettuate.

---

## 🚀 Funzionalità Drill-Through

È stata implementata una funzionalità di **drill-through** sul KPI **Guadagno Totale**.
Quando l'utente seleziona un elemento di un visual contenente il guadagno (ad esempio un mese nel grafico temporale), può effettuare il drill-through verso la pagina **Vendite**.
La pagina di dettaglio viene automaticamente filtrata mostrando esclusivamente le transazioni associate all'elemento selezionato.
Questa funzionalità consente di passare rapidamente da una vista aggregata ad una vista di dettaglio, facilitando l'analisi delle vendite che contribuiscono ai risultati osservati.

---

## 📌 Risultati

La dashboard fornisce una panoramica completa delle performance commerciali attraverso KPI sintetici e visualizzazioni interattive, permettendo sia analisi ad alto livello sia approfondimenti sulle singole transazioni mediante funzionalità di drill-through e filtraggio dinamico.
