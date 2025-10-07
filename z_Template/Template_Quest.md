---
tags: [quest] 
alias: [Inserisci un nome breve/soprannome della Quest]
tipo_quest: principale # Usa un solo valore (principale, secondaria, fazione)
stato: attiva # Usa un solo valore (attiva, completata, fallita, in pausa)
priorita: alta # Usa un solo valore (alta, media, bassa)

datore_di_lavoro: "[[Nome PNG o Fazione]]"
luogo_partenza: "[[Nome Luogo]]"
ricompensa: "Descrivi qui la ricompensa (es. 500 mo, Spada +1)"
scadenza_stimata: "Tra X giorni o una data specifica" 

data_inizio: {{date}}
data_completamento: 
---
# Quest: {{title}}

> **Obiettivo Principale:** Consegnare il baule a un gruppo di Nani che si trovano oltre il passo montano.

| Proprietà | Valore |
| :--- | :--- |
| **Datore di Lavoro** | [[$= this.datore_di_lavoro]] |
| **Luogo di Partenza** | [[$= this.luogo_partenza]] |
| **Ricompensa Promessa** | **$= this.ricompensa** |
| **Stato Attuale** | **$= this.stato** | 
| **Priorità** | **$= this.priorita** |

## Passo Passo (Sotto-obiettivi)
*Utilizza le checkboxes per segnare i progressi.*

### Fase 1: Investigazione
- [ ] 
- [ ] 

### Fase 2: Azione
- [ ] 
- [ ] 

### Fase 3: Conclusione
- [ ] Ritorna dal [[{{datore_di_lavoro}}]] per riscuotere la {{ricompensa}}.

---

## Note e Piste

* **Connessioni:** Questa quest potrebbe essere collegata a [[Storia - Rivalità tra Gilde]].
* **Ostacoli:** Un drago è stato avvistato vicino all'ultima posizione del Pugnale.
* **Risorse:** Ho bisogno di un veleno per addormentare i cani da guardia.

## Riassunto (A Fine Quest)
*Quando la quest è completata o fallita, inserisci qui un breve resoconto.*