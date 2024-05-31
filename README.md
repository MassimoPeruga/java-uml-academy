# Esercitazione UML

Dobbiamo sviluppare una dashboard di gestione dei dati del personale dei corsi di una Academy tech.
Gli analisti funzionali ci hanno consegnato i seguenti 3 casi d’uso che rappresentano i requisiti funzionali di questa
applicazione. Disegnare il Domani Model (diagramma delle classi) dell’applicazione utilizzando lo strumento che
preferite (diagrams o altre applicazioni) e consegnate su GitHub il file con l’immagine del diagramma. Buon lavoro!

#### Casi d’uso:

###### UC1: Inserimento di un nuovo studente - Attore primario: Utente Amministratore

1. L’Utente seleziona l’attività “Inserisci nuovo studente”
2. L’Utente inserisce nome, cognome, sesso, numero di telefono e titolo di studio dello studente
3. L’Utente inserisce l’indirizzo dello studente, composto da città, provincia, cap, via e numero civico
4. L’Utente richiede la lista di tutti i corsi non conclusi
5. Il Sistema mostra il codice, il nome, la data inizio e la data fine di ciascun corso
6. L’Utente seleziona il codice del corso che frequenta lo studente
7. Il Sistema registra il nuovo studente

###### UC2: Visualizzazione dati singolo corso - Attore primario: Utente Amministratore

1. L’Utente seleziona l’attività “Statistiche”
2. Il Sistema mostra la lista di tutti i corsi
3. L’Utente seleziona il codice di un corso
4. Viene mostrato uno ScatterPlot con sesso, età e media dei voti di tutti gli studenti

###### UC3: Export dati insegnanti - Attore primario: Utente Amministratore

1. L’Utente seleziona l’attività “Export Insegnanti”
2. Il Sistema genera un file JSON contenente i seguenti dati per ogni insegnante: nome, cognome, sesso, data inizio
   collaborazione, materie insegnate

#### Consegna:

![Soluzione](./esercitazione%20UML.png "Soluzione")