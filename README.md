# Guida all'Utilizzo del Bot per la Gestione delle Scommesse

## Introduzione

Benvenuto nel bot per la gestione delle scommesse! Questo bot ti permette di gestire le tue scommesse in modo professionale utilizzando tre metodi di puntata: fixed, updown e wincons. Segui questa guida per iniziare e gestire le tue scommesse.

## Comandi Principali

### Comando di Avvio

- **/start**: Avvia il bot e ricevi una breve introduzione.

### Comando di Inserimento

- **/inserimento** o **⏫ Inserimento**: Avvia il processo di inserimento di una nuova scommessa.

### Comando di Risultato

- **/risultato** o **☑️ Risultato**: Avvia il processo di inserimento del risultato di una scommessa.

### Comando di Eliminazione Strategia

- **/elimina_strategia**: Avvia il processo di eliminazione di una strategia.

### Comando di Modifica

- **/edit**: Avvia il processo di modifica di una scommessa esistente.

### Comando di Tabella

- **/tabella**: Genera una tabella di resoconto per una strategia specifica.

## Passaggi per l'Inserimento di una Nuova Scommessa

1. **Seleziona il Comando di Inserimento**:
   - Invio il comando `/inserimento` o seleziona "⏫ Inserimento" dalla tastiera.

2. **Seleziona una Strategia**:
   - Seleziona una strategia esistente o aggiungi una nuova strategia selezionando "+Nuova Strategia".

3. **Inserisci i Dettagli della Scommessa**:
   - Inserisci il nome dell'evento, la quota e il metodo (opzionale) nel formato: `nome evento, quota, metodo`.

4. **Conferma l'Inserimento**:
   - Il bot ti mostrerà i dettagli della scommessa inserita.

## Passaggi per l'Inserimento del Risultato di una Scommessa

1. **Seleziona il Comando di Risultato**:
   - Invio il comando `/risultato` o seleziona "☑️ Risultato" dalla tastiera.

2. **Seleziona la Scommessa**:
   - Seleziona la scommessa per la quale vuoi inserire il risultato.

3. **Inserisci il Risultato**:
   - Seleziona il risultato della scommessa: `✅ Vinta`, `❌ Persa` o `🔄 Annullata`.

## Passaggi per l'Eliminazione di una Strategia

1. **Seleziona il Comando di Eliminazione Strategia**:
   - Invio il comando `/elimina_strategia`.

2. **Seleziona la Strategia da Eliminare**:
   - Seleziona la strategia che desideri eliminare.

## Passaggi per la Modifica di una Scommessa

1. **Seleziona il Comando di Modifica**:
   - Invio il comando `/edit`.

2. **Seleziona la Strategia da Modificare**:
   - Seleziona la strategia della scommessa che desideri modificare.

3. **Seleziona la Scommessa da Modificare**:
   - Seleziona la scommessa che desideri modificare.

4. **Seleziona la Colonna da Modificare**:
   - Seleziona la colonna che desideri modificare: EVENTO, QUOTA, STAKE o RISULTATO.

5. **Inserisci il Nuovo Valore**:
   - Inserisci il nuovo valore per la colonna selezionata.

## Passaggi per la Generazione di una Tabella di Resoconto

1. **Seleziona il Comando di Tabella**:
   - Invio il comando `/tabella`.

2. **Seleziona la Strategia per la Tabella di Resoconto**:
   - Seleziona la strategia per la quale desideri generare la tabella di resoconto.

## Parametro Metodo

Il parametro "metodo" determina come viene calcolata la puntata (stake) per ogni scommessa. Ci sono tre metodi principali che puoi utilizzare:

1. **fixed**:
   - **Descrizione**: Questo metodo utilizza una puntata fissa per ogni scommessa.
   - **Formato**: `fixed(importo)`, dove `importo` è la puntata fissa.
   - **Esempio**: `fixed(10)` significa che ogni scommessa avrà una puntata di 10 unità.

2. **updown**:
   - **Descrizione**: Questo metodo aumenta la puntata dopo una perdita e diminuisce la puntata dopo una vittoria.
   - **Formato**: `updown(importo)`, dove `importo` è l'unità di base per il calcolo della puntata.
   - **Esempio**: `updown(10)` significa che la puntata verrà calcolata in base all'unità di 10 unità, aumentando dopo una perdita e diminuendo dopo una vittoria.

3. **wincons**:
   - **Descrizione**: Questo metodo recupera le perdite dopo un numero prestabilito di vittorie consecutive. Se il ciclo attuale non è in perdita, il metodo non funzionerà.
   - **Formato**: `wincons(numero_vittorie)`, dove `numero_vittorie` è il numero di vittorie consecutive necessarie per recuperare le perdite del ciclo attuale.
   - **Esempio**: `wincons(3)` significa che le perdite verranno recuperate dopo 3 vittorie consecutive se il ciclo attuale è in perdita.

### Esempi di Utilizzo

- **fixed(10)**: Ogni scommessa avrà una puntata di 10 unità.
- **updown(10)**: La puntata verrà calcolata in base all'unità di 10 unità, aumentando dopo una perdita e diminuendo dopo una vittoria.
- **wincons(3)**: Le perdite verranno recuperate dopo 3 vittorie consecutive se il ciclo attuale è in perdita.

### Note Importanti

- Il metodo `fixed` è il più semplice e prevedibile, ma non tiene conto delle variazioni di risultato.
- Il metodo `updown` è più dinamico e può aiutare a recuperare le perdite rapidamente, ma richiede una gestione attenta del capitale.
- Il metodo `wincons` è complesso e richiede una comprensione approfondita della gestione del capitale e delle probabilità di vittoria. Se il ciclo attuale non è in perdita, il metodo non funzionerà.

Scegli il metodo che meglio si adatta alla tua strategia di scommesse e gestione del capitale.

## Note Finali

- Assicurati di comprendere bene la gestione del capitale e le funzionalità del bot prima di iniziare.
- Se hai bisogno di assistenza, contatta il supporto o consulta la documentazione del bot.

Buona gestione delle tue scommesse!
