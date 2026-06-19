# Analisi Statistica: Prestiti Regionali e Grado di Istruzione

## Descrizione del Progetto
Questo progetto applica un modello di regressione lineare semplice in R per analizzare le differenze interregionali in Italia riguardanti l'ammontare dei prestiti erogati a società non finanziarie e famiglie produttrici. L'obiettivo iniziale era testare l'ipotesi che il grado di istruzione (percentuale di laureati) potesse spiegare la disparità di accesso al credito tra le regioni.

## Fonti Dati
1. **Banca d'Italia**: Dataset "TFR20255_52000700" (Prestiti regionali).
2. **ISTAT**: Dataset "POPTIT" (Popolazione per titolo di studio e regioni).

## Risultati dell'Analisi
L'output del modello ha evidenziato una relazione debole e non statisticamente significativa tra la percentuale di laureati e i volumi dei prestiti:
- **P-value**: 0.258
- **R-squared**: 0.07036

L'ipotesi di partenza è stata rigettata. Il grado di istruzione non agisce come predittore forte per l'ammontare dei prestiti. Variabili alternative come il PIL regionale o il volume di attività produttive risultano metriche preferibili per analisi future.

## Tecnologie Utilizzate
- **Linguaggio**: R
- **Librerie**: `tidyverse`, `readxl`, `ggplot2`
