# Guardia e Ladro 1

Si vuole sviluppare un’applicazione per la simulazione di un gioco denominato guardia e ladro. 
Un utente (giocatore) si identifica tramite il nome e cognome. 
Si suppone di avere una stanza pavimentata a tasselli quadrati (caselle), dotata di pareti esterne ed interne. Nella stanza sono presenti una guardia e un ladro. Il giocatore deve permettere al ladro di uscire dalla stanza. 
Sia il ladro che la guardia si muovono di una casella alla volta tra le otto caselle vicine. Devono essere previsti diversi scenari. Per ogni scenario le strategie con cui si muove la guardia sono (K è la probabilità):

* nel K% dei casi la guardia si muove a caso in una delle otto caselle vicine possibili (parete permettendo);
* nel (100 − K)% dei casi la direzione della guardia viene calcolata usando l’algoritmo di ottimizzazione ant colony.

## Inoltre, nella stanza ci sono oggetti di diversi colori a disposizione del ladro:

<div style="text-align:left">
    <p>Verde - la guardia va nella direzione opposta a quella del ladro per 10 secondi.</p>
    <img src="https://github.com/Atymia/Programmazione_3/assets/92294051/70722189-76d6-416d-b6f7-8dc91b10ebf6" alt="verde">
</div>

<div style="text-align:left">
    <p>Giallo - la guardia va in una direzione casuale per 10 secondi.</p>
    <img src="https://github.com/Atymia/Programmazione_3/assets/92294051/f0f66375-7dd0-4ed3-a5fa-0df3a08c93c9" alt="giallo">
</div>

<div style="text-align:left">
    <p>Rosso - la guardia va nella direzione dell’uscita (ottimizzazione ant colony).</p>
    <img src="https://github.com/Atymia/Programmazione_3/assets/92294051/078b2dbc-48d6-4803-adf7-d40b15ff479e" alt="rosso">
</div>

Scrivere un programma per la gestione del gioco che permette di visualizzare, ad ogni inizio e fine partita, la classifica dei risultati migliori ottenuti, da tutti i giocatori, in tutte le partite (minore numero di passi per raggiungere l’uscita).


## Authors

- [@atymia](https://github.com/Atymia)
- [@ssdj3nt](https://github.com/Ssdj3nt)
