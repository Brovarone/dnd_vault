---
tags:
  - quest
alias: Baule ai Nani
tipo_quest: principale
stato: attiva 
priorita: alta
datore_di_lavoro: "[[Baldric]]"
luogo_partenza: "[[Korrak]]"
ricompensa: 500 mo, 1 pozione di cura superiore
scadenza_stimata: Tra 3 giorni
data_inizio: 2025-10-07
data_completamento:
---
# Quest: Baule ai nani

## Dettagli Essenziali
> **Obiettivo Principale:** Consegnare il baule a un gruppo di Nani che si trovano oltre il passo montano.

| Proprietà | Valore |
| :--- | :--- |
| **Datore di Lavoro** | [[$= this.datore_di_lavoro]] |
| **Luogo di Partenza** | [[$= this.luogo_partenza]] |
| **Ricompensa Promessa** | **$= this.ricompensa** |
| **Stato Attuale** | **$= this.stato** | 
| **Priorità** | **$= this.priorita** |

---

## Passo Passo (Sotto-obiettivi)
*Utilizza le checkboxes per segnare i progressi.*

### Fase 1: Preparazione
- [ ] Ricevere il baule da [[$= this.datore_di_lavoro]].
- [ ] Comprare provviste per il viaggio (stimate 20 mo).

### Fase 2: Viaggio
- [ ] Raggiungere il passo montano.
- [ ] Individuare il campo dei Nani.

### Fase 3: Conclusione
- [ ] Consegnare il baule.
- [ ] Riscattare la **$= this.ricompensa**.