Istruzioni per l'utilizzo:

Nella cartella 'src' ci sono i file della fase di Clean e della fase di Merge, nel file 'Yours_Data.py' sono da inserire i path dei datasets che si vogliono utilizzare e le proprie chiavi API, 
si possono inoltre modificare i parametri di sistema (CBS, Cx, Nt, MBS, BtC) e scegliere quale famiglia di LLMs utilizzare, pure lo specifico modello.
Ci sono inoltre i prompt per le chiamate ai modelli linguistici nel caso li si voglia modificare.

Per eseguire l'intero modello runnare il file 'main.py', per eseguire le fasi singolarmente runnare i rispettivi file ('Clean_Clusters.py' e 'Merge_Clusters.py').
Al termine di ogni esecuzione del modello completo o della fase di Merge viene valutato l'output sulla GT inserita.
Durante la fase di Clean vengono mostrate le valutazioni delle operazioni eseguite su ogni documento processato e sul corpus totale.

Nella cartella 'data' sono presenti i datasets della strage di Bologna utilizzati per testare e valutare il modello, mentre nella cartella 'Ground_Truth' sono presenti le tre tipologie di GT per ogni datasets
(Gold_Operations è singolo perche vengono fatte le verifiche tramite ID del documento).

Nella cartella 'LLM_CER_datasets' sono presenti le otto cartelle contenenti file di Input e file GT per ogni datasets usato per il confronto.

Nella cartella 'ECB+' sono presenti i file di Input e GT delle partizioni Eventi, Entità e Completa.
