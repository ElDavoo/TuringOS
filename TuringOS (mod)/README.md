# Basato sulle macchine di TuringOS di ElDavoo, modificato ed ampliato da xDonatello
# TuringOS originale: https://github.com/ElDavoo/TuringOS

- Pani utilizza JFlap 8, inoltre le macchine sono state create su tale versione. Non sono compatibili col 7.

- Non modificare il nome/numero delle transizioni (q0, q4, q7...), altrimenti la macchina smetterà di funzionare correttamente.

- Aprire singolarmente le macchine su JFlap in finestre separate (File > Open) e utilizzare la funzione "Convert > Combine Automata" per unirle.


- Modifiche multiple istantanee: 

• Aprire il file .jflap col Blocco Note e tramite la funzione Sostituisci, sostituire ad esempio: "=" con "," oppure "L" con "R"

• Per cambiare il numero di nastri di una macchina, sostituire <tapes>3</tapes> con <tapes>2</tapes> (da 3 a 2 nastri)
  Cancellare tutte le righe con "move0", "read0, "write0" per eliminare il contenuto del primo nastro (0 = primo, 1 = secondo, 2 = terzo)
  Cambiare tutti quelli che terminano col numero "2" (move2,read2,write2) con "0" per spostare il contenuto del terzo nastro sul primo.

