# Risposta alla domanda n.2

## Caso d'uso n.1

*Codice caso d'uso*: UC01

*Nome caso d'uso*: Raccolta

*Descrizione breve*: registrazione delle ordinazioni al tavolo.

*attori coinvolti*: Cameriere

*Pre-condizioni*: non specificato

*Post-condizioni*: Ordine in attesa

*Descrizione*: 

1. Il cameriere registra la richiesta, ed il numero del tavolo da dove proviene.
2. Il sistema crea l'ordine.
3. Mentre ci sono ancora ordinazioni da regisatrare, il sistema registra l'ordine.
4. Il cameriere chiude l'ordine.
5. Il sistema cambia lo stato dell'ordine a "InPreparazione".

****

## Caso d'uso n.2

*Codice caso d'uso*: UC02

*Nome caso d'uso*: Preparazione.

*Descrizione breve*: registrazione della preparazione dell'ordine.

*Attori coinvolti*: Cameriere, Preparatore.

*Pre-condizione*: Ordine in attesa.

*Post-condizione*: Preparazione in attesa.

*Descrizione*: 

1. Il preparatore richiama, il prossimo ordine da preparare.
2. Mentre ci sono ancora ordini da preparare, Il preparatore, provvede alla preparazione dello stesso, ed aggiorna il suo stato.
3. Il sistema aggiorna lo stato dell' ordine in "InAttesaDiConsegna", e lo segnala al cameriere.

**Sequenza alternativa degli eventi**: ArticoloMancante



