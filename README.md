# Tante macchine di turing

"Sometimes I lose myself, but I try to find it" G.P. 12/11/2020

Se avete contributi da dare, contribuite!

## fatte

Tracce ed esercizi svolti. Il nome del file indica con quanti nastri è stata implementata la macchina.

## tracce

Varie tracce non fatte

## pezzi

Pezzi da assemblare per realizzare una macchina completa, consulta il readme inside

## Riassunto di Tony

Il Riassunto comprende tutti gli argomenti che il professore """spiega""". Quelli evidenziati sono le domande che fa tipo sempre.

## Basilari e Difficili (Tony)

Le macchine di Turing binarie, essendo molto semplici, ne ho fatte alcune ma non tutte, mi sono concentrato maggiormente su quelle degli esami impossibili. Studiatevi la complessità che è l'unica cosa di cui tiene conto nella relazione della macchina di turing. Nella relazione per il funzionamento della macchina potete anche scrivere troiate.
Tony

## Nicola

Cartella di Nicola (roba disordinata), fatta in jflap 7.0

## tips / how to

- Non modificare il nome/numero delle transizioni (q0, q4, q7...), altrimenti la macchina smetterà di funzionare correttamente.

- Aprire singolarmente le macchine su JFlap in finestre separate (File > Open) e utilizzare la funzione "Convert > Combine Automata" per unirle.

- Modifiche multiple istantanee: 

• Aprire il file .jflap col Blocco Note e tramite la funzione Sostituisci, sostituire ad esempio: "=" con "," oppure "L" con "R"

• Per cambiare il numero di nastri di una macchina, sostituire <tapes>3</tapes> con <tapes>2</tapes> (da 3 a 2 nastri)
  Cancellare tutte le righe con "move0", "read0, "write0" per eliminare il contenuto del primo nastro (0 = primo, 1 = secondo, 2 = terzo)
  Cambiare tutti quelli che terminano col numero "2" (move2,read2,write2) con "0" per spostare il contenuto del terzo nastro sul primo.



## jflap 7 o 8?

8, perché il prof lo usa e le macchine sono create con l'8, e altri motivi che non mi ricordo. 

Ricordatevi di salvare prima di provare a modificare una transizione.

## Contributors (not listed in github's contributors)

Tony @tonywrall

Nicola @heruamin
