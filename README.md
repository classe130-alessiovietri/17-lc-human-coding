# Human Coding

1. Tutte le mattine il professore chiama uno studente a caso per un’esercitazione guidata. Una volta chiamati tutti gli studenti ricomincia da capo.

PASSI DA SVOLGERE: (il programma viene eseguito automaticamente alle 7 di mattina ogni giorno in classe)
STEVEN
- chiama uno studente a caso
- apro l'esercitazione
- esegue l'esercitazione guidata
- SE ho chiamato tutti gli studenti
-- ricomincio da capo
- ALTRIMENTI
-- chiama il prossimo studente

SALVATORE
- scegli uno studente a caso
- SE è presente
-- lo chiamo
-- fai eseguire l'esercitazione allo studente
- ALTRIMENTI
-- chiama il prossimo studente

CLAUDIO
- scegli uno studente a caso
- SE è presente
-- lo chiamo
-- SE lo studente non ha già eseguito l'esercitazione
--- fai eseguire l'esercitazione allo studente
-- ALTRIMENTI
--- torna all'inizio
- ALTRIMENTI
-- torna all'inizio

JOSHUA
INIZIO
- aggiorna la lista dei presenti oggi
- SE ho chiamato tutti gli studenti
-- azzera la lista degli studenti chiamati
- scegli uno studente a caso
- SE è presente
-- lo chiamo
-- SE lo studente non ha già eseguito l'esercitazione
--- fai eseguire l'esercitazione allo studente
-- ALTRIMENTI
--- torna all'inizio
- ALTRIMENTI
-- torna all'inizio
FINE

COSE DA RICORDARE:
- lista degli studenti chiamati
- lista degli studenti totali
- lista degli studenti presenti oggi

------------------------------------------------------------------------------------------------------------------

2. Durante le vacanze ho fatto mille mila foto, ora come faccio a scegliere quella giusta da caricare su Instagram? I paesaggi mozzafiato che ho visitato non ne avrebbero bisogno, però cercherò il filtro giusto per migliorare la luce e rendere più vividi i colori, in modo che le foto rendano giustizia alla bellezza della natura

INIZIO
- apri galleria foto
- filtra le foto per data/e
- seleziona solo le foto dei panorami
- SE la singola foto richiede una modifica
-- scegli il filtro adatto
-- applica il filtro
- ALTRIMENTI
-- seleziona per la pubblicazione
FINE

INIZIO
- apri galleria foto
- scorri tutte le foto
- analizza la singola foto
- SE è della mia vacanza
-- SE ha bisogno di modifiche
--- scegli filtro
--- applica filtro
-- SE mi piace molto E è più bella della foto selezionata in precedenza
--- selezionala per la pubblicazione
-- SE ci sono altre foto
--- passa alla prossima foto
-- ALTRIMENTI
--- pubblica foto
- ALTRIMENTI
-- SE ci sono altre foto
--- passa alla possima foto
-- ALTRIMENTI
--- pubblica foto
FINE