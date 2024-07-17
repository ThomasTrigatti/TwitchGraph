# TwitchGraph
Progetto di analisi di una rete per l'esame di Advanced Data Science.

# Esecuzione del Progetto
L'esecuzione del progetto e della generazione delle slide tramite Knit è molto onerosa in termini di tempo, almeno per me, con una durata minima di 40 min. Le computazioni onerose, con riferimento alla label del chunk, sono:
- 3.6, ovvero il calcolo della Closeness Centrality
- 3.10, ovvero il calcolo della Betweenness Centrality
- 4.1, ovvero l'esecuzione degli algoritmi di grouping e calcolo del valore di *modularity*
- 5.2, ovvero il calcolo della distanza media dei percorsi e del diametro della rete (in maniera meno pesante rispetto ai 3 punti precedenti)

Ho voluto aggiungere questo avviso in modo tale che, se si ha intenzione di eseguire il progetto, si abbia una stima del tempo necessario per il completamento dell'esecuzione.
