
# 📊 Power BI - Financial Sample Dashboard

## 📌 Descrizione del Progetto
Questo repository contiene un progetto completo di **Business Intelligence** sviluppato su Power BI Desktop basato sul dataset aziendale *Financial Sample*. Il report è stato progettato per analizzare le performance economico-finanziarie commerciali, tracciando margini, profitti e vendite aggregate a livello globale.

---

## 🛠️ Architettura e Processo ETL
Il progetto segue il flusso di lavoro standard end-to-end:

1. **Estrazione & Pulizia (Power Query):**
   * Tipizzazione corretta dei campi numerici e temporali (`Date`, `Sales`, `Profit`).
   * Normalizzazione dei dati e gestione dei valori nulli.
2. **Modellazione & Calcolo (DAX):**
   * Creazione di **Misure DAX** dinamiche per KPI chiave 
3. **Visualizzazione & UX Design:**
   * Strutturazione dell'interfaccia secondo le regole di gerarchia visiva (layout F-shape).
   * Schede KPI posizionate in evidenza per i dati di picco.
   * Grafici a barre e stacked column chart per l'analisi dimensionale (Prodotti e Segmenti).
   * Grafico ad anello per l'impatto geografico degli sconti.
   * **Slicer interattivi** per la segmentazione e il filtraggio dinamico.

---

## 📈 Key Insights & Dashboard Layout
* **KPI Principali:** Monitoraggio immediato di Unità vendute massime, Profitto massimo e Sconti.
* **Segment Performance:** Confronto dei profitti generati tra settori (*Government*, *Small Business*, *Enterprise*).
* **Geographic Distribution:** Ripartizione percentuale del valore degli sconti applicati per ciascun Paese.
* **Product Analytics:** Confronto diretto tra costi di produzione (*Manufacturing Price*) e prezzi di vendita (*Sale Price*).

---

<img width="1408" height="755" alt="Screenshot 2026-09-15 175856" src="https://github.com/user-attachments/assets/2defb600-1af6-49b9-b78e-d230775fad27" />
